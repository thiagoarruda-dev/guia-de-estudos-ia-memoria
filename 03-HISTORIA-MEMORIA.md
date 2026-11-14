# 03 - Estudo: Quando a IA começou a ter Memória?

> Para Devs Jr: Entender a história te faz entender POR QUE usamos _context-modelo/ hoje.

### A Linha do Tempo da Memória em IA

**1. Fase Cega (até 2020) - IA sem memória nenhuma**
- Modelos como GPT-2 eram "stateless": cada pergunta era a primeira.
- Você falava "meu nome é Thiago" e na próxima mensagem ele esquecia.
- Interação era só por comandos soltos, sem contexto.

**2. A Virada: RAG (2020)**
- Artigo "Retrieval-Augmented Generation" (Lewis et al., Meta AI, 2020).
- Ideia: E se a IA pudesse CONSULTAR um arquivo externo antes de responder?
- Foi quando nasceu a ideia de "dar arquivos para a IA ler". É o avô do nosso `_context-modelo/`.

**3. Janela de Contexto Gigante (2022-2023)**
- ChatGPT mostrou o poder do "System Prompt" - um comando escondido que fica SEMPRE na memória.
- De 4k tokens (2 páginas) fomos para 128k, 1M de tokens.
- De repente, coube um projeto inteiro dentro da memória da IA.

**4. A Era dos Comandos com Memória (2023-2024)**
- Surgem os "AI Agents" e o MemGPT (2023) - IA com sistema operacional de memória.
- Conceito de interação por comandos evolui: de `pergunta-resposta` para `instrução com contexto persistente`.
- Nasce o padrão que usamos hoje: `01-persona.md + 02-stack.md + 03-regras.md` = Memória externa via comandos.

**Referência pra estudar:**
- Paper RAG (2020) - Retrieval-Augmented Generation
- MemGPT Paper (2023) - Towards LLMs as Operating Systems
- Documentação LM Studio sobre System Prompt e Context Injection

> Exercício: Abra o LM Studio com e sem o `_context-modelo/` e veja a diferença na resposta. Isso é a história acontecendo.
