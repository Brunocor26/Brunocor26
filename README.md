<div align="center">

# Bruno Correia
**Computer Engineering Student @ UBI · 3rd Year**

[![Portfolio](https://img.shields.io/badge/Portfolio-Brunocor26.github.io-blue?style=flat-square&logo=github)](https://brunocor26.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Bruno%20Correia-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bruno-correia-5479851a2/)
[![Gmail](https://img.shields.io/badge/Gmail-bafc.2608@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:bafc.2608@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Brunocor26-181717?style=flat-square&logo=github)](https://github.com/Brunocor26)

---

</div>

## 👤 About Me

Sou aluno do 3º ano de Engenharia Informática na Universidade da Beira Interior (UBI). Atualmente, estou a desenvolver a minha tese de licenciatura focada em **runtime monitoring** para ambientes heterogéneos — desde microcontroladores *edge* até ao navegador — através de **WebAssembly** como camada de execução universal.

---

## 🎓 Bachelor's Thesis — UMA Monitors Artifact

> **Universal Microservices for Application Monitoring**
> — Compilação de monitores de lógica temporal formal em módulos WebAssembly portáteis para dispositivos IoT limitados.

O projeto utiliza especificações **RMTLD3** (Runtime Metric Temporal Logic with Durations) e compila-as em monitores que correm de forma idêntica em:

| Target | Runtime |
|:-------|:--------|
| **Native Linux/macOS** | C++11 binary |
| **Raspberry Pi Pico** (ARM Cortex-M0+) | WAMR (WebAssembly Micro Runtime) |
| **Cloud / Browser** | WASI module |

**Principais conceitos:**
- Gerados automaticamente via `rmtld3synth`.
- Arquitetura de três ficheiros: `instrument.h` → `compute.h` → `monitor.h`.
- Segurança em tempo real garantida por ring-buffer lock-free (`rtmlib`).
- Lógica trivalente: **TRUE** / **FALSE** / **UNKNOWN**.
- Portabilidade total: zero alterações de código para mudar o target para WASM.

**Stack:** `C++11` · `WebAssembly (WASI)` · `WAMR` · `Docker` · `rmtld3synth` . `OCaml`

[![Thesis Repo](https://img.shields.io/badge/Repo-UMA__Monitors__Artifact-brightgreen?style=flat-square&logo=github)](https://github.com/Brunocor26/UMA_Monitors_Artifact)

---

## 🚀 Other Projects

| Project | Description | Tech Stack |
|:---|:---|:---|
| [**OurProgress**](https://github.com/Brunocor26/OurProgress) | App Android para gestão e descoberta de filmes (API OMDb). | Java · Firebase · Room |
| [**VotoInformado**](https://github.com/Brunocor26/VotoInformado) | App de apoio ao voto informado com API REST. | Java · JavaScript |
| [**Software-Incident-Management**](https://github.com/Brunocor26/Software-Incident-Management-System) | Plataforma full-stack de tracking de incidentes. | JavaScript |
| [**ChessFX**](https://github.com/Brunocor26/ChessFX) | Motor de xadrez com interface gráfica JavaFX. | Java |
| [**ProjetoFinal_CG**](https://github.com/Brunocor26/ProjetoFinal_CG) | Projeto final de Computação Gráfica. | C++ · OpenGL |
| [**SO_ProbSched**](https://github.com/Brunocor26/SO_ProbSched) | Escalonador probabilístico de sistema operativo. | OCaml |
| [**KeyZero**](https://github.com/henriquelaia/KeyZero) | Projeto desenvolvido para o hackathon Shift to Digital. | JavaScript · React |

---

## 🛠 Languages & Tools

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![OCaml](https://img.shields.io/badge/OCaml-EC6813?style=flat-square&logo=ocaml&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![Bruno's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Brunocor26&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Brunocor26&layout=compact&theme=github_dark&hide_border=true&hide=Prolog)

</div>
