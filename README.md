# dmEdit — releases

**dmEdit** is a full-screen text editor for the terminal by
**Dalacu Marius** — [sites.google.com/site/dmsimpleapps](https://sites.google.com/site/dmsimpleapps).

It edits source code and configuration files with syntax highlighting for
48 languages, and shows almost any file sensibly: Markdown and HTML
rendered, CSV / XLSX / ODS as tables, DOCX / ODT / EPUB as text, PDF text,
certificates as readable reports, images as coloured text art, binaries as
a hex dump. Every command is in a palette (`Alt+P`); the full manual is
built in (*Help > Documentation*, or `dmEdit --help-doc`).

This repository holds the **released binaries** only. dmEdit is
proprietary freeware: free to use, see [LICENSE.txt](LICENSE.txt).

## Install

| System | How |
|---|---|
| Windows 10 / 11 (x64) | `winget install mdalacu.dmEdit` *(once the package is accepted)*, or download `dmEdit.exe` from the [latest release](https://github.com/mdalacu/dmEdit-releases/releases/latest) |
| Linux (x86_64) | download `dmEdit` from the [latest release](https://github.com/mdalacu/dmEdit-releases/releases/latest), `chmod +x dmEdit` |

Every release lists the SHA-256 of each file.

## Reporting a problem

Open an [issue](https://github.com/mdalacu/dmEdit-releases/issues) with
the dmEdit version (`dmEdit --help`, first line), the system, and what you
did; `dmEdit --paths` shows where dmEdit keeps its files.
