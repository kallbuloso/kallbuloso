<br clear="both">
<img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=008080&text=Amaral&section=header&desc=Software%20Architect%20%E2%80%A2%20AI-native%20SaaS%20%E2%80%A2%20Agentic%20Systems&descAlign=50&descAlignY=55&textBg=false&animation=twinkling&stroke=FFF&descSize=22&fontAlignY=28" width="100%" alt="Amaral — Software Architect, AI-native SaaS and Agentic Systems" />

<h1 align="left">👋 Olá, eu sou o Amaral <sub>(kallbuloso)</sub></h1>

Sou desenvolvedor de software e arquiteto de sistemas, com cerca de **20 anos construindo software** e uma base de aproximadamente **30 anos em eletrônica**.

Hoje meu foco está em **software AI-native**: memória semântica, knowledge graphs, sistemas agênticos, automações e SaaS verticais construídos a partir de problemas reais de negócio — não apenas CRUDs com um botão de IA colado depois.

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
  <img alt="Laravel" src="https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white">
  <img alt="Vue.js" src="https://img.shields.io/badge/Vue.js-3-42B883?logo=vuedotjs&logoColor=white">
  <img alt="Vuetify" src="https://img.shields.io/badge/Vuetify-3-1867C0?logo=vuetify&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white">
  <img alt="pgvector" src="https://img.shields.io/badge/pgvector-semantic%20search-336791">
  <img alt="Neo4j" src="https://img.shields.io/badge/Neo4j-knowledge%20graph-4581C3?logo=neo4j&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
</p>

---

## 🚀 O que estou construindo agora

### 🧠 [Sofias Memory](https://github.com/kallbuloso/sofias_memory)

Uma camada de **memória semântica e knowledge graph** para aplicações e sistemas agênticos.

O projeto nasceu inspirado por ideias do ecossistema Cognee, mas evoluiu para uma arquitetura própria, com **PostgreSQL + pgvector como fonte autoritativa**, **Neo4j como projeção reconstruível**, pipelines duráveis, recuperação híbrida, GraphRAG, provenance e mecanismos explícitos de consistência e recovery.

**Estado atual: v0.4.0**

- ingestão de texto, arquivos e URLs;
- Remember, Cognify, Recall, Improve e Forget;
- busca vetorial, lexical, híbrida e graph-grounded RAG;
- datasets e runs duráveis com retry/cancel;
- armazenamento filesystem ou S3-compatible;
- **Sessions** e `SessionEntries` como contexto temporal durável;
- **Skills** versionadas como memória procedural, com resolução semântica e interoperabilidade `SKILL.md`.

> Para mim, memória de IA não é um campo `conversation_history` maior. É infraestrutura.

### 🤖 [Sofia's Assistant](https://github.com/kallbuloso/sofias_assistant)

Um **assistente pessoal local-first e agêntico**, atualmente em desenvolvimento.

A intenção é usar o Sofias Memory como camada transversal de memória, conhecimento e contexto, enquanto o Assistant concentra **agents, tools, sessions, orchestration, execução e evolução do comportamento**.

O projeto está sendo construído a partir de PRD + ADRs + backlog técnico, com arquitetura antes de improvisação — porque “vamos conectar alguns agentes e ver o que acontece” funciona muito bem até começar a acontecer.

### 🛠️ Sofias Lyder

Um **SaaS vertical para assistências técnicas**, em desenvolvimento privado, baseado em décadas de experiência prática no domínio.

A proposta não é um ERP genérico: o produto modela o fluxo real da oficina — entrada do equipamento, diagnóstico, orçamento quando necessário, autorização, execução, estoque, venda, comunicação e entrega.

O projeto também funciona como campo de aplicação para a infraestrutura de IA e memória que estou desenvolvendo no ecossistema Sofias.

### 🧩 SofiasTech

É a identidade sob a qual concentro meus projetos de **software com IA, automações, agentes e SaaS**.

A direção é construir produtos nos quais IA faça parte da arquitetura e do fluxo operacional — não seja apenas uma integração decorativa com um LLM.

---

## 🧭 Como penso arquitetura

Alguns princípios aparecem repetidamente no que construo:

