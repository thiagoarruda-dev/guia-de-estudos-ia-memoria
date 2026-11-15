# AGENT.md - Guia do Agente

Este projeto usa Cline/Agent com memória externa.

## Como funciona?
O agente não tem memória própria. Toda memória está em _context-modelo/

## O que ler ao iniciar?
1. 01-persona.md - Quem você está ajudando (Dev Jr)
2. 02-stack.md - Stack permitida
3. 03-regras.md - Regras de resposta

## O que é cada pasta?
- _context-modelo/ = memória (persona, stack, regras)
- LEARNING_log/ = onde você deve registrar o que aprendeu
- / (raiz) = .clinerules, .gitignore, AGENT.md (regras públicas)

## O que NUNCA fazer?
- Nunca pedir pro usuário decorar algo, sempre ler dos arquivos
- Nunca mostrar chave de .env
- Nunca inventar stack que não está em 02-stack.md

## REGRA: 
Se a API do Gemini falhar com "quota exceeded", troque automaticamente para modelo local no LM Studio e avise o usuário para tentar em 8h.
