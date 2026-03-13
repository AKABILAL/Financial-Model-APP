# FinTech Übermensch

**A Big 4-grade IFRS financial modelling and audit knowledge platform — entirely in your browser.**

> Built by Bilal. No installation. No login. No dependencies. Open the file and start modelling.

---

## What Is This?

FinTech Übermensch is a single-file HTML/JavaScript application that puts professional-grade IFRS financial modelling and audit knowledge directly in your browser. It is built to the standard expected of a Big 4 advisory engagement — with exact IFRS/IAS paragraph references, full journal entries, automated disclosure notes, and an AI-powered technical search engine covering both IFRS standards and ISA auditing standards.

Everything runs locally. There is no server, no backend, no account, and no data sent anywhere — except for the optional AI search feature, which calls the Anthropic API directly from your browser.

---

## Quick Start

1. Download `index_html.html`
2. Open it in any modern browser (Chrome, Edge, or Firefox recommended)
3. Select a model from the left panel
4. Enter your entity's financial inputs
5. Click **⚡ Build Model** — or press `Ctrl + Enter`

That is all. Results appear instantly across five output tabs.

---

## Features

### 📊 Financial Models (26 Models)

Fully computed IFRS and IAS financial models with output tables, journal entries, and IFRS disclosure notes generated automatically.

**IFRS Standards**
| Model | Standard |
|---|---|
| Expected Credit Loss (ECL) | IFRS 9 |
| Hedge Accounting | IFRS 9 |
| Classification & Measurement | IFRS 9 |
| Revenue from Contracts with Customers | IFRS 15 |
| Right-of-Use Asset & Lease Liability | IFRS 16 |
| Lease Modification & Reassessment | IFRS 16 |
| Insurance Contracts (General Measurement Model) | IFRS 17 |
| Statement of Profit or Loss | IFRS 18 |
| Business Combination (PPA & Goodwill) | IFRS 3 |
| Financial Instruments: Disclosures (Risk) | IFRS 7 |
| Group Consolidation Worksheet | IFRS 10 |

**IAS Standards**
| Model | Standard |
|---|---|
| Inventories | IAS 2 |
| Income Taxes — Deferred Tax (P&L) | IAS 12 |
| Deferred Tax (Balance Sheet Approach) | IAS 12 |
| Property, Plant & Equipment | IAS 16 |
| Defined Benefit Employee Benefits | IAS 19 |
| Impairment Test (Value in Use) | IAS 36 |
| Provisions, Contingent Liabilities & Assets | IAS 37 |
| Intangible Assets | IAS 38 |

**Valuation & Finance**
| Model | Description |
|---|---|
| DCF — Discounted Cash Flow Valuation | WACC-based intrinsic value |
| LBO — Leveraged Buyout Analysis | Entry, debt structure, exit IRR |
| Dividend Discount Model (DDM) | Gordon Growth and multi-stage |
| Trading Comps — Relative Valuation | EV/EBITDA, P/E peer multiples |
| Net Asset Value (NAV) / Sum-of-Parts | Asset-by-asset valuation |

Each model produces:
- Computed output table with labelled IFRS paragraph sources
- Visual dashboard with interactive charts
- Editable assumptions panel with live recalculation
- Sensitivity and scenario analysis
- Auto-generated IFRS disclosure notes in publication-ready format
- Excel export with live formulas
- CSV export

---

### 📚 IFRS Reference — Knowledge Base (27 Standards)

A fully searchable library of IFRS and IAS standards, powered by AI. Ask natural language questions and receive Big 4 Technical Partner-level answers with exact paragraph references, worked numerical examples, and auditor considerations.

**Standards covered:**

`IFRS 1` `IFRS 2` `IFRS 3` `IFRS 5` `IFRS 7` `IFRS 8` `IFRS 9` `IFRS 10` `IFRS 13` `IFRS 15` `IFRS 16` `IFRS 17` `IFRS 18`

`IAS 1` `IAS 2` `IAS 7` `IAS 8` `IAS 10` `IAS 12` `IAS 16` `IAS 19` `IAS 21` `IAS 32` `IAS 36` `IAS 37` `IAS 38` `IAS 40`

**Example queries:**
- *"When can development costs be capitalised under IAS 38?"*
- *"How is ECL Stage 2 triggered under IFRS 9?"*
- *"What is the 5-step revenue recognition model in IFRS 15?"*
- *"How is a right-of-use asset initially measured under IFRS 16?"*
- *"What are the impairment indicators under IAS 36?"*

---

### 🔬 ISA Reference — Audit Knowledge Base (43 Standards)

A complete library of International Standards on Auditing, searchable via AI. Covers the full ISA suite from ISA 200 to ISA 810, plus review, assurance, and agreed-upon procedure standards.

**Standards covered:**

**Core Auditing (ISA)**
`ISA 200` `ISA 210` `ISA 220` `ISA 230` `ISA 240` `ISA 250` `ISA 260` `ISA 265` `ISA 300` `ISA 315` `ISA 320` `ISA 330` `ISA 402` `ISA 450` `ISA 500` `ISA 501` `ISA 505` `ISA 510` `ISA 520` `ISA 530` `ISA 540` `ISA 550` `ISA 560` `ISA 570` `ISA 580` `ISA 600` `ISA 610` `ISA 620` `ISA 700` `ISA 701` `ISA 705` `ISA 706` `ISA 710` `ISA 720` `ISA 800` `ISA 805` `ISA 810`

**Review Engagements (ISRE)**
`ISRE 2400` `ISRE 2410`

