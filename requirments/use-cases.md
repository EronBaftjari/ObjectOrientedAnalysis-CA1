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

