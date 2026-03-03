# Object Structure

## 1. Contact (Candidate)

Fields:
- Candidate ID (Auto Number: C-{0000})
- Experience Level (Picklist: Fresher, Mid-Level, Senior)
- Application Status (Picklist: New, Screening, Interview, Offer, Hired)

## 2. Job Opening

Fields:
- Department (Picklist: IT, HR, Finance, Sales)
- Salary Range (Currency)
- Vacancies (Number)
- Job Status (Picklist: Open, Closed, On Hold)

## 3. Candidate Application

Relationships:
- Candidate → Master Detail (Contact)
- Job Opening → Master Detail (Job Opening)

Fields:
- Application Date (Date)
- AI Candidate Score (Number)
- Offer Amount (Currency)
- Application Status (Picklist: Active, Inactive)
- Approval Status (Picklist: Pending, Approved, Rejected)
