<div align="center">

# Bruno Correia

**Computer Engineering Student @ UBI · 3rd Year**

[![Portfolio](https://img.shields.io/badge/Portfolio-Brunocor26.github.io-blue?style=flat-square&logo=github)](https://brunocor26.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Bruno%20Correia-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bruno-correia-5479851a2/)
[![Gmail](https://img.shields.io/badge/Gmail-bafc.2608@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:bafc.2608@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Brunocor26-181717?style=flat-square&logo=github)](https://github.com/Brunocor26)

</div>

---

## About Me

I'm a 3rd year Computer Engineering student at the University of Beira Interior (UBI), working on my bachelor's thesis on runtime monitoring for heterogeneous environments — from edge microcontrollers to the browser — using **WebAssembly** as the universal execution layer.

---

## 🎓 Bachelor's Thesis — UMA Monitors Artifact

> **Universal Microservices for Application Monitoring**
> — compiling formal temporal logic monitors into portable WebAssembly modules for constrained IoT devices

The project takes **RMTLD3** (Runtime Metric Temporal Logic with Durations) specifications and compiles them into monitors that run identically across:

| Target | Runtime |
|--------|---------|
| Native Linux/macOS | C++17 binary |
| Raspberry Pi Pico (ARM Cortex-M0+) | WAMR (WebAssembly Micro Runtime) |
| Cloud / Browser | WASI module |

**Key ideas:**
- Monitors are auto-generated from logical formulas via `rmtld3synth`
- Each monitor follows a three-file architecture: `instrument.h` → `compute.h` → `monitor.h`
- Lock-free ring-buffer via `rtmlib` ensures real-time safety
- Results use three-valued logic: **TRUE** / **FALSE** / **UNKNOWN**
- Zero code changes needed to retarget from native to WASM

**Stack:** C++17 · WebAssembly (WASI) · WAMR · Docker · `rmtld3synth`

[![Thesis Repo](https://img.shields.io/badge/Repo-UMA__Monitors__Artifact-brightgreen?style=flat-square&logo=github)](https://github.com/Brunocor26/UMA_Monitors_Artifact)

---

## Other Projects

| Project | Description | Tech |
|---------|-------------|------|
| [Software-Incident-Management-System](https://github.com/Brunocor26/Software-Incident-Management-System) | Full-stack incident tracking platform | JavaScript |
| [VotoInformado](https://github.com/Brunocor26/VotoInformado) | Informed voting app + REST API | Java · JavaScript |
| [ChessFX](https://github.com/Brunocor26/ChessFX) | Chess engine with JavaFX GUI | Java |
| [ProjetoFinal_CG](https://github.com/Brunocor26/ProjetoFinal_CG) | Computer graphics final project | C |
| [SO_ProbSched](https://github.com/Brunocor26/SO_ProbSched) | Probabilistic OS scheduler | OCaml |


---

## Languages & Tools

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![OCaml](https://img.shields.io/badge/OCaml-EC6813?style=flat-square&logo=ocaml&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## GitHub Stats

<div align="center">

![Bruno's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Brunocor26&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Brunocor26&layout=compact&theme=github_dark&hide_border=true)

</div>
