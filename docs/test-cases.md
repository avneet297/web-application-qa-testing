# Manual Test Cases

## TC-001 — Homepage Loading

**Priority:** High

**Precondition:** Application URL is available.

**Steps:**

1. Open the application URL.
2. Wait for the page to load.

**Expected Result:**

Homepage loads successfully without errors.

**Expected Status:** PASS

---

## TC-002 — Navigation Links

**Priority:** High

**Steps:**

1. Open the homepage.
2. Click each primary navigation link.
3. Verify the destination page.

**Expected Result:**

Each link opens the correct destination.

---

## TC-003 — Empty Form Submission

**Priority:** High

**Steps:**

1. Navigate to the form.
2. Leave all fields empty.
3. Click Submit.

**Expected Result:**

Required-field validation messages are displayed and the form is not submitted.

---

## TC-004 — Invalid Email Validation

**Priority:** High

**Steps:**

1. Enter an invalid email address.
2. Complete other required fields.
3. Submit the form.

**Expected Result:**

The application displays an appropriate email validation message.

---

## TC-005 — Valid Form Submission

**Priority:** High

**Steps:**

1. Enter valid information in all required fields.
2. Submit the form.

**Expected Result:**

The form is successfully submitted and the user receives appropriate confirmation.

---

## TC-006 — Broken Links

**Priority:** Medium

**Steps:**

1. Navigate through the application.
2. Click available links.
3. Verify that each destination loads.

**Expected Result:**

Links do not result in 404 pages or unexpected errors.

---

## TC-007 — Browser Back Navigation

**Priority:** Medium

**Steps:**

1. Navigate through multiple pages.
2. Use the browser Back button.

**Expected Result:**

The user is returned to the previous page without unexpected behavior.

---

## TC-008 — Mobile Responsive Layout

**Priority:** High

**Steps:**

1. Open browser developer tools.
2. Enable mobile device simulation.
3. Test common mobile viewport sizes.
4. Navigate through major pages.

**Expected Result:**

Content remains readable and usable without horizontal scrolling or overlapping elements.

---

## TC-009 — Button Behavior

**Priority:** Medium

**Steps:**

1. Identify interactive buttons.
2. Click each button.
3. Verify the resulting action.

**Expected Result:**

Each button performs its intended action.

---

## TC-010 — Error Handling

**Priority:** High

**Steps:**

1. Enter invalid or incomplete information.
2. Submit the workflow.

**Expected Result:**

The application provides a clear and useful error message without exposing technical information.
