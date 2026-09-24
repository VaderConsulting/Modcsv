# Modcsv

CSC VB6 ModCSV (`ModCSV.exe`) - Modify Domain Admin .csv files. Finds Traveller rows in domain-admin CSVs and rewrites drive-path columns (Q/O/X/N/T/P style `%siteserver%\...` paths) for traveller users via a RichTextBox (`richtx32.ocx`).

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `ModCSV` (`Modcsv.vbp`) | VB6 | WinForms exe | Modify Domain Admin traveller CSV paths |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Modcsv.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `richtx32.ocx`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Modcsv`.
Company names in project files: CSC.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
