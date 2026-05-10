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

---

## 3. Sprint Planning & Estimation

### Story Points
- Estimation uses Fibonacci-like sequence:
  - 1, 2, 3, 5, 8, 13, 21
- Represents relative size, not time

### Estimating Sprints (Forecast)
- Number of Sprints ≈ (Total story points) / Velocity
  - Velocity = average story points completed per sprint
  - Sprints = fixed time box (e.g., 2 weeks)
 
### Sprint Planning Example:
- 100 total story points
- 20 points per sprint velocity (avg. completed per sprint)
- → Number of Sprints ≈ 5 sprints

---

## 4. Burndown Chart

### Purpose
- Tracks sprint progress over time
- Helps forecast if sprint goal can be achieved

### How to Read
- Vertical axis = remaining story points
- Horizontal axis = sprint days/time
- Story points should decrease over time ("burn down")

### Burndown Chart Components
- Dot
  - Represents completed story
- Actual line (blue line)
  - Real progress made by the team during the sprint
- Ideal line (dotted line)
  - Expected progress path during the sprint
- Vertical block
  - Indicates non-working days

### Burndown Chart Example
- <img src="../main/assets/burndown-chart.jpg" alt="Burndown Chart Example" height="512">
