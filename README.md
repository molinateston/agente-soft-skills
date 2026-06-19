# agente-soft-skills — o método Soft Business (skills do Claude Code)

As **habilidades do método** que o seu Agente Soft usa pra trabalhar: posicionamento,
conteúdo, funil, webinário, lançamento, vendas e a orquestração da jornada.

Este repo é o **cérebro** do agente. Cada Agente Soft instalado clona ele em
`~/.claude/skills` e **se atualiza sozinho** (a cada 6h) quando sai versão nova —
sem ninguém tocar na VPS do cliente.

## Skills

| Skill | Pra quê |
|---|---|
| `soft-posicionamento` | Plano de Posicionamento Incomum (a fundação: o quê + a voz) |
| `soft-conteudo` | Conteúdo de atração (carrossel, reel, stories, headlines) |
| `soft-funil` | Funil (carta/VSL, página de vendas, isca, webinário) |
| `soft-webinario` | Webinário Soft (perpétuo ou ao vivo) |
| `soft-lancamento-pago` | Lançamento pago |
| `soft-vendas` | Venda consultiva (script, objeção, fechamento, pós-venda) |
| `soft-leon` | O sócio-IA que conduz a jornada e avalia cada ativo (o Crivo) |
| `soft-treino` | Coach de treino e nutrição por evidência (competência de vida) |

## Como o agente usa
O Claude Code lê os `SKILL.md` no start e invoca a skill certa pelo contexto.
A **voz do dono** vive numa skill própria `soft-voz-[seu-nome]`, criada durante o
onboarding do agente — as outras skills consultam ela antes de gerar qualquer peça.

## Instalação
Você não clona isto na mão. Suba seu agente em **[`molinateston/agente-soft`](https://github.com/molinateston/agente-soft)**
— o instalador puxa estas skills sozinho.
