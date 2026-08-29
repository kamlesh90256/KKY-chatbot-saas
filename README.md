<div align="center">

# 🤖 KKY Chatbot SaaS

### Production-Ready AI Chatbot SaaS Platform

<img
src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=900&color=00D9FF&center=true&vCenter=true&width=850&lines=Real-Time+AI+Chat;SSE+Streaming;Multi-User+SaaS;Stripe+Subscriptions;Resume+%26+Document+Processing;Admin+Analytics;Docker+%2B+Kubernetes;Production-Oriented+Architecture"
alt="Typing Animation"
/>

<br/>
<br/>

<a href="https://kky-chatbot-demo.vercel.app/">
<img src="https://img.shields.io/badge/🚀_LIVE_DEMO-KKY_Chatbot-00D9FF?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>

<a href="https://github.com/kamlesh90256/KKY-chatbot-saas">
<img src="https://img.shields.io/badge/💻_SOURCE_CODE-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/>
<br/>

<img src="https://img.shields.io/github/stars/kamlesh90256/KKY-chatbot-saas?style=for-the-badge&logo=github"/>
<img src="https://img.shields.io/github/forks/kamlesh90256/KKY-chatbot-saas?style=for-the-badge&logo=github"/>
<img src="https://img.shields.io/github/last-commit/kamlesh90256/KKY-chatbot-saas?style=for-the-badge"/>
<img src="https://img.shields.io/github/repo-size/kamlesh90256/KKY-chatbot-saas?style=for-the-badge"/>

<br/>
<br/>

<img src="https://skillicons.dev/icons?i=nextjs,react,typescript,nodejs,express,postgresql,prisma,docker,kubernetes,githubactions"/>

</div>

---

# 🧠 What is KKY Chatbot SaaS?

**KKY Chatbot SaaS** is a production-oriented AI chatbot platform
designed around real-time conversational AI, multi-user access,
subscription management, file processing and administrative workflows.

The platform combines:

```text
Modern Web Application
        +
AI Conversation Engine
        +
Streaming Responses
        +
Authentication
        +
Subscriptions
        +
File Processing
        +
Admin Analytics
        +
Cloud-Native Deployment
```

The current project documentation describes the platform as a
Next.js + Node.js AI SaaS with real-time SSE chat, authentication,
conversation history, Stripe subscriptions, file handling,
admin functionality and Docker/Kubernetes deployment. 

---

# 🌐 Live Application

<div align="center">

## 🚀 Try KKY Chatbot SaaS

<a href="https://kky-chatbot-demo.vercel.app/">

<img src="https://img.shields.io/badge/OPEN_LIVE_DEMO-00D9FF?style=for-the-badge&logo=vercel&logoColor=white"/>

</a>

<br/>
<br/>

**https://kky-chatbot-demo.vercel.app/**

</div>

---

# 🎯 Product Vision

The goal is not simply to create a chatbot UI.

The system is designed as a complete SaaS product:

```text
User
 ↓
Authentication
 ↓
AI Chat
 ↓
Conversation History
 ↓
Files / Resume
 ↓
Subscription
 ↓
Premium Features
 ↓
Admin Management
```

---

# ⚡ Core Product Experience

```mermaid
flowchart LR

    USER["👤 User"]

    AUTH["🔐 Authentication"]

    CHAT["💬 AI Chat"]

    STREAM["🌊 SSE Streaming"]

    HISTORY["🗂️ Conversation History"]

    FILES["📄 File Processing"]

    BILLING["💳 Subscription"]

    ADMIN["👨‍💼 Admin"]

    USER --> AUTH
    AUTH --> CHAT
    CHAT --> STREAM
    CHAT --> HISTORY
    CHAT --> FILES
    AUTH --> BILLING
    ADMIN --> CHAT
```

---

# ✨ Features

<table>
<tr>

<td width="50%">

## 💬 Real-Time AI Chat

- Conversational AI
- Streaming responses
- SSE transport
- Markdown responses
- Syntax highlighting

</td>

<td width="50%">

## 👥 Multi-User SaaS

- User signup
- User login
- Profiles
- Conversation history
- Multi-conversation management

</td>

</tr>

<tr>

<td width="50%">

## 💳 Subscription System

- Stripe checkout
- Subscription management
- Payment webhooks
- Premium tiers
- Subscription tracking

</td>

<td width="50%">

## 📄 File Processing

- File uploads
- Resume processing
- Document workflows
- Candidate-related data

</td>

</tr>

<tr>

<td width="50%">

## 👨‍💼 Admin Dashboard

- User management
- Analytics
- Platform monitoring
- Administrative workflows

</td>

<td width="50%">

## ☁️ Cloud-Ready

