Barclays Bank statement PDF-to-CSV
==================================
The original repository works with Business account statements.
Forked from
https://github.com/penrosestudio/barclays-bank-pdf-to-csv.git

This version works just for personal account statements.

Reads Barclays Bank statements and extracts transactions. Validates transactions against the total payments and receipts shown in the top-right of the bank statement.


## Installation

Clone the git repository, then install dependencies:

    git clone https://github.com/cmalangone/barclays-bank-pdf-to-csv.git
    npm install

## Usage under Node.js

    node statement-parser <folder>

`<folder>` should be a directory containing Barclays Bank statement PDFs.

## Usage in a browser

Open index.html in a browser and drop a PDF onto the drop-zone.

Browsers tested and compatible:
* Mac OS X 10.9.5:
  * Chrome 40.0
  * Safari 7.0.6
  * Firefox 35.0.1
* Windows 7:
  * Firefox 36.0

## Output

A single CSV file will be created called `statements.csv`.
The file header is 

date of transaction, description, money in, money out


## Issues
I don't think to have time to solve issues. :-(
