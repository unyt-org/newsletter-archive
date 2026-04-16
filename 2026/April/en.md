# April 2026

Dear readers,

February and March have been eventful months for unyt.org. We held our Annual General Assembly, continued pushing the DATEX ecosystem forward with a major structural overhaul, and laid the groundwork for a new AI policy.

# Association

- **Annual General Assembly**

  On February 14, the association held its public Annual General Assembly. Some highlights from the numbers presented: our Discord server has surpassed its 150-member target with **179 members**, and the [UIX repository](https://github.com/unyt-org/uix) crossed **100 GitHub stars**. Newsletter readership has grown from 25 to **31 readers**, and the total user base has nearly doubled to approximately **195 users**. The association currently consists of 3 board members and 18 regular members.

  The assembly also featured a presentation by the **Institut für Digitale Lehre (IfDL)**, a partner institute focused on innovative software solutions for schools and universities. The IfDL showcased its two products, [quix.digitalelehre.org](https://quix.digitalelehre.org) and Kritzel, alongside an encouraging trend: the number of support requests per user in the *New Web Technologies* course at TU Berlin has steadily declined over the past two years, a sign of a maturing UIX/DATEX developer experience.

- **AI Policy in the Works**

  At the management meeting on March 17, our members voted in favor of pursuing an official unyt.org AI policy. The core principles under discussion include a prohibition on GitHub Copilot suggestions and on vibe-coding features from scratch, while permitting tab completion, research applications, and minimal AI-generated code snippets. Once the full draft is prepared, it will be opened for a formal adoption vote. A dedicated blog post on the policy is also planned.

- **New Interns**

  We welcomed two new internes in February and March. Both are contributing to active development efforts.

# Development

The most significant change is a structural one: the DATEX ecosystem has been reorganised around a new top-level `datex` Cargo workspace, bringing together the `core` and `macro` crates under one coherent project. Alongside this, the JavaScript binding layer has been renamed and a dedicated native crate has been established, giving the ecosystem a clearer shape across its three target environments – web, desktop/server, and embedded.

The structural changes were made possible by the previous owner of the `datex` name on crates.io who has been very friendly and supportive in transferring the name to the unyt.org project. Thank you!

## [DATEX](https://github.com/unyt-org/datex-core)

* **Major project restructuring.** The DATEX Core Rust project has been reorganised around a main `datex` workspace, cleanly separating the `core` and `macro` crates.
* **v0.0.11 released**, incorporating macro dependency updates, AST fixes, and a series of refactoring improvements. The previous **v0.0.10** delivered a thorough refactoring of value and reference ownership semantics alongside a revamped Crypto API.
* **New `range` datatype.** A dedicated range type for numeric values has been introduced to the DATEX type system.
* **[datex-web](https://github.com/unyt-org/datex-web)** – the JavaScript/TypeScript binding layer – has been officially renamed from `datex-core-js` to better reflect its role as the web-specific layer. It reached **v0.0.14** with dependency updates and crypto fixes. Work on cross-network pointer synchronisation is ongoing and remains a central near-term goal.
* **[datex-native](https://github.com/unyt-org/datex-native)** – a new dedicated crate for desktop and server platforms, complementing `datex-web` – reached **v0.0.10** with an improved CI pipeline and test workflows.
* **[datex-embedded](https://github.com/unyt-org/datex-embedded)** received crypto support for the ESP32 target and a major refactor of the embedded update loop, improving stability and preparing the groundwork for a TCP client interface.

## [DATEX Workbench](https://github.com/unyt-org/datex-workbench)

* **Network interfaces view.** The first live network interfaces panel has been built, showing active WebSocket and TCP connections with real-time updates. This gives developers direct visibility into the communication layer of a running DATEX endpoint.
* **Script editor.** Work on an integrated DATEX script editor continues, expanding the Workbench into a more complete development and inspection environment.

# Upcoming Events

Everyone is invited to participate in our public meetings.

* **Bi-Weekly Developers Meeting:** Tuesdays on a biweekly schedule, 8:00 PM CET/CEST.
* **Weekly DATEX Spec Talk:** Every Monday, 8:00 PM CET/CEST.
* **Monthly Management Meeting:** Tuesday, May 12, 8:00 PM CET/CEST.
