---
layout: post
title: Composer Tips & Tricks Talk
author: hkdobrev
---

I've recently gave a talk about Composer Tips & Tricks at the [Bulgaria PHP user group meeting in March](https://www.facebook.com/events/1538125716485720/).

Here are my slides and a list of tips and some useful links with examples from the talk:

<script async class="speakerdeck-embed" data-id="86ae1f9abe88404dbc0ba5c4237348f4" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script><noscript><a href="https://speakerdeck.com/hkdobrev/composer-tips-and-tricks" rel="nofollow" title="Composer Tips & Tricks talk from Haralan Dobrev">Go to SpeakerDeck for the slides.</a></noscript>

---

- [`composer create-project`](https://getcomposer.org/doc/03-cli.md#create-project)

- [clippings/composer-init](https://github.com/clippings/composer-init)

- [`composer update --with-dependencies`](https://getcomposer.org/doc/03-cli.md#update), [`composer require --update-with-dependencies`](https://getcomposer.org/doc/03-cli.md#require), [`composer remove --update-with-dependencies`](https://getcomposer.org/doc/03-cli.md#remove)

- [`composer update --prefer-lowest`](https://getcomposer.org/doc/03-cli.md#update)

-  [Travis CI with build matrix](https://docs.travis-ci.com/user/customizing-the-build/#Build-Matrix)

- [Example of a `.travis.yml` using `--prefer-lowest`](https://github.com/OpenBuildings/spiderling/blob/master/.travis.yml) and an [example Travis CI build with that matrix](https://travis-ci.org/OpenBuildings/spiderling/builds/115010097)

- [`config.platform`](https://getcomposer.org/doc/06-config.md#platform)

- [`config.preferred-install`](https://getcomposer.org/doc/06-config.md#preferred-install)

- [.gitattributes export-ignore](https://git-scm.com/book/en/v2/Customizing-Git-Git-Attributes#export-ignore-KpTEIVH6hk)

- [`composer test` and `composer run-script`](https://getcomposer.org/doc/articles/scripts.md)

- [`composer depends`](https://getcomposer.org/doc/03-cli.md#depends), [`composer prohibits`](https://getcomposer.org/doc/03-cli.md#prohibits)

- [composer branch aliases](https://getcomposer.org/doc/articles/aliases.md)

- Bonus: [Facebook's PR mention bot for GitHub](https://github.com/facebook/mention-bot)

---

We are eager to be organising, attending and speaking at more events. [Drop me a line if you have ideas about various events](mailto:harry@clippings.com).

We're hiring! If you want to know more [read about working at Clippings.com](https://clippings.github.io/working-at-clippings).
