---
layout: post
title: "!Copy and paste code to minimize the impact:"
date: '2020-08-28 16:48:20'
tags:
- 97-things-not-to-do
---

<figure class="kg-card kg-image-card"><img src="/content/images/2020/08/image.png" class="kg-image" alt srcset="/content/images/2020/08/image.png 600w"></figure>

Have you ever seen code in your module, which was so complex that you decided to copy and paste it entirely rather than changing it to accommodate your requirement? What does it say about you and your codebase?

Though a seemingly harmless action at the time of copying and pasting can become the root of many issues in the future, imagine, one will have to remember to fix the problems in all the duplicated code all the time. If all duplicate code instances do not get fixes, these bugs may reappear in different places in the application. Remember, code is a liability; the more of it you have, the more time you will spend in maintaining it.

When intentional duplication becomes the way of safely making changes, you don't have enough tests, or your tests are not trustworthy. Also, the system may not follow SOLID principles, which makes it tough to extend and change.

.

