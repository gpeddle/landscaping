# Domain model

Landscaping Service domain model 

## Summary

The major entities in the model are listed below. Each is an important concept in the core business domain.

1. **Customer:**
   - A person or entity seeking landscaping services.
   - Has a unique ID, first name, last name, email, and phone number.
   - May have multiple properties or addresses.

2. **Address:**
   - Represents a physical location where landscaping services are provided.
   - Has a unique ID, street address, city, state, and postal code.
   - Associated with a customer, quote, or work order.

3. **Service:**
   - Different types of landscaping services offered, such as lawn mowing, tree trimming, etc.
   - Has a unique ID, name, description, and price.

4. **Quote:**
   - A proposal or estimate for landscaping services provided to a customer.
   - Has a unique ID, customer ID, service ID, date, total amount, status, and a single associated address.

5. **WorkOrder:**
   - Represents the actual work performed in service of a quote.
   - Has a unique ID, quote ID, date, description, hours worked, materials used, total cost, an associated Quote and a single associated address.

6. **WorkflowEvent:**
   - Represents a step in the overall workflow process for a quotation as it progresses to a WorkOrder. 

## Minor Entities

The following minor entities exist to support non-core parts of the busoiness domain.

1. Message

2. Email

