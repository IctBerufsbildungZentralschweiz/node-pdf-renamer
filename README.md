# node-pdf-renamer
Kleine NodeJS Applikation um Lohnabrechnungen vom ICT-BZ Sekretariat umzubennen 

## Requirements
* [NodeJS installiert](https://nodejs.org/en/)
* [GitBash installiert (nur Windows)](https://git-scm.com/downloads)

## Installation
```bash
git clone https://github.com/IctBerufsbildungZentralschweiz/node-pdf-renamer.git
cd node-pdf-renamer
npm i
```

## Usage
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