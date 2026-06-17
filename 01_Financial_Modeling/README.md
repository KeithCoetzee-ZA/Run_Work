# South African Retail Calendar Automation Engine

---

##  Overview
This project is a modular, multi-year calendar system designed to integrate public holidays, events, and school holidays into a single automated framework[cite: 1]. It serves as a foundational tool for retail managers, operations analysts, and planners to optimize labor forecasting, track shifting trading patterns, and coordinate seasonal campaigns[cite: 1]. 

By eliminating manual calendar creation, the engine improves operational readiness, aligns labor budgets with trading intensity, and ensures that promotional timelines are built on accurate, region-specific data[cite: 1].

---

##  Core Features & Architecture

▪ **Automated Date Breakdown:** Generates supporting data points (day, month, year, weekday name) automatically from a single input to eliminate manual entry and drive downstream operational logic[cite: 1].
▪ **Multi-Table Lookups:** Seamlessly cross-references dates against structured data sets for Public Holidays, Retail Events, and School Holidays[cite: 1].
▪ **Observed Holiday Logic:** Automatically detects when a public holiday falls on a weekend and shifts the business impact flag to the observed day (typically the following Monday)[cite: 1].
▪ **Dynamic Range Validation:** Uses start-and-end ranges for school holiday periods instead of individual date lists, maximizing calculation performance and reducing long-term maintenance[cite: 1].
▪ **Visual Guardrails:** Employs automated conditional formatting to instantly highlight Sundays, public holidays, events, and school breaks for immediate operational scannability[cite: 1].

---

##  Fail-Safe & Protection Strategy
Built with an intentional architecture designed to minimize user error while maintaining absolute scalability[cite: 1]:

▪ **Single-Cell Execution ($A$2):** To generate a completely new calendar year, a user only needs to change a single unlocked cell ($A$2)[cite: 1]. The entire workbook updates instantly using dynamic references (e.g., `='2018 '!A366+1`)[cite: 1].
▪ **Formula Lockout:** All underlying calculation sheets, function structures, and core logic cells are completely locked to prevent accidental overwrites[cite: 1]. 
▪ **Open Maintenance:** Only the specific rows within the lookup sheets are left open, allowing non-technical users to expand holiday or event datasets safely without risking system corruption[cite: 1].

---

##  Technical Skills Demonstrated
▪ **Advanced Excel Design:** Array logic (`SUMPRODUCT`), advanced text manipulation (`TEXT`, `WEEKDAY`), and dynamic logical nesting (`IF`, `OR`, `COUNTA`)[cite: 1].
▪ **Systems Architecture:** Scalable, table-driven data modeling that allows seamless expansion without altering core logic formulas[cite: 1].
▪ **Domain Expertise:** Direct application of retail operations knowledge, specifically workforce optimization, trading pattern alignment, and operational risk mitigation[cite: 1].

---

##  Repository Files
▪ `Calendar_with_Holidays_South_Africa.xlsx`: The core, fully functioning automated Excel engine[cite: 1].
▪ `PDF - South African Retail Calendar Automation Engine.docx`: Comprehensive technical documentation detailing the function library, sheet architecture, and user deployment steps[cite: 1].
