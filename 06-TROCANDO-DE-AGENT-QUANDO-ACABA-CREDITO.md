# Fase 2.5 - E se acabar o crédito da IA? Como trocar de AGENT sem perder memória

Muitos Jrs pensam: "Minha memória tá no Cline, se acabar o crédito, perdi tudo."

Mentira. Sua memória NÃO está no Cline. Está no _context-modelo/.

## Analogia pra Jr:
- _context-modelo/ = Seu HD externo com sua memória
- .clinerules, AGENT.md, CURSOR.md = Cabos USB diferentes
    - Cline usa cabo .clinerules
    - Cursor usa cabo AGENT.md
    - Claude Code usa cabo CLAUDE.md

Se quebrar um cabo (acabou crédito), você só troca o cabo. O HD continua igual.

## Como trocar na prática (Sem perder nada):

1. Seu HD já existe: _context-modelo/01-persona.md, 02-stack.md, 03-regras.md

2. Acabou crédito do Cline?
      - Vai no Cursor / Windsurf / VS Code com Copilot
      - Cria na raiz o arquivo que ele pede: AGENT.md ou .cursorrules
      - Cola dentro o mesmo texto: "Leia sempre _context-modelo/ como fonte da verdade"

3. Pronto. Nova IA, mesma memória. Você continua sendo o Thiago de Porto de Galinhas, com stack LM Studio + VS Code + GitHub.

REGRA DE OURO DO GUIA:
NUNCA escreva sua memória direto no .clinerules ou AGENT.md.
Sempre deixe a memória no _context-modelo/ e faça os outros só APONTAREM pra ela.
Assim sua memória é portátil.

Teste: Troquei de Cline pra Cursor. Perguntei "quem sou eu?". Respondeu igual? Deu certo.