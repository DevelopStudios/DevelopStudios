<div align="center">
  <h1>Charl Roux</h1>
  <p>Senior AI &amp; Frontend Engineer &nbsp;·&nbsp; Michigan &nbsp;·&nbsp; Open to remote</p>
  <p>
    <a href="https://charlportfolio.online">Portfolio</a> &nbsp;·&nbsp;
    <a href="https://www.linkedin.com/in/charl-roux-50b124122/">LinkedIn</a> &nbsp;·&nbsp;
    charlit641@gmail.com
  </p>
</div>

---

I build full-stack AI applications: retrieval pipelines, streaming interfaces, and the production
engineering that keeps them reliable. Seven years shipping Angular platforms at enterprise scale
before that.

---

## DocLocal

**[Live](https://doclocal-1bb7p.kinsta.page)** &nbsp;·&nbsp; **[Code](https://github.com/DevelopStudios/doclocal)**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![NVIDIA NIM](https://img.shields.io/badge/NVIDIA_NIM-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Nx](https://img.shields.io/badge/Nx-143055?style=flat-square&logo=nx&logoColor=white)
![WebGPU](https://img.shields.io/badge/WebGPU-6c3483?style=flat-square)

Retrieval-augmented PDF question answering. Ask a question, get a streamed answer, then click any
citation to jump to the highlighted passage in the source document and check it yourself.

Angular 21 and Nx on the frontend, Python 3.12 and FastAPI on the backend, NVIDIA NIM for embeddings,
retrieval and streamed answers. Answers cancel mid-response and recover when the backend drops a
session: if it loses one, the client re-indexes the document and still answers. API credentials stay
server-side and never reach the browser, and the backend stores only hashed tokens. Failure paths are
tested against a mock inference server with configurable latency and forced failures, so recovery is
verified rather than assumed.

An earlier build ran the whole pipeline on-device: Transformers.js embeddings and WebLLM inference on
WebGPU inside Web Workers, with a SharedWorker so every open tab shares one model instance instead of
each loading its own multi-GB copy.

---

## More AI work

**[Precision Ledger](https://precisionledger-j423d.kinsta.page)**
&nbsp;
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![WebLLM](https://img.shields.io/badge/WebLLM-black?style=flat-square)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square)

Live Binance feed into a 10,000-row virtual grid. When an asset moves more than 2% a local
Llama-3.2-1B streams a technical read straight into the panel. RxJS `bufferTime` absorbs 500+ ticker
events per second without locking the UI.

---

**[TalentBoard](https://devjobs-fe-a0h85.kinsta.page)**
&nbsp;
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Transformers.js](https://img.shields.io/badge/Transformers.js-FFD21E?style=flat-square)
![Orama](https://img.shields.io/badge/Orama-black?style=flat-square)

In-browser semantic search over 1,000+ job listings. Search `cloud engineer` and it surfaces DevOps
roles. Search `mobile app` and it finds iOS positions. `all-MiniLM-L6-v2` embeddings computed in a
Web Worker, no backend, no round-trip.

---

**[VaultKey](https://password-generator-duah3.kinsta.page)**
&nbsp;
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![WebLLM](https://img.shields.io/badge/WebLLM-black?style=flat-square)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

Password generator with in-browser mnemonics. Web Crypto entropy, a deterministic word map per
character, and Qwen2.5-1.5B streaming a vivid scene to make the password stick. Playwright E2E tests
cover model start-up inside the worker and the streamed response reaching the UI, testing the system
around the AI feature rather than only that it renders.

---

**[InvoiceFlow](https://invoice-1qmx1.kinsta.page)**
&nbsp;
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![WebLLM](https://img.shields.io/badge/WebLLM-black?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

Natural-language invoicing. Type "Bill Acme Corp for 5 hours of senior engineering at $100/hr, net
15" and a local Qwen2.5 parses the intent into a structured invoice. The draft → pending → paid flow
is a finite state machine enforced at the service layer, so the UI cannot put an invoice into an
illegal state.

---

## Also

**[Virtual AHU](https://virtual-ahu-m820f.sevalla.app/docs)**
&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

FastAPI service simulating a BACnet air-handling unit: PID control loop, point registry with priority
arrays, REST and WebSocket change-of-value notifications. 25 tests, Dockerized, deployed, OpenAPI
documented.

---

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=flat-square&logo=reactivex&logoColor=white)
![Nx](https://img.shields.io/badge/Nx-143055?style=flat-square&logo=nx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Cypress](https://img.shields.io/badge/Cypress-17202C?style=flat-square&logo=cypress&logoColor=white)

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DevelopStudios&show_icons=true&theme=dark&hide_border=true&include_all_commits=true" />
</div>
