<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=180&section=header&text=Lord%20Melflam&fontSize=58&fontColor=ffffff&fontAlignY=34&animation=fadeIn&desc=Systems%20%C2%B7%20Cybersecurity%20%C2%B7%20Software&descAlignY=56&descSize=17" width="100%" alt="Lord Melflam" />

### François Junior Meli Ngueunkeung

**MSc Computer Science Engineering, UCLouvain (2026)**

<a href="https://www.linkedin.com/in/francois-junior-meli-ngueunkeung">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://github.com/Lord-Melflam?tab=repositories">
  <img src="https://img.shields.io/badge/Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" />
</a>

</div>

---

I build solutions that are **maintainable, reusable, evolvable**.

If it's slow, fragile, or hand-wavy, I find my way to strengthen it.<br>
If it's already working, I find my way to optimize it.

I care about how things work *under the hood*, and most of all about keeping them working
in a reliable and secure way.

<br />

## 🎯 Domain of Focus

<table>
<tr>
<td width="50%" valign="top">

**Software engineering**<br>
Architecture that survives its own growth. Specifications before code.

**Cybersecurity & networks**<br>
Exploitation, defense, and privacy enforced where it actually holds: the server.

</td>
<td width="50%" valign="top">

**Systems & low-level programming**<br>
C, memory, compilers, the layer under the abstraction.

**Performance & databases**<br>
Measurement over intuition. Query plans, load tests, numbers you can reproduce.

</td>
</tr>
</table>

<br />

## 🛠️ Arsenal

<div align="center">

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-121011?style=for-the-badge&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

**Web & Data**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=firebase&logoColor=white)

**Infrastructure & Tooling**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

**Security, Debugging & Benchmarking**

![Kali](https://img.shields.io/badge/Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![pwntools](https://img.shields.io/badge/pwntools-111111?style=for-the-badge&logo=python&logoColor=white)
![GDB](https://img.shields.io/badge/gdb%20%2F%20pwndbg-000000?style=for-the-badge&logo=gnu&logoColor=white)
![WRK](https://img.shields.io/badge/WRK-444444?style=for-the-badge)

</div>

<br />

## 📂 Selected Works

### 🎓 [Studens](https://github.com/Lord-Melflam/Studens) · `TypeScript` `PostgreSQL`

A modular web platform for students in higher education. Three languages, sign-in without
passwords of my own, modules mounted on a shared base.

The specification came first and still leads: **154 requirements**, each carrying the reasoning
that produced it, and 8 questions left open instead of guessed.

- Anonymity enforced on the server, not the interface. An anonymous review returns its text
  and its date, nothing else, and there is no column that could join it to a person.
- An account somebody can leave: full data export, deletion that detaches what was signed,
  notification consent per kind with the date the choice was made.
- 469 tests, typecheck, lint and schema validation behind a single `npm run gates`.
- A build gate that fails if a sentence is hardcoded in a component.
- First module is **RYC**, running against the real UCLouvain catalogue: 546 courses reached
  through 43 EPL programmes, scraped rather than hand-listed, structure discovered at runtime.

### 🔬 [Master Thesis](https://github.com/Lord-Melflam/Master_Thesis_Francois_Meli_2026) · `Python`

*Profiling Novice Programmers' Behavior through the Analysis of Incremental Programming Submissions*<br>
École polytechnique de Louvain, 2025-2026.

Students submit to an autograder that keeps every attempt, not just the last one. From those
histories I build behavior features per student, with the final grade deliberately excluded,
then group them with Ward hierarchical clustering.

- 36 analysis scripts, 36 figures, one source of truth for the cohort and the clustering recipe.
- Every figure and every headline number in the manuscript maps back to the script that produced
  it. That traceability is the point of the repository.

### ⚙️ [Compiler](https://github.com/Lord-Melflam/linfo2132_project_2025) · `Java`

A compiler for an imperative language, written from scratch: lexer, recursive descent parser,
semantic analysis with static type checking on a strongly typed language, and code generation.

### 🏥 [SmartMedicalManager](https://github.com/Lord-Melflam/LINFO2252_SmartMedicalManager_G7) · `Java`

A dynamically adaptive appointment system built with a feature-oriented approach. MVC and a time
event system, designed so that a new feature is added rather than woven in.

### 🛡️ Systems Security & Performance

Coursework repositories are private, so here is what they contain.

**Exploitation under real constraints:** buffer overflows, ASLR-enabled binaries, shellcode
injection, and the BREACH attack. Tooling: `pwntools`, `pwndbg`, Kali Linux.

**Server performance under load:** controlled experiments with WRK traffic generation, latency
and throughput analysis, and a methodology written down so the numbers can be reproduced.

<br />

## 📊 Activity

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Lord-Melflam&theme=tokyonight" width="88%" alt="Profile summary" />

<img height="195" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Lord-Melflam&theme=tokyonight" alt="Top languages by repository" />
<img height="195" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Lord-Melflam&theme=tokyonight" alt="Most committed languages" />

<img height="195" src="https://streak-stats.demolab.com/?user=Lord-Melflam&theme=tokyonight&hide_border=true" alt="Contribution streak" />
<img height="195" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Lord-Melflam&theme=tokyonight&utcOffset=2" alt="Productive time" />

</div>

<br />

## 📬 Presence

<div align="center">

<a href="https://www.linkedin.com/in/francois-junior-meli-ngueunkeung">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>

</div>

<br />

<div align="center">

*The one behind every scene*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%" alt="" />

</div>
