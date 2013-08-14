---
layout: post
title: A New Beginning
date: 2013-08-14 11:00
categories: personal
---

I love the internet. There are so many awesome, free things out there for you to play with. Case in point, Github.
This blog is hosted on [Github Pages](http://pages.github.com/) for the wonderful price of free. Granted, they only
allow you to have static sites, but you can still build something awesome even without server side coding.

Last year I had created a site not unlike this one using this very same service. However, I ended up taking it down
after a while. I had essentially created it using a massive template and I didn't feel like I could really call it
my own. Maybe that seems a bit silly, but I feel that, as a programmer, I should understand the things that I build
on as intimate a level as possible. That way when things go wrong, as they often do, I have a much better idea about
what may have happened. It's the same sort of philosophy that drives my love of Arch Linux.

Anyway, I've been doing some web development during my summer internship with BP3 (Rails 4), and I've been learning
a lot about how things work. I can't say that I'm an expert, but I'm definitely much more comofortable with the idea
of web development. All this new-found confidence really got me pumped to get my site back up, and so here I am!

As I mentioned, Github Pages will only let you use static sites. Specifically, they use a tool called
[Jekyll](http://jekyllrb.com/) to generate the sites. Now you *can* use any static site generator, but I figure that
Github has their reasons for sticking with Jekyll (it helps that one of their engineers develops it), so my life will
be easiest if I use it. Last time around I used Jekyll-Bootstrap, a massive addon to Jekyll that automates essentially
everything for you. It was nice if you stuck to defaults, but customization was a pain. Most notably, the order of the
navbar links would randomize on each build, which was incredibly annoying. On top of all that, it hasn't really kept
up to date with changes in Jekyll (or Bootstrap).

So here I am with Jekyll and Bootstrap 3, having a blast. Since, at time of writing, Bootstrap 3 is only on RC2, my
hands have been tied on certain things. In particular, the scaffolding isn't all there yet. They seem to have
implemented everything for `col-sm` and `col-lg`, but nothing for `col-xs` or `col-md`. In particular this means
that the year on my archives page shows back up in xs sizes even though it shouldn't. I also want my contact links
to be on the bottom in xs and part of the navbar otherwise, but currently they're also on the bottom in sm. Aside from
that, things are working great! I love the new look!

Aside from those concerns, I'm really happy with the way this blog has turned out! I don't know how much I'll actually
be posting here, but it's always nice to have it available.

Cheers!