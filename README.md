# NextGenFinalProject
NextGen final project BabySitter Requester Application


Work Memo

3/21/2024 by @ShuLiu

Started to use App Engine Studio develop our final project BabySitter Requester. 

Data- BabySitter Requster table extends from Task table. Added new fields: Requester, Start Date/Time, End Date/Time, Children Number, Children Age

Roles- babysitter, babysitter_manager

Group-BabySitter Group

Experience- 

1. Active user use Service Catalog >Can we help you>BabySitter Requester to access our application. Record Producer was created.

2. babysitter_manager use workplace to access the applicatioin. view All requests, unassigned tasks, overdue tasks.
            
3. babysitter: use babysitter workplace to access the application. view All my tasks, new tasks, and tasks on today

UI policy/action and business rules were created as well. When Allergy is YES, madatory Allergy List will be pop up. 
            
log and automation: New request creat: when a new requested is submitted by a requester, an email notification is sent to requester and babysitter manager.
                    Request assigned to a babysitter: When a requester is assigned to a babysitter, an email will be sent to babysitter, requester, and cc to manager as well. 

Future plan: imporve workplace UI interface, test flows, create data visualization on workplace.

==================================================================
