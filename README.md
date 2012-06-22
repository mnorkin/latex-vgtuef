# VGTU EF Latex Bachelor Thesis Style

This is a simple style for writing a bachelor thesis in latex

# INSTALLATION

# USAGE

```
\documentclass[]{vgtuef} % include style
% Critical packages for writing with lithuanian letters
\usepackage[utf8x]{inputenc}
\usepackage[L7x]{fontenc}
\usepackage[lithuanian]{babel}
```

# EXAMPLE

```
\documentclass[]{vgtuef}
\usepackage[utf8x]{inputenc}
\usepackage[L7x]{fontenc}
\usepackage[lithuanian]{babel}

\author{Maksim Norkin\\Vilniaus Gedimino technikos universitetas\\Elektronikos fakultetas\\Elektroninių sistemų katedra\\\texttt{foo.bar@ieee.org}}
\title{Bakalauro baigiamasis darbas\\Foo bar}

\begin{document}

\setcounter{page}{7}

\onehalfspacing

\tableofcontents

\section*{Žymenys ir santrumpos}
\addcontentsline{toc}{section}{Žymenys ir santrumpos}

\begin{tabbing}
VŽRJ (angl. \textit{Vertical Ground Reaction Force}) \= Vertikali žemės reakcijos jėga; \\
PCA (angl. \textit{Principal Component Analysis}) \> principinių komponenčių analizė;\\
LDA (angl. \textit{Linear Diskriminant Analysis}) \> tiesinė disktriminanto analizė; \\
SVM (angl. \textit{Support Vector Machine}) \> vektoriaus palaikymo mašina; \\
STC (angl. \textit{Signal Turn Counter}); \> signalo nuokrypio skaitiklis \\
Co \> kontrolinis subjektas, kurio ligos istorijoje nebuvo užregistruota jokių neurologinių susirgimų; \\
Pt \> Parkinsono liga sergantis subjektas; \\
\end{tabbing}

\section{Įvadas. Užduoties analizė}

```