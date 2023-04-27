# IT-Ticket-Impact-Prediction
*Predict ticket impact*

*Objective: Predict High Impact tickets to Prioritise.* 

**Solution:**
ML Classification model to identify high impact tickets
Two Groups (Low+Medium) & High impact tickets

*Inputs to predict High Impact*:
ID - Incident identifier 
Category ID - First-level description of the affected service
Opened Time - Incident user opening date and time

*Results:*
- Precise Model: 
  - How many High impact tickets are retrieved of total High Impact tickets - 71% (Recall) 
  - How many retrieved High impact tickets are True - 85% (Precision) 
- Recall Model: Recall is more important here
  - How many High impact tickets are retrieved of total High Impact tickets - 89% (Recall) 
  - How many retrieved High impact tickets are True - 36% (Precision) 

Use of this approach: Save time to resolve High impact tickets.


Use-case: Auto-predict high impact tickets & notify IT team to verify it.


*EDA Observations:*
- 95% of tickets are medium priority.
- Disproportionate Document knowledge
  - High Impact Tickets - No document knowledge 
  - Medium Impact Tickets - 20%
  - Low Impact Tickets - 40%
- 30% of tickets are opened by Group 17
- 30% of tickets are handled by Support-group 70
Most affected services categories are, 
- Category 26 - 13%
- Category 53 - 11%
- Category 42 - 11%
- Category 46 - 10%