- Docker
- Docker Compose
- Kubernetes
- GitHub Actions
- Production deployment

</td>

</tr>
</table>

The documented feature set includes SSE chat, multi-user support,
Stripe subscription management, resume/document handling, admin
analytics and cloud-ready deployment. 

---

# 🏗️ Complete System Architecture

```mermaid
flowchart TB

    USER["👤 USER"]

    subgraph CLIENT["🌐 CLIENT"]
        NEXT["▲ Next.js"]
        REACT["⚛️ React"]
        TS["🔷 TypeScript"]
        UI["🎨 Tailwind UI"]
        STATE["🧠 Zustand"]
        QUERY["🔄 React Query"]
    end

    subgraph API["⚙️ APPLICATION SERVER"]
        EXPRESS["🟢 Express.js"]
        ROUTES["🛣️ API Routes"]
        VALIDATION["✅ Zod Validation"]
        AUTH["🔐 Authentication"]
        SERVICES["🧩 Service Layer"]
    end

    subgraph DATA["🗄️ DATA LAYER"]
        POSTGRES[("🐘 PostgreSQL")]
        PRISMA["🔷 Prisma ORM"]
    end

    subgraph AI["🤖 AI LAYER"]
        OPENAI["✨ OpenAI"]
        FALLBACK["🔄 Local Fallback"]
        SSE["🌊 SSE Streaming"]
    end

    subgraph BILLING["💳 BILLING"]
        STRIPE["Stripe"]
        WEBHOOK["Stripe Webhooks"]
    end

    subgraph FILES["📄 FILE PROCESSING"]
        UPLOAD["File Upload"]
        RESUME["Resume Processing"]
    end

    subgraph ADMIN["👨‍💼 ADMIN"]
        DASHBOARD["📊 Admin Dashboard"]
        ANALYTICS["📈 Analytics"]
        USERS["👥 User Management"]
    end

    subgraph DEVOPS["☁️ DEVOPS"]
        DOCKER["🐳 Docker"]
        K8S["☸️ Kubernetes"]
        CICD["⚙️ GitHub Actions"]
    end

    USER --> NEXT

    NEXT --> REACT
    REACT --> TS
    REACT --> UI
    REACT --> STATE
    REACT --> QUERY

    REACT --> EXPRESS

    EXPRESS --> ROUTES
    ROUTES --> VALIDATION
    ROUTES --> AUTH
    ROUTES --> SERVICES

    SERVICES --> PRISMA
    PRISMA --> POSTGRES

    SERVICES --> OPENAI
    SERVICES --> FALLBACK
    OPENAI --> SSE

    SERVICES --> STRIPE
    STRIPE --> WEBHOOK

    SERVICES --> UPLOAD
    UPLOAD --> RESUME

    EXPRESS --> DASHBOARD
    DASHBOARD --> ANALYTICS
    DASHBOARD --> USERS

    DOCKER --> EXPRESS
    K8S --> DOCKER
    CICD --> DOCKER
```

---

# 🔄 A-to-Z Architecture

```mermaid
flowchart LR

    A["A — 👤 User"]

    B["B — 🌐 Browser"]

    C["C — ▲ Next.js"]

    D["D — ⚛️ React"]

    E["E — 🔐 Authentication"]

    F["F — 💬 Chat Request"]

    G["G — 🟢 Express API"]

    H["H — ✅ Validation"]

    I["I — 🧩 Service Layer"]

    J["J — 🤖 AI Provider"]

    K["K — 🌊 SSE Stream"]

    L["L — 💬 Client Response"]

    M["M — 🗂️ Conversation"]

    N["N — 🐘 PostgreSQL"]

    O["O — 🔷 Prisma"]

    P["P — 📄 File Processing"]

    Q["Q — 💳 Stripe"]

    R["R — 🔔 Webhooks"]

    S["S — 👨‍💼 Admin"]

    T["T — 📊 Analytics"]

    U["U — 🐳 Docker"]

    V["V — ☸️ Kubernetes"]

    W["W — ⚙️ CI/CD"]

    X["X — ☁️ Cloud"]

    Y["Y — 📈 Monitoring"]

    Z["Z — 🚀 Production"]

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G
    G --> H
    H --> I
    I --> J
    J --> K
    K --> L
    L --> M
    M --> O
    O --> N
    I --> P
    I --> Q
    Q --> R
    I --> S
    S --> T
    I --> U
    U --> V
    V --> W
    W --> X
    X --> Y
    Y --> Z
```

---

# 💬 Real-Time Chat Architecture

The primary conversational path uses Server-Sent Events.

