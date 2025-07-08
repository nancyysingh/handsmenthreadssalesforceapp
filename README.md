 HandsMen Threads - Salesforce Project

A custom Salesforce app to streamline men's bespoke tailoring and enhance the customer experience through personalized styling and seamless order management.


 Project Overview

Use Case:  
Develop a premium fashion platform for personalized men's tailoring and customer order tracking.

Platform: Salesforce  
Complexity: Medium  
Duration: 30 mins  

---

 Objectives

- Allow customers to input their measurements
- Track tailored clothing orders
- Enable stylists to assign recommendations
- Automate order confirmations and delivery tracking using Salesforce Flows

 Data Model

| Object Name | Description |
|---------------------|----------------------------------------|
| `Customer__c` | Stores customer details |
| `Measurement__c` | Body measurements linked to customer |
| `Order__c` | Tailoring order and status tracking |
| `Stylist__c` | Records stylist information |
| `Recommendation__c` | Style suggestions for customers |

 Relationships

- One `Customer__c` → many `Measurement__c`
- One `Customer__c` → many `Order__c`
- One `Stylist__c` → many `Recommendation__c`

---

 Flows Used

- **Order Confirmation Flow**  
  Sends email when an order is placed.

- **Styling Suggestion Flow**  
  Recommends outfits based on customer preferences.

 How to Use

1. Clone this repo or use as reference.
2. Create a Salesforce Developer Org.
3. Set up custom objects and relationships.
4. Build Flows using Flow Builder.
5. Deploy the app and test with sample data.

---
Acknowledgements

Built as part of the **SkillWallet Salesforce Developer Virtual Internship Project**.
