# node-pdf-renamer
Kleine NodeJS Applikation um Lohnabrechnungen vom ICT-BZ Sekretariat umzubennen.
```bash
$ ./pdfRenameTool -h
Usage: pdfRenameTool [options]

Options:
  -v, --version             output the version number
  -d, --debug               enable debug-mode
  -i, --input [directoy]    input directory with PDFs
  -o, --output [directory]  output directory for renamed PDFs
  -h, --help                output usage information
```

## Benötigte Software
* [NodeJS installiert](https://nodejs.org/en/)
* [GitBash installiert (nur Windows)](https://git-scm.com/downloads)

## Installation
In der Gitbash eingeben:
```bash
cd /g/GL/Finanzen/
git clone https://github.com/IctBerufsbildungZentralschweiz/node-pdf-renamer.git pdfRenameTool
cd pdfRenameTool
npm i
```

## Anleitung
1) PDF-Dateien mit Windows-Explorer in den Ordner `G:\GL\Finanzen\pdfRenameTool\_input` kopieren 
2) Programm "Gitbash" öffnen
3) Folgendes Script starten:
```bash
 cd /g/GL/Finanzen/pdfRenameTool; ./pdfRenameTool -i "_input" -o "_output"
```
4) Umbenennte PDF-Dateien  dem  Ordner `G:\GL\Finanzen\pdfRenameTool\_output` entnehmen 