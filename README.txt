D&K LIQUOR POS & BUSINESS CONTROL SYSTEM
==========================================

This is the POS version of the accounting principles in the D&K Liquor workbook.

STARTING THE SOFTWARE
---------------------
1. Extract the ZIP folder.
2. Double-click Start_DK_Liquor_POS.bat.
3. The POS opens in your normal browser.
4. Your data is stored locally in the browser on that computer.

MAIN FUNCTIONS
--------------
- Point of Sale checkout
- Product and inventory control
- Purchase recording
- Customer credit / receivables
- Supplier payables
- Expenses
- Cash / Bank / Mobile Money
- Loans and debt
- Fixed assets
- Owner equity
- Income Statement
- Balance Sheet
- Dashboard and control alerts
- Receipt printing
- JSON backup and restore

IMPORTANT
---------
Because this first version is a local offline POS, data is stored on the computer/browser.
Use Setup / Backup regularly to download a backup file.

ACCOUNTING LOGIC
----------------
Sales:
  Revenue is recorded.
  Inventory quantity is reduced.
  Product cost is retained so gross profit can be calculated.
  Cash/Bank/Mobile Money increases for paid sales.
  Credit sales create receivables.

Purchases:
  Inventory increases.
  Cash/Bank/Mobile Money decreases when paid.
  Unpaid purchases remain as supplier balances.

Expenses:
  Expenses reduce profit.
  The selected cash account decreases when paid.

Loans:
  Principal is tracked separately from operating expenses.
  Loan balances are reduced by principal payments.

Equity:
  Capital introduced increases equity.
  Drawings reduce equity.

BACKUP
------
Use Setup / Backup -> Download Backup.
To move the company database to another computer, copy the JSON backup and use Restore Backup.

NEXT DEVELOPMENT
-----------------
This version is designed as the working POS foundation. It can later be packaged as a Windows .EXE with a local database/server and can be expanded with barcode scanners, thermal receipt printers, multiple cashier accounts, permissions, daily closing, VAT/tax invoices, supplier purchase orders, and network/multi-terminal synchronization.
