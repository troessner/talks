The abstract is the 300 character elevator pitch for this talk.

--------------------

Parsing is the process of taking your code and turning it into an abstract syntax tree, a powerful abstraction that allows you to write code that works on code itself with ease. Let's talk about what abstract syntax trees are and discuss two gems that are leveraging their power.

--------------------




Description

This field supports Markdown. The description is the public abstract of your talk. The description will be seen by reviewers during the CFP process and will eventually be seen by the attendees of the event.

--------------------

Parsing is the process of taking your code and turning it into an abstract syntax tree, a powerful abstraction that allows you to write code that works on code itself with ease.

Let's talk about what abstract syntax trees are and discuss two gems that are leveraging their power.

The first gem we will look at is the [Reek gem](https://github.com/troessner/reek), a static code analyzer that examines Ruby classes, modules and methods and reports any [Code Smells](https://github.com/troessner/reek/blob/master/docs/Code-Smells.md) it finds.

We'll see in detail how Reek is wired up internally to parse the given source code into an abstract syntax tree, construct a tree of contexts out of it and then run various smell detectors on it.

The second gem we will look at is the [Mutant gem](https://github.com/mbj/mutant), one of the most advanced mutation testing tools for Ruby, that uses the same parser under the hood as `Reek` (the [Parser gem](https://github.com/whitequark/parser)) but has a vastly different approach how it operates on the abstract syntax tree.

--------------------

Notes

This field supports Markdown. Notes will only be seen by reviewers during the CFP process. This is where you should explain things such as technical requirements, why you're the best person to speak on this subject, etc...

--------------------

__Why I believe I'm qualified to speak about this subject__

I'm one of the current maintainers of the [Reek gem](https://github.com/troessner/reek).
I regularly blog about [advanced technical topics](https://tech.blacklane.com/2016/04/23/lessons-learned-from-some-of-the-best-ruby-codebases-part-1/). At the moment I'm also working on an article series about the [Mutant gem](https://github.com/mbj/mutant).

__Technical requirements__

The presentation is done via [reveal.js](http://lab.hakim.se/reveal-js/#/) but I can easily create a pdf out of this.

--------------------

Bio
This field supports Markdown. Your bio sells you. Who are you? Why should people listen to you? Who's your favorite member of One Direction?
This is your chance to put it all out there.

--------------------

I'm a long time Ruby developer and tech evangelist who's in love with all sorts of programming languages.
I work as director of engineering at [Blacklane](https://www.blacklane.com) in lovely Berlin and I am one of the maintainers of the awesome [Reek gem](https://github.com/troessner/reek), a static code analyzer that leverages the power of abstract syntax trees.

--------------------

Additional Information

--------------------

"What makes you a qualified person to speak about the proposed subject?"

I already talked about this in the notes above but let me just c&p it here for convenience:

I'm one of the current maintainers of the [Reek gem](https://github.com/troessner/reek).
I regularly blog about [advanced technical topics](https://tech.blacklane.com/2016/04/23/lessons-learned-from-some-of-the-best-ruby-codebases-part-1/). At the moment I'm also working on an article series about the [Mutant gem](https://github.com/mbj/mutant).

"Have you given this talk before at another conference? If so, where/when?"

No, I only have given this talk to my team at Blacklane.

"Are you a first-time speaker?"

No, but I'm also not an experienced conference speaker. The biggest talk I have given so far was a tech talk at Zalando with ~150 attendees.
