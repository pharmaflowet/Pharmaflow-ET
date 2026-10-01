# PharmaFlow ET

PharmaFlow ET is a pharmacy management system built for Ethiopian pharmacies. It handles everything a pharmacy needs to run day-to-day: selling at the counter, managing stock, consulting clinical references, reporting adverse drug events, tracking finances, processing payroll, and reviewing performance — all in one application, in English or Amharic, using the Ethiopian calendar and ETB currency throughout.

---

## Who uses it

- **Cashiers** ring up sales at the POS counter
- **Pharmacists / stock managers** receive goods, manage batches, track expiry dates, consult medicine guidance, check interactions, and record adverse drug events
- **Accountants / managers** review financials, manage cash and bank balances, process payroll, and monitor daily performance
- **Administrators** manage users, configure the system, and handle backups

---

## Recently added in version 1.0.5

- **Accurate inventory balances** — shelf and store stock now determine available quantity; older batches are upgraded automatically.
- **Saved stock alerts** — alert colors and notifications use each product's configured thresholds, including zero.
- **Faster order entry** — newly added Sale Hub products appear at the top of the order grid.
- **In-app updates** — installers download with visible progress and checksum verification, then the setup wizard opens.
- **10-day trial** — the free trial runs for 10 days from the original installation date, including for existing unlicensed installations.

## Added in version 1.0.4

- **Inventory alerts and summaries** — compact goods KPIs, stock and expiry filters, and a notification bell with saved read status and direct access to affected batches.
- **Expiry visibility** — translucent row highlighting, badges beside batch expiry dates, and dashboard expiry summaries.
- **Stock status accuracy** — new products remain neutral until first stocked; stockouts use red text and low stock uses orange text.
- **Stock entry improvements** — supplier fields synchronize with credit supplier details, expiry fields replace date-received inputs, and received batch numbers may remain blank.
- **Clearer logs and grids** — quantities display their selling units and column headers follow their row alignment.
- **Desktop fixes** — credit-sale activity displays the cashier, app exit stops the embedded server, and the splash appearance is refined.

## Added in version 1.0.3

- **Modern startup experience** — a branded splash screen appears immediately while PharmaFlow ET prepares the local data and workspace.
- **Continuous loading feedback** — the splash screen's blue loading indicator remains animated throughout startup so users can see that loading is still in progress.
- **Direct help access** — question-mark buttons on both the login and main windows open the built-in bilingual Help system.
- **Updated support details** — the login window now displays PharmaFlow ET's current contact information for assistance.

## Added in version 1.0.2

- **Clinical Resources workspace** — open Rx Reference, the Good Dispensing Practice manual, and the EFDA-based adverse drug event reporting form from the main window's Resources menu.
- **Searchable Rx Reference** — search clinical conditions, medicines, and supported alternate drug names; browse A–Z or by classification; and follow links between conditions and related medicines.
- **Multi-medicine interaction checker** — add two or more medicines to evaluate every possible pair and review known interaction severity, descriptions, and management information.
- **ADE report generation** — capture patient, reaction, medicine or vaccine, clinical-history, and reporter details, then export an EFDA-based yellow PDF for review and manual submission.
- **Bilingual resource guidance** — English and Amharic Help topics and tooltips explain resource navigation, interaction checks, ADE reports, source documents, and access after trial or license expiry.
- **Cash & Equivalents workspace** — view physical cash, bank and mobile-money balances, monthly movement, account details, and recent transactions from one Assets tab.
- **Cash transaction recording and statements** — record transfers, owner-capital deposits, and owner withdrawals, then open a detailed debit, credit, and running-balance statement for any selected account.
- **Automatic accounting synchronization** — transactions that affect cash or bank accounts post to the journals and ledger and refresh the Cash & Equivalents balances, including entries created by the manual journal and other accounting workflows.
- **Daily asset accounting and refreshed Help** — fixed-asset depreciation and prepaid amortization now accrue daily, while the bilingual Help window highlights newly updated guidance.

---

## What you can do

### Point of Sale

Search for a product by name or code, pick the right batch (automatically selected by expiry), set the quantity, and complete the sale. Payment can be split across cash and multiple bank transfers. Credit sales are tracked against named customers. Completed sales are retained as internal business records with a full audit trail; the application does not issue customer receipts or other customer-facing proof-of-sale documents.

### Inventory Management

Add products individually or import them from an Excel template. Each product can have multiple stock batches with separate expiry dates and purchase prices. You receive new stock as a batch, edit batch details, dispose of expired or damaged quantities, and transfer stock between locations. A full event log shows every movement for any product. Services (non-stocked items like consultations or tests) are managed alongside physical goods.

Drug classification is built in — you pick from a standard classification catalogue when adding a product, or define your own custom categories.

### Sales Reporting

Pull sales reports by day, week, month, or any custom date range. See revenue totals, top-selling products, and a full transaction list. Reports support both Gregorian and Ethiopian calendar date entry.

### Clinical Resources

The main window's **Resources** menu opens clinical and dispensing tools without interrupting other PharmaFlow ET work.

**Rx Reference** combines clinical conditions and medicine information based on Ethiopia's Standard Treatment Guidelines (4th edition, 2021) and National Medicines Formulary (3rd edition). Search across conditions, medicines, and supported generic, common, British, and American alternate names, or browse A–Z and by classification. Entries include expandable guidance, source references, links between related conditions and medicines, and back/home navigation.

