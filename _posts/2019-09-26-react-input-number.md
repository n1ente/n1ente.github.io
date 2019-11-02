---
title: React input number done right
tags:
  - JavaScript
description: >
     Having an input number working correctly is not that easy, let me share my implementation.
---

In this article I am going to share my own implementation, you may want to use as a starting point.
There are some use cases where you prefer to write an implementation from scratch, avoid dependencies as much as possible, and get maximum control and chance to customization.

## Analysis

Using `<input type='number' />` has few issues: for example you can type the following:

* `-1-2`
* `1.2...`
* `1.2.3.4----`

This **is bold**, this _is italic_
