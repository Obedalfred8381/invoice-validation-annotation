# Invoice Validation and Annotation Project

## Overview
A document annotation and validation project covering 5 sample
invoices. Each invoice is annotated in JSON format with full
field level validation including math checks, format checks,
and error documentation.

## Validation Checks Performed
- Line item math: qty x unit_price = total
- Subtotal: sum of all line item totals
- VAT: subtotal x 7.5%
- Grand Total: subtotal + VAT
- Date format: YYYY-MM-DD standard

## Files
- invoices.xlsx — source invoice documents
- invoice1_clean.json — clean reference invoice
- invoice2_lineitem_error.json — line item calculation error
- invoice3_subtotal_error.json — subtotal mismatch
- invoice4_date_error.json — invalid date format
- invoice5_grandtotal_error.json — grand total calculation error

## Tools Used
- Microsoft Excel (invoice creation)
- JSON (annotation and validation output)
- Manual math validation

## Purpose
Portfolio project demonstrating document annotation,
field level validation, and financial QA skills.
