<div align="center">

# vennictus / Ishjaap Singh

**Backend engineer. Computer Engineering @ TIET Patiala.**  
I build systems from scratch — to understand how things work at execution level.

[![Email](https://img.shields.io/badge/ishjaap.singh07%40gmail.com-000000?style=flat&logo=gmail&logoColor=white)](mailto:ishjaap.singh07@gmail.com)
[![X](https://img.shields.io/badge/@vennictus-000000?style=flat&logo=x&logoColor=white)](https://x.com/vennictus)
[![Portfolio](https://img.shields.io/badge/portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://portfolio-vennictus.vercel.app/)

</div>

---

<div align="center">

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat&logo=webassembly&logoColor=white)

</div>

---

## Current Focus

- Backend engineering and system design
- Compilers, execution models, and low-level systems
- How things actually behave at runtime — not just what the docs say

---

## Some Projects I Built

### [ORION](https://github.com/vennictus/orion) — WebAssembly Compiler
`TypeScript` &nbsp;·&nbsp; *compiler · wasm · binary*

Compiles a custom low-level language directly into raw WebAssembly binary modules. No toolchain wrappers, no WAT intermediate — byte by byte, from scratch. Built to understand what actually lives inside a `.wasm` file.

---

### [benz](https://github.com/vennictus/benz) — Graph Query Execution Engine
`Go` &nbsp;·&nbsp; *execution model · graph · volcano*

An in-memory graph query engine with a lazy, pull-based Volcano-style execution model — the same architecture behind real query engines. Built to answer the question: how does a traversal pipeline actually pull data through itself?

---

### [gosearch](https://github.com/vennictus/gosearch) — Blazing-Fast CLI Search Tool
`Go` &nbsp;·&nbsp; *cli · concurrency · systems*

A concurrent code search tool that pipelines file traversal, I/O, and pattern matching across 4 parallel stages. Respects `.gitignore`, scales workers dynamically, outputs JSON, and benchmarks at ~1.2ms over 10k files. Zero dependencies.

```sh
gosearch -i "error" ./src
gosearch -regex "func\s+\w+\(" .
gosearch -format json "config" . | jq '.matches'
```

---

### [kilo](https://github.com/vennictus/kilo-txt-editor) — Terminal Text Editor in C
`C` &nbsp;·&nbsp; *raw terminal · systems · zero deps*

A fully functional terminal text editor in pure C — raw terminal mode, ANSI escape sequences, low-level file I/O. No libraries. No abstractions. Just the metal.

---

## Currently Exploring

- AI agents and agentic architectures
- Data-driven system design
- Execution behavior of modern runtimes

---

<div align="center">
<sub>Building things to understand them.</sub>
</div>
