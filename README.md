# LaTeX Vorlagen
## Allgemeine Hinweise
Die meisten Beispiele basieren auf den sogenannten KOMA-Klassen, wie scrartcl, scrreprt oder scrlttr2. Des Weiteren sind alle Dokumente *UTF-8* kodiert und es werden die folgenden Pakte standardmäßig eingebunden:
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
Das Beispiel verwendet die Klasse *scrartcl* und stellt damit `\section{}` als oberste Gliederungsebene bereit. Dieses Beispiel kann beispielsweise für die Erstellung einfacher Berichte, Protokolle oder kurzer Artikel verwendet werden.

  :page_with_curl: [Weitere Details](./simple-article/README.md)

### Einfacher Report
Das Beispiel und die darauf aufbauenden Beispiele verwenden die KOMA-Klasse *scrreprt*. Somit wird als oberste Gliederungsebene `\chapter{}` zur Verfügung gestellt.  
  Der einfache Report ist beispielsweise für die Erstellung von umfangreicheren Protokollen geeignet. Im Unterschied zum einfachen Artikel sind zusätzliche Pakete bereits eingebunden.

  :page_with_curl: [Weitere Details](./report-minimal/README.md)

### Erweiterter Report
Beim erweiterten Report handelt es sich um eine Erweiterung des Grundbeispiels. Beispielsweise werden zusätzlich Kopf- und Fußzeilen und ein Quellenverzeichnis (bibtex) verwendet.

:page_with_curl: [Weitere Details](./report-basic/README.md)

### Komplexes Beispiel (z.B. Bachelor, Master, Diplom)
Bei diesem Beispiel werden alle grundlegenden Pakete für eine wissenschaftliche Arbeit eingebunden (Ingenieurswissenschaften). Es besteht die Möglichkeit der Verwendung von Quellen (biblatex), einem eigenen Titelblatt, korrekte Verwendung von Maßeinheiten. Des Weiteren sind diesem Beispiel einzelne kleine Anwendungsbeispiele beigefügt.

:page_with_curl: [Weitere Details](./report-full/README.md)

---
## Vorlagen zu Erstellung von Briefen
Zur Erstellung von Briefen ist LaTeX ebenso geeignet wie zur Erstellung von einfachen oder komplexen Berichten. Einzelne Beispiele sind im Ordner [briefe](./briefe) zu finden.

:page_with_curl: [Weitere Details](./briefe/README.md)