```mermaid
sequenceDiagram

    participant U as 👤 User
    participant F as ⚛️ Frontend
    participant A as 🟢 Express API
    participant AI as ✨ AI Provider
    participant DB as 🐘 PostgreSQL

    U->>F: Enter message

    F->>A: POST /api/chat/stream

    A->>DB: Load conversation

    DB-->>A: Conversation context

    A->>AI: Send AI request

    AI-->>A: Stream token

    A-->>F: SSE event

    F-->>U: Render partial response

    AI-->>A: Continue stream
    A-->>F: SSE event
    F-->>U: Update response

    AI-->>A: Stream complete

    A->>DB: Save message

    DB-->>A: Saved

    A-->>F: Complete event

    F-->>U: Final answer
```

---

# 🌊 Why SSE?

Instead of waiting for the entire AI response:

```text
User
 ↓
Request
 ↓
Wait
 ↓
Complete Answer
```

the system streams the response:

```text
User
 ↓
Request
 ↓
Token 1
 ↓
Token 2
 ↓
Token 3
 ↓
Token 4
 ↓
...
 ↓
Complete
```

This improves perceived responsiveness in conversational interfaces.

The repository documents `/api/chat/stream` as an SSE-based streaming
chat endpoint returning `text/event-stream`. 

---

# 🧠 AI Request Pipeline

```mermaid
flowchart LR

    Q["❓ User Question"]

    API["⚡ Chat API"]

    CONTEXT["🗂️ Conversation Context"]

    MODEL["✨ OpenAI"]

    FALLBACK["🔄 Local Fallback"]

    STREAM["🌊 SSE"]

    UI["💬 Chat UI"]

    Q --> API
    API --> CONTEXT
    CONTEXT --> MODEL

    MODEL --> STREAM
    MODEL --> FALLBACK

    STREAM --> UI
```

---

# 💾 Conversation Architecture

```text
User
 │
 ├── Conversation 1
 │      ├── Message
 │      ├── Message
 │      └── Message
 │
 ├── Conversation 2
 │      ├── Message
 │      └── Message
 │
 └── Conversation 3
        ├── Message
        └── Message
```

The platform maintains chats, messages and conversation history as part
of the documented database functionality. 

---

# 🔐 Authentication Architecture

```mermaid
sequenceDiagram

    participant U as 👤 User
    participant F as ⚛️ Frontend
    participant A as 🟢 Express
    participant D as 🐘 PostgreSQL

    U->>F: Signup / Login

    F->>A: Authentication Request

    A->>D: Find / Create User

    D-->>A: User Data

    A->>A: Authenticate

    A-->>F: Authentication Result

    F->>A: Protected Request

    A->>A: Validate Authentication

    A->>D: Authorized Query

    D-->>A: Result

    A-->>F: JSON Response
```

---

# 💳 Stripe Subscription Architecture

```mermaid
flowchart TD

    USER["👤 User"]

    APP["⚛️ Application"]

    CHECKOUT["💳 Stripe Checkout"]

    STRIPE["Stripe"]

    WEBHOOK["🔔 Stripe Webhook"]

    API["🟢 Express"]

    DB[("🐘 PostgreSQL")]

    PREMIUM["⭐ Premium Access"]

    USER --> APP

    APP --> CHECKOUT

    CHECKOUT --> STRIPE

    STRIPE --> WEBHOOK

    WEBHOOK --> API

    API --> DB

    DB --> PREMIUM
```

The documented payment surface includes checkout, webhooks and
subscription retrieval. 

---

# 📄 File Processing Architecture

```mermaid
flowchart LR

    USER["👤 User"]

    UI["⚛️ Frontend"]

    UPLOAD["📤 Upload API"]

    PROCESS["⚙️ Processing Service"]

    RESUME["📄 Resume / Document"]

    DB[("🐘 PostgreSQL")]

    USER --> UI
    UI --> UPLOAD
    UPLOAD --> PROCESS
    PROCESS --> RESUME
    PROCESS --> DB
```

The platform documentation includes file uploads and resume processing as
part of the backend functionality. 

---

# 👨‍💼 Admin Architecture

```mermaid
flowchart TB

    ADMIN["👨‍💼 Admin"]

    AUTH["🔐 Authentication"]

    DASH["📊 Admin Dashboard"]

    USERS["👥 Users"]

    ANALYTICS["📈 Analytics"]

    SUBS["💳 Subscriptions"]

    CHATS["💬 Conversations"]

    DB[("🐘 PostgreSQL")]

    ADMIN --> AUTH
    AUTH --> DASH

    DASH --> USERS
    DASH --> ANALYTICS
    DASH --> SUBS
    DASH --> CHATS

    USERS --> DB
    ANALYTICS --> DB
    SUBS --> DB
    CHATS --> DB
```

---

# 📊 SaaS Data Architecture

