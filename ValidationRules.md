# Salesforce Validation Rules Examples

1. Prevent Opportunity Close Date in the past  
   Formula: CloseDate < TODAY()  
   Error Message: "Close Date cannot be in the past."

2. Ensure Email is company domain  
   Formula: NOT(CONTAINS(Email, "@company.com"))  
   Error Message: "Please enter company email."
