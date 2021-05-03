---
layout: post
title: "!Optimize Prematurely"
date: '2020-09-04 19:43:00'
tags:
- 97-things-not-to-do
---

Once again, you would think that the software development community has moved past this point, but I still get many teammates who want to "save memory" using HashMaps instead of POJOs. I am not too sure how efficient HashMaps are when compared to POJOs, but I am sure of how they can become a maintenance nightmare if wherever we could use POJO, we start using maps.

In hindsight, it now seems foolish, but I have been guilty of committing crimes like sprinkling static variables, singletons, and data structures like maps instead of more compiler friendly data structures. All this, because either I had some misconception about how performance optimization works or I had an obscure scenario in my mind like "what will happen when 2,13,00093 users access my piece of code in parallel."

Between a speculative performance issue that you may or may not encounter and use of clean code, clean code should always win. If your code is clean, it will be easy to find it and fix it when a performance issue arises.

