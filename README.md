<div align="center">
  <h1>Charl Roux</h1>
  <p>Senior AI Frontend Engineer &nbsp;·&nbsp; Michigan &nbsp;·&nbsp; Open to remote</p>
  <p>
    <a href="https://charlportfolio.online">Portfolio</a> &nbsp;·&nbsp;
    <a href="https://www.linkedin.com/in/charl-roux-50b124122/">LinkedIn</a> &nbsp;·&nbsp;
    charlit641@gmail.com
  </p>
</div>

---

I build AI features end to end: the interface, the streaming and recovery behaviour, and the
inference service behind it. Seven years shipping Angular platforms at enterprise scale before that.

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