```mermaid
flowchart TB

    USERS["👥 Users"]

    CHATS["💬 Conversations"]

    MESSAGES["📝 Messages"]

    FILES["📄 Files"]

    SUBSCRIPTIONS["💳 Subscriptions"]

    PAYMENTS["💰 Payments"]

    INTERVIEWS["🎤 Interviews"]

    CANDIDATES["👤 Candidate Data"]

    DB[("🐘 PostgreSQL")]

    USERS --> DB

    CHATS --> DB
    MESSAGES --> DB

    FILES --> DB

    SUBSCRIPTIONS --> DB
    PAYMENTS --> DB

    INTERVIEWS --> DB
    CANDIDATES --> DB
```

The existing documentation describes database areas for users,
authentication, chats/messages/history, files/resumes, subscriptions,
payments, interviews and candidate data. 

---

# 🧩 Frontend Architecture

```mermaid
flowchart TD

    NEXT["▲ Next.js"]

    APP["App Router"]

    COMPONENTS["🧩 Reusable Components"]

    CHAT["💬 Chat Interface"]

    ADMIN["📊 Admin Dashboard"]

    STATE["🧠 Zustand"]

    QUERY["🔄 React Query"]

    MOTION["✨ Framer Motion"]

    MARKDOWN["📝 Markdown Renderer"]

    API["🌐 API Client"]

    BACKEND["🟢 Express"]

    NEXT --> APP

    APP --> COMPONENTS

    COMPONENTS --> CHAT
    COMPONENTS --> ADMIN

    CHAT --> STATE
    CHAT --> QUERY
    CHAT --> MARKDOWN
    COMPONENTS --> MOTION

    QUERY --> API
    API --> BACKEND
```

The current README documents Next.js 15, React, TypeScript, Tailwind,
Framer Motion, Zustand and React Query on the frontend. 

---

# 🟢 Backend Architecture

```mermaid
flowchart TB

    CLIENT["⚛️ Frontend"]

    EXPRESS["🟢 Express"]

    ROUTES["🛣️ Routes"]

    VALIDATION["✅ Zod"]

    AUTH["🔐 Authentication"]

    SERVICES["🧩 Services"]

    DB["🔷 Prisma"]

    POSTGRES[("🐘 PostgreSQL")]

    AI["🤖 AI"]

    STRIPE["💳 Stripe"]

    FILES["📄 Files"]

    CLIENT --> EXPRESS

    EXPRESS --> ROUTES

    ROUTES --> VALIDATION
    ROUTES --> AUTH
    ROUTES --> SERVICES

    SERVICES --> DB
    DB --> POSTGRES

    SERVICES --> AI
    SERVICES --> STRIPE
    SERVICES --> FILES
```

---

# 🗄️ Database Layer

The documented stack uses PostgreSQL with Prisma ORM. 

```text
                    PostgreSQL
                         │
       ┌─────────────────┼─────────────────┐
       │                 │                 │
       ▼                 ▼                 ▼
     Users        Conversations      Subscriptions
       │                 │                 │
       │                 ▼                 ▼
       │              Messages          Payments
       │
       ├─────────────────────────────────────
       │
       ▼
     Files
       │
       ▼
   Interviews
       │
       ▼
   Candidates
```

---

# 🔌 API Architecture

```mermaid
flowchart TB

    CLIENT["⚛️ Client"]

    API["🌐 API"]

    CHAT["💬 /api/chat"]

    AUTH["🔐 /api/auth"]

    PAYMENT["💳 /api/payments"]

    UPLOAD["📄 /api/upload"]

    RESUME["📄 /api/resume"]

    HEALTH["❤️ /api/health"]

    CLIENT --> API

    API --> CHAT
    API --> AUTH
    API --> PAYMENT
    API --> UPLOAD
    API --> RESUME
    API --> HEALTH
```

---

# 📡 Chat API

```http
POST /api/chat/stream
```

Request concept:

```json
{
  "message": "Create a backend roadmap",
  "conversationId": "optional-id"
}
```

Response:

```text
Content-Type: text/event-stream
```

The repository documents this streaming endpoint and payload pattern. 

---

# 🔐 Authentication API

```http
POST /api/auth/signup
POST /api/auth/login
GET  /api/auth/me
```

---

# 💳 Payment API

```http
POST /api/payments/checkout
POST /api/payments/webhook
GET  /api/payments/subscription
```

---

# 📄 Upload API

```http
POST /api/upload
POST /api/resume
```

---

# ❤️ Health API

```http
GET /api/health
```

---

# 🐳 Docker Architecture

