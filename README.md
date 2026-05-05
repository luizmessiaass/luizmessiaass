<h1 align="center">Olá, sou Luiz Messias 👋</h1>

<p align="center">
  <strong>Full Stack Developer · IA-Powered Engineering</strong><br/>
  Construo aplicações web modernas com foco em arquitetura escalável, boas práticas e integração com inteligência artificial para automatizar, acelerar e melhorar a experiência do usuário.
</p>

<p align="center">
  <a href="https://github.com/luizmessiaass?tab=followers">
    <img src="https://img.shields.io/github/followers/luizmessiaass?style=flat-square&label=Followers&color=0f172a" />
  </a>
  <a href="mailto:inoveautomations@gmail.com">
    <img src="https://img.shields.io/badge/Email-inoveautomations@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" />
  </a>
</p>

---

## 🚀 Sobre

Trabalho como desenvolvedor full stack com forte interesse em engenharia assistida por IA — uso modelos LLM como ferramenta de produtividade, integração de produtos (chatbots, triagem automática, agentes) e como aliado no design de arquitetura.

Minha abordagem: código testado, observável, com permissões claras e pronto pra produção. Nada de POC bonito que quebra no primeiro usuário concorrente.

---

## 🛠️ Stack

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![NextAuth.js](https://img.shields.io/badge/NextAuth.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

**IA & Automação**

![Anthropic Claude](https://img.shields.io/badge/Anthropic_Claude-D97706?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EF5B2B?style=for-the-badge&logo=n8n&logoColor=white)

**Testes & Observabilidade**

![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Pino](https://img.shields.io/badge/Pino-EAB308?style=for-the-badge&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

**Deploy & DevOps**

![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 💡 O que me move

- 🧠 **IA como ferramenta de engenharia** — uso LLMs pra acelerar desenvolvimento, gerar testes, fazer code review e construir features assistivas pros usuários
- 🏗️ **Arquitetura limpa** — matrizes de permissão centralizadas, filas assíncronas, rate limiting, observability estruturada
- 📐 **UX / Design Systems** — kanbans com drag-drop fluido, animações sutis com Framer Motion, glassmorphism e dashboards densos sem ficar pesado
- 🔒 **Segurança em primeiro lugar** — validação de uploads, sanitização HTML, audit logs, redaction automática de logs sensíveis

---

## 🌟 Projetos em destaque

### 🛒 [Elevater](https://github.com/i9automations/Elevater) — Gestão Inteligente de Marketplaces

Plataforma multi-tenant que consolida vendas, publicidade e rentabilidade do Mercado Livre e Shopee em dashboards unificados. Inclui curva ABC, mapa de calor 7×24h, automação visual drag-and-drop com React Flow, análise por IA com Claude e RBAC com 4 níveis (Master → Supervisor → Gestor → Cliente). Tokens OAuth armazenados no Supabase Vault com refresh automático.

`Next.js 16` `React 19` `TypeScript` `Supabase (Postgres + RLS + Vault)` `Tailwind v4` `shadcn/ui` `TanStack Table` `Recharts` `React Flow` `Zustand` `Anthropic Claude` `Node.js` `PM2`

---

### 🎫 Avant IA Desk — Sistema de Chamados

Sistema completo de gestão de tickets internos usado em ambiente real. Inclui kanban de tasks, Gantt, SLA com horário comercial brasileiro + feriados, milestones/sprints, notas seguras de projeto (com toggle de credenciais), fila assíncrona de emails com retry exponencial, rate limiting per-route, audit log estruturado com pino e matriz de permissões centralizada.

`Next.js 16 (Turbopack)` `TypeScript` `Prisma` `PostgreSQL (Supabase)` `NextAuth v5` `Tailwind v4` `Framer Motion` `Three.js` `Vitest`

---

### 🕷️ Marketing Scrapping — Pipeline de Conteúdo Social

Coleta automatizada de Instagram (estáticos/carrosséis/vídeos), YouTube e Meta Ads Library. Transcreve com Whisper (Groq), analisa multimodal com Claude, gera hooks magnéticos, roteiros e ranking de melhor conteúdo. Backend FastAPI async + scheduler. Frontend exporta relatórios em PDF/DOCX.

`FastAPI` `Python` `Anthropic Claude` `Groq Whisper` `Apify` `yt-dlp` `Supabase Edge Functions` `React 19` `Vite` `Tailwind v4`

> 📌 Mais projetos sendo estruturados — incluindo módulo de agentes IA pra triagem automática de tickets.

---

## 📊 GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=luizmessiaass&show_icons=true&theme=github_dark&hide_border=true&count_private=true" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=luizmessiaass&layout=compact&theme=github_dark&hide_border=true" height="160" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=luizmessiaass&theme=github-dark-blue&hide_border=true" />
</p>

---

## 📫 Contato

- 📧 **Email:** inoveautomations@gmail.com
- 💼 **GitHub:** [@luizmessiaass](https://github.com/luizmessiaass)

<p align="center"><em>"Boas ferramentas amplificam bons engenheiros — IA é a nova boa ferramenta."</em></p>
