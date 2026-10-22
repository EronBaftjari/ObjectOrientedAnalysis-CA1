//Had AI break this down into smaller pieces and help me how it should be answerd
## Candidate-Concept Analysis

**Initial Candidate Extraction**

|Candinate Term| Classification | Reason| 
|-----|----|----|
|Organisations | Requires Clarification  | May be customer type or others,  needs more Clarification |
| quotations | Conceptual class| Quote has its own price and can be approved |
| Drawings | Possible  Conceptual class| Customers can provide more than 1 drawing and could contain other bits of information  |
| Materials | Conceptual Class | Supplied by customer or shop used on Jobs so it would have its own details |
| notes | Attribute|  single Piece of information attached to a job   |
| job cards | Implementation detail | Used to record Information of jobs and operations and is still needed  |
| Email | Attribute| Workshop needs customers email to contact them about approvals   |
| Spread sheet | Role or Synonym  | Same as jobs card would be merged  |
| specification | Requires Clarification | Could it be single piece of data saved or could it contain more little bits information |
| Job Status | Attribute | Single value repersenting Jobs status |
| Customer | Conceptual class | Workshop system must remember customers details and its which job its assigned to |
| description | Attribute or value |   single Short text description describing job |
| Target date | Attribute or value| Single data describing when Job should be completed   |
| inspect | Operation or Event  | Something that happens after job is completed, results are kept and could point to a conceptual class |
| Telephone | Attribute | Customers details to communicate and  Way of customer interacting back |
| Employees | Actor or Conceptual Class | Uses the System but may need to store details such as who did the work  |
| Machine | Conceptual Class | Has its own identity and is used for operations and must be known if its available if jobs can continue |
| Specialist | Requires Clarification | Scenario does not specify who this could be |
| Scheduled | Attribute or value | Contains single piece of information containing when job is expected to start |
| Operations | Possible Conceptual class | information of job , its machine ,worker and status of job |
| Component | Conceptual class | Item could be collected and has its own details |
| Completion  | Attribute or value  | Completion date or status on the job  |
| Approval | Conceptual class | Records the customers price and how they approved it (email or phone number) |
| Rework | Conceptual class  | Could have the jobs detail , the cause and who did it  |
| Rework cause | Attribute or value | Single piece of information on the reasoning of rework |
| Workshop error | derived information | This is given based on other inputs if it was a workshop error  |
| Welder | Actor or Conceptual class | Uses the system, so an actor. Possibly a class too, since FR12 records who did the work |








//Used AI to Refine and give me other suggestions on some Terms what they could be and kept note of it 

What’s weak
Every evidence s

**Refine the Candidate List**
**Keep, merge, convert and remove decisions**

|Candidate |	Decision|	Final term or destination|	Justification|
|----|---|-------|---------|
|Organisation| convert | Attribute of customer |The scenario says customers are farms, businesses and community organisations, so this is the type of customer
|quotations| coceptual class| Quotation  |Has a price and a type, and can be revised, so one job may have several quotations|
| Drawings  | Keep | Drawing | Customer can supply more than 1 drawing for a job  |
| Materials | Keep | Material | Supplied by customer or shop and used on jobs has its own details |
| Notes | convert | Job attribute |  Single piece of information of job |
| Job cards | remove | Implementation detail | Old way of holding information|
| Email | convert | Attribute of customer | Way of communcating to customer when retrieving details of quotations  |
| Spread sheet | Remove | Implementation detail |Old way of holding information  |
| Specification | Keep | Possible Conceptual class |Can be revised, and staff need to know which version is current|
| Job Status | convert | Attribute of job | Value repersenting jobs status |
| Customer | Keep | Customer | Has identity, eligibility information, registrations and job history |
| Description | convert | Attribute of job | Information describing Job |
| Target Date | convert | Attribute of job | Single piece of information describing wanted finish date |
| Inspect | remove | Points to Inspection class | This is a event not a thing or a attribute |
| Telephone | convert | Attribute of job | Way of communcating to customer when asking for quotation |
| Employees | Keep | Employees | Uses the Workshop and need to keep track of who did the work , inspections etc.. |
| Machine | Keep | Machine | Has its own identity, is used for operations, and its availability affects whether jobs can continue |
| Specialist | Requires Clarification |  Employee or External Contractor | Workshop Scenario does not specify who this could be |
| Schedule | convert | Attribute of job | Single Date which it is expected to finish |
| Operations | keep | Operation | 	A step in a job with its own machine, worker and status |
| Component | Keep | Component | Contain Information of job and which customer it belongs to  and can be collected |
| Completion | convert | Attribute of job | Information on Completion date |
| Approval | Keep | Approval class | Contains information on who approved it and what job was approved |
| ReWork | Keep | Rework |	Work done again on an item , with its own job, cause and who did it  |
| ReWork Cause | convert | Attribute of Rework | Single piece of information containing the ReWork Cause  |
| Workshop Error | Convert | Value of Rework cause | One of the possible causes, along with customer chang |
|Welder|Merge|Employee|A welder is an Employee doing welding work, and FR12 records who did the work|
|Job|Keep|Job|Main thing in the Workshop, Has its own description,date,status and components|

