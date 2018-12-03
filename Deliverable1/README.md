# Deliverable 1

## Use Cases

ID|Use Case|Description
---|---|---
UC-1|View course information|The system should allow the user to view all associated course information to the courses that they are registered for. They should also control the access levels of different types of users
UC-2|Store course information|All the associated course information should be stored on the server associated with the CMS, so that all information is controlled in its whereabouts.
UC-3|Allow there to exist a messaging system|Students, TA’s, and Professors should be able to communicate with each other about the course material directly inside of the CMS.
UC-4|Show student’s course history|Students should be able to see a history of all the courses that they have taken with the school.
UC-5|Search a course of all information|The student should be able to search all associated course materials for certain information directly inside of the CMS, to help speed up the lookup time for students.
UC-6|Collaborative student work environment|Provide an environment where students are able to work collaboratively together to complete assignments, without having to leave the CMS.
UC-7|Student logs in to the CMS|Each user of the CMS is required to log-in to access the content of the CMS, and the content is modified to reflect the privilege level of the user.
UC-8|Be accessible|The CMS should actively use and implement the industry standard of accessibility functionality so that no user is unable to work on the CMS.
UC-9|Lecturer uploads course content to CMS|The professor or TA should be able to upload any required content to the CMS, which is then access controlled to the students.
UC-10|Professor assigns a teaching assistant|Professors should be able to control and assign who acts in the role of TA for the course they are teaching.
UC-11|Store backups of the CMS on the server|The CMS should actively perform backups of the system to ensure that no problems exist in the event that the server should crash.

## Quality Attribute Scenarios

ID|Quality Attribute|Scenario|Associated Use Case
---|---|---|---
QA-1|Performance|Large searches are regularly performed and the resulting search times must be within a specified range.|UC-5
QA-2|Availability|The CMS uses icons and images that are mapped to descriptions for those who are visually impaired.|UC-8
QA-3|Modifiability|Professor is able to add as many TA’s as possible to their course.|UC-10
QA-4|Security|Integrity of backups are regularly tested to ensure that they are ready to be swapped into prod if need be|UC-11
QA-5|Security|All course information is only available to the correct user with the correct privilege.|UC-2

## Constraints Imposed on CMS

ID|Constraint
---|---
CON-1|Minimum of ½ school capacity of concurrent users
CON-2|System must be available and accessible on all available platforms
CON-3|The physical CMS server should exist as close to the school as possible
CON-4|The CMS must have a 99.999% (four nines) uptime during the school months
CON-5|Each day the latest backup of the server should be stored, with a minimum backup history of 1 week
CON-6|All inputs on the CMS must prevent basic injection type vulnerabilities, as well as other more advanced levels of vulnerabilities.
