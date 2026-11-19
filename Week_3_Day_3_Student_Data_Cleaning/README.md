# Week 3 Day 3 – Student Data Cleaning and Validation

## Objective
Build an n8n workflow to clean, validate, filter, and export student records.

## Workflow Nodes
1. Manual Trigger
2. Google Drive – Download File
3. Extract from File – CSV
4. Remove Duplicates
5. Edit Fields – Data Cleaning and Normalization
6. Filter – Fee Paid = Yes
7. Convert to File – CSV
8. Google Drive – Upload File

## Results
- 50 input records
- 50 records processed after duplicate removal
- 33 fee-paid records retained
- 17 records discarded
- Names converted to uppercase
- Email format validation added
- Output generated as students_clean.csv
- Uploaded to Google Drive
