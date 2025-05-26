---
title: J’ai pas besoin du meilleur langage. J’ai besoin de finir mon sprint
author: Adrien Gras
theme:
  name: catppuccin-mocha
  override:
    palette:
      colors:
        cyan: "94e2d5"
        pink: "cba6f7"
        blue: "89b4fa"
        red: "f38ba8"
        green: "a6e3a1"
        orange: "fab387"
    intro_slide:
      title:
        alignment: left
        padding_bottom: 1
        padding_top: 0
        colors:
          foreground: palette:orange
        bold: true
        font_size: 5
      author:
        colors:
          foreground: palette:cyan
        positioning: page_bottom
    footer:
      style: template
      left: "J’ai pas besoin du meilleur langage. J’ai besoin de finir mon sprint"
      center: "@AdrienGras"
      right: "{current_slide} / {total_slides}"
      height: 2
---

<!-- font_size: 3 -->

C'est quoi le meilleur langage pour... ?
===

![](./assets/meme01.png)

<!-- end_slide -->
<!-- font_size: 3 -->

La réalité du terrain
===

<!-- pause -->
- <span style="color: palette:cyan">**5%**</span> Écrire du code
<!-- pause -->
- <span style="color: palette:pink">**5%**</span> Gérer les tickets
<!-- pause -->
- <span style="color: palette:blue">**10%**</span> Essayer de se comprendre avec le product manager
<!-- pause -->
- <span style="color: palette:red">**75%**</span> NullPointerException at line 55
<!-- pause -->

<!-- new_lines: 1 -->
*TypeError: Cannot read properties of undefined*  
*Segmentation fault (core dumped)*  
*thread 'main' panicked*  
*Fatal error: Attempt to access property on null*  
*...*


<!-- end_slide -->
