# Kotlin-like-Rust  
Experimental language fusion project — interpreting **Kotlin semantics** through a **Rust-style execution model**.

This repository is part of the **Freeing-the-Lang** ecosystem, where languages are reimagined, cross-mapped, and rebuilt with new memory models such as **All-is-Heap**, **Heap-Hop Edition**, and **LLVM-free execution**.

---

## 🔥 What is Kotlin-like-Rust?

A hybrid concept language where:

- Kotlin-style syntax  
- Rust-style safety model (but simplified)  
- Expression-first design  
- No JVM  
- No Kotlin compiler dependency  
- Optional “Pure-Rust-No-LLVM” backend connection  
- Possible NASM backend (future)

This project aims to explore:
- new parser structures  
- proof-of-build ledgers  
- cross-language transpilation  
- multi-main execution (no fixed `main`)  
- heap-based evaluation models  

---

## 📦 Goals
- Define a small Kotlin-like syntax set  
- Map it to Rust-like semantics  
- Produce C++ / NASM / Rust / Go targets  
- Use 3OS automated builds (Linux / macOS / Windows)  
- Generate SHA256 proof ledger for every build  

---

## 🏗️ Roadmap
- [ ] Minimal parser  
- [ ] Expression evaluator  
- [ ] Rust-like borrowing emulation (light version)  
- [ ] Soft type inference  
- [ ] Transpiler to C++  
- [ ] Transpiler to Rust  
- [ ] NASM backend  
- [ ] Pure-Rust-no-LLVM backend option  
- [ ] Auto-release workflow  

---

## 🌍 Freeing-the-Lang Ecosystem
This repository is one of many language-experiment repos across the ecosystem, including:

- Rust-like-Java  
- Go-like-Rust  
- Ada-like-Rust  
- Swift-like-Ada  
- Haskell-like-Rust  
- Rust-like-Ruby  
- JVM-without-Java  
- Pure-Rust-No-LLVM  

Each explores how languages behave when reinterpreted through different semantic or memory models.

---

## 📜 License
MIT License
