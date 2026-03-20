# CaWaQS-Viz User Guide

This repository contains the LaTeX source files for the CaWaQS-Viz user guide, available in both **French** and **English**.

## Repository Structure

```
.
├── main_FR.tex                          # Master file – French version
├── main_ENG.tex                         # Master file – English version
├── shortcuts_FR.tex / shortcuts_ENG.tex # Shared LaTeX macros (French/English)
├── couverture/
│   ├── couverture_FR.tex               # Cover page (French)
│   └── couverture_ENG.tex              # Cover page (English)
├── 0_introduction/
│   ├── introduction_FR.tex             # Introduction (French)
│   └── introduction_ENG.tex            # Introduction (English)
├── Nouveautés_FR.tex                    # What's New (French)
├── Nouveautes_ENG.tex                   # What's New (English)
├── 1_installation_requirements/
│   ├── Chap1_FR.tex                    # Chapter 1 (French)
│   └── Chap1_ENG.tex                   # Chapter 1 (English)
├── 2_application_user_guide/
│   ├── Chap2_FR.tex                    # Chapter 2 (French)
│   └── Chap2_ENG.tex                   # Chapter 2 (English)
├── 3_features/
│   ├── Chap3_FR.tex                    # Chapter 3 (French)
│   └── Chap3_ENG.tex                   # Chapter 3 (English)
├── 4_application_scripts/
│   ├── Chap4_FR.tex                    # Chapter 4 (French)
│   └── Chap4_ENG.tex                   # Chapter 4 (English)
├── 5_develloppeur/
│   ├── 5_dev_FR.tex                    # Chapter 5 (French)
│   └── 5_dev_ENG.tex                   # Chapter 5 (English)
├── bibliographie_FR.tex                 # Bibliography (French)
├── bibliographie_ENG.tex                # Bibliography (English)
└── references.bib                       # Bibliography database
```

## How to Compile in Overleaf

### Step 1: Upload the Repository

1. Go to [Overleaf](https://www.overleaf.com) and log in.
2. Click **New Project** → **Upload Project**.
3. Compress the entire repository as a `.zip` file and upload it.

### Step 2: Compile the French Version

1. In the Overleaf project, locate the file `main_FR.tex` in the file tree on the left.
2. Click on `main_FR.tex` to open it in the editor.
3. In the top menu, click the arrow next to the **Compile** button and select **Set as main file** (or simply open `main_FR.tex` as the main document).
4. Click **Compile** (or press Ctrl+Enter / Cmd+Enter).
5. The compiled French PDF will appear in the preview panel on the right.

### Step 3: Compile the English Version

1. In the Overleaf file tree, locate `main_ENG.tex`.
2. Click on `main_ENG.tex` to open it.
3. Set it as the main file: click the three-dot menu next to the filename and choose **Set as Main File**.
4. Click **Compile**.
5. The compiled English PDF will appear in the preview panel.

### Tips

- To switch between versions, simply change the main file between `main_FR.tex` and `main_ENG.tex`.
- The **compiler** should be set to **pdfLaTeX** (Overleaf default). Check via **Menu** → **Compiler**.
- If you see errors related to missing packages, ensure Overleaf is using **TeX Live 2023** or later.
- The `alertmessage.sty` custom style file is included in the repository root.