- **Fonte de verdade explícita:** em sistemas cognitivos, dados autoritativos precisam estar claramente separados de projeções reconstruíveis.
- **Durabilidade antes do happy path:** idempotência, retry, recovery, concorrência e observabilidade são parte da feature.
- **IA com provenance:** respostas são melhores quando é possível explicar de onde o contexto veio.
- **Graph quando há motivo:** knowledge graph é ferramenta de modelagem e recuperação, não decoração arquitetural.
- **SaaS vertical antes de SaaS genérico:** conhecimento de domínio vale mais que uma tela CRUD perfeitamente alinhada.
- **Automação acima de repetição:** se uma rotina é previsível e frequente, provavelmente deveria ser automatizada.
- **Local-first / self-hosted quando fizer sentido:** controle de dados e infraestrutura pode ser uma vantagem, não um inconveniente.
- **Documentação como parte da implementação:** PRDs, ADRs, contratos e backlogs ajudam a manter a arquitetura coerente enquanto o produto cresce.

---

## 🧰 Stack que uso com mais frequência

| Camada | Tecnologias |
|---|---|
| **Backend** | Python, FastAPI, PHP, Laravel, REST APIs, workers e pipelines assíncronos |
| **Frontend** | Vue 3, Composition API, Inertia.js, Vuetify 3, Vite, Pinia |
| **Dados** | PostgreSQL, pgvector, Neo4j, Redis, SQLite |
| **IA** | LLMs OpenAI-compatible, embeddings, RAG, GraphRAG, semantic memory, agentes |
| **Automação** | n8n, webhooks, Chatwoot, Evolution API |
| **Infra** | Docker, WSL2, Portainer, EasyPanel, S3-compatible storage, Cloudflare |
| **Integrações** | Google APIs, WhatsApp, Mercado Livre, Mercado Pago, OAuth2 |

Tecnologia para mim é meio, não identidade. Laravel continua excelente onde Laravel é a melhor resposta; Python entrou com força porque sistemas cognitivos e agênticos pedem outro conjunto de ferramentas.

---

## 🔬 Interesses técnicos atuais

- arquiteturas de memória para agentes;
- memória episódica, semântica e procedural;
- agent management e orchestration;
- skills reutilizáveis e progressive disclosure;
- context engineering;
- knowledge graphs e GraphRAG;
- pipelines duráveis e sistemas recuperáveis;
- IA aplicada a SaaS vertical;
- integração entre aplicações Laravel e serviços Python;
- infraestrutura self-hosted para aplicações com IA.

---

## ⚡ Um pouco da trajetória

Minha formação prática veio primeiro da **eletrônica**: diagnóstico, reparo e resolução de problemas reais, onde a explicação bonita perde imediatamente para o circuito que continua queimando fusível.

Essa mentalidade foi comigo para o software. Ao longo dos anos trabalhei com aplicações comerciais, automações, integrações, sistemas para assistências técnicas e diferentes gerações de aplicações Laravel/Vue.

Hoje estou juntando essas duas décadas de software com a experiência de domínio acumulada para construir uma nova geração de produtos centrados em **IA, memória e agentes**.

---

## 📌 Alguns repositórios

- 🧠 **[sofias_memory](https://github.com/kallbuloso/sofias_memory)** — memória semântica, knowledge graph, RAG, Sessions e Skills.
- 🤖 **[sofias_assistant](https://github.com/kallbuloso/sofias_assistant)** — fundação do assistente pessoal agêntico local-first.
- 🔧 **[eletrolyder_new](https://github.com/kallbuloso/eletrolyder_new)** — experiência acumulada em software para assistências técnicas.
- 🐳 **[compose-easypanel](https://github.com/kallbuloso/compose-easypanel)** — stacks e experimentos de infraestrutura self-hosted.

---

## 🌐 Contato

- **GitHub:** [@kallbuloso](https://github.com/kallbuloso)
- **LinkedIn:** [Claudinei de Carvalho](https://www.linkedin.com/in/claudineicarvalho)
- **Email:** [kallbuloso@gmail.com](mailto:kallbuloso@gmail.com)

---

<div align="center">
  <strong>Construindo software que consiga lembrar, raciocinar sobre contexto e continuar funcionando depois que a demo termina.</strong>
</div>
