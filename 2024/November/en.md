# November 2024

Dear readers,

the last two months consisted of numerous hours of work and planning that eventually led to the release of UIX 0.3 – a leap in Developer Experience.

# Association

- **The StartupSÜD Summit Has Been a Success.**
  
  In October, the association [exhibited at the StartupSÜD Summit](https://de.linkedin.com/posts/unyt-org_unytorg-uix-startups%C3%BCd-activity-7255479246079324160-5oft) in 
  Ulm, Germany. A lot of interesting conversations took place at the
  prominent unyt.org Pavillon. We are looking forward to working and
  partnering with the inspiring people we met there.

- **Approaching the Website Overhaul**
  
  After several proposals have been made, the unyt.org main page 
  overhaul is now coming into reality with the joining of a new
  member for our Communication and Public Relations department.
  As a professional web and marketing designer, she will
  explicitly focus on the new website and dedicate her time to
  the creation of a coherent and visually appealing user
  interface throughout our entire web presence.

- **Celebrating One Year of New Web Technologies**
  
  [New Web Technologies](https://www.tu.berlin/en/snet/study/modules/programming-practical-course-new-webtechnologies) is a
  course that teaches fundamentals of modern interconnection
  and web application development while taking serious security
  approaches into account. It is also one of the first courses
  to teach unyt.org technologies and be accredited as
  an official qualification on state university diplomas. After
  many interesting student projects ranging from productivity
  tools to live entertainment, New Web Technologies celebrated
  its first anniversary in October 2024. 

# Quick Bit: Introducing Magic – Announcing UIX 0.3
UIX 0.3 is a remarkable leap towards enjoyable developer experience. It introduces automatic reactivity by default, significantly simplifying development. This release eliminates the need for manual reactivity management, such as using `$`-properties or the `always` method. The framework now handles state updates and DOM rendering autonomusly, all by itself! This is achieved through JUSIX, a new Deno SWC plugin that processes JSX as reactive JavaScript and is bundled with _Deno for UIX 2.0_.

For example, this UIX 0.3 code snippet shows a checkbox bound to a `checked` pointer, automatically updating the UI when toggled:

```tsx
const checked = $(false);
export default
    <div>
        <input type="checkbox" checked={checked}/>
        <label>{checked ? "Checked" : "Not checked"}</label>
    </div>
```

In UIX 0.3, you no longer need to manually use the `always` method for reactive updates. The following code is now sufficient to automatically reflect changes:

```tsx
const myVar = $(4);
<div>{myVar + 1}</div>;
myVar.val ++;
```

Reactivity does now work out of the box. The new version also includes performance improvements, bug fixes, and a new custom installation script that simplifies setup to provide a coherently comfortable developer experience.

# Development
UIX 0.3 with its new syntax and a custom optimized Deno for UIX runtime is released. DATEX 0.2 is released. A new DATEX Workbench is under development.

## [UIX](https://github.com/unyt-org/uix/pulls?q=is:closed%20created:2024-09-01..2024-10-31)
* **UIX 0.3 is released**! Being one of the largest releases in the history of the Full-Stack Framework, it supports an entirely new reactivity syntax which significantly simplifies developing applications with reactive state.
* **Deno for UIX 2.0 is released.** For the first time, UIX is accompanied by its own dedicated version of Deno. The implemented modifications live deep in the core of the modern runtime environment, with enhancements to the JSX compiler and code linter that make the convenience of UIX 0.3 just possible.
* **Introducing the new setup experience.** Following the 2024/Q3 Developer Experience Initiative, one of the first impressions to new developers has been vastly improved. The new installation procedure requires just one command and works on all major operating systems. It installs Deno for UIX and UIX and populates environment variables in one go. The project creation procedure is more customizable with a range of templates to choose from.
* **Cross-platform TailwindCSS support is now available.** After many requests, the previously experimental native TailwindCSS theme that ships and integrates with UIX is now available on all major operating systems.
* **Docker-Host v2 is released.** The new version features token-based access protection and numerous security and usability enhancements.

## [DATEX](https://github.com/unyt-org/datex-core-js-legacy/pulls?q=is:closed%20created:2024-09-01..2024-10-31)
* **DATEX 0.2 is released.** The enhancements include wide-ranging support for the new unified reactivity function (`$()`), improved sqlite3 support that reached beta status and may soon be released as the default storage backend for eternal pointers and security and performance improvements.
* **The DATEX Workbench is under development.** First versions have already been presented in developer meetups. The Workbench will be a set of inspection, debugging and testing tools for DATEX that run right in the Browser Developer Tools or in Visual Studio Code. Pre-releases can already be installed [from the Chrome Web Store](https://chromewebstore.google.com/detail/datex-workbench/pkbjldajjofekolhdglbncpjpkdplnok).


# Upcoming Events 

We invite you to join our open meetings.

* **Bi-Weekly Developers Meeting:** Every first and third tuesday a month, 8:00 pm CET/CEST.
* **Monthly Management Meeting:** December 03, 2024, 8:00 pm CET/CEST.