**Assurance Engagements (ISAE)**
`ISAE 3000` `ISAE 3402` `ISAE 3410`

**Related Services (ISRS)**
`ISRS 4400`

**Example queries:**
- *"What are the group auditor's responsibilities under ISA 600?"*
- *"When must the auditor issue a disclaimer of opinion?"*
- *"What are the two presumed fraud risks under ISA 240?"*
- *"How does the auditor select key audit matters under ISA 701?"*
- *"What is the difference between a Type 1 and Type 2 SOC report?"*

---

### 📥 Import & Export

| Feature | Description |
|---|---|
| **Import Excel** | Upload an `.xlsx` file to pre-populate model inputs from your own data |
| **Export — Excel + Formulas** | Download the full model as a spreadsheet with live Excel formulas |
| **Export — CSV** | Download a flat CSV of model output for use in other tools |
| **Share Link** | Generate a URL that encodes your model inputs — shareable with no account required |

---

## Output Tabs

After building a model, five tabs are available:

| Tab | Contents |
|---|---|
| **📊 Model Output** | Primary results table with IFRS-referenced line items and journal entries |
| **📈 Dashboard** | Visual charts and graphs that update with your inputs |
| **⚙ Assumptions** | All input assumptions, editable cell-by-cell with live recalculation |
| **🔍 Analysis** | Sensitivity analysis, scenario comparisons, and key ratios |
| **📋 IFRS Notes** | Auto-generated disclosure notes in publication-ready format |

---

## Navigation Bar

The top navigation bar provides access to all major functions:

```
📥 Import Excel   ⬇ Excel + Formulas   ⬇ CSV   🔗 Share   📚 IFRS Reference   🔬 ISA Reference
```

The **📚 IFRS Reference** and **🔬 ISA Reference** buttons open a full-screen knowledge base overlay, accessible at any time regardless of which model is loaded.

---

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl + Enter` | Build the model from the current inputs |
| `Escape` | Close any open overlay or modal |

---

## AI Search

The IFRS and ISA knowledge base search is powered by the Anthropic Claude API. When you type a query and press Enter (or wait briefly), the app sends your question along with the relevant standard entries as context, and returns a structured technical answer.

**No API key is required.** The app uses a browser-direct access configuration that works out of the box when opened via claude.ai or in environments where the Anthropic API is accessible.

Each AI answer includes:
- The exact IFRS or ISA paragraph reference (e.g. `IAS 38.57`, `ISA 600.40`)
- The core rule or requirement
- Step-by-step application guidance
- A worked numerical example from Big 4 advisory practice
- Auditor considerations and documentation requirements
- Common errors or regulatory findings

Use the **📋 Copy** button beneath any answer to copy it to your clipboard for use in workpapers, technical memos, or client presentations.

---

## Who Is This For?

| Audience | Use Case |
|---|---|
| **Finance professionals** | Build IFRS-compliant models quickly without setting up Excel from scratch |
| **External auditors** | Reference exact standard requirements; look up ISA procedures during fieldwork |
| **Finance students & CPA/ACCA candidates** | Study IFRS and ISA standards with worked examples and practical context |
| **CFOs and FDs** | Understand the IFRS impact of transactions — leases, acquisitions, impairments |
| **Financial controllers** | Prepare IFRS disclosure notes and accounting policy documents |
| **Valuation practitioners** | Run DCF, LBO, DDM, NAV and trading comps with IFRS 13 context |

---

## Technical Notes

- **Single file:** The entire application is contained in one HTML file (`index_html.html`), approximately 680 KB.
- **No dependencies:** No npm, no build step, no framework installation required.
- **No server:** All financial model computation runs entirely in the browser via JavaScript.
- **Privacy:** No financial data you enter is transmitted anywhere. Only the text of your knowledge base search query is sent to the Anthropic API when you use the AI search feature.
- **Browser support:** Chrome 90+, Edge 90+, Firefox 88+. Not tested on Internet Explorer.
- **Offline use:** The financial modelling engine works fully offline. The AI search feature requires an internet connection.

---

## File Structure

```
index_html.html        ← The entire application. This is the only file you need.
README.md              ← This file.
```

---

## Tips

- **Review Assumptions first.** After building a model, navigate to the Assumptions tab and verify every input before drawing conclusions. Output quality depends entirely on input quality.
- **Use the Dashboard filter.** Click a chart segment in the Dashboard to isolate specific series — useful for comparing Stage 1 vs Stage 2 ECL, or individual CGU impairments.
- **Cross-reference IFRS with ISA.** After building an IAS 36 impairment model, search *"ISA 540 auditing accounting estimates"* in the ISA tab to get the corresponding audit approach.
- **Export before editing assumptions.** Download an Excel export before and after adjusting assumptions to maintain a clean audit trail of your modelling.
- **Share scenarios.** Use the 🔗 Share button to generate separate links for base-case and downside scenarios — useful for presenting multiple outcomes to stakeholders.
- **IFRS Notes are presentation-ready.** The text generated in the IFRS Notes tab follows standard disclosure language and can be used directly in financial statement drafts, subject to your entity-specific review.

---

## Disclaimer

This tool is designed to assist qualified finance and audit professionals. The financial models and knowledge base content are provided for reference and educational purposes. Outputs should be reviewed by a suitably qualified professional before use in financial statements, audit files, or client deliverables. Nothing in this application constitutes legal, tax, or professional advice.

---

*FinTech Übermensch by Bilal — IFRS · IAS · ISA · AI-Powered · Big 4 Grade*
