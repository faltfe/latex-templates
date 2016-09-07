# Brief
Briefe schreiben kann ziemlich anstrenegende werden, wenn man die korrekte Formiertierung beachtet. LaTeX nimmt einen genau diese Arbeit ab. Die einzelnen Klassen können teilweise mit unterschiedlichen Paketen erweitert werden. Einzelheiten sind bei den jeweiligen Klassen aufgelistet.

## g-brief (veraltet :bangbang:)
Für die Erstellung eines Briefs mit einem Format, welches in Deutschland verbreitet ist, eignet sich diese Klasse. Allerdings sollte sie durch g-brief2 ersetzt werden.

## g-brief2
Die Klasse ist der Nachfolger von g-brief und ist ebenfalls für die Erstellung eines Briefs mit deutscher Formatierung geeignet.

## letter (veraltet :bangbang:)
Mithilfe dieser Klasse lassen sich einfache Briefe ohne Ansprüche erstellen. Für komplexere Briefe ist die Klasse scrlttr2 zu bevorzugen.

## scrlttr2
Die Klasse kann für die Erstellung von internationalen Briefen verwendet werden. Anpassungen an das Design sind durch die Verknüpfung mit KOMA-Script einfacher vorzunehmen.

Verwendete Pakete:
```
\usepackage{graphicx}
\usepackage{geometry}
\usepackage{marvosys}
\usepackage{xcolor}
\usepackage{scrlayer-scrpage} % optional für Kopf- und Fußzeile
```
