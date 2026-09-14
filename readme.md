<div align="center">

# 🛣️ Road to JS Master [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

**A curated roadmap of the best JavaScript books — from your first `console.log()` to production-grade engineering.**

[![Books](https://img.shields.io/badge/Books%20%26%20Guides-24-6C5CE7?style=flat-square)](#roadmap)
[![Free](https://img.shields.io/badge/Free-15-2EA043?style=flat-square)](#roadmap)
[![Paid](https://img.shields.io/badge/Paid-9-F5A623?style=flat-square)](#roadmap)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-00B894?style=flat-square)](#contributing)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-0984E3?style=flat-square)](LICENSE)

<sub>Searching for the <b>best JavaScript books</b>, <b>top JS books</b>, or a <b>JavaScript learning path</b>? You're in the right place.</sub>

</div>

---

<a id="roadmap"></a>

## 🗺️ The Roadmap

```mermaid
flowchart LR
    A["🌱 Foundations"] --> B["⚡ Fluency"] --> C["🧠 Mastery"]
    C --> D["🔬 Language<br/>Internals"]
    C --> E["🌐 Browser<br/>Platform"]
    C --> F["🟩 Node.js"]
    D --> G["🛡️ TypeScript"]
    E --> G
    F --> G
    G --> H["🧪 Testing"] --> I["🚀 Performance"]

    classDef start fill:#2EA043,stroke:#1A7F37,color:#fff
    classDef core fill:#6C5CE7,stroke:#4834D4,color:#fff
    classDef branch fill:#0984E3,stroke:#0652DD,color:#fff
    classDef end_ fill:#F5A623,stroke:#D68910,color:#fff

    class A start
    class B,C core
    class D,E,F,G branch
    class H,I end_
```

### 🎯 Where should I start?

| If this sounds like you… | Start here |
| :-- | :-- |
| 🐣 I've never written code before | [Stage 1 · Foundations](#foundations) |
| 🧩 I can write JS, but I copy-paste a lot | [Stage 2 · Fluency](#fluency) |
| 🤔 I know *what* JS does, not *why* | [Stage 3 · Mastery](#mastery) · [Stage 4 · Internals](#internals) |
| 🖥️ I want to build for the browser | [Stage 5 · Browser Platform](#browser) |
| 🖧 I want to build servers and CLIs | [Stage 6 · Node.js](#nodejs) |
| 🏭 I ship to real users and it hurts | [Stage 7](#typescript) → [8](#testing) → [9](#performance) |

---

<a id="contents"></a>

## 📚 Contents

| Stage | Track | Books |
| :--: | :-- | :--: |
| 1 | [🌱 Foundations](#foundations) | 4 |
| 2 | [⚡ Fluency](#fluency) | 4 |
| 3 | [🧠 Mastery](#mastery) | 3 |
| 4 | [🔬 JavaScript in Depth](#internals) | 3 |
| 5 | [🌐 Web APIs & Browser](#browser) | 2 |
| 6 | [🟩 Node.js](#nodejs) | 2 |
| 7 | [🛡️ TypeScript](#typescript) | 2 |
| 8 | [🧪 Testing](#testing) | 2 |
| 9 | [🚀 Performance & Reliability](#performance) | 2 |

➕ [🔗 Resources](#resources) · [🤝 Contributing](#contributing) · [⚖️ License](#license)

---

<a id="foundations"></a>

## 🌱 Stage 1 · Foundations

> **Goal:** write your first hundred programs without fear. Variables, functions, loops, and the habit of shipping something that runs.

| Book | Access | Why it earns your time |
| :-- | :--: | :-- |
| **[Eloquent JavaScript (4th Edition)](https://eloquentjavascript.net/)** | ![Free](https://img.shields.io/badge/Free-2EA043?style=flat-square) | A modern introduction to programming with lots of exercises and small projects. Great if you want practice, not just theory. |
| **[The JavaScript Tutorial](https://javascript.info/)** | ![Free](https://img.shields.io/badge/Free-2EA043?style=flat-square) | A structured online "book" that starts from fundamentals and builds toward real-world language and browser topics. |
| **[JavaScript for Kids](https://nostarch.com/javascriptforkids)** | ![Paid](https://img.shields.io/badge/Paid-F5A623?style=flat-square) | A friendly, hands-on introduction that teaches core programming ideas through small games and visual examples. |
| **[Head First JavaScript Programming](https://www.oreilly.com/library/view/head-first-javascript/9781449340124/)** | ![Paid](https://img.shields.io/badge/Paid-F5A623?style=flat-square) | A highly visual, beginner-friendly approach that helps concepts stick through exercises and puzzles. |

<div align="right"><a href="#contents">⬆️ back to contents</a></div>

---

<a id="fluency"></a>

## ⚡ Stage 2 · Fluency

> **Goal:** stop fighting the language. Scope, closures, `this`, async, and how to structure code someone else can read.

| Book | Access | Why it earns your time |
| :-- | :--: | :-- |
| **[You Don't Know JS Yet (2nd Edition)](https://github.com/getify/You-Dont-Know-JS)** | ![Free](https://img.shields.io/badge/Free-2EA043?style=flat-square) | A deep-dive series that explains *why* JavaScript behaves the way it does (scope, closures, types, async). Perfect once you've written some JS and want to level up. |
| **[Effective JavaScript](https://www.oreilly.com/library/view/effective-javascript/9780132902250/)** | ![Paid](https://img.shields.io/badge/Paid-F5A623?style=flat-square) | 68 practical tips that improve correctness, readability, and maintainability. Focuses on the sharp edges and best practices. |
| **[JavaScript: The Definitive Guide](https://www.oreilly.com/library/view/javascript-the-definitive/9781491952016/)** | ![Paid](https://img.shields.io/badge/Paid-F5A623?style=flat-square) | A comprehensive reference that covers the language plus the important web platform APIs. |
| **[Learning JavaScript Design Patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book/)** | ![Free](https://img.shields.io/badge/Free-2EA043?style=flat-square) | Classic patterns and practical guidance for structuring applications, plus common anti-patterns to avoid. |

<div align="right"><a href="#contents">⬆️ back to contents</a></div>

---

<a id="mastery"></a>

## 🧠 Stage 3 · Mastery

> **Goal:** build the mental models. Know the language's history, its traps, and the machinery underneath the DOM.

| Book | Access | Why it earns your time |
| :-- | :--: | :-- |
| **[JavaScript: The Good Parts](https://www.oreilly.com/library/view/javascript-the-good/9780596517748/)** | ![Paid](https://img.shields.io/badge/Paid-F5A623?style=flat-square) | A short, opinionated classic that highlights the powerful ideas in the language — and the pitfalls. Useful for historical context and fundamentals. |
| **[JavaScript Enlightenment](https://frontendmasters.com/books/javascript-enlightenment/)** | ![Free](https://img.shields.io/badge/Free-2EA043?style=flat-square) | A compact, detail-oriented exploration of the language's tricky parts — great for strengthening mental models. |
| **[DOM Enlightenment](http://domenlightenment.com/)** | ![Free](https://img.shields.io/badge/Free-2EA043?style=flat-square) | A focused technical guide to the DOM, events, and the realities of browser scripting. |

<div align="right"><a href="#contents">⬆️ back to contents</a></div>

---

<a id="internals"></a>

## 🔬 Stage 4 · JavaScript in Depth

> **Goal:** read the spec without flinching. Where ES features came from and what problem each one solved.

| Book | Access | Why it earns your time |
| :-- | :--: | :-- |
| **[Speaking JavaScript](http://speakingjs.com/es5/)** | ![Free](https://img.shields.io/badge/Free-2EA043?style=flat-square) | A detailed guide for programmers coming from other languages; explains JS concepts, idioms, and common patterns. |
| **[Exploring ES6](https://exploringjs.com/es6.html)** | ![Free](https://img.shields.io/badge/Free-2EA043?style=flat-square) | A thorough walkthrough of ES2015 features and how they changed modern JavaScript. |
| **[Understanding ECMAScript 6](https://www.nostarch.com/understandinges6)** | ![Paid](https://img.shields.io/badge/Paid-F5A623?style=flat-square) | A clear explanation of ES6 features with examples and rationale — good if you want a book rather than an online guide. |

<div align="right"><a href="#contents">⬆️ back to contents</a></div>

---

<a id="browser"></a>

## 🌐 Stage 5 · Web APIs & Browser

> **Goal:** the platform is bigger than the language. Fetch, storage, canvas, events, and everything MDN documents.

| Reference | Access | Why it earns your time |
| :-- | :--: | :-- |
| **[MDN Web Docs: JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)** | ![Free](https://img.shields.io/badge/Free-2EA043?style=flat-square) | The go-to reference for core language concepts, with examples and links to related Web APIs. |
| **[MDN Web Docs: Web APIs](https://developer.mozilla.org/en-US/docs/Web/API)** | ![Free](https://img.shields.io/badge/Free-2EA043?style=flat-square) | Reference pages for DOM, events, fetch, storage, canvas, and many other browser APIs. |

<div align="right"><a href="#contents">⬆️ back to contents</a></div>

---

<a id="nodejs"></a>

## 🟩 Stage 6 · Node.js

> **Goal:** take JavaScript server-side. Modules, streams, async patterns, and architecture that survives traffic.

| Book | Access | Why it earns your time |
| :-- | :--: | :-- |
| **[Node.js Design Patterns](https://nodejsdesignpatterns.com)** | ![Paid](https://img.shields.io/badge/Paid-F5A623?style=flat-square) | A strong guide to building scalable Node applications with proven patterns, architecture, and async best practices. *A free chapter is available.* |
| **[The Node.js Handbook](https://www.freecodecamp.org/news/the-node-js-handbook/)** | ![Free](https://img.shields.io/badge/Free-2EA043?style=flat-square) | A practical, fast-moving introduction to Node concepts, modules, npm, and building simple apps. |

<div align="right"><a href="#contents">⬆️ back to contents</a></div>

---

<a id="typescript"></a>

## 🛡️ Stage 7 · TypeScript

> **Goal:** let the compiler catch what your tests would have. Narrowing, generics, and types that document intent.

| Book | Access | Why it earns your time |
| :-- | :--: | :-- |
| **[TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)** | ![Free](https://img.shields.io/badge/Free-2EA043?style=flat-square) | The official guide that explains the type system, narrowing, generics, and best practices. |
| **[Effective TypeScript](https://www.oreilly.com/library/view/effective-typescript/9781492053736/)** | ![Paid](https://img.shields.io/badge/Paid-F5A623?style=flat-square) | A best-practices book focused on writing TypeScript that is safe, ergonomic, and maintainable. |

<div align="right"><a href="#contents">⬆️ back to contents</a></div>

---

<a id="testing"></a>

## 🧪 Stage 8 · Testing

> **Goal:** refactor on a Friday without fear. Strategy first, tooling second.

| Book | Access | Why it earns your time |
| :-- | :--: | :-- |
| **[Testing JavaScript Applications](https://www.manning.com/books/testing-javascript-applications)** | ![Paid](https://img.shields.io/badge/Paid-F5A623?style=flat-square) | A practical approach to testing strategy — unit, integration, UI, and tooling choices. |
| **[Jest Documentation](https://jestjs.io/docs/getting-started)** | ![Free](https://img.shields.io/badge/Free-2EA043?style=flat-square) | Hands-on docs for unit and integration testing with a popular JavaScript test runner. |

<div align="right"><a href="#contents">⬆️ back to contents</a></div>

---

<a id="performance"></a>

## 🚀 Stage 9 · Performance & Reliability

> **Goal:** the last mile. Measure what users feel, and understand the network you're shipping across.

| Book | Access | Why it earns your time |
| :-- | :--: | :-- |
| **[Web Performance 101](https://3perf.com/book)** | ![Free](https://img.shields.io/badge/Free-2EA043?style=flat-square) | A modern performance primer: metrics, loading strategies, and real-world optimization techniques. |
| **[High Performance Browser Networking](https://hpbn.co/)** | ![Free](https://img.shields.io/badge/Free-2EA043?style=flat-square) | A deep dive into how browsers and networks actually work (TCP/TLS/HTTP/2/3), and what that means for performance. |

<div align="right"><a href="#contents">⬆️ back to contents</a></div>

---

<a id="progress"></a>

## ✅ Track Your Progress

Fork this repo and tick the boxes as you go:

- [ ] 🌱 **Stage 1 — Foundations:** I can build a small app from an empty file
- [ ] ⚡ **Stage 2 — Fluency:** closures, `this`, and `async/await` no longer surprise me
- [ ] 🧠 **Stage 3 — Mastery:** I know which "parts" to avoid and why
- [ ] 🔬 **Stage 4 — Internals:** I can read the ECMAScript spec for an answer
- [ ] 🌐 **Stage 5 — Browser:** I reach for the right Web API instead of a library
- [ ] 🟩 **Stage 6 — Node.js:** I've shipped a server or CLI that others use
- [ ] 🛡️ **Stage 7 — TypeScript:** my types document intent, not just shapes
- [ ] 🧪 **Stage 8 — Testing:** I refactor confidently because the suite has my back
- [ ] 🚀 **Stage 9 — Performance:** I optimize from measurements, not hunches

---

<a id="resources"></a>

## 🔗 Resources

| Resource | What it's for |
| :-- | :-- |
| 📜 **[ECMAScript (Language Spec)](https://tc39.es/ecma262/)** | The official JavaScript specification — the final word on behavior. |
| 📊 **[Can I use](https://caniuse.com/)** | Browser support tables for Web platform features. |
| 📖 **[MDN Web Docs](https://developer.mozilla.org/)** | Reference and guides across the entire Web platform. |
| 🎓 **[Frontend Masters Book Collection](https://frontendmasters.com/books/)** | Several high-quality, free JS-related books. |

---

<a id="contributing"></a>

## 🤝 Contributing

Contributions are very welcome — this roadmap gets better with every pair of eyes.

**To add a book, open a PR that includes:**

| ✔️ | Requirement |
| :--: | :-- |
| 1️⃣ | **Title + link + access tag** (`Free` or `Paid`) |
| 2️⃣ | A **1–3 sentence original blurb** — no copy-paste from the publisher |
| 3️⃣ | An **official source** (author, publisher, or project site) over third-party mirrors |
| 4️⃣ | Placement in the **stage that matches its difficulty** |

Spotted a dead link, an outdated edition, or a book that belongs in a different stage? [Open an issue](https://github.com/zero-0002/Road_to_JS_Master/issues) — those PRs are just as valuable.

---

<a id="license"></a>

## ⚖️ License

Licensed under the **[Creative Commons Attribution 4.0 International License (CC BY 4.0)](LICENSE)**.

You are free to share and adapt this list — just give credit.

<div align="center">

---

**⭐ If this roadmap helped you, star the repo — it helps other developers find it.**

<sub>Made for everyone walking the road from <code>console.log("hello")</code> to shipping JavaScript at scale.</sub>

</div>
