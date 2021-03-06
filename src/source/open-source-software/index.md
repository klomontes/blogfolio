---
title: Open Source Software
intro: The existence of open source software is one of the most beautiful things about this industry and our craft. This page seeks to document my efforts to help maintain it and create new micro modules that others might find useful.
seo_description: Some thoughts on my commitment to open source software and how we can all chip in.
date: 2018-03-28
---

## ❤️ Open Source

I’ve decide that the best I can do to get involved in big projects is to focus on improving docs, developer experience, and reporting bugs.

When it comes to small tools I try to actively contribute code. Usually this is because of a need to get a bug fixed or to speed up the addition of a new feature.

It’ve authored several open source modules of my own, and they’re used in commercial software around the world – and by people other than myself. :)

I’ll list a few of them here.

### ⚛️ spicy-datatable

<a href="https://github.com/filipdanic/spicy-datatable" target="_blank">**spicy-datatable**</a> is my first OSS project that got some traction from the community. 🎉 It’s a React.js datatable component that includes search, pagination, CSV export, and localization support.

The motivation for creating this module was:

1. Most React datatable components use jQuery for some DOM manipulation dark magic.
2. Others were just too complex for a simple use case or did not have all the features I needed.

### 🛠 Utilities

I’ve authored quite a few utilities so far. I love micro modules like this and actively look for an opportunity to pluck out some code from my commercial projects and post it on GitHub.

I keep a list of them here for reference:
- <a href="https://github.com/filipdanic/is-of-type" target="_blank">**is-of-type**</a> – various utility functions such as `isString`, `isNumber`, `isDefinedAndNotNull`, etc.
- <a href="https://github.com/filipdanic/matchcase" target="_blank">**functional-match-case**</a> – say goodbye to switch statements in JavaScript.
- <a href="https://github.com/filipdanic/with-prefix" target="_blank">**with-prefix**</a> – ensures that a string starts with the given prefix, if it does not already.
- <a href="https://github.com/filipdanic/monogatari" target="_blank">**monogatari**</a> – an opinionated logging wrapper around chalk.
- <a href="https://github.com/filipdanic/verify-facebook-request-signature" target="_blank">**verify-facebook-request-signature**</a> – express.js middleware to handle Facebook’s `x-hub-signature` header.
- <a href="https://github.com/filipdanic/listify-messenger-webhook-events" target="_blank">**listify-messenger-webhook-events**</a> – parses the events object from Facebook Messenger and returns an array of events that is easier to work with.
- <a href="https://github.com/filipdanic/json2csvexporter" target="_blank">**json2csvexporter**</a> – a simple client-side solution to generate CSV files from JSON.
- <a href="https://github.com/filipdanic/get-nested-value" target="_blank">**get-nested-value**</a> – utility package to get deeply nested values from objects. Support arrays.
- <a href="https://github.com/filipdanic/24h-to-12h-format" target="_blank">**24hto12hformat**</a> – convert 24-hour format strings (`hh:mm`) to 12-hour format with AM/PM suffix.
- <a href="https://github.com/filipdanic/compact-timezone-list" target="_blank">**compact-timezone-list**</a> – an exported array of timezones with their `label`, `tz` code, and `UTC offset`.
- <a href="https://github.com/filipdanic/is-non-empty-array" target="_blank">**is-non-empty-array**</a> – a utility that does what it says. :)
- <a href="https://github.com/filipdanic/execute-if-function" target="_blank">**execute-if-function**</a> – please no more `func && func()`! 😐
- <a href="https://github.com/filipdanic/get-random-in-range" target="_blank">**get-random-in-range**</a> – get a random number in range as a lazy curried function.

### 🐺 spwolf

<a href="https://github.com/filipdanic/spwolf" target="_blank">**spwolf**</a> is an opinionated solution for creating forms in React.js by using `.spec` files. Although it is very much a work-in-progress, I’m using it in production and updating things as I go. It has already saved me tons of time and effort when it comes to constructing forms, implementing validation, and diff-ing data.

**Reach out!**

Remember, you can always <a href="mailto:filipdanic7@gmail.com">email me</a> or reach out <a href="https://twitter.com/DanicFilip" target="_blank">via Twitter,</a> if you want to learn more. I’m also actively looking for <a href="/speaking">new speaking opportunities,</a> or going out for a beer if you’re in Belgrade. 🍻

You can also catch me on <a href="https://www.twitch.tv/filipdanic" target="_blank">on Twitch,</a> where I occasionally live stream. Past recording are posted <a href="https://www.youtube.com/channel/UClctBvKpOUts0_B_kvooo_w" target="_blank">on YouTube.</a>
