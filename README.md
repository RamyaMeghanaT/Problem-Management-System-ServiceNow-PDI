# Problem-Management-System-ServiceNow-PDI
A ServiceNow Problem Management System built using ServiceNow PDI to practice ITSM, scripting, security, SLAs, and notifications.

## Overview
A ServiceNow Problem Management System built to track and manage recurring and major problems.

The project provides hands-on practice with Problem Management, Client Scripts, Business Rules, GlideRecord, UI Policies, ACLs, SLAs, Notifications, and other ServiceNow configuration concepts.

### ServiceNow Concepts & Implementation

#### Custom Table & Task Extension
Created a custom Problem table by extending the Task table to manage Problem records.

#### Fields & Choice Lists
Configured fields and choice values for Problem Type, Impact, Urgency, Priority, Status, and other Problem details.

#### Client Scripts
Used Client Scripts to automatically calculate Priority based on Impact and Urgency.

#### UI Policies
Used UI Policies to make specific fields mandatory based on the Problem Status.

#### ACLs & Roles
Used ACLs and Roles to control access to Problem records and protect the data.

#### SLAs
Configured Response and Resolution SLAs to track the time taken to respond to and resolve Problems.

#### Notifications
Configured Notifications to inform the Assigned To user when a new Problem is created.

#### Business Rule & GlideRecord
Used a Business Rule with GlideRecord to query Problem records and identify similar Problems.

#### Work Notes
Used Work Notes to record internal updates and activity for Problem records.

## Screenshots

Screenshots of the Problem Management System configuration and implementation are available in the "PMS Screenshots" folder.

## Scripts

The "Scripts" folder contains the Client Script and Business Rule with GlideRecord used in this project.

## Tools Used

- ServiceNow Personal Developer Instance (PDI)
- JavaScript
- Git & GitHub
