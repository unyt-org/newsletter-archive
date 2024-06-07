# June 2024

Dear readers,

during the last weeks, we have fixed some bugs and improved the documentation for our flagship products UIX and DATEX.
While we are still waiting for results on our application for funding, we are getting our decentralized authentication
service unyt Auth ready to go online after its big refactoring.

# Association

**Results on our transformD application are expected for the end of June.**
In March, we submitted our application for the [transformD](https://www.deutsche-stiftung-engagement-und-ehrenamt.de/foerderung/transformd/) support program.
We are awaiting the results and expect them to be announced at the end of this month. With a successful funding, we will primarily invest the resources into
expanding, maturing and maintaining our decentralized authentication infrastructure unyt Auth. Secondarily, UIX and DATEX will benefit from this investment
as well.

# Quick Bit: What is unyt Auth?
unyt Auth is a free of charge web-based open-source _service for authenticating persons, institutions and machines_ in applications that are built with
unyt.org technologies.

_For developers_, it offers easy integration with just a few lines of code.  
_For users_, it acts like a Single-Sign-On provider such as "Log in with Google".

_unyt Auth however is decentralized_ and writes the information to a distributed network storage that is _encrypted_ with keys owned by
the user. _The user has control_ over what information gets shared with what services he/she signs up for.

In the future, unyt Auth will support account validation for natural persons and institutions using government-official proofs and thereby offer a
fast and tamper-proof alternative to costly Know-Your-Customer (KYC) processes.

# Development
For the last few months we have been working on improving our project documentation on [docs.unyt.org](https://docs.unyt.org) and fixing many bugs to improve the overall stability of UIX and DATEX.

## [UIX](https://github.com/unyt-org/uix/pulls?q=is:closed%20created:%3E=2024-05-01)
* Initial work on an improved error handling system to allow for better developer experience. The user shall be provided with information about error stack, reason and steps to resolve the issue *(WIP)*
* Improvement of UIX session handling logic on the server to allow for verified and trusted endpoint communication

## [DATEX](https://github.com/unyt-org/datex-core-js-legacy/pulls?q=is:closed%20created:%3E=2024-05-01)
* The [match method](https://docs.unyt.org/manual/datex/storage-collections#pattern-matching) was added for [StorageMaps](https://docs.unyt.org/manual/datex/storage-collections#storagemaps)

## Other
* Started development of the unyt Auth project to provide a decentralized flexible authentication mechanism for the UIX@0.2.x version

# Upcoming Events 

We invite you to join our open meetings.

* **Weekly Developers Meeting:** Tuesdays, 8:00 pm CEST.
* **Monthly Management Meeting:** Tuesday, July 02, 8:00 pm CEST.
