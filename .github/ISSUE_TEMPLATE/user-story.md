---
name: User Story
about: 'Describing what needs to be done '
title: ''
labels: ''
assignees: ''

---

**As a** Manager
 **I need** A mailing service
 **So that** I can send mail to customers
   
 ### Details and Assumptions
 * A mailing service database
 * A UI 
 * SMTP service
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given I'm logged in as a manager
 When i mail customers
 Then the customers should receive the mail immediately
