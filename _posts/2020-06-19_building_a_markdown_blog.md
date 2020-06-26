# Building a Markdown Blog

This is tricky cuz I'm gonna try to build the tools that build this blog while blogging this blog. I'm going to use a project
I built a while ago called [`spud`](https://github.com/broothie/spud). It's just a command executor written as a ruby DSL 
(yes, similar to [Rake](https://github.com/ruby/rake), but with some features I personally think Rake is missing).

Anyway, my [`Spudfile`](./Spudfile) is going to contain all the logic for building from Markdown to HTML. I'll use the gem
[kramdown](https://github.com/gettalong/kramdown) gem to do the actual conversion.

I guess the most annoying thing here will be setting up CSS. Unless kramdown comes with it, which I don't *think* it does,
but there's only one way to find out!
