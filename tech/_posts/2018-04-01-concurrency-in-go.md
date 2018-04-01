---
layout: post
title: Concurrency in Go
---

Concurrency isn't a concept I've ever really worked with. It's exactly the type of thing that bootcamp graduates like myself typically fall short on. 

At Monzo all of our backend code is written in Go, with services living within a microservices infrastructure. We need to be able to process requests with speed and reliability. That means writing code that's both efficent and fails well. If I'm gonna level up, I've got to become familiar with how Go deals with concurrency.

I started by watching [this video](https://www.youtube.com/watch?v=LvgVSSpwND8), which provided a whistlestop tour of the main concepts.

Main take-aways:
- Concurrency is
