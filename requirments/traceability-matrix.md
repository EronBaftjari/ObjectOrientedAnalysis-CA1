# Tracability Matrix

|Problem\Stakeholder Goal| Requirment | Gherkin/Use Case | Domain Concepts |
|----|----|----|-----|
| Customers Approve by email, telephone or signed form and staff record the type of approval and spending limits |FR01: Record Customer approval, method and spending limit approval | Customer approves new spending limit | Job,Quotation,Approval |
| Customer : "Contact me before extra work pushes the cost above the agreed limit" | FR07 : Alert staff when extra work will go over the agreed spending limit | Alert staff about spending limit when customers spending limit goes overboard | Job,Quotation,Approval |
| "Material in the rack is already committed" | FR06: Record materials allocated to a job wheather stock is available | Material is already committed to another job | Job,Material |
| "Person who performed the work does not always have the authority to accept it" | FR05: Record which inspector approved a completed component  | Inspected Comments and passes a completed component  | Inspection record ,Employee  | 
| "Staff cannot always identify the job status or reason for delay" | FR10: Show the current status of each job | Search customers jobs to see their status | Job,Component |
|"Finished manufacturing does not mean accepted for release" | FR04: System shall record an inspection result for a component as pass rework  |Inspect compononents : Inspector passes a completed compononent | Component,InspectionRecord |
|"Manager needs information about approved jobs and expected completion"|FR11: Manager searches customers jobs and status|Manager searching customers job to see s job tatus|Customer,Job| 
|"Enquiries are spread across job cards and spreadsheets"|FR02: Record a new job enquiry with customer details and description of work|Use-Case ROB01: Staff records job with details|Customer,Job,Component|

