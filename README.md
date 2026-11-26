Inno Setup
==========

Copyright (C) 1997-2026 Jordan Russell. All rights reserved.  
Portions Copyright (C) 2000-2026 Martijn Laan. All rights reserved.  
For conditions of distribution and use, see LICENSE.TXT.

Isfaq README

Getting Started
---------------

Go to [isfaq.html] and suggest new entries or other improvements using the Edit button. Thanks in advance!

Please try to make your changes as consistent as possible with the existing text and write them in such a way that the information will stay accurate for many years to come and requires as little maintenance as possible.

The anchor of a section is the id of its `<h2>`, which the top of the FAQ page links to. A new section needs a link there too.

Below its `<h2>`, each section has a button "Expand all" for its topics. A new section needs one too.

Each topic is a `<details>` with its question as the `<summary>`. The anchor of a topic is the id of the `<div>` with its answer, because a browser opens a closed `<details>` for a link to an element in it.

Give the `<tt>` of a code example of one line the class `example`. A code example of several lines doesn't need it.

Please do <b>not</b> submit translations.

<!-- Link references -->
[isfaq.html]: <https://github.com/jrsoftware/isfaq/blob/main/isfaq.html>