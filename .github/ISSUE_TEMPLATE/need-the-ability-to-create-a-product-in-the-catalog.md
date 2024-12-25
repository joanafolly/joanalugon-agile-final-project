---
name: Need the ability to create a product in the catalog
about: user story
title: ''
labels: ''
assignees: ''

---

**As a** User.
**I need** the ability to create a product in the catalog
**So that** I can add new items to the store.

### Details and Assumptions
* The product catalog will store product names, descriptions, and prices.
* Each product will have a unique identifier for tracking purposes.
* The ability to create products will be available via an API endpoint.

### Acceptance Criteria
'gherkin
Given I have access to the product catalog API
When I send a request to create a new product with valid details
Then the product should be successfully added to the catalog
