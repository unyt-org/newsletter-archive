# November 2025

Dear readers,

November has shown continous progress and collaborations. We've welcomed new members to our community, gained a partnership in the education sector, and expanded work on our new DATEX Core.

---

# Association

We're thrilled to welcome our **new members** Bhavna and Mayank to the unyt.org association this month! Following our latest application round, we've expanded our community with talented individuals who share our vision.

- **Onboarding with Mayank**

  We've onboarded Mayank to advance our DATEX Core initiatives. His expertise will help drive forward the development of our core technologies.

- **Websites Team Expansion**

  [Lennart](https://github.com/lennartstoelting) and [Khaled](https://github.com/kha1dx), who joined us last month to work on the DATEX Workbench, have now been officially added to our websites team page as interns. Both continue to make valuable contributions to the project.

- **Partnership with IfDL**

  We held a strategic meeting with the **Institut für Digitale Lehre (IfDL)**, our co-department focused on digital education. This initiative opens up exciting opportunities to explore how DATEX and UIX can support modern educational platforms and digital learning environments.

---

# Development

November saw intensive work across multiple fronts, from the DATEX Workbench to both our Rust and JavaScript implementations of DATEX Core.

## [DATEX Workbench](https://github.com/unyt-org/datex-workbench/pulls?q=created:2025-11-01..2025-11-30)

The **DATEX Workbench** - our tooling and debugging environment for the DATEX ecosystem - continues to take shape.

This month, we completed initial code reviews integrating key components:
* **DATEX pointer view / explorer** – for inspecting the memory of a DATEX endpoint
* **DATEX Block viewer** – for intercepting and inspecting incoming and outgoing DXB blocks

A merge and deployment of the first rudimentary variant is planned for mid-December, bringing these debugging capabilities to the team.

## [DATEX Core (Rust)](https://github.com/unyt-org/datex-core/pulls?q=is:closed%20created:2025-11-01..2025-11-30)

Significant progress has been made on the **DIF protocol** (DATEX Interchange Format), which facilitates data exchange between DATEX implementations (e.g. DATEX Core Rust in WebAssembly) and foreign environments such as JavaScript. This is a crucial piece of infrastructure that will enable seamless integration between DATEX and existing technologies.

We're reviewing the last feature branches as we target **release 0.0.7**, with ongoing DIF updates and components to allow for JS pointer synchronization planned for completion by the start of December.

## DATEX Core JS

Our DatexCore<->JavaScript connection implementation has received important enhancements to its type system. We've added **type mappings** that enable **JS objects, maps, and arrays to sync with actual DATEX core types**.

---

# Upcoming Events

We invite you to join our open meetings.

* **Bi-Weekly Developers Meeting:** Tuesdays on a biweekly schedule, 8:00 pm CET/CEST.
* **Weekly DATEX Spec Talk:** Every monday, 8:00 pm CET/CEST.
* **Monthly Management Meeting:** Tuesday, December 09, 8:00 pm CET/CEST.
