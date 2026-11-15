# 🧠 Deep Dive: Memória em Inteligência Artificial (IA)

> **Fase do Guia:** Fase 2 - Memória (Dando um HD externo para a IA)  
> **Nível:** Dev Iniciante / Junior

---

## 📌 O que é Memória em IA?

Por padrão, um modelo de linguagem (LLM) é **amnésico**. Isso significa que a cada nova conversa ou prompt, a IA não se lembra de quem você é, qual é o seu projeto ou quais regras você definiu anteriormente.

Ela funciona quase que exclusivamente com **memória de curto prazo** (a Janela de Contexto). Quando a conversa fica muito longa ou o chat é reiniciado, tudo o que foi conversado desaparece!

---

## 💡 A Analogia do Computador sem HD

Imagine usar um computador que só possui **memória RAM**, mas **não tem disco rígido (HD/SSD)**:

- Enquanto o computador estiver ligado, ele consegue processar tarefas na RAM.
- Se você desligar o computador (fechar o chat ou estourar a memória), tudo se perde.
- **A Solução:** Criar um "HD Externo" usando arquivos de texto (`.md`) no VS Code!

---

## 🛠️ Como damos memória para a IA no nosso projeto?

Na nossa stack atual (**LM Studio + VS Code + Files Markdown**):

1. **Arquivos de Contexto (`_context-modelo/`):** Criamos arquivos como `01-persona.md`, `02-stack.md` e `03-regras.md`.
2. **Regras Automáticas (`.clinerules` / `AGENT.md`):** Definimos instruções obrigatórias que a IA deve ler antes de dar qualquer resposta.
3. **Leitura Obrigatória:** A IA lê o "HD Externo" logo no início da conversa. Com isso, ela passa a saber quem você é, onde está e como deve te responder!

---

## 🚀 Próximos Passos e Visão de Futuro

- **[FUTURO - FASE 3]** Fazer busca semântica automatizada usando um **Banco Vetorial** (como o Qdrant) para recuperar apenas as partes relevantes da memória.
- **[FUTURO - FASE 3]** Implementar **RAG (Retrieval-Augmented Generation)** usando scripts em Python.

---

## 📂 Onde encontrar este arquivo no VS Code?

1. No menu lateral esquerdo do VS Code, clique no ícone de **Explorador de Arquivos** (ou aperte `Ctrl + Shift + E`).
2. Abra a pasta `deep-dives`.
3. Abra a pasta `ia-memoria`.
4. Clique no arquivo `README.md`.
