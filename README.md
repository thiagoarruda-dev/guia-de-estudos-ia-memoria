> **📝 Nota:** Este projeto está em construção e recebe **atualizações não periódicas**, conforme avanço nos estudos e testes práticos.

## 📁 COMO COMEÇAR DO ZERO SEM SE PERDER

**A REGRA DE OURO É: NOME IGUAL EM TUDO.** Se o nome da pasta no seu PC for diferente do GitHub e do VS Code, você se perde e acha que sumiu arquivo. Não sumiu, você só criou em outro lugar.

**1. Criando a pasta raiz (onde tudo vai morar):**

**No PC (Windows):**
1. Vai em Documentos
2. Botão direito > Novo > Pasta
3. Nomeie EXATAMENTE igual ao seu repositório no GitHub. Ex: `nome do seu projeto`
4. Essa é sua pasta MÃE. Tudo tem que ser criado DENTRO dela.

**No VS Code (pra não se perder):**
1. Abra o VS Code > `Arquivo > Abrir Pasta`
2. Selecione a pasta MÃE que você criou
3. Pronto, tudo que criar agora já cai dentro dela.

**2. Criando arquivos e pastas DENTRO da raiz:**
- Para criar ARQUIVO: botão direito na pasta MÃE > `Novo Arquivo` > `02-stack.md`
- Para criar PASTA: botão direito na pasta MÃE > `Nova Pasta` > `_context-modelo`

**3. Como salvar e sair sem perder:**
- **Salvar:** `Ctrl + S` sempre. Ou ative `Arquivo > Salvamento Automático`.
- **Sair:** Nunca feche com bolinha branca (●) no arquivo. Bolinha = não salvo.
- **Dica:** Olhe sempre o nome da pasta no topo do VS Code. Se não for sua pasta MÃE, você está no lugar errado.

**4. Nomeie com concordância:**
- ✅ Certo: `02-stack.md`, `AGENT.md`, `LEARNING_LOG.md` (minúsculo, com hífen, sempre igual)
- ❌ Errado: `Stack`, `stack MD` (cada hora um nome, você nunca mais acha)

---

## 📁 MODELO PRONTO - Adapte para o SEU projeto

Este guia foi roteirizado em ESTUDOS. Copie a estrutura e troque pelas palavras do SEU tema.

| Se seu projeto é sobre... | `AGENT.md` vira... | `_context-modelo/` vira... |
| :--- | :--- | :--- |
| **JOGOS** | Regras do jogo, o que o NPC não pode fazer | Mecânicas, personagens, mapa |
| **E-COMMERCE** | Regras de venda, o que o bot não pode prometer | Produtos, clientes, política |
| **O MEU (IA + Memória)** | Regras da IA, o que não pode inventar | Minha stack, meu perfil |

**O que é o quê:**

**📄 ARQUIVOS NA RAIZ:**
- `README.md` -> Seu mapa
- `AGENT.md` -> As REGRAS do seu projeto
- `LEARNING_LOG.md` -> Seu diário de aprendizado
- `02-stack.md` -> Suas ferramentas reais
- `.gitignore` -> A LISTA NEGRA. O que o GitHub NUNCA pode ver (sua chave API, .env)
- `.env.example` -> O MOLDE da sua chave. Sem o valor real, só pra outro dev saber o que preencher

**📁 PASTAS:**
- `_context-modelo/` -> A MEMÓRIA do seu projeto (o que a IA precisa saber)
- `deep-dives/` -> O FUTURO do seu projeto

meu-projeto-[SEU-TEMA]/
├── 📄 README.md
├── 📄 AGENT.md
├── 📄 LEARNING_LOG.md
├── 📄 .gitignore (OBRIGATÓRIO)
├── 📄 .env.example (OBRIGATÓRIO se usar API)
├── 📄 02-stack.md
├── 📄 03-HISTORIA.md
├── 📄 04-ESTUDOS-BASE.md
├── 📄 05-GUIA-COMPLETO.md
├── 📁 _context-modelo/
└── 📁 deep-dives/


---

# Guia de Estudos IA + Memória - Para Devs Jr

> Criado por um Dev Jr para Devs Jr que querem dar memória e contexto para projetos de IA.

## O que este projeto ensina?

Ensinar na prática como um projeto pode TER MEMÓRIA, usando só LM Studio + VS Code + GitHub. Sem magia, com história e comandos.

### O Mapa do Guia em 4 Fases (Minha Trilha Pessoal)

**FASE 0 - A História: Quando a memória ficou possível?**
Antes de codar, entender o PORQUÊ. De 2020 (RAG) até hoje, quando a IA parou de esquecer tudo.
-> Comece aqui: `03-HISTORIA-MEMORIA.md`

**FASE 1 - O Básico que todo Jr precisa (Onde estou hoje)**
Como organizar estudos com LM Studio local, VS Code e GitHub. Minha fase atual.
-> Veja: `04-ESTUDOS-BASE.md`

**FASE 2 - Dando Memória pro Projeto (O Pulo do Gato)**
Como usar a pasta `_context-modelo/` como memória externa via System Prompt no LM Studio.
-> Veja: `05-GUIA-COMPLETO.md` e a pasta `_context-modelo/`

**FASE 3 - Futuro (Quando dominar a Fase 2)**
Evoluir para memória vetorial (Qdrant), Docker, etc. 

## Como usar este guia se você é Jr?

1.  Leia a Fase 0 para entender a pesquisa de memória por comandos
2.  Faça a Fase 1 e suba 3 arquivos .md pro seu GitHub
3.  Na Fase 2, copie os arquivos de `_context-modelo/` para o System Prompt do seu LM Studio e veja a IA lembrar de você

Stack Real Hoje: LM Studio, VS Code, GitHub + Extensões.