```mermaid
flowchart TB

    COMPOSE["🐳 Docker Compose"]

    FRONTEND["⚛️ Frontend Container"]

    BACKEND["🟢 Backend Container"]

    DATABASE["🐘 PostgreSQL"]

    FRONTEND --> BACKEND
    BACKEND --> DATABASE

    COMPOSE --> FRONTEND
    COMPOSE --> BACKEND
    COMPOSE --> DATABASE
```

The repository includes Docker Compose plus Docker support for frontend
and backend deployment. 

---

# ☸️ Kubernetes Architecture

```mermaid
flowchart TB

    INTERNET["🌍 Internet"]

    INGRESS["🌐 Ingress"]

    FRONTEND["⚛️ Frontend Pod"]

    BACKEND1["🟢 Backend Pod 1"]
    BACKEND2["🟢 Backend Pod 2"]
    BACKEND3["🟢 Backend Pod 3"]

    SERVICE["🔗 Backend Service"]

    DATABASE["🐘 PostgreSQL"]

    INTERNET --> INGRESS

    INGRESS --> FRONTEND

    INGRESS --> SERVICE

    SERVICE --> BACKEND1
    SERVICE --> BACKEND2
    SERVICE --> BACKEND3

    BACKEND1 --> DATABASE
    BACKEND2 --> DATABASE
    BACKEND3 --> DATABASE
```

The repository contains Kubernetes manifests under `k8s/`. 

---

# ⚙️ CI/CD Architecture

```mermaid
flowchart LR

    DEV["👨‍💻 Developer"]

    GIT["Git Push"]

    ACTIONS["⚙️ GitHub Actions"]

    BUILD["🔨 Build"]

    TEST["🧪 Test"]

    LINT["🔍 Lint"]

    PRISMA["🔷 Prisma Generate"]

    DEPLOY["🚀 Deploy"]

    DEV --> GIT
    GIT --> ACTIONS

    ACTIONS --> BUILD
    BUILD --> TEST
    TEST --> LINT
    LINT --> PRISMA
    PRISMA --> DEPLOY
```

The project documentation says GitHub Actions builds frontend/backend,
runs tests and linting and generates the Prisma client. 

---

# ☁️ Production Architecture

```mermaid
flowchart TB

    USER["🌍 Users"]

    VERCEL["▲ Vercel"]

    FRONTEND["⚛️ Next.js"]

    API["🟢 Node.js / Express"]

    DATABASE[("🐘 PostgreSQL")]

    AI["✨ OpenAI"]

    STRIPE["💳 Stripe"]

    K8S["☸️ Kubernetes"]

    USER --> VERCEL

    VERCEL --> FRONTEND

    FRONTEND --> API

    API --> DATABASE
    API --> AI
    API --> STRIPE

    K8S --> API
```

---

# 🔐 Security Architecture

```text
                     INTERNET
                         │
                         ▼
                  ⚛️ FRONTEND
                         │
                         ▼
                   🟢 API
                         │
             ┌───────────┼───────────┐
             │           │           │
             ▼           ▼           ▼
          Helmet       CORS       Rate Limit
             │           │           │
             └───────────┼───────────┘
                         ▼
                    Authentication
                         │
                         ▼
                       JWT
                         │
                         ▼
                  Protected Routes
```

The documented security stack includes Helmet, JWT authentication,
CORS and rate limiting. 

---

# 🛡️ Security Principles

```text
✅ JWT Authentication
✅ Protected Routes
✅ Helmet Security Headers
✅ CORS Configuration
✅ Rate Limiting
✅ Zod Request Validation
✅ Environment-Based Secrets
✅ Stripe Webhook Handling
```

---

# 📂 Project Structure

```text
KKY-chatbot-saas/
│
├── .github/
│   └── workflows/
│
├── backend/
│   ├── src/
│   │   ├── routes/
│   │   ├── services/
│   │   ├── middleware/
│   │   └── index.ts
│   │
│   └── prisma/
│       └── schema
│
├── frontend/
│   ├── app/
│   ├── src/
│   │   ├── components/
│   │   └── store/
│   │
│   └── ...
│
├── k8s/
│   └── Kubernetes manifests
│
├── docker-compose.yml
│
├── render.yaml
│
├── DEPLOYMENT_GUIDE.md
├── DEPLOYMENT_CHECKLIST.md
├── LOCAL_DEVELOPMENT.md
├── QUICK_REFERENCE.md
├── LICENSE
└── README.md
```

The repository currently contains the frontend/backend split, Kubernetes
directory, GitHub workflow directory, Docker Compose, deployment guides,
license and other project documentation. 

---

# 🧰 Technology Stack

<div align="center">

### Frontend

<img src="https://skillicons.dev/icons?i=nextjs,react,typescript,tailwind"/>

<br/><br/>

### Backend

