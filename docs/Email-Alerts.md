Milestone 8 — Email Alerts
Objective

Notify recruiters or hiring managers automatically when a candidate application is submitted or when an offer requires approval.

Steps

Navigate to Setup.

In Quick Find, search for Email Templates.

Click New Email Template.

Create the template:

Template Name

Candidate Application Notification

Subject

New Candidate Application Submitted

Body

A new candidate application has been submitted.

Candidate: {!Candidate_Application__c.Candidate__c}
Job Opening: {!Candidate_Application__c.Job_Opening__c}
Application Date: {!Candidate_Application__c.Application_Date__c}

Save the template.

Create Email Alert

Go to Setup → Email Alerts

Click New Email Alert

Configure:

Object: Candidate Application
Email Template: Candidate Application Notification
Recipients: Hiring Manager / Recruiter

Save.
