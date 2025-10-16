# 🦀 My Rustlings Journey

This repository contains **my personal solutions and notes** from working through the [Rustlings](https://rustlings.rust-lang.org/) 

> These files represent my progress and reflections as I learn the Rust programming language step by step.

---

## 📘 About Rustlings

[Rustlings](https://github.com/rust-lang/rustlings) is an open-source project by the Rust community. It offers small exercises that teach you Rust syntax, ownership, borrowing, traits, lifetimes, and more 

You can think of it as an interactive Rust tutorial where each error message is part of the learning process.

---

## 💻 What's in This Repo

This repo mirrors my journey through Rustlings. Each folder or file corresponds to a specific exercise, topic, or concept.

```
.
├─ exercises/
│  ├─ variables/
│  ├─ functions/
│  ├─ ownership/
│  ├─ borrowing/
│  ├─ structs_enums/
│  ├─ error_handling/
│  ├─ iterators/
│  ├─ traits_generics/
│  ├─ lifetimes/
│  ├─ tests/
│  └─ ...more as I progress
├─ notes/
│  ├─ learning_log.md
│  └─ helpful_tips.md
└─ README.md
```

Each section has the Rust source files I’ve completed and sometimes additional notes about what I learned or found tricky.

---

## 🚀 How to Run My Exercises

### 1) Install Rust

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
rustup update
```

### 2) Install Rustlings (optional)

```bash
cargo install rustlings --locked
```

### 3) Run the Exercises

If you have Rustlings installed:

```bash
rustlings watch
```

Or, to test individual files manually:

```bash
cargo run
# or
cargo test
```

---

## 🧭 My Learning Approach

1. Read the comments in each exercise.
2. Try to fix compiler errors without peeking at hints.
3. Review the related section of *The Rust Programming Language* book.
4. Write notes in `notes/learning_log.md` to summarize insights.
5. Commit each working solution before moving on.

---

## 🧩 Progress Tracking

* ✅ **Variables & Functions** – complete
* ✅ **Ownership & Borrowing** – complete
* 🟡 **Structs, Enums & Traits** – in progress
* ⚪ **Lifetimes & Advanced Topics** – upcoming

---

## 🛠️ Tools I’m Using

* **Rust Analyzer** (VS Code extension)
* **Clippy** for linting (`cargo clippy -- -D warnings`)
* **rustfmt** for consistent formatting (`cargo fmt`)
* Occasionally, **rustlings hint <exercise>** for guidance


---

## 🤝 Credits

All exercises are originally from the [Rustlings](https://github.com/rust-lang/rustlings) project by the Rust community.

This repo only contains **my personal progress, modifications, and notes**.

---

## 📜 License

My additions (comments, notes, or scripts) are shared under the MIT License.
The original Rustlings exercises remain under their respective license.

---

🦀 *Learning Rust, one compiler message at a time.*
