
# Brainexa App

AI-Powered EdTech Platform built with TanStack Start, Supabase, and Cloudflare Workers.

---

# Overview

Brainexa is a scalable role-based educational platform designed for:

* students
* teachers
* administrators

The platform combines:

* structured course delivery
* dashboard systems
* authentication architecture
* AI-assisted learning workflows
* future monetization systems

The project is being engineered with production scalability in mind.

---

# Tech Stack

## Frontend

* React
* TypeScript
* TanStack Start
* TanStack Router
* TailwindCSS
* shadcn/ui

---

## Backend

* Supabase Auth
* Supabase PostgreSQL
* Supabase APIs

---

## Deployment

* Cloudflare Workers
* Wrangler CLI
* GoDaddy Domain Integration

---

# Core Features

## Authentication

* Email/password login
* Role-based access
* Protected routes
* Session persistence

---

## Dashboards

### Student Dashboard

Features:

* course access
* lesson navigation
* tests
* PDFs
* progress tracking

---

### Teacher Dashboard

Features:

* assigned subjects
* content management
* quiz moderation
* student handling

---

### Admin Dashboard

Features:

* platform management
* teacher assignment
* referrals
* withdrawals
* analytics

---

# Planned AI Features

* AI tutor assistant
* AI-generated quizzes
* AI doubt solving
* AI explanation system
* AI moderation tools

---

# Project Structure

<pre class="overflow-visible! px-0!" data-start="1407" data-end="1593"><div class="relative w-full mt-4 mb-1"><div class=""><div class="relative"><div class="h-full min-h-0 min-w-0"><div class="h-full min-h-0 min-w-0"><div class="border border-token-border-light border-radius-3xl corner-superellipse/1.1 rounded-3xl"><div class="h-full w-full border-radius-3xl bg-token-bg-elevated-secondary corner-superellipse/1.1 overflow-clip rounded-3xl lxnfua_clipPathFallback"><div class="pointer-events-none absolute end-1.5 top-1 z-2 md:end-2 md:top-1"></div><div class="relative"><div class="pe-11 pt-3"><div class="relative z-0 flex max-w-full"><div id="code-block-viewer" dir="ltr" class="q9tKkq_viewer cm-editor z-10 light:cm-light dark:cm-light flex h-full w-full flex-col items-stretch ͼs ͼ16"><div class="cm-scroller"><pre class="cm-content q9tKkq_readonly m-0"><code><span>src/</span><br/><span>├── components/</span><br/><span>├── routes/</span><br/><span>├── hooks/</span><br/><span>├── integrations/</span><br/><span>├── lib/</span><br/><span>└── styles/</span><br/><br/><span>docs/</span><br/><span>├── architecture.md</span><br/><span>├── roadmap.md</span><br/><span>├── auth.md</span><br/><span>├── deployment.md</span><br/><span>└── known-issues.md</span></code></pre></div></div></div></div></div></div></div></div></div><div class=""><div class=""></div></div></div></div></div></pre>

---

# Local Development

## Install Dependencies

<pre class="overflow-visible! px-0!" data-start="1646" data-end="1669"><div class="relative w-full mt-4 mb-1"><div class=""><div class="relative"><div class="h-full min-h-0 min-w-0"><div class="h-full min-h-0 min-w-0"><div class="border border-token-border-light border-radius-3xl corner-superellipse/1.1 rounded-3xl"><div class="h-full w-full border-radius-3xl bg-token-bg-elevated-secondary corner-superellipse/1.1 overflow-clip rounded-3xl lxnfua_clipPathFallback"><div class="pointer-events-none absolute inset-x-4 top-12 bottom-4"><div class="pointer-events-none sticky z-40 shrink-0 z-1!"><div class="sticky bg-token-border-light"></div></div></div><div class="relative"><div class=""><div class="relative z-0 flex max-w-full"><div id="code-block-viewer" dir="ltr" class="q9tKkq_viewer cm-editor z-10 light:cm-light dark:cm-light flex h-full w-full flex-col items-stretch ͼs ͼ16"><div class="cm-scroller"><pre class="cm-content q9tKkq_readonly m-0"><code><span class="ͼ10">npm</span><span> install</span></code></pre></div></div></div></div></div></div></div></div></div><div class=""><div class=""></div></div></div></div></div></pre>

---

## Run Development Server

