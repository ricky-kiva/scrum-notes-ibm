# Scratch Notes on Scrum

## 1. Templates

### User Story
- As a `<role>`
- I need `<functionality>`
- So that `<benefit>`

### Assumptions & Details
- Any assumptions
- Any implementation details that may help the software engineers

### Acceptance Criteria (Gherkin)
- Given `<preconditions>`
- When `<event/action>`
- Then `<expected outcome>`

---

## 2. Full User Story Example

### User Story
- As a Marketing Manager
- I need a list of customer names and emails
- So that I can notify customers about marketing promotions

### Assumptions & Details
- Customer emails are stored in the database
- Customers have opted in to receive promotional emails

### Acceptance Criteria (Gherkin)
- Given there are 100 customers in the database
  - And 90 customers have opted in to email promotions
- When I request the customer email list
- Then I should see a list of 90 customer emails
