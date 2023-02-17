# Task 2

## Bug Report.

**Title:** Updating a todo does not validate that its empty or not

**Description:** When a user is updating a todo, the application should validate that the text field is not empty before updating a todo row

**Priority:** Critical

**Severity:** Critical

## Recreation Steps
1. Launch the todo application
2. Add a todo
3. Update the added todo, without entering a value in the update field
4. Press the "update" button 

**ACTAUL Results:** todo row is updated without validation if text field is empty or not


![Leave the update input box empty](test\screenshots\Picture1.png)

![Press update without value](test\screenshots\Picture2.png)

**EXPECTED Results:** text field should be validated to make sure a todo is not updated to nothing



