# Requirements for the Course Management System

## Introduction

This document specifies the requirements for a Course Management System (CMS). The requirements are grouped by their stakeholders, and functional and non-functional requirements are separated. 

## Stakeholders
letter|thing
--- | ---
S|Students
L|Lecturers
B|Administration
M|System Maintainer

## General Requirements

rNum|Requirement
--- | ---
R1|The system shall provide static course information
R2|The system shall be able to store static course information
R3|The system shall be able to represent static course information 
R4|The system shall provide dynamic course information 
R5|The system shall be able to store dynamic course information 
R6|The system shall be able to represent dynamic course information 
R7|The system shall provide a messaging system 

## Requirements of Students

### Functional Requirements


rNum|Requirement
--- | ---
R8|The system shall enable students to retrieve contact information of students and lecturers of subscribed courses 
R9|The system shall provide the history of a course (view contents of a course over the years) 
R10|The system shall provide the history of attended courses 
R11|The system shall enable students to subscribe/unsubscribe to courses
R12|The system shall enable students to subscribe/unsubscribe to exams 
R13|The system shall be able to provide a collaboration environment in a course (so students can share files and notes within a team) 
R14|The system shall be able to let students submit textual content 
R15|The system shall be able to let students upload files 
R16|The System shall allow sending messages to individuals, teams or all course participants at once 
R17|The system shall allow students to create teams. 
R18|Teams are created by students inviting other students in the same course using the messaging system. 
R19|The system shall facilitate searches in all static information of courses. 
R20|The system shall facilitate searches within all dynamic information and files in a course 
R21|The system shall allow students to edit their personal information
R22|The system shall allow students to change their password 
R23|3 The system shall provide a password reset function, which resets the password and mails it to the user 
R24|The system shall notify students of events (posted news messages, team invites and scheduled exams) 
R25|The system shall allow students to customize the notification behaviour 
R26|The system shall allow students to view course grade statistics per semester 

### Non-Functional Requirements

rNum|Requirement
--- | ---
R27|The system shall protect the user’s privacy 
R28|The system shall prevent students from viewing grades of others 
R29|The system shall provide a user-customizable visibility policy for the personal information

### Availability

rNum|Requirement
--- | ---
R30|The system shall have high availability 
R31|The system shall not have unexpected downtime 
R32|The system shall have downtime at most 4 hours/month 
R33|The system shall have its expected downtime announced at least 48 hours in advance 
R34|The system shall have downtime only during low-intensity hours 

### User Friendliness

rNum|Requirement
--- | ---
R35|The system will be user friendly
R36|The system shall have bilingual support (Dutch and English) 
R37|The system shall have a maximum of 3 clicks to reach any content
R38|The system shall have a single login to access all content 
R39|The system shall have a consistent UI (in all the views and dialogs, the UI elements behave and are placed in a similar way) 
R40|The system shall have a UI which is intuitive (the behaviour of the system is according to the intuition of a standard end user) 
R41|The system shall have a descriptive UI (all UI elements should have a descriptive text) 

### Accessibility

rNum|Requirement
--- | ---
R42|The system shall have high accessibility 
R43|The system shall be accessible by disabled (blind) users, who should be able to navigate the system and have access to all content and functionality

### Security 

rNum|Requirement
--- | ---
R44| The system will be secure 
R45|The system shall allow only students to change study information of others 

### Interoperability

rNum|Requirement
--- | ---
R46|The system shall be highly interoperable 
R47|The system shall provide an export to commonly used calendar formats (allowing users to import scheduled lectures into a personal calendar) 