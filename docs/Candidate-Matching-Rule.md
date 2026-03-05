# Candidate Matching Rule

## Description
This matching rule helps identify potential duplicate Candidate (Contact) records in the recruitment system. It compares key fields such as email and phone number to ensure that the same candidate is not entered multiple times.

## Object
Contact (Candidate)

## Matching Criteria
The system checks the following fields:

- Email (Exact Match)
- Phone Number (Exact Match)
- Full Name (Fuzzy Match)

## Steps to Create Matching Rule

1. Go to **Setup** in Salesforce.
2. Search for **Matching Rules** in the Quick Find box.
3. Click **Matching Rules**.
4. Select **Contact** as the object.
5. Click **New Rule**.
6. Add matching criteria:
   - Email → Exact
   - Phone → Exact
   - Name → Fuzzy
7. Save the rule.
8. Click **Activate**.

## Purpose
This rule helps maintain clean and reliable candidate data by detecting possible duplicates during record creation.
