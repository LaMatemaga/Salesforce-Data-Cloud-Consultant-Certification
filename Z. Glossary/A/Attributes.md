---
group: Concepts
tags:
    - glossary
---
The information or data found in data model objects (DMOs). For segmentation, Data Cloud offers two types of attributes: [[Direct Attributes]] (1:1) and [[Related Attributes]] (1:N). This evaluation originates from the object that was selected for Segment On.
- **Direct attributes (1:1)**: Attributes that have only one value for a record in the Segment On object. For example, if Individual DMO is selected as Segment On, then Individual.First Name or Individual.Gender attributes are listed as direct attributes. Additionally, all attributes from other DMOs that are related to Individual with a relationship cardinality of 1:1 are direct attributes. 
- **Related attributes (1:N)**: Attributes that have one or more values for a record in the Segment On object. For example, if Individual DMO is selected as Segment On, then Contact Point Email.Is Active or Sales Order.Grand Total Amount attributes are listed as related attributes.