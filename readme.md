<br clear="both">
<img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=008080&text=Amaral%20karl&section=header&desc=kallbuloso&descAlign=51&descAlignY=53&textBg=false&animation=twinkling&stroke=FFF&descSize=35&fontAlignY=26" width="100%" alt="header image"  />

<h1 align="left">👋 Olá! Eu sou o Amaral (kallbuloso)</h1>

Full-Stack focado em <strong>Laravel + Vue 3 + Vuetify + Inertia.js</strong>, com ~20+ anos de desenvolvimento e ~30 anos de eletrônica.  
Construo <strong>SaaS multi-tenant</strong> e <strong>automações com IA</strong> (n8n, LLMs, <strong>RAG/GraphRAG</strong>) para PMEs e comércios locais.

<p>
  <img alt="Laravel" src="https://img.shields.io/badge/Laravel-12-FF2D20?logo=laravel&logoColor=white">
  <img alt="Vue" src="https://img.shields.io/badge/Vue-3-42B883?logo=vuedotjs&logoColor=white">
  <img alt="Vuetify" src="https://img.shields.io/badge/Vuetify-3-1867C0?logo=vuetify&logoColor=white">
  <img alt="Inertia" src="https://img.shields.io/badge/Inertia-2-9553e9?logo=laravel&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-16-336791?logo=postgresql&logoColor=white">
  <img alt="GraphRAG" src="https://img.shields.io/badge/GraphRAG-Neo4j-111?logo=neo4j&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-ready-2496ED?logo=docker&logoColor=white">
  <img alt="n8n" src="https://img.shields.io/badge/n8n-Orchestrations-fe2c55?logo=n8n&logoColor=white">
  <img alt="Chatwoot" src="https://img.shields.io/badge/Chatwoot-CX-1F93FF?logo=chatwoot&logoColor=white">
</p>

---

## 🚀 Destaques

- **Eletrolyder SaaS** — Assistências técnicas: OS, estoque, marketplace, base técnica (RAG/GraphRAG).  
  *Stack:* Laravel 12, Inertia 2, Vue 3, Vuetify 3, Postgres, pgvector, S3.

- **e-burguer** — Gestão de hamburguerias com atendimento humanizado (LLMs) e integrações (WhatsApp/Meta, Mercado Pago).  
  *Stack:* Laravel + Vue 3 + Vuetify + Inertia; impressão na cozinha; fidelidade.

- **Sofias Tech (Automations)** — n8n + agentes orquestrados (Crew-style) para Google/Meli/Chatwoot/RAG.  
  *Stack:* n8n, Docker, OpenAI, Postgres/Redis, Webhooks.

- **Curta.se** — Portal criativo/motivacional com experimentos de conteúdo gerado por IA.

---

## 🧰 Stack principal

- **Backend:** PHP (Laravel 12), Eloquent, Queues/Jobs/Events, Policies, Mail/Notifications, WebSockets.  
- **Frontend:** Vue 3 (Composition API), Vuetify 3, Inertia 2, Vite, Pinia (persist), Ziggy.  
- **Banco:** PostgreSQL (prod), SQLite (dev), Redis; **Vetores:** pgvector.  
- **IA & RAG:** OpenAI, Dify/Langflow quando útil, **GraphRAG** (knowledge graphs para contexto profundo).  
- **Infra/DevOps:** Docker, Traefik/Portainer, Easypanel, S3/Wasabi, Cloudflare, CI/CD GitHub.  
- **CX/Atendimento:** Chatwoot (Sofias Tech), integrações WhatsApp/Meta.  
- **Pagamentos/Marketplace:** Mercado Pago/Mercado Livre, Stripe quando aplicável.  
- **APIs usuais:** Google (Drive/Gmail/Calendar/Maps), IBGE, OAuth2, Webhooks.

---

## 🧭 Princípios de arquitetura

- **Multi-tenant first** (`tenant_id`, permissões, rate limits por tenant).  
- **Naming em inglês** para tabelas/colunas (ex.: `service_orders`, `status_steps`, `client_id`).  
- **Statuses/steps genéricos** via morphs/pivots para reuso cross-módulo.  
- **Observabilidade** (logs estruturados, tracing mínimo, métricas pragmáticas).  
- **DX acima de tudo**: seeders úteis, make-commands, doc viva.  
- **Automação > Repetição**: flows n8n para import/sync/notificações.

