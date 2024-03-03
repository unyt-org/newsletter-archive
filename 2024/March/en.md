# March 2024

Dear friends of the unyt.org e.V.,

the last month's updates revolve around major compatibility and stability improvements for our frameworks and strategic decision making regarding the way we present ourselves in the public.

# Association
The main website will be overhauled. We will participate in social networks. 

- **The unyt.org e.V. is growing.**
  
	Over the last weeks **5 new members** joined our association. Welcome on board!

	You can apply for a membership [here](https://unyt.org/join).


- **We are working on a homepage overhaul.**

	After intensive discussions and inputs from various members, we have decided on a tone for our public communication. We intend to efficiently convey what unyt.org's objectives are and how we attempt to turn them into a reality through the provision of tools and platforms we develop. As the community we are, we would like to point out the open and welcoming nature of our projects throughout all of our sites.

- **We are increasing our social media presence. Support is welcome!**

	In order to make people aware of our projects, we will actively engage in certain digital media. Primarily, we will use [LinkedIn](https://linkedin.com/company/unyt-org) to communicate topics regarding our association and the community (e.g. gatherings). Mastodon and [X (Twitter)](https://unyt.org/twitter) will constitute the less formal mediums for interacting with the community of developers. If this sounds like a fun activity to you, we happily invite you to join our public relations working group.

# Development
UIX loading times were significantly improved. We incorporated multiple bugfixes into DATEX Core JS and did lots of refactoring.

The new releases `UIX 0.2.x` and `DATEX 0.1.x` include breaking changes due to the new [ES6 Decorators](https://devblogs.microsoft.com/typescript/announcing-typescript-5-0/#decorators). We are now supporting the latest Deno version. Please make sure to migrate your projects!

## [UIX](https://github.com/unyt-org/uix/pulls?q=is:closed%20created:%3E=2024-02-01)
* Migrated to new decorators, now compatible with Deno v0.40.0+
* Improved source map support for TypeScript files
* Hybrid rendering does now support [early hydration](https://docs.unyt.org/manual/uix/rendering-methods#hybrid-rendering)
* Added [minification and module preloading](https://github.com/unyt-org/uix/issues/102) to increase loading speed

## [DATEX](https://github.com/unyt-org/datex-core-js-legacy/pulls?q=is:closed%20created:%3E=2024-02-01)
* Migrated to new decorators, now compatible with Deno v0.40.0+
* Introduced the new [SQL Storage](https://github.com/unyt-org/datex-core-js-legacy/pull/90) location for more efficient handling of large data
* Added [match conditions](https://docs.unyt.org/manual/datex/storage-collections#match-conditions) for StorageCollections
* Major bugfixes and memory improvements

# Other topics
The course "Neue Web-Technologien" at **TU Berlin**, which was accompanied by Adrian Siebig as a lecturer, was concluded on 14th of February with the presentation of the UIX project work of the students. We are impressed by the results achieved by the course participants and are proud of the fact that the unyt.org projects played a major role in the course.

# Upcoming Events 

We invite you to join our open meetings.

* **Weekly Developers Meeting:** Tuesdays, 8:00 pm CET.
* **Monthly Management Meeting:** March 05, 8:00 pm CET.

----------------

We hope that our new communication channels spread awareness about our projects and that the association will grow and gain new valuable contributors. Thank you for being with us.