The **Drug Interaction Checker** accepts two or more medicines, normalizes supported alternate names to avoid duplicates, and evaluates every possible medicine pair. Known results show severity, a description, and available management information. An absent result does not prove a combination is safe, so decisions should still be checked against current references and the individual patient's needs.

**Good Dispensing Practice** opens the included Medicines Good Dispensing Manual, second edition (2012), in the computer's default PDF reader for reading or printing.

**Record Adverse Drug Event** provides an EFDA-based ADE/ADR/medication-error form covering report type, patient details, the event or reaction, medicines and vaccines, relevant history and tests, and reporter information. Add suspected or concomitant medicines as separate rows, expand or collapse form sections, and export the completed report as a yellow PDF. Exporting saves the report but does not submit it automatically; the reporter must review it and send it to EFDA through an accepted channel.

Interactive Rx Reference and ADE reporting are available during an active trial or license. If access expires, PharmaFlow ET provides the original Standard Treatment Guidelines, medicines formulary, and EFDA reporting-form PDFs; the Good Dispensing Practice manual remains directly available.

### Cash & Equivalents

The Assets window includes a Cash & Equivalents tab with four KPI cards spanning the available width: total cash equivalents, physical cash, bank/mobile-money balances, and this month's net movement. Positive monthly movement is shown in green with an up arrow; negative movement uses the warning color with a down arrow.

Below the KPIs, a 60/40 split shows non-zero Cash POS, Cash Operations, Cash in Vault, and individual bank or mobile-money balances on the left, with recent transaction account, type, direction, amount, and date details on the right. Both grids use the application's shared grid theme and localized headers.

Use **Record Transaction** to transfer funds between cash and bank accounts, record an owner's capital deposit, or record an owner's withdrawal to the drawings account. Selecting Bank reveals the configured bank picker. Transactions can include an amount, effective date, description or reference, and an optional service fee that defaults to zero. Dates use the dual Gregorian/Ethiopian picker and the shared day-month-year display format.

The **Show Statement** button becomes available after an account row is selected and opens the account's debit, credit, and running-balance history. **Refresh** reloads the KPIs, account balances, and recent transactions.

Cash and bank balances remain synchronized with the journals and ledger. Sales, expenses, collections, payments, manual journals, and other accounting actions that affect a cash or bank account automatically appear in Cash & Equivalents and trigger updated balances.

### Accounting & Ledger

The accounting module maintains a double-entry ledger automatically updated by sales, expenses, and Cash & Equivalents transactions. You can view the master ledger, cash-flow statement, per-bank balances, revenue breakdown, and expense summary. Manual journal entries are supported for adjustments, and cash/bank journal lines also update Cash & Equivalents. Reconciliation helps compare recorded balances with external statements.

### Assets, Prepaids & Receivables

Track fixed assets such as equipment and furniture with depreciation schedules, upgrades, revaluation, disposal, and full history. New fixed-asset schedules accrue depreciation daily using an accounting day that changes at 6:00 a.m.; missed days catch up when the Assets view loads.

Record prepaid expenses and amortize them across eligible coverage days. New schedules recognize amortization daily, exclude Pagume days, and present closed Ethiopian months as ledger summaries while current balances and reports remain up to date. Existing historical journals are preserved.

Log receivable invoices owed to the pharmacy and record payments as they come in. Manage liabilities such as loans or taxes and track repayment schedules.

### HRM & Payroll

Maintain an employee register with positions, work schedules, and HR documents. Run Ethiopian payroll with automatic income tax (progressive brackets), pension deductions, and overtime calculation. Mark payroll as paid each cycle and keep a full payment history.

### Dashboard

The home screen shows today's key numbers at a glance: total revenue, number of sales, top products, and recent transactions. Figures update as sales are posted.

### Help System

A built-in bilingual help window covers every feature in English and Amharic. Browse by section, search by keyword or question, or use the Recently Updated cards to open guidance for Clinical Resources, Rx Reference, drug interactions, ADE reporting, Cash & Equivalents, daily depreciation, prepaid amortization, and cash-aware manual journals. The new resource screens also include bilingual tooltips for their main controls.

---

## Multi-PC support

PharmaFlow ET can run on a local network with one PC acting as the server and others as client terminals. The server holds the database; clients connect over the LAN. Sales posted on any terminal are immediately visible on all others. The server can also run in single-PC mode with no network setup required.

---

## Licensing & trial

Each installation gets a 10-day free trial with full access. After the trial, a license serial is required to continue using the system without restrictions. The license is tied to the machine it is activated on.

---

## Language & calendar

The interface switches between English and Amharic at any time without restarting. Dates can be displayed and entered in either the Gregorian or Ethiopian calendar — a dual date picker shows both side by side. Currency is Ethiopian Birr (ETB). VAT rules follow Ethiopian pharmaceutical exemptions.

---

## Backup & security

Automatic scheduled backups save the database to a folder of your choice. Manual backups and restore are available at any time. Each user has a role (Admin, Accountant, Cashier, etc.) with configurable permissions. Login attempts are logged, and an admin recovery system lets the owner regain access if credentials are lost.
