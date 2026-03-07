# Milestone 9 – Declarative Automation (Flows)

## Objective
Automate the creation of Candidate Applications using Salesforce Screen Flow.

This flow allows recruiters to input candidate information and automatically create a Candidate Application record in Salesforce.

---

## Flow Overview

The Screen Flow collects candidate data, calculates the final offer amount, and creates a Candidate Application record.

Workflow:

Recruiter → Screen Flow → Assignment Logic → Create Candidate Application Record

---

## Steps to Create the Flow

### 1. Create a Screen Flow

Navigate to:

Setup → Flows → New Flow

Select:

Screen Flow

Click:

Create

---

### 2. Candidate Details Screen

Add a Screen element.

Screen Name:

Candidate Details

Fields:

- Candidate
- Job Opening
- Application Date

---

### 3. Offer Details Screen

Add another Screen element.

Screen Name:

Offer Details

Fields:

- Experience Level
- AI Candidate Score
- Offer Amount

---

### 4. Assignment Element

Create a variable:

finalOfferAmount

Assignment Example:

finalOfferAmount = Offer Amount

---

### 5. Create Candidate Application Record

Add element:

Create Records

Object:

Candidate_Application__c

Field Mapping:

- Candidate → Candidate
- Job Opening → Job Opening
- Application Date → Application Date
- Offer Amount → finalOfferAmount

---

### 6. Confirmation Screen

Display message:

Candidate Application Created Successfully

---

### 7. Activate the Flow

Click:

Save → Activate

---

## Result

Recruiters can now create candidate applications through a guided screen flow which automates data entry and record creation.

---

## Screenshot

Add the following screenshot:

screenshots/flow-builder-candidate-application.png

Caption:

Figure: Candidate Application Screen Flow in Flow Builder
