---
layout: archive
title: "Academic Genealogy"
permalink: /genealogy/
author_profile: true
redirect_from:
  - /genealogy
---

{% include base_path %}

<iframe src="/files/genealogy.pdf" width="100%" height="800px">
</iframe>

```mermaid
graph TD
  Miller["Merton Miller"]
  Fama["Eugene Fama"]
  Watts["Ross Watts"]
  Sloan["Richard Sloan"]
  Richardson["Scott Richardson"]
  Ellahie["Atif Ellahie"]
  Wang["Ching-Chuan (David) Wang"]

  Miller --> Fama
  Fama --> Watts
  Watts --> Sloan
  Sloan --> Richardson
  Richardson --> Ellahie
  Ellahie --> Wang
