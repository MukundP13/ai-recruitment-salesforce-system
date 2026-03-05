# Candidate Duplicate Rule

## Description
The duplicate rule prevents duplicate candidate (Contact) records from being created in the recruitment system. It uses the matching rule to detect duplicate records.

## Object
Contact (Candidate)

## Matching Rule Used
Candidate Matching Rule

## Steps to Create Duplicate Rule

1. Go to **Setup**.
2. Search for **Duplicate Rules** in the Quick Find box.
3. Click **Duplicate Rules**.
4. Select **Contact** as the object.
5. Click **New Rule**.
6. Choose the **Candidate Matching Rule**.
7. Configure rule behavior:
   - Action on Create → Block
   - Action on Edit → Alert
8. Set alert message for duplicate detection.
9. Save the rule.
10. Click **Activate**.

## Purpose
This rule ensures that the recruitment system does not contain duplicate candidate records, improving data quality and reporting accuracy.