<img src="https://skillicons.dev/icons?i=nodejs,express,typescript"/>

<br/><br/>

### Database

<img src="https://skillicons.dev/icons?i=postgresql,prisma"/>

<br/><br/>

### AI

<img src="https://skillicons.dev/icons?i=openai"/>

<br/><br/>

### DevOps

<img src="https://skillicons.dev/icons?i=docker,kubernetes,githubactions"/>

</div>

---

# 🛠️ Detailed Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js 15 |
| UI | React |
| Language | TypeScript |
| Styling | Tailwind CSS |
| Animation | Framer Motion |
| State | Zustand |
| Data Fetching | React Query |
| Backend | Node.js |
| API | Express.js |
| Validation | Zod |
| Database | PostgreSQL |
| ORM | Prisma |
| AI | OpenAI API |
| Streaming | Server-Sent Events |
| Authentication | JWT |
| Security | Helmet + CORS + Rate Limiting |
| Payments | Stripe |
| Containers | Docker |
| Orchestration | Kubernetes |
| CI/CD | GitHub Actions |

This matches the documented technical stack in the repository README. 

---

# 🧠 SaaS Architecture Principles

## 1. Separation of Concerns

```text
Presentation
     ↓
API
     ↓
Business Logic
     ↓
Persistence
     ↓
External Services
```

## 2. Streaming-First UX

```text
Request
  ↓
AI Processing
  ↓
Immediate Stream
  ↓
Progressive Rendering
```

## 3. Service Isolation

```text
Chat Service
    │
    ├── AI
    ├── Conversation
    └── Streaming

Payment Service
    │
    ├── Checkout
    ├── Subscription
    └── Webhook

File Service
    │
    ├── Upload
    └── Processing
```

---

# 🧪 Testing Strategy

```mermaid
flowchart TD

    TEST["🧪 Test Strategy"]

    UNIT["Unit Tests"]

    API["API Tests"]

    INTEGRATION["Integration Tests"]

    E2E["End-to-End"]

    AI["AI Behavior Tests"]

    PAYMENT["Payment Tests"]

    TEST --> UNIT
    TEST --> API
    TEST --> INTEGRATION
    TEST --> E2E
    TEST --> AI
    TEST --> PAYMENT
```

Important flows:

```text
Authentication
Chat Streaming
Conversation History
File Upload
Resume Processing
Subscriptions
Stripe Webhooks
Admin Access
Health Check
```

---

# 🚨 Failure Handling

```text
AI Failure
   ↓
Fallback Provider
   ↓
Graceful Response
```

```text
Payment Failure
   ↓
Webhook / Verification
   ↓
Do Not Grant Invalid Subscription
```

```text
Database Failure
   ↓
Error Handling
   ↓
Safe API Response
```

```text
Streaming Failure
   ↓
Close SSE Stream
   ↓
Client Error State
```

---

# 📈 Scalability Architecture

```mermaid
flowchart TB

    CLIENTS["👥 Clients"]

    LB["⚖️ Load Balancer"]

    API1["🟢 API Instance 1"]
    API2["🟢 API Instance 2"]
    API3["🟢 API Instance 3"]

    REDIS["🔴 Redis"]

    DB[("🐘 PostgreSQL")]

    AI["✨ AI Provider"]

    STRIPE["💳 Stripe"]

    CLIENTS --> LB

    LB --> API1
    LB --> API2
    LB --> API3

    API1 --> REDIS
    API2 --> REDIS
    API3 --> REDIS

    API1 --> DB
    API2 --> DB
    API3 --> DB

    API1 --> AI
    API2 --> AI
    API3 --> AI

    API1 --> STRIPE
```

---

# 🔭 Future Evolution

## AI

- [ ] RAG pipeline
- [ ] Conversation memory
- [ ] Better model routing
- [ ] AI evaluation
- [ ] Tool calling
- [ ] Agent workflows

## SaaS

- [ ] Team workspaces
- [ ] Organization accounts
- [ ] Usage metering
- [ ] Billing analytics
- [ ] Enterprise roles

## Infrastructure

- [ ] Redis
- [ ] Background jobs
- [ ] Queue-based processing
- [ ] Observability
- [ ] Distributed tracing
- [ ] Horizontal scaling

## AI Multimodality

- [ ] Image understanding
- [ ] Voice input
- [ ] Voice output
- [ ] Multimodal conversations

---

# 🧭 End-to-End SaaS Flow

