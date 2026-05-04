# Test Cases for Digital Parking Permit System

## System Tests

### Test Case 1: User Registration
- **Objective:** Verify that a new user can register successfully.
- **Preconditions:** User is on the registration page.
- **Test Steps:**  
  1. Enter a valid email address.  
  2. Enter a valid password.  
  3. Click on 'Register' button.  
- **Expected Result:** User receives a confirmation email and is redirected to the login page.

### Test Case 2: Permit Generation
- **Objective:** Verify that a registered user can generate a parking permit.
- **Preconditions:** User is logged in and has access to the permit generation page.
- **Test Steps:**  
  1. Select the vehicle type.  
  2. Enter the permit duration.  
  3. Click on 'Generate Permit' button.  
- **Expected Result:** A parking permit is generated and displayed to the user.

## Acceptance Tests

### Test Case 1: Permit Usage
- **Objective:** Verify that permits are recognized during parking enforcement.
- **Preconditions:** A valid permit exists for a vehicle.
- **Test Steps:**  
  1. Park the vehicle in a designated area.  
  2. Present the permit to the parking enforcement officer.  
- **Expected Result:** Officer verifies the permit and allows the user to park without a ticket.

### Test Case 2: User Login
- **Objective:** Verify that users can log in to their account.
- **Preconditions:** User is registered.
- **Test Steps:**  
  1. Navigate to the login page.  
  2. Enter registered email and password.  
  3. Click on 'Login' button.  
- **Expected Result:** User is redirected to the dashboard.

## Regression Tests

### Test Case 1: Permit Validation
- **Objective:** Ensure that permit validation logic still works after code changes.
- **Preconditions:** Codebase has been modified recently.
- **Test Steps:**  
  1. Generate a valid permit.  
  2. Attempt to use the permit at a parking location.  
- **Expected Result:** System validates the permit successfully.

### Test Case 2: User Interface Integrity
- **Objective:** Ensure that the user interface remains functional after updates.
- **Preconditions:** New UI design has been implemented.
- **Test Steps:**  
  1. Navigate through all UI sections.  
  2. Check for layout and functionality consistency.  
- **Expected Result:** All sections function without errors, and the layout is consistent.
