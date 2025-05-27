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
<!-- new_lines: 3 -->
![image:width:50%](./assets/meme01.png)

<!-- end_slide -->
<!-- font_size: 3 -->

La réalité du terrain
===

<!-- pause -->
- <span style="color: palette:cyan">**10%**</span> Écrire du code
<!-- pause -->
- <span style="color: palette:blue">**15%**</span> Essayer de faire comprendre au product manager (ou au client) que le ticket #125 ne ne prend pas **QUE** 3h
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

<!-- font_size: 3 -->
Des trucs absurdes… mais qui tournent
===

<!-- font_size: 2 -->

* <span style="color: palette:cyan">**Minecraft** développé avec **Java**</span>
  * *Configuration minimale: 2000€*
<!-- pause -->
<!-- new_lines: 1 -->
* <span style="color: palette:cyan">**Le backend de Facebook** développé avec **PHP** *(avec HHVM)*</span>
  * *Askip c'est un langage mort depuis 15 ans*
<!-- pause -->
<!-- new_lines: 1 -->
* <span style="color: palette:cyan">**Le backend de Whatsapp** développé avec **Erlang**</span>
  * *C'est le même langage qui propulse les feux rouges*
<!-- pause -->
<!-- new_lines: 1 -->
* <span style="color: palette:cyan">**Le RER A (Île-de-France)** développé avec **COBOL** et **Fortran**</span>
  * *...quand ton passe Navigo dépend d’un mainframe IBM des années 70*
<!-- pause -->
<!-- new_lines: 1 -->
* <span style="color: palette:cyan">**La majorité des banques & assurances** utilisent **COBOL**</span>
  * *Il y a plus de COBOL en prod aujourd’hui qu’en 1980... Et plus personne ne sait le maintenir*

<!-- end_slide -->

<!-- font_size: 3 -->
Le bon langage, c’est celui qui coche les bonnes cases
===

<!-- font_size: 2 -->

* <span style="color: palette:green">**L'équipe le connaît**</span>
  * Moins de bugs, montée en charge rapide
<!-- pause -->
<!-- new_lines: 1 -->
* <span style="color: palette:green">**Il est déjà en place**</span>
  *	Moins de friction, moins de coût
<!-- pause -->
<!-- new_lines: 1 -->
* <span style="color: palette:green">**Il est maintenable dans le temps**</span>
  * On pense à la personne qui passera derrière
<!-- pause -->
<!-- new_lines: 1 -->
* <span style="color: palette:green">**Il a une bonne communauté**</span>
  * Stack Overflow = support non-officiel mais vital
<!-- pause -->
<!-- new_lines: 1 -->
* <span style="color: palette:green">**Il fait le job**</span>
  * Si la prod tourne, on a déjà gagné

<!-- end_slide -->

<!-- font_size: 3 -->
Conclusion
===
<!-- new_lines: 2 -->

![image:width:35%](./assets/meme02.png)

<!-- end_slide -->

<!-- font_size: 3 -->
Conclusion
===

<!-- alignment: center -->
<!-- new_lines: 4 -->
<!-- font_size: 2 -->
*<span style="color: palette:blue">**"Il n'y a que deux sortes de langages de programmation : ceux dont les gens disent toujours du mal et ceux que personne n'utilise."**</span>*
<!-- new_lines: 1 -->
<!-- alignment: right -->
Bjarne Stroustrup - créateur de C++
