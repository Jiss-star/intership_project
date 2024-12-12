1.channel_name
 
Indicates the communication channel used for the interaction.

Possible values:

Inbound: Customer initiated the interaction.
 
Outcall: Support team initiated the interaction.

2.category

Broad category describing the issue or purpose of the interaction.

Examples:

Product Queries: Questions about products.

Order Related: Issues related to orders.

Returns: Inquiries about returning items.

Cancellation: Request to cancel an order.

4. Sub-category
Provides further details within the broader category.

Examples:

Life Insurance (under Product Queries).

Reverse Pickup Enquiry (under Returns).

5. Customer Remarks

Comments or feedback from the customer.

Many entries are empty (NaN), indicating no remarks were left.

Example: "The product did not match the description."

6. Order_id
   
Unique identifier for the order associated with the interaction.

7. order_date_time

   
Date and time of the order, if applicable.

Many missing values (NaN) suggest this column is relevant only for order-related issues.

Example: 01/08/2023 11:13.

8.Issue_reported at
 
The date and time when the issue was reported by the customer.

Example: 01/08/2023 11:13.
9.issue_responded

The date and time when the support team responded to the issue.

Example: 01/08/2023 11:47.
10. Survey_response_Date
 
The date when the customer provided feedback or completed a survey.

Example: 01-Aug-23.

1. Customer_City
   
City where the customer is located.

Missing values indicate that location data is not always available.

Example: New York.

12. Product_category
    
The category of the product related to the interaction.

Examples:
Electronics.
Clothing.

14. Item_price
    
Price of the item associated with the interaction (if applicable).
Missing values likely indicate non-product-related interactions.
Example: 49.99.
16. connected_handling_time

Duration (in minutes) spent resolving the issue.
Many missing values suggest this was not measured for all interactions.
Example: 15.2 minutes.

17. Agent_name
    
Name of the customer service agent who handled the interaction.
Example: Richard Buchanan.

19. Supervisor
    
Name of the agent's supervisor.
Example: Mason Gupta.
21. Manager
Name of the manager overseeing the team.
Example: Jennifer Nguyen.

22. Tenure Bucket
    
Indicates the tenure of the agent handling the interaction.
Categories:
On Job Training: New hires in training.
0-30: Agents with 0–30 days of experience.
>90: Agents with over 90 days of experience.

19. Agent Shift

Specifies the time shift of the agent:
Morning.
Evening.

20. CSAT Score

Customer Satisfaction Score, typically on a scale of 1–5.
Example: 5 indicates high satisfaction.