```mermaid
flowchart LR

    USER["👤 User"]

    AUTH["🔐 Auth"]

    CHAT["💬 Chat"]

    AI["🤖 AI"]

    STREAM["🌊 Stream"]

    HISTORY["🗂️ History"]

    FILE["📄 File"]

    BILLING["💳 Billing"]

    PREMIUM["⭐ Premium"]

    ADMIN["👨‍💼 Admin"]

    USER --> AUTH
    AUTH --> CHAT

    CHAT --> AI
    AI --> STREAM
    STREAM --> USER

    CHAT --> HISTORY

    USER --> FILE

    AUTH --> BILLING
    BILLING --> PREMIUM

    ADMIN --> HISTORY
    ADMIN --> BILLING
```

---

# 🧩 Product Modules

```text
KKY Chatbot SaaS
│
├── 💬 Conversational AI
│
├── 👥 User Management
│
├── 🔐 Authentication
│
├── 🗂️ Conversation History
│
├── 📄 File / Resume Processing
│
├── 💳 Subscription Management
│
├── 👨‍💼 Admin Dashboard
│
├── 🌊 Real-Time Streaming
│
└── ☁️ Cloud Deployment
```

---

# 📊 Engineering Surface

```text
Frontend Engineering
        ↓
Next.js + React + TypeScript
        ↓
API Engineering
        ↓
Express + REST
        ↓
Data Engineering
        ↓
PostgreSQL + Prisma
        ↓
AI Engineering
        ↓
OpenAI + Streaming
        ↓
Security Engineering
        ↓
JWT + Helmet + CORS + Rate Limits
        ↓
Payments
        ↓
Stripe
        ↓
Infrastructure
        ↓
Docker + Kubernetes
        ↓
CI/CD
        ↓
GitHub Actions
```

---

# 🚀 Local Development

## Prerequisites

```text
Node.js 18+
npm / yarn
PostgreSQL 13+
OpenAI API Key
Stripe API Keys
```

The current project documentation lists Node.js 18+, PostgreSQL 13+,
OpenAI and Stripe credentials as prerequisites. 

---

# 1️⃣ Clone Repository

```bash
git clone https://github.com/kamlesh90256/KKY-chatbot-saas.git

cd KKY-chatbot-saas
```

---

# 2️⃣ Install Dependencies

Backend:

```bash
cd backend
npm install
```

Frontend:

```bash
cd ../frontend
npm install
```

The current README documents separate dependency installation for
backend and frontend. 

---

# 3️⃣ Environment Variables

Backend:

```env
DATABASE_URL=postgresql://user:password@localhost:5432/novamind_ai

JWT_SECRET=your-secret-key

OPENAI_API_KEY=your-openai-key

OPENAI_MODEL=your-model

CORS_ORIGIN=http://localhost:3000

NODE_ENV=development
```

Frontend:

```env
NEXT_PUBLIC_API_URL=http://localhost:4000
```

> Never commit real API keys or secrets.

---

# 4️⃣ Prisma Setup

```bash
cd backend
```

Generate Prisma client:

```bash
npx prisma generate
```

Run migrations:

```bash
npx prisma migrate dev
```

---

# 5️⃣ Start Backend

```bash
npm run dev
```

Backend:

```text
http://localhost:4000
```

Health:

```text
http://localhost:4000/api/health
```

---

# 6️⃣ Start Frontend

```bash
cd ../frontend
npm run dev
```

Frontend:

```text
http://localhost:3000
```

---

# 🐳 Docker Quick Start

```bash
docker-compose build
```

```bash
docker-compose up
```

Stop:

```bash
docker-compose down
```

The repository includes Docker Compose configuration. 

---

# ☸️ Kubernetes

```bash
cd k8s
kubectl apply -f .
```

The repository contains Kubernetes manifests under `k8s/`. 

---

# 🔍 API Documentation

Health:

```http
GET /api/health
```

Chat:

```http
POST /api/chat/stream
```

Auth:

```http
POST /api/auth/signup
POST /api/auth/login
GET /api/auth/me
```

Payments:

```http
POST /api/payments/checkout
POST /api/payments/webhook
GET /api/payments/subscription
```

Files:

```http
POST /api/upload
POST /api/resume
```

These endpoints are part of the existing project documentation. 

---

# ⚙️ Development Lifecycle

```mermaid
flowchart LR

    IDEA["💡 Idea"]

    FEATURE["🧩 Feature"]

    CODE["💻 Code"]

    TEST["🧪 Test"]

    LINT["🔍 Lint"]

    BUILD["🔨 Build"]

    DOCKER["🐳 Container"]

    DEPLOY["🚀 Deploy"]

    MONITOR["📈 Monitor"]

    IDEA --> FEATURE
    FEATURE --> CODE
    CODE --> TEST
    TEST --> LINT
    LINT --> BUILD
    BUILD --> DOCKER
    DOCKER --> DEPLOY
    DEPLOY --> MONITOR
```

---

# 🔐 Production Security Checklist