---

## 📦 “Skills como código” (snapshot 2025)

```ts
export const amaral = {
  fullName: "Claudinei de Carvalho",
  nickName: "Amaral Karl",
  github: "https://github.com/kallbuloso",
  email: "mailto:kallbuloso@gmail.com",
  origin: "São Paulo, Brazil",
  role: "Full-Stack Developer • SaaS Architect",
  stack: {
    backend: ["PHP", "Laravel 12", "REST", "WebSockets"],
    frontend: ["Vue 3", "Vuetify 3", "Inertia 2", "Vite", "Pinia", "TypeScript"],
    database: ["PostgreSQL", "SQLite", "Redis", "pgvector"],
    devops: ["Docker", "Traefik", "Easypanel", "S3/Wasabi", "Cloudflare"],
    automation_ai: ["n8n", "OpenAI", "RAG", "GraphRAG"],
    integrations: ["Mercado Pago", "Mercado Livre", "Google APIs", "Chatwoot"],
  },
  experience: { electronics: "≈30y", software: "≈20y" },
  updatedAt: "2025-10-29",
};
```
---
📊 GitHub Stats
<div align="center"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=kallbuloso&show_icons=true&include_all_commits=false&count_private=true&title_color=00bfbf&text_color=00bfbf&bg_color=0d1117&hide_border=true&locale=pt-br" /> <img src="https://github-readme-stats.vercel.app/api?username=kallbuloso&show_icons=true&include_all_commits=false&count_private=true&hide_border=true&locale=pt-br" height="180" alt="stats graph" /> </picture> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=kallbuloso&locale=pt-br&langs_count=10&layout=compact&hide_border=true&title_color=00bfbf&text_color=00bfbf&bg_color=0d1117" /> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kallbuloso&locale=pt-br&langs_count=10&layout=compact&hide_border=true" height="180" alt="languages graph" /> </picture> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-streak-stats.herokuapp.com?user=kallbuloso&theme=tokyonight&hide_border=true&locale=pt_BR&date_format=j%2Fn%5B%2FY%5D&background=0D1117&currStreakNum=00BFBF&stroke=00BFBF&fire=EB5454&sideNums=00BFBF&currStreakLabel=00BFBF&sideLabels=00BFBF" /> <img src="https://github-readme-streak-stats.herokuapp.com?user=kallbuloso&theme=tokyonight&hide_border=true&locale=pt_BR&date_format=j%2Fn%5B%2FY%5D" height="180" alt="streak graph" /> </picture> </div>
🧪 Tecnologias & Ferramentas (seleção)
<div align="left"> <!-- FE --> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="32" alt="javascript" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="32" alt="typescript" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" height="32" alt="vue" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuetify/vuetify-original.svg" height="32" alt="vuetify" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="32" alt="html5" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="32" alt="css3" /> <!-- Backend --> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="32" alt="php" /> <!-- Laravel (corrigido) --> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-original.svg" height="32" alt="laravel" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="32" alt="nodejs" /> <!-- DB --> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="32" alt="postgresql" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" height="32" alt="redis" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" height="32" alt="sqlite" /> <!-- DevOps --> <!-- Nginx (corrigido) --> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nginx/nginx-original.svg" height="32" alt="nginx" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apache/apache-original.svg" height="32" alt="apache" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="32" alt="docker" /> <!-- IA / RAG / CX --> <!-- OpenAI (corrigido) --> <img src="https://cdn.simpleicons.org/openai" height="32" alt="openai" /> <!-- Chatwoot (corrigido) --> <img src="https://cdn.simpleicons.org/chatwoot/1F93FF" height="32" alt="chatwoot" /> </div>
🌐 Social & Contato

LinkedIn: <a href="https://www.linkedin.com/in/claudineicarvalho" target="_blank">Claudinei</a>

Email: <a href="mailto:kallbuloso@gmail.com">kallbuloso@gmail.com
</a>
