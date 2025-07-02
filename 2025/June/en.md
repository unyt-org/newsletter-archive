# June 2025

Dear readers,

in may we have made significant progress with the development of DATEX Core Rust (also known as DATEX v2).
Furthermore, we are delighted to welcome new interns to our association.

# Association

Following our website overhaul which marks another milestone in the professionalization of
the unyt.org e.V., we have decied to publish job postings on both our Website and on the
career network LinkedIn. We were overwhelmed by the many applications and have had some
nice conversations with many of the applicants.

We are still in the process of hiring interns but are already delighted to welcome **Norbert**
to our team. He has already and will contribute highly qualitative software components to
our high-priority flagship development DATEX Core Rust. In particular, he will use his
experience to focus on cryptography implementations that are a crucial element
to DATEX' security.

Applications are possible at any time at: [https://unyt.org/career](https://unyt.org/career).

# Development
A first version of the DATEX language is implemented. The focus will now be shifted to synchronizing data (Pointers)
over the network. UIX received minor bugfixes. Initial work on the DATEX specification viewer has been done.

## [DATEX (Rust)](https://github.com/unyt-org/datex-core/pulls?q=is:closed%20created:2025-06-01..2025-06-30)
* Migrated the values branch, DATEX can now represent "primitive" values (all JSON values) such as booleans, arrays, strings and integers
* As JSON is a subset of the DATEX script language, the DATEX Core runtime can now parse JSON
* We added benchmarks to test the speed of our installer
* We added assignments to the DATEX language: `val x = 42 + 5`; `ref y = 52`
* We will now shift our focus towards the DATEX _Pointers_ concept so that we become able to transfer DATEX data across endpoints
* Added tuples: `(1,5,"hello world")`

## [UIX](https://github.com/unyt-org/uix/pulls?q=is:closed%20created:2025-06-01..2025-06-30)
* Minor bugfixes (e.g. permission error for hydration)

## Other
* Work on spec viewer to display our DATEX specification

# Upcoming Events 

We invite you to join our open meetings.

* **Bi-Weekly Developers Meeting:** Tuesdays on a biweekly schedule, 8:00 pm CET/CEST.
* **Weekly DATEX Spec Talk:** Every monday, 8:00 pm CET/CEST.
* **Monthly Management Meeting:** July 08, 8:00 pm CET/CEST.
