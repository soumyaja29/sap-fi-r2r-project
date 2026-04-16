# SAP FI Record-to-Report (R2R) Project

## Project Overview

This project demonstrates the implementation of the **Record-to-Report (R2R)** business process in **SAP Financial Accounting (SAP FI)**. It covers the end-to-end financial closing cycle including journal postings, asset accounting, accruals, reconciliations, and financial statement generation.

---

## Business Scenario

A fictitious company, **ABC Global Manufacturing Pvt Ltd**, is implementing SAP FI to automate and streamline its financial closing and reporting process.

---

## Scope of Implementation

* General Ledger Posting
* Accounts Payable / Receivable
* Asset Acquisition
* Depreciation Run
* Accrual / Provision Posting
* Foreign Currency Valuation
* GR/IR Clearing
* Bank Reconciliation
* Financial Statement Generation
* Balance Carry Forward

---

## Enterprise Structure

* **Company Code:** ABC1
* **Currency:** INR
* **Fiscal Year Variant:** K4
* **Chart of Accounts:** INT

---

## SAP Transactions Used

| Process                    | T-Code |
| -------------------------- | ------ |
| G/L Posting                | F-02   |
| Vendor Invoice             | FB60   |
| Customer Invoice           | FB70   |
| Asset Acquisition          | F-90   |
| Depreciation Run           | AFAB   |
| Accrual Posting            | FBS1   |
| Foreign Currency Valuation | F.05   |
| GR/IR Clearing             | F.13   |
| Financial Statement        | F.01   |
| Balance Carry Forward      | F.16   |

---

## Repository Contents

* `SAP_R2R_Project_Implementation.xlsx` – Configuration and implementation workbook
* `SAP_R2R_Project_Documentation.pdf` – Project documentation/report
* `README.md` – Project overview

---

## Objective

To design and document an SAP FI Record-to-Report process for academic and implementation-learning purposes.

---

## Author

Soumyaja Dey
