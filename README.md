# Dataflow Studio

Offline, no-code legacy data migration toolkit (Access, FoxPro, CSV, fixed-width)

---

## Table of Contents

1. [Overview](#overview)  
2. [Key Features](#key-features)  
3. [Supported Formats](#supported-formats)  
4. [Installation](#installation)  
5. [Getting Started](#getting-started)  
   - [1. Import Your Data](#1-import-your-data)  
   - [2. Transform Visually](#2-transform-visually)  
   - [3. Export or Save](#3-export-or-save)  
6. [Frequently Asked Questions](#frequently-asked-questions)  
7. [License](#license)  
8. [Contact](#contact)  

---

## Overview

**Dataflow Studio** is a desktop application by J Smith that lets you extract, clean, and export legacy data—completely offline, without writing any code. Whether you have an old Access database, a FoxPro/DBF file, a CSV export, or a fixed-width text file, Dataflow Studio provides a no-code, visual interface to transform messy tables into audit-ready datasets.

- **100% Offline**: No cloud, no telemetry, and no user accounts required.  
- **No-Code**: Point-and-click transformations (rename, filter, replace, remove columns).  
- **Audit Trail**: Every change is recorded internally so you can undo or remove any step.  
- **Large Dataset Support**: Handles hundreds of thousands of rows with efficient pagination.  

Download the latest release from the [GitHub Releases page](https://github.com/smitjb45/dataflow-studio/releases).

---

## Key Features

- **Offline & Secure**  
  All data processing happens on your local machine. Data never leaves your computer.

- **No-Code Transformation Engine**  
  • Add or remove columns  
  • Rename columns via dropdown + input  
  • Change column data types  
  • Filter rows with multiple operators (e.g., “=,” “!=,” “contains,” “starts with”)  
  • Replace values with advanced matching modes (case-sensitive, wildcard, etc.)

- **Visual History Panel**  
  Every transformation step is recorded. Easily undo or delete individual steps in any order.

- **Live Data Preview & Pagination**  
  View real data (200 rows per page) as you apply changes. Jump to any page for large tables.

- **One-Click Export**  
  Export your cleaned data to CSV or SQL script for import into downstream systems.

---

## Supported Formats

- **MS Access Databases**  
  - `.mdb`  
  - `.accdb`

- **FoxPro / dBase Files**  
  - `.dbf`

- **Generic CSV Files**  
  - Comma, tab, or custom-delimited text files

- **Fixed-Width Text Files**  
  - Legacy exports where each column occupies a fixed number of characters

---

## Installation

1. Go to the [Dataflow Studio Releases](https://github.com/smitjb45/dataflow-studio/releases) page.  
2. Download the latest `DataflowStudio_Free_Installer.exe` asset.  
3. Run the installer:  
   - Double-click `DataflowStudio_Free_Installer.exe`  
   - Follow the on-screen prompts to install Dataflow Studio on your Windows machine  
4. Launch Dataflow Studio from your Start Menu or desktop shortcut.

---

## Getting Started

Once installed, follow these three simple steps to start modernizing your legacy data:

### 1. Import Your Data

1. Open **Dataflow Studio**.  
2. Click **Import Table**.  
3. In the file dialog, select your source file:  
   - `.mdb` or `.accdb` (Access)  
   - `.dbf` (FoxPro/dBase)  
   - `.csv` (any delimiter)  
   - Fixed-width text file  
4. Preview the table schema. Click **Confirm** to load it into the application.  
5. The imported table will appear in your list of tables, ready for transformation.

### 2. Transform Visually

1. Select your imported table and click the **Transform** tab.  
2. Choose an operation from the dropdown:  
   - **Add Index Column**  
   - **Remove Blank Rows**  
   - **Rename Column**  
   - **Change Column Data Type**  
   - **Replace Values**  
   - **Drop Column**  
   - **Filter Rows**  
3. Configure the operation via on-screen controls (dropdowns, text fields, checkboxes).  
4. Click **Apply**. The table preview updates immediately—showing the first 200 rows.  
5. Repeat for each transformation step. All actions are recorded in the History panel on the right.

### 3. Export or Save

1. When your data looks correct, switch to the **Export** tab.  
2. Select your desired export format:  
   - **CSV** (`.csv`)  
   - **SQL Script** (`.sql`), generating `INSERT` statements for your cleaned table  
3. Choose an output folder and filename.  
4. Click **Export**. Dataflow Studio writes the clean data file or SQL script to disk.  
5. Use the exported CSV or SQL script to load data into your CRM, ERP, or any other database.

---

## Frequently Asked Questions

**Q: Does Dataflow Studio require an internet connection?**  
A: No. The app runs fully offline. No cloud, no telemetry, and no user accounts are required.

---

**Q: Which file types can I import?**  
A: Dataflow Studio supports:  
- MS Access (`.mdb`, `.accdb`)  
- FoxPro/DBF (`.dbf`)  
- Generic CSV (`.csv`)  
- Fixed-width text tables

---

**Q: How large of a dataset can it handle?**  
A: You can work with hundreds of thousands of rows. Built-in pagination and efficient data indexing ensure smooth performance.

---

**Q: Can I undo or remove transformation steps?**  
A: Yes. Every action—rename, drop, filter, replace—is recorded. Open the History panel to undo or delete any step at any time.

---

## License

**Dataflow Studio** is proprietary software. All rights reserved by J Smith.

---

## Contact

For questions or feedback, please reach out via GitHub Issues:  
[Create a new issue](https://github.com/smitjb45/dataflow-studio/issues)

© 2025 J Smith  

