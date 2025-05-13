# April 2025

Dear readers,

in April we started working on the new website and pushed forward the Rust rewrite of DATEX Core.

# Association

**Working on the website**
We were delighted to welcome our two new team members, Marvin and Dave, to our association.
After the introductory phase, we are now moving on to developing a holistic concept and subsequently
implementing our new website.

# Development
We made several enhancements to the documentation on docs.unyt.org to provide clearer guidance on using our projects. This includes:

* More detailed API usage examples
* Clarified behavior of key components
* Remove legacy API documenation (soft deletions)

## [UIX](https://github.com/unyt-org/uix/pulls?q=is:closed%20created:2025-04-01..2025-05-13)
* Improved documentation on docs.unyt.org to provide clearer information on API usage and specific topics.
* Enhanced structure and examples to better support new users and contributors.
* Fixed a bug that was caused by [TSC](https://github.com/microsoft/TypeScript) when the UIX project contains spaces in it's path

## [DATEX](https://github.com/unyt-org/datex-core-js-legacy/pulls?q=is:closed%20created:2025-04-01..2025-04-01)
* Enhanced documentation for [Storage collections](https://github.com/unyt-org/datex-core-js-legacy/blob/main/docs/manual/15%20Storage%20Collections.md)

## [DATEX (RUST)](https://github.com/unyt-org/datex-core)
* **First protocol send and routing logic is now functional!** This means we're able to send blocks across different channels (e.g. WebSocket and TCP), and the routing/redirecting mechanism - while still in early stages - is working. This is an exciting step toward building a faster, more robust core for DATEX.
* Next goals:
  * Implementing DATEX Values and Pointers
  * Supporting serialization, updates, and retrieval of values across endpoints
  * Laying the groundwork for the full data interaction pipeline


## Other
The New Web Technologies programming course at the Technical University of Berlin is starting again this semester.
It uses unyt.org tools to enable students to develop their own extensive web applications in groups. We are looking forward to see which ideas are being developed.

# Upcoming Events 

We invite you to join our open meetings.

* **Bi-Weekly Developers Meeting:** Every first and third tuesday a month, 8:00 pm CET/CEST.
* **Weekly DATEX Spec Talk:** Every monday, 8:00 pm CET/CEST.
* **Monthly Management Meeting:** May 06, 8:00 pm CET/CEST.
