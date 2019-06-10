---
layout: post
title: Current Application Delivery
author: Jamie Pope
---
## **Current State**
>`Application Name:` Timbuktoo <br>
`Development Environments:` 3 pipelines consisting of _DEV, TEST, QA, STAGE_ <br>
`Automation:` Maven for build (manual process to execute) and scripts for data refresh <br>

### **Deployment Process:**
1. Developer Task: Check code into proper branch (Subversion)
2. Developer Task: Create deployment ticket
3. Environments Management: Pick-up request ticket (3 day turnaround)
   - Tickets are processed by priority and first in 
4. Environments Management: Execute build job
   - If success, move to deploy status and update ticket 
   - If failure, capture build log and attach to request ticket 
5. Environments Management: Execute deploy job
   -  
 





