emmet cheatsheet

# EMMET
* EMMET ist ein Weg Code in Kurzschreibweise zu schreiben und mit einem Click auf "tab" oder "enter" in echten HTML Code zu verwandeln.


* EMMET hat seinen Ursprung im ZEN-Coding, das aus dem minimalistischen Ansatz des japanischen ZEN entstanden ist.

* EMMET gibt es für die verschiedensten Codeeditoren und IDEs und auch nicht nur für HTML.

## EMMET - EINFACHE ELEMENTE
* Einfache Elemente
h1, div, img, ...

* Einfache Elemente mit ID
h1#MyId, div#MyId, #MyId

* Einfache Elemente mit Class(es)
h1.my-class, div.my-class, .my-class

* Einfache Elemente mit Multiplikator
p*3, img*4

## EMMET - VERSCHACHTELTE ELEMENTE
* Verschachtelte Elemente
ul>li, ul>li*3

* Verschachtelte Elemente mit dynamischen IDs
ul>li#item$*5

* Verschachtelte Elemente mit dynamischen IDs und Inhalt
ul>li#item${item $}*5

## EMMET - GESCHWISTER ELEMENTE
* Geschwister Elemente
section>h3+p.teaser

* Gruppen von Geschwistern
div>h3{Suche}+(form>input*2)

## EMMET - ELEMENTE MIT ATTRIBUTEN
* Elemente mit Typen
form>input:text+input:password

* Elemente mit Attributen - Login Form
form>input:text[name="user"]+input:password[name="pass"]+input:submit[value="login"]

* Elemente mit Attributen - Search Form
section>h3{Suche}+(form>input[name="search"]+input:submit[value="suchen"])

## EMMET - SPECIAL
* html5 boilerplate
!

* article with dummy-text
article>h1{hello world}+p*2>lorem