<pre class="overflow-visible! px-0!" data-start="1703" data-end="1726"><div class="relative w-full mt-4 mb-1"><div class=""><div class="relative"><div class="h-full min-h-0 min-w-0"><div class="h-full min-h-0 min-w-0"><div class="border border-token-border-light border-radius-3xl corner-superellipse/1.1 rounded-3xl"><div class="h-full w-full border-radius-3xl bg-token-bg-elevated-secondary corner-superellipse/1.1 overflow-clip rounded-3xl lxnfua_clipPathFallback"><div class="pointer-events-none absolute inset-x-4 top-12 bottom-4"><div class="pointer-events-none sticky z-40 shrink-0 z-1!"><div class="sticky bg-token-border-light"></div></div></div><div class="relative"><div class=""><div class="relative z-0 flex max-w-full"><div id="code-block-viewer" dir="ltr" class="q9tKkq_viewer cm-editor z-10 light:cm-light dark:cm-light flex h-full w-full flex-col items-stretch ͼs ͼ16"><div class="cm-scroller"><pre class="cm-content q9tKkq_readonly m-0"><code><span class="ͼ10">npm</span><span> run dev</span></code></pre></div></div></div></div></div></div></div></div></div><div class=""><div class=""></div></div></div></div></div></pre>

---

## Build Project

<pre class="overflow-visible! px-0!" data-start="1751" data-end="1776"><div class="relative w-full mt-4 mb-1"><div class=""><div class="relative"><div class="h-full min-h-0 min-w-0"><div class="h-full min-h-0 min-w-0"><div class="border border-token-border-light border-radius-3xl corner-superellipse/1.1 rounded-3xl"><div class="h-full w-full border-radius-3xl bg-token-bg-elevated-secondary corner-superellipse/1.1 overflow-clip rounded-3xl lxnfua_clipPathFallback"><div class="pointer-events-none absolute inset-x-4 top-12 bottom-4"><div class="pointer-events-none sticky z-40 shrink-0 z-1!"><div class="sticky bg-token-border-light"></div></div></div><div class="relative"><div class=""><div class="relative z-0 flex max-w-full"><div id="code-block-viewer" dir="ltr" class="q9tKkq_viewer cm-editor z-10 light:cm-light dark:cm-light flex h-full w-full flex-col items-stretch ͼs ͼ16"><div class="cm-scroller"><pre class="cm-content q9tKkq_readonly m-0"><code><span class="ͼ10">npm</span><span> run build</span></code></pre></div></div></div></div></div></div></div></div></div><div class=""><div class=""></div></div></div></div></div></pre>

---

# Environment Variables

Required variables:

<pre class="overflow-visible! px-0!" data-start="1829" data-end="1882"><div class="relative w-full mt-4 mb-1"><div class=""><div class="relative"><div class="h-full min-h-0 min-w-0"><div class="h-full min-h-0 min-w-0"><div class="border border-token-border-light border-radius-3xl corner-superellipse/1.1 rounded-3xl"><div class="h-full w-full border-radius-3xl bg-token-bg-elevated-secondary corner-superellipse/1.1 overflow-clip rounded-3xl lxnfua_clipPathFallback"><div class="pointer-events-none absolute inset-x-4 top-12 bottom-4"><div class="pointer-events-none sticky z-40 shrink-0 z-1!"><div class="sticky bg-token-border-light"></div></div></div><div class="relative"><div class=""><div class="relative z-0 flex max-w-full"><div id="code-block-viewer" dir="ltr" class="q9tKkq_viewer cm-editor z-10 light:cm-light dark:cm-light flex h-full w-full flex-col items-stretch ͼs ͼ16"><div class="cm-scroller"><pre class="cm-content q9tKkq_readonly m-0"><code><span>VITE_SUPABASE_URL=</span><br/><span>VITE_SUPABASE_ANON_KEY=</span></code></pre></div></div></div></div></div></div></div></div></div><div class=""><div class=""></div></div></div></div></div></pre>

Additional deployment variables may exist for Cloudflare Workers.

---

# Deployment

## Cloudflare Workers Deployment

<pre class="overflow-visible! px-0!" data-start="2004" data-end="2035"><div class="relative w-full mt-4 mb-1"><div class=""><div class="relative"><div class="h-full min-h-0 min-w-0"><div class="h-full min-h-0 min-w-0"><div class="border border-token-border-light border-radius-3xl corner-superellipse/1.1 rounded-3xl"><div class="h-full w-full border-radius-3xl bg-token-bg-elevated-secondary corner-superellipse/1.1 overflow-clip rounded-3xl lxnfua_clipPathFallback"><div class="pointer-events-none absolute inset-x-4 top-12 bottom-4"><div class="pointer-events-none sticky z-40 shrink-0 z-1!"><div class="sticky bg-token-border-light"></div></div></div><div class="relative"><div class=""><div class="relative z-0 flex max-w-full"><div id="code-block-viewer" dir="ltr" class="q9tKkq_viewer cm-editor z-10 light:cm-light dark:cm-light flex h-full w-full flex-col items-stretch ͼs ͼ16"><div class="cm-scroller"><pre class="cm-content q9tKkq_readonly m-0"><code><span>npx wrangler deploy</span></code></pre></div></div></div></div></div></div></div></div></div><div class=""><div class=""></div></div></div></div></div></pre>

---

# Deployment Flow

