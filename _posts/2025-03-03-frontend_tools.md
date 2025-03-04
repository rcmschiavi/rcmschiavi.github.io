---
title: "Frontend and Tool surprises"
date: 2025-03-03
layout: post
image: /assets/images/jekyllrb.png
headerImage: true
---

Before creating this project, I found a [github tutorial about](https://github.com/skills/github-pages) automating the page creation.
None the less, haven't stoped to understand what was happening. 

And then, boom. You endup needing to deploy every change to github to have your updates and test your layout. It is not as simple as html and css to check locally. 

There was something behind and it was a static file generator.

Choosing a tool... so hard task! But I did not need to think about it, it got chosen from commodity.

However, it comes with surprises!

Jekyll was a good surprise. Simple and flexible. Two great characteristics for a tool. 

 *Setup, the bad surprise*

:fearful:

Not cool rellying on stages to test your changes, so I got my shit together and read the [documentation](https://jekyllrb.com/docs/).

`$ gem install jekyll bundler`

`gem`? Where have I heard about it? Oh, no, ruby. Years without using it, my packages must be a mess.
Sometimes it's harder to change a package version then installing from scratch. But a few minutes fighting the terminal got it to work.

I had a setup using `rvm`, `ruby-2.6`. Then installed the ruby's new version available, 3.0.0. `rvm use 3.0.0` and followed with the documentation

`$ bundle exec jekyll serve`

You will then have a local url `http://localhost:4000` to call your own.

Jekyll features: 

- Markdown compatibility
- HTML support
- CSS support
- Scripting capabilities
- Pagination
- Tagging



End of the begining, beniging, begning...

:grin:

It is just starting

Now I can test better the layout changes and have a better time coding.

Thas what it is about:

Strugle until you're not.

Happy coding!
