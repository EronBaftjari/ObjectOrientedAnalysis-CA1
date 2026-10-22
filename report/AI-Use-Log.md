# AI Use Log

**Tool:** Claude AI/Chat GPT | **Level:** 3 | **Date:** 22 October 2026

I used AI to explain concepts and to check my analysis against the Munster Engineering Workshop scenario. Below are the most significant examples.

| Area | Purpose | Representative prompt | Checks I performed | Outcome |
|------|---------|-----------------------|--------------------|---------|
|Candidate concepts| Review my classifications| "Give me classifications for each of these and explain what u did " | AI then said that quotation was a class. i Then thought it was a single price, so I then checked the scenario and found it mentions revised quotations and also the quotation types | Modified the quotat |
| Candidate concepts | Review my classifications | "give me classifications for each of these and explain what you did" | AI said Quotation was a class. I thought it was a single price, so I checked the scenario and found it mentions revised quotations and quotation types | **Modified.** Kept Quotation as a class, backed by the scenario |
| Refine candidate list | Check my decisions against the scenario | Uploaded the scenario with my refine table | Checked each point against the scenario text. Inspection results and who accepts the work must be kept | **Modified.** Changed Inspect from Remove to Convert to InspectionRecord |
| Domain model | Draft and explain the model | "teach me concept of domain modelling so i can understand" | AI added a `customerType` attribute. I checked my requirements and none need it | **Rejected.** Removed customerType. Also questioned why everything linked to Job, so Operation and Rework moved to Component |
| Use case | Review RB01 Record Job Enquiry | Uploaded my use case | AI suggested renaming "Item name" to "Component name". Customers bring in an item, not a component | **Rejected** the rename. **Accepted** fixes to the job status and phone number |
| Gherkin and traceability matrix | Review scenarios and link Must Haves | "show me how to complete this part" | Checked every Must Have had a problem, scenario and domain class. FR06 had no scenario | **Modified.** AI wrote the FR06 scenario. Matrix limited to Must Haves using my own scenario names |
| Functional requirements | Review my requirements | Pasted my functional requirements table (FR01–FR012) to build the traceability matrix | AI pointed out my IDs weren't the same format (FR010 instead of FR10), spelling mistakes, and that FR09 (start date) didn't match the domain model. I checked each one against my FR table and domain model | **Modified.** Fixed the IDs and spelling, and added startDate to Job to match FR09 |


AI Pointed Out the Risks that may be As I read though the Scenario and asked AI to give me its inputs Along with what possible answers could be 
AI also helped me understand how to layout my answers on Each section i wrote 