<pre class="overflow-visible! px-0!" data-start="2061" data-end="2147"><div class="relative w-full mt-4 mb-1"><div class=""><div class="relative"><div class="h-full min-h-0 min-w-0"><div class="h-full min-h-0 min-w-0"><div class="border border-token-border-light border-radius-3xl corner-superellipse/1.1 rounded-3xl"><div class="h-full w-full border-radius-3xl bg-token-bg-elevated-secondary corner-superellipse/1.1 overflow-clip rounded-3xl lxnfua_clipPathFallback"><div class="pointer-events-none absolute end-1.5 top-1 z-2 md:end-2 md:top-1"></div><div class="relative"><div class="pe-11 pt-3"><div class="relative z-0 flex max-w-full"><div id="code-block-viewer" dir="ltr" class="q9tKkq_viewer cm-editor z-10 light:cm-light dark:cm-light flex h-full w-full flex-col items-stretch ͼs ͼ16"><div class="cm-scroller"><pre class="cm-content q9tKkq_readonly m-0"><code><span>GitHub</span><br/><span>   ↓</span><br/><span>Build</span><br/><span>   ↓</span><br/><span>Wrangler</span><br/><span>   ↓</span><br/><span>Cloudflare Workers</span><br/><span>   ↓</span><br/><span>Custom Domain</span></code></pre></div></div></div></div></div></div></div></div></div><div class=""><div class=""></div></div></div></div></div></pre>

---

# Current Engineering Focus

Main stabilization priorities:

* authentication flow
* redirect stability
* SSR hydration consistency
* dashboard loading states
* deployment consistency

---

# Documentation

Detailed engineering docs:

* `/docs/architecture.md`
* `/docs/roadmap.md`
* `/docs/auth.md`
* `/docs/deployment.md`
* `/docs/known-issues.md`

---

# Current Project Status

<pre class="overflow-visible! px-0!" data-start="2536" data-end="2831"><div class="relative w-full mt-4 mb-1"><div class=""><div class="relative"><div class="h-full min-h-0 min-w-0"><div class="h-full min-h-0 min-w-0"><div class="border border-token-border-light border-radius-3xl corner-superellipse/1.1 rounded-3xl"><div class="h-full w-full border-radius-3xl bg-token-bg-elevated-secondary corner-superellipse/1.1 overflow-clip rounded-3xl lxnfua_clipPathFallback"><div class="pointer-events-none absolute end-1.5 top-1 z-2 md:end-2 md:top-1"></div><div class="relative"><div class="pe-11 pt-3"><div class="relative z-0 flex max-w-full"><div id="code-block-viewer" dir="ltr" class="q9tKkq_viewer cm-editor z-10 light:cm-light dark:cm-light flex h-full w-full flex-col items-stretch ͼs ͼ16"><div class="cm-scroller"><pre class="cm-content q9tKkq_readonly m-0"><code><span>Frontend UI           → Mostly Stable</span><br/><span>Authentication        → Needs Stabilization</span><br/><span>Routing               → Medium Stability</span><br/><span>Deployment            → Stable on Cloudflare</span><br/><span>Role Management       → Needs Refinement</span><br/><span>Database Integration  → Stable</span><br/><span>SSR Hydration         → Under Investigation</span></code></pre></div></div></div></div></div></div></div></div></div><div class=""><div class=""></div></div></div></div></div></pre>

---

# Engineering Philosophy

Brainexa is being built with focus on:

* modular architecture
* scalable deployment
* production-grade systems
* AI-native workflows
* long-term maintainability

---

# Future Vision

Brainexa aims to evolve into a complete AI-powered education ecosystem featuring:

* intelligent tutoring
* automated assessments
* scalable teacher tools
* analytics-driven learning
* monetized educational infrastructure

---

# Maintainer

<pre class="overflow-visible! px-0!" data-start="3291" data-end="3323"><div class="relative w-full mt-4 mb-1"><div class=""><div class="relative"><div class="h-full min-h-0 min-w-0"><div class="h-full min-h-0 min-w-0"><div class="border border-token-border-light border-radius-3xl corner-superellipse/1.1 rounded-3xl"><div class="h-full w-full border-radius-3xl bg-token-bg-elevated-secondary corner-superellipse/1.1 overflow-clip rounded-3xl lxnfua_clipPathFallback"><div class="pointer-events-none absolute end-1.5 top-1 z-2 md:end-2 md:top-1"></div><div class="relative"><div class="pe-11 pt-3"><div class="relative z-0 flex max-w-full"><div id="code-block-viewer" dir="ltr" class="q9tKkq_viewer cm-editor z-10 light:cm-light dark:cm-light flex h-full w-full flex-col items-stretch ͼs ͼ16"><div class="cm-scroller"><pre class="cm-content q9tKkq_readonly m-0"><code><span>Ayush Gupta | AR Engineering</span></code></pre></div></div></div></div></div></div></div></div></div></div></div></div></pre>