```text
✅ JWT authentication
✅ Password security
✅ Zod validation
✅ Helmet
✅ CORS
✅ Rate limiting
✅ Environment variables
✅ Stripe webhook validation

Recommended:

⬜ Secret rotation
⬜ Audit logs
⬜ Security scanning
⬜ Dependency scanning
⬜ Centralized logging
⬜ Distributed tracing
```

---

# 🌍 Deployment Resources

### Deployment Guide

https://github.com/kamlesh90256/KKY-chatbot-saas/blob/main/DEPLOYMENT_GUIDE.md

### Deployment Checklist

https://github.com/kamlesh90256/KKY-chatbot-saas/blob/main/DEPLOYMENT_CHECKLIST.md

### Local Development

https://github.com/kamlesh90256/KKY-chatbot-saas/blob/main/LOCAL_DEVELOPMENT.md

### Quick Reference

https://github.com/kamlesh90256/KKY-chatbot-saas/blob/main/QUICK_REFERENCE.md

These supporting documentation files are actually present in the
repository. 

---

# 📚 Engineering Learning Path

```text
1. Next.js
      ↓
2. React
      ↓
3. TypeScript
      ↓
4. REST APIs
      ↓
5. Express
      ↓
6. PostgreSQL
      ↓
7. Prisma
      ↓
8. Authentication
      ↓
9. SSE Streaming
      ↓
10. OpenAI Integration
      ↓
11. Stripe
      ↓
12. Docker
      ↓
13. Kubernetes
      ↓
14. CI/CD
      ↓
15. Production Architecture
```

---

# 🧠 Architecture Summary

```text
                     👤 USER
                        │
                        ▼
                ▲ NEXT.JS FRONTEND
                        │
                        ▼
                 🟢 EXPRESS API
                        │
          ┌─────────────┼─────────────┐
          │             │             │
          ▼             ▼             ▼
       🔐 AUTH       💬 CHAT       💳 STRIPE
          │             │             │
          │             ▼             │
          │          ✨ OPENAI         │
          │             │              │
          │             ▼              │
          │         🌊 SSE             │
          │             │              │
          └─────────────┼──────────────┘
                        │
                        ▼
                  🔷 PRISMA ORM
                        │
                        ▼
                  🐘 POSTGRESQL
                        │
                        ▼
                  👨‍💼 ADMIN
                        │
                        ▼
                  📊 ANALYTICS

                        │
                        ▼
              🐳 DOCKER / ☸️ K8S
                        │
                        ▼
                  ⚙️ CI/CD
```

---

# ⭐ Project Highlights

<div align="center">

<table>

<tr>

<td align="center">

## 💬

### Real-Time AI

SSE-powered responses

</td>

<td align="center">

## 🔐

### Secure SaaS

JWT + validation + security middleware

</td>

<td align="center">

## 💳

### Subscription

Stripe billing architecture

</td>

</tr>

<tr>

<td align="center">

## 📄

### File Processing

Resume/document workflows

</td>

<td align="center">

## 👨‍💼

### Admin

Analytics + user management

</td>

<td align="center">

## ☸️

### Cloud Ready

Docker + Kubernetes + CI/CD

</td>

</tr>

</table>

</div>

---

# 👨‍💻 Developer

<div align="center">

<img
src="https://avatars.githubusercontent.com/u/155698651?v=4"
width="120"
alt="Kamlesh Kumar Yadav"
/>

# Kamlesh Kumar Yadav

### Software Engineer • Full Stack • Backend • AI

Building scalable software systems, AI products and production-oriented
applications.

<br/>

<a href="https://github.com/kamlesh90256">
<img src="https://img.shields.io/badge/GitHub-kamlesh90256-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://kky-chatbot-demo.vercel.app/">
<img src="https://img.shields.io/badge/Project-Live_Demo-00D9FF?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>

</div>

---

# 🔗 Project Links

<div align="center">

### 🚀 Live Demo

**https://kky-chatbot-demo.vercel.app/**

### 💻 GitHub

**https://github.com/kamlesh90256/KKY-chatbot-saas**

</div>

---

# 📄 License

This project is licensed under the MIT License.

See:

```text
LICENSE
```

---

<div align="center">

# 🤖 KKY Chatbot SaaS

### Real-Time AI • SaaS • Backend • Cloud

<br/>

<img src="https://img.shields.io/badge/NEXT.JS-000000?style=for-the-badge&logo=next.js&logoColor=white"/>
<img src="https://img.shields.io/badge/EXPRESS-000000?style=for-the-badge&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/POSTGRESQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/OPENAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/DOCKER-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/KUBERNETES-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>

<br/>
<br/>

**Build • Stream • Scale • Ship**

</div>
