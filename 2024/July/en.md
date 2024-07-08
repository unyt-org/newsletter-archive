# July 2024

Dear friends of the unyt.org e.V.,

for the last month we've discussed standardization strategies and worked on a series of technical improvements to our core products UIX and DATEX.

# Association
UIX 0.2.16 introduces a new client-side routing in the current UIX routing system. This implementation uses the new [Navigation API](https://developer.mozilla.org/en-US/docs/Web/API/Navigation). The new system avoids the complete reloading of pages during navigation and creates a smooth transition between different views and routes.

As soon as the `"frontend-navigation"` flag is added to the `experimental_features` list in the [app.dx configuration](https://docs.unyt.org/manual/uix/configuration#experimental-features), frontend routes can now be resolved and displayed without reloading the page. With the new [View Transitions API](https://developer.mozilla.org/en-US/docs/Web/API/View_Transitions_API), animations for transitions can also be added with minimal effort to achieve a seamless visual appeal.

[This article on unyt.blog](https://unyt.blog/article/2024-07-07-client-side-routing-for-web-apps-with-uix) gives a first introduction to the new UIX routing system and explains how to use the new features.


# Wick🕯️Bit: Happy Birthday, Benedikt
Today is a special day for one of the founders of our association and the driving force behind the entire unyt.org project - **Benedikt Strehle**. With more than a decade of experience gained together with his cousin Jonas, he will certainly have witnessed how the Internet was powered by horse-drawn carriages, the Windows UI was still black and white and Steve Jobs actually had hair. Always moving with the times and the spirit of innovation, however, he soon picked up on the Cretaceous ideas of Deno, Rust & co to build a huge tech stack with UIX, DATEX, unyt Auth, HELIX & co brick by brick.

However, he and Jonas originally started out developing games, constantly working on anything that was fun and entertaining, no matter what technical challenge they faced. With great games like "Keks-mas" or "Card-To-Throw", there has never been any doubt that Benedikt would later revolutionize the entire Internet. Even if none of us know for sure whether you're Benedikt, Benni, Ben, or (improbably) Beni - all of that is pretty inspiring and cool - so thank you, Ben[\w]*! And happy birthday!

# Development
A new front-end routing system was introduced with the latest UIX release. Extensive stability improvements have been made to our core projects.

## [UIX](https://github.com/unyt-org/uix/pulls?q=is:closed%20created:%3E=2024-06-01)
* Introduction of an experimental [Frontend-Router](https://github.com/unyt-org/uix/pull/160) for client-side navigation
* Support for the new [View Transitions API](https://docs.unyt.org/manual/uix/configuration#experimental-features)
* [`Dates`](https://github.com/unyt-org/uix/issues/154) can now be used as values for HTMLInputElements

## [DATEX](https://github.com/unyt-org/datex-core-js-legacy/pulls?q=is:closed%20created:%3E=2024-06-01)
* Improvement of the [Endpoint instance determination](https://github.com/unyt-org/datex-core-js-legacy/pull/116) between different browser tabs
* Other stability improvements and bug fixes

## Other
* The [unyt Auth](https://auth.unyt.org) service is now active again

# Upcoming Events 

We invite you to join our open meetings.

* **Weekly Developers Meeting:** Tuesdays, 8:00 pm CET.
* **Monthly Management Meeting:** July 09, 8:00 pm CET.
