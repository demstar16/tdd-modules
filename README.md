# 🧠 Ramda Function Re-creations (TDD-Driven)

This is a curated collection of Ramda.js function re-implementations, each built from the ground up using **test-driven development (TDD)**. The purpose is to demonstrate clarity of thought, functional programming understanding, and clean incremental development.

Each function lives in its own repository and is included here as a Git submodule to preserve its individual commit history.

---

## 🔧 Cloning This Project (With Submodules)

```bash
git clone --recurse-submodules https://github.com/your-username/ramda-recreations.git
```

If you've already cloned the repo without submodules:

```bash
git submodule update --init --recursive
```

---

## 📁 Repository Structure

| Function     | Module   | Repo                                                        |
| ------------ | -------- | ----------------------------------------------------------- |
| `map`        | Built-in | [🔗 View Repo](https://github.com/demstar16/map-tdd)        |
| `filter`     | Built-in | [🔗 View Repo](https://github.com/demstar16/filter-tdd)     |
| `reduce`     | Built-in | [🔗 View Repo](https://github.com/demstar16/reduce-tdd)     |
| `transduce`  | Ramda    | [🔗 View Repo](https://github.com/demstar16/transduce-tdd)  |
| `apply-spec` | Ramda    | [🔗 View Repo](https://github.com/demstar16/apply-spec-tdd) |
| `curry`      | Ramda    | [🔗 View Repo](https://github.com/demstar16/curry-tdd)      |
| `lens`       | Ramda    | [🔗 View Repo](https://github.com/demstar16/lens-tdd)       |
| `promise`    | Built-in | [🔗 View Repo](https://github.com/demstar16/promise-tdd)    |
| `create-selectors` | Redux | [🔗 View Repo](https://github.com/demstar16/create-selectors-tdd) |

---

## 🧪 TDD Approach

Each module was developed using a strict test-first approach:

- ✅ Write a failing test
- ✅ Write minimal code to pass the test
- 🔁 Refactor
- 🔄 Repeat

---

## 🎯 Goals

- Deeper understand built-in JavaScript functionality
- Deepen understanding of Ramda’s behavior and API
- Practice functional design principles
- Showcase clean, test-first development

---

## 📚 Extending the Collection

To add a new function implementation:

```bash
git submodule add https://github.com/your-username/ramda-xyz xyz
```

Then commit and push.

---
