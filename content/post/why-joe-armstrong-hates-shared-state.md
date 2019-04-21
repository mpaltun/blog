---
title: "Why Joe Armstrong hates shared state?"
date: 2019-04-21T22:59:57+03:00
draft: false
---

I stumbled across an awesome quote by Joe Armstrong when he was explaining the reason why he hates threads and shared state on a [Hacker News Thread](https://news.ycombinator.com/item?id=19708900) (It was an email conversation actually):

---

> In distributed systems there is no real shared state (imagine one machine in the USA another in Sweden) where is the shared state? In the middle of the Atlantic? - shared state breaks laws of physics.
> State changes are propagated at the speed of light - we always know how things were at a remote site
> not how they are now. What we know is what they last told us. If you make a software abstraction that
> ignores this fact you'll be in trouble.

---

I heard/read similar ideas from him but not in those words and I actually quite like it.

I'll miss him even though I never met him in person but read his writings, watched presentations, retweeted him and (of course) implemented fair amount of programs with Erlang. 

RIP Joe. 

