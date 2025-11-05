# October 2025

Dear readers,

as autumn settles in, we've been busy pushing the boundaries of what DATEX and UIX can do - from restructuring our codebase for smarter type inference to extending the ecosystem with an entirely new tool: the **DATEX Workbench**.

Meanwhile, our presence at events and in education keeps growing: we've been connecting with new talents at the [ITCS München](https://messe-muenchen.de/de/veranstaltungen/itcs-2025.html). Let's dive into what's new this month.

---

# Association

We're excited to welcome **three new members** to the unyt.org association: [Oliver](https://github.com/Silauras), [Lennart](https://github.com/lennartstoelting), and [Khaled](https://github.com/kha1dx).
All three have joined to work on the new **[DATEX Workbench](https://github.com/unyt-org/datex-workbench)** - a application designed to support ongoing development of **DATEX Core**, initially for internal use but ultimately open-sourced for everyone.

The DATEX Workbench aims to become a **tooling and debugging environment** within the DATEX cosmos. It will allow developers to:

* Inspect the memory of a DATEX endpoint via a **pointer view**
* Filter, modify, and debug live data
* Intercept **incoming and outgoing DXB blocks** to see their contents
* Provide a **REPL, language support**, and an integrated **DATEX IDE**

In the future, it will be directly integrated into **browser devtools** and **IDEs like VS Code**.

Oliver is currently defining the **architecture and window management system**, while also supporting the core team with **task coordination and mentoring**.
We're thrilled to have all three onboard - welcome to the team!

---

# Events

On **October 24, 2025**, we visited the **[ITCS Messe München](https://it-cs.io/)** - where we've got to meet a wide range of developers and potential collaborators.
Our goal: to connect with like-minded individuals and explore new partnerships for unyt.org and its open-source initiatives.

It was inspiring to see how much interest there is in distributed technologies and in projects like **DATEX** and **UIX**. We're looking forward to future collaborations born from this event.

---

# Education

As part of the **TU Berlin** course *"Neue Webtechnologien"* by **Adrian Siebing**, both **UIX** and **DATEX** continue to serve as teaching examples for cutting-edge web development.

A **tutorial video series** is currently in production - it will guide students (and the community!) through:

* Setting up **UIX**
* Building a **full-stack web app** with UIX and DATEX
* Understanding the principles of **reactivity and distributed computation**

Stay tuned - the tutorials will be published soon and available to everyone.

---

# Development

## [UIX](https://github.com/unyt-org/uix)

This month's focus has been on stability and developer experience.

* Bugfixes for [CSS scope selectors](https://github.com/unyt-org/uix/commit/1f9bb24d818b03a3bdfcab819623e4a5acc6428f)
* [Improvements](https://github.com/unyt-org/uix/commit/507589ed22a9d24fee21ba948a5228ffcfb1e402) for better startup times in large applications

## [DATEX (Rust)](https://github.com/unyt-org/datex-core/pulls?q=is:closed%20created:2025-10-01..2025-10-31)

DATEX Core development continues at high speed.
We've been working on a **major restructuring** of the project to improve **type inference** and **IDE integration**.
A first **Language Server prototype** for [DATEX CLI](https://github.com/unyt-org/datex-cli) is now operational - it enables **syntax error highlighting** and **type hints** directly within **VS Code**.

Additionally, early steps have been made toward **embedded support**, targeting **ESP32** and similar microcontrollers - bringing DATEX to constrained hardware for the first time.
This is still a **work in progress**, but the foundation is laid.

We aim to release **DATEX Core Rust 0.0.7** next month, including these updates and several **language enhancements**.

---

# Upcoming Events

Join our open community discussions - all are welcome!

* **Bi-Weekly Developers Meeting:** Tuesdays, biweekly, 8:00 pm CET
* **Weekly DATEX Spec Talk:** Mondays, 8:00 pm CET
* **Monthly Management Meeting:** Tuesday, November 25, 8:00 pm CET
