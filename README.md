# LaTeX Vorlagen
## Allgemeine Hinweise
Die meisten Beispiele basieren auf den sogenannten KOMA-Klassen, wie scrartcl, scrreprt oder scrlttr2. Des Weiteren sind alle Dokumente *UTF-8* kodiert und es werden die folgenden Pakte standardmÃ¤Ãig eingebunden:
```latex
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage[ngerman]{babel}
\usepackage{lmodern}
\usepackage{blindtext}
```
---
## Vorlagen zum Erstellen eines Berichts
### Einfacher Artikel
Das Beispiel verwendet die Klasse *scrartcl* und stellt damit `\section{}` als oberste Gliederungsebene bereit. Dieses Beispiel kann beispielsweise fÃ¼r die Erstellung einfacher Berichte, Protokolle oder kurzer Artikel verwendet werden.

  :page_with_curl: [Weitere Details](./simple-article/README.md)

### Einfacher Report
Das Beispiel und die darauf aufbauenden Beispiele verwenden die KOMA-Klasse *scrreprt*. Somit wird als oberste Gliederungsebene `\chapter{}` zur VerfÃ¼gung gestellt.  
  Der einfache Report ist beispielsweise fÃ¼r die Erstellung von umfangreicheren Protokollen geeignet. Im Unterschied zum einfachen Artikel sind zusÃ¤tzliche Pakete bereits eingebunden.

  :page_with_curl: [Weitere Details](./report-minimal/README.md)

### Erweiterter Report
Beim erweiterten Report handelt es sich um eine Erweiterung des Grundbeispiels. Beispielsweise werden zusÃ¤tzlich Kopf- und FuÃzeilen und ein Quellenverzeichnis (bibtex) verwendet.

:page_with_curl: [Weitere Details](./report-basic/README.md)

### Komplexes Beispiel (z.B. Bachelor, Master, Diplom)
Bei diesem Beispiel werden alle grundlegenden Pakete fÃ¼r eine wissenschaftliche Arbeit eingebunden (Ingenieurswissenschaften). Es besteht die MÃ¶glichkeit der Verwendung von Quellen (biblatex), einem eigenen Titelblatt, korrekte Verwendung von MaÃeinheiten. Des Weiteren sind diesem Beispiel einzelne kleine Anwendungsbeispiele beigefÃ¼gt.

:page_with_curl: [Weitere Details](./report-full/README.md)

---
## Vorlagen zu Erstellung von Briefen
Zur Erstellung von Briefen ist LaTeX ebenso geeignet wie zur Erstellung von einfachen oder komplexen Berichten. Einzelne Beispiele sind im Ordner [briefe](./briefe) zu finden.

:page_with_curl: [Weitere Details](./briefe/README.md)
