The Scope is defined in the purpose and boundary section , in this instantce the customer is out of the scope as the customer is not interacting with the system directly at all
Staff  interact with the system like record Information of jobs and customers 

**Actors**


// --< Asked Ai to Lay out the Layout of the answers for me and give me details that i might have missed   >-- \\
 |Actor/StakeHolder | Type | Goal | Direct ? |
 |----|----|-------|----|
|Staff| Primary StakeHolder | Records job specifications, quotations, customer approvals, faults  and completion estimates.  | Yes |
|Manager| Primary StakeHolder | See Shortage of Materials and expected finish dates and Record Material Storage | Yes |
|Customer| Offstage Stakeholder | Supply Materials or Supply Information of jobs  | No |
|Supplier| Offstage StakeHolder | Deliver Materials For jobs | No |
|External Providers| Offstage Stakeholders | Provide Service such as Welding and coating | No |
|Inspector| Primary Stakeholder | Inspects and Approves jobs then are released | Yes |

**Use-Case Catalogue**
|Use case| Primary Actor | Meaningful Outcome | Source requirement | 
|--------|---|-------|----|
|Record Job | Staff | Job is created and recorded with customers details and Description of the Work as they supplied | FR02 |
|Record Customer Approval| Staff | How the Request was given and Answer Recorded | FR01 |
|Allocate Materials to job | Staff | Materials are recorded to what job they are allocated for and stock availability is shown | FR06 |
|Inspect Comment /Approve | Inspector | The result (pass, rework or needs customer acceptance) and the inspector who approved it are recorded | FR05,FR4 |
|Check Status of Jobs | Manager | Manager Finds Customers Job and finds its status | FR11,FR10 |
|Record Job collection | Staff | When Customer Collects finished item Staff will record as Collected | FR03 |
|Record rework Cause | Staff | Start date , Who did the job ,Mark what the issue was  | FR09,FR12 |
| Alert Customer When limit is broken | Staff | Alert Customer that Spending limit is Broken  | FR07 |




**AI use in this section**

| What I used AI for | How it helped me |
|---|---|
| Laying out the use-case model | Showed me how to set out the actor table and use-case catalogue in the same format as the Session 4 lab |
| Understanding actors and stakeholders | Explained that only people who use the system directly are actors, and that people like the customer are offstage stakeholders |
| Deciding who goes on the diagram | Helped me see that Customer, Supplier and External Providers don't use the system, so they shouldn't be on the use-case diagram |
| Checking use cases against my requirements | Pointed out that FR08 was missing, and that FR09 and FR12 belonged in a different use case to rework |
| Spotting things that aren't use cases | Explained that FR07 (the spending limit alert) is something the system does by itself, not a goal a person has, so it belongs inside another use case |
| Naming use cases | Showed me how to name use cases as actor goals (e.g. Check Job Status instead of Show Status of Jobs) |
| Naming the system boundary | Pointed out that the rubric asks for a named boundary, so I gave the system a clear name |
| Writing the use-case diagram | Helped me write the PlantUML code for the boundary, actors and use cases |

Using AI this way helped me check my work against the lab and the rubric, find gaps between my requirements and use cases, and understand the reasons behind each modelling choice.
