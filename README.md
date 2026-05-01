# 👋 Hi, I’m Delpi Kye  

I’m a **Software Engineer** passionate about building **scalable web applications, frontend architectures, and developer tooling**.  
With experience in **React, Vue.js, Golang, Python, and cloud-native systems**, I enjoy creating tools and libraries that improve developer experience.  

---

## 📌 Highlighted - Framework
- **[routexiz](https://www.npmjs.com/package/routexiz)** - A modern tree-based router for React with intent-driven navigation, Suspense-first data loading, and built-in guards, middleware, and caching.
- **[railiz](https://www.npmjs.com/package/railiz)** - Lightweight Node.js engine for deterministic, intent-driven domain logic orchestration.
- **[react-fast-context-z](https://www.npmjs.com/package/react-fast-context-z)** – Ultra-lightweight, selector-based React state container. No Provider. No reducer. No proxy. No magic.
- **[eventbus-z](https://www.npmjs.com/package/eventbus-z)** – Minimal, synchronous, framework-agnostic EventBus alternative for UI signaling, micro-frontends, and TypeScript projects.
- **[railizator](https://www.npmjs.com/package/railizator)** - Lightweight decorator-based routing & pipeline engine for deterministic, intent-driven Node.js domain logic.
- **[railiz-serverless](https://www.npmjs.com/package/railiz-serverless)** - Serverless adapter and modular architecture layer for Railiz, enabling lightweight, scalable Node.js backends.
- **[railpy](https://pypi.org/project/railpy)** - Deterministic high-performance ASGI engine for modern **Python** backends 

---

## 🧠 Architecture – Frontend framework-agnostic

- **[intentx-react](https://www.npmjs.com/package/intentx-react)** – Intent-driven logic adapter for React.
- **[intentx-svelte](https://www.npmjs.com/package/intentx-svelte)** – Intent-driven logic adapter for Svelte.
- **[intentx-solid](https://www.npmjs.com/package/intentx-solid)** – Intent-driven logic adapter for SolidJS.
- **[intentx-runtime](https://www.npmjs.com/package/intentx-runtime)** – Intent-first business logic runtime. Deterministic, headless, and framework-agnostic.

This ecosystem keeps **business logic outside React**, fully orchestrated and predictable.

> UI renders. Logic orchestrates. Runtime guarantees determinism.
> Modular business logic, No reducers. No boilerplate.

```text
Frontend/Adapter
   │
   ▼
intentx-runtime
   │
   ▼
intentx-core
```

---

<b> 🔄 Intent Flow </b>

```text
UI / HTTP / Queue / Cron
        │
        ▼
     emit(intent)
        │
        ▼
   effects / middleware
        │
        ▼
   intent handlers
        │
        ▼
     mutate state
        │
        ▼
computed (derived state) / subscribers
```

> events → behavior → state → derived state

---

![Architecture diagram](https://raw.githubusercontent.com/delpikye-v/intentx-runtime/main/architect.png)

---

## 🧩 Highlighted
- **[intentx-core-z](https://www.npmjs.com/package/intentx-core-z)** – A fine-grained, intent-driven reactive state runtime for building complex React logic outside components.   
- **[reactive-query-z](https://www.npmjs.com/package/reactive-query-z)** – is a lightweight, reactive data-fetching library for React.
- **[intentx-react-router](https://www.npmjs.com/package/intentx-react-router)** - Intent-based routing for React. Navigate by intent instead of URLs. (react-router)
- **[rsx-z](https://www.npmjs.com/package/rsx-z)** – Minimal atomic CSS-in-JS engine. Deterministic hashing, runtime style execution, and SSR-ready injection.   
- **[react-if-vz](https://www.npmjs.com/package/react-if-vz)** – Conditional rendering component for React.
- **[react-event-channel-z](https://www.npmjs.com/package/react-event-channel-z)** – Fully typed React-aware event channel built on top of eventbus-z.
- **[react-tooltip-z](https://www.npmjs.com/package/react-tooltip-z)** – Lightweight, customizable React tooltip component with hover, click, focus and manual trigger support.   
- **[react-lifecycle-z](https://www.npmjs.com/package/react-lifecycle-z)** – Tiny declarative lifecycle hook utilities for React. Mount, update, unmount — expressed clearly.   
- **[react-animate-z](https://www.npmjs.com/package/react-animate-z)** – Text & block animation components.    
- **[react-modal-e2z](https://www.npmjs.com/package/react-modal-e2z)** – A lightweight, headless, fully controlled React modal built on portals. Hook-first, composable, SSR-safe.    
- **[intentium-z](https://www.npmjs.com/package/intentium-z)** – modular framework for intent-driven orchestration, reactive store, effects, and DI-enabled modules.   
- **[mfe-intentiz](https://www.npmjs.com/package/mfe-intentiz)** – Framework-agnostic micro-frontend runtime (makecolor - testing).

## 🧱 Base
- **[react-loop-z](https://www.npmjs.com/package/react-loop-z)** – React utility for loops and conditional rendering. Simple, clean, and flexible.   
- **[rc-tc-ifn](https://www.npmjs.com/package/rc-tc-ifn)** – Truncates text with ellipsis and shows tooltip only when content overflows..    
- **[react-otp-z](https://www.npmjs.com/package/react-otp-z)** – Lightweight and flexible React OTP input component with full control over UX and behavior.
- **[react-calendar-z](https://www.npmjs.com/package/react-calendar-z)** – Lightweight React calendar component.    
- **[react-smooth-scrollbar-z](https://www.npmjs.com/package/react-smooth-scrollbar-z)** – Power, fully for scrollbar.      
- **[react-perfect-scrollbar-z](https://www.npmjs.com/package/react-perfect-scrollbar-z)** – React wrapper for `perfect-scrollbar`.      
- **[react-treeview-z](https://www.npmjs.com/package/react-treeview-z)** – Flexible treeview UI library.    
- **[runtime-intent-z](https://www.npmjs.com/package/runtime-intent-z)** – Intent-first orchestration engine with computed graph and effect pipeline.       
- **[react-intent-engine-z](https://www.npmjs.com/package/react-intent-engine-z)** – What does the user intend to do, and what should happen next?      
- **[react-auto-memo-z](https://www.npmjs.com/package/react-auto-memo-z)** – Automatically apply memo when needed.       
- **[react-loading-z](https://www.npmjs.com/package/react-loading-z)** – Collection and make some loaders.       
- **[react-slot-engine](https://www.npmjs.com/package/react-slot-engine)** – Lightweight slot & plugin engine for extensible React UI composition.       

## 🚀 More
…… [my NPM profile →](https://www.npmjs.com/~delpikye) 🚀


## 🚀 Tech Stack & Expertise  

**Languages**  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ★★★★★  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ★★★★☆  
![Java](https://img.shields.io/badge/Java-007396?logo=java&logoColor=white) ★★★★☆  
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ★★★★☆  
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white) ★★★★☆  

**Frontend**  
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ★★★★★  
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vue.js&logoColor=white) ★★★★☆  
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) ★★★★☆  
![Redux](https://img.shields.io/badge/Redux-764ABC?logo=redux&logoColor=white) ★★★★☆  
![Material-UI](https://img.shields.io/badge/MUI-007FFF?logo=mui&logoColor=white) ★★★★☆  
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?logo=tailwindcss&logoColor=white) ★★★★☆  

**Backend & API**  
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white) ★★★★☆  
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white) ★★★★☆  
![Golang](https://img.shields.io/badge/Golang-00ADD8?logo=go&logoColor=white) ★★★★☆  
![Spring](https://img.shields.io/badge/Spring-6DB33F?logo=spring&logoColor=white) ★★★☆☆  
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white) ★★★☆☆  
![gRPC](https://img.shields.io/badge/gRPC-000000?logo=grpc&logoColor=white) ★★★☆☆  
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?logo=graphql&logoColor=white) ★★★☆☆  

**Databases**  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white) ★★★★☆  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ★★★☆☆  
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) ★★★☆☆  
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?logo=amazon-dynamodb&logoColor=white) ★★★☆☆  
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white) ★★★★☆  

**Cloud & DevOps**  
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white) ★★★★☆  
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white) ★★★★☆  

---

## 📚 Currently Learning / Exploring  
- 🧠 **AI & Machine Learning with Python** (FastAPI, TensorFlow, LangChain).
- ☁️ **AWS Architectures**.  
- 🔗 **Microservices & Event-driven systems**.  
- 🧩 **Domain-Driven Design (DDD)** and **Clean Architecture** with Go.  

---

## 🌐 Connect with Me  
- GitHub: [@delpikye](https://github.com/delpikye-v)  
- NPM: [@delpikye](https://www.npmjs.com/~delpikye)  

☕ [Buy me a coffee](https://www.buymeacoffee.com/delpikye)  

---

## ✨ Fun Fact  
> “A little code every day keeps the bugs away.” 🐞
