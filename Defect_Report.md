# Defect Report

## Project

Quality Assessment of SunFi's Customer Acquisition Journey

---

# SF-001

## Title

In-app "Go Back" navigation does not consistently return users to the previous step.

### Severity

High

### Priority

High

### Environment

- Google Chrome
- Microsoft Edge
- Desktop

### Preconditions

User has progressed through the customer acquisition journey.

### Steps to Reproduce

1. Start the customer acquisition journey.
2. Complete one or more steps.
3. Click the in-app **Go Back** button.

### Expected Result

The user should be returned to the immediately previous step while preserving their progress.

### Actual Result

The user is redirected away from the expected previous step (e.g., back to the homepage or into a navigation loop), requiring parts of the journey to be repeated.

### Business Impact

Interrupts the customer acquisition journey, increases friction, and may discourage users from completing their enquiry.

**Evidence:** See `Screenshots/SF-001-Go-Back-Navigation.png`

---

# SF-002

## Title

"Need Help / Chat with Us" link is displayed but is non-responsive.

### Severity

High

### Priority

High

### Environment

- Google Chrome
- Microsoft Edge
- Mobile

### Preconditions

User is on a page where the support link is displayed.

### Steps to Reproduce

1. Navigate to a page displaying the **Need Help / Chat with Us** link.
2. Click the link.

### Expected Result

The support interface should open and allow the user to request assistance.

### Actual Result

The link is displayed but does not respond to user interaction.

### Business Impact

Users who require assistance during the purchase journey cannot access support, which may reduce confidence and impact conversion.

**Evidence:** See `Screenshots/SF-002-Chat-Widget.png`

---

# SF-003

## Title

Recommendation review modal cannot be scrolled independently.

### Severity

Medium

### Priority

Medium

### Environment

- Google Chrome
- Desktop

### Preconditions

User opens the recommendation review modal.

### Steps to Reproduce

1. Generate a recommendation.
2. Open the recommendation review modal.
3. Attempt to scroll through the modal using the mouse wheel.

### Expected Result

Users should be able to scroll through all modal content without affecting the background page.

### Actual Result

The modal cannot be scrolled independently, while the background page scrolls instead, making parts of the modal inaccessible.

### Business Impact

Users may be unable to review all recommendation details before proceeding, reducing usability and decision confidence.

**Evidence:** See `Screenshots/SF-003-Modal-Scroll.png`

---

# SF-004

## Title

"Clear All" action remains disabled after appliances have been added.

### Severity

Medium

### Priority

Medium

### Environment

- Google Chrome
- Desktop

### Preconditions

User has added one or more appliances while building a custom solar system.

### Steps to Reproduce

1. Navigate to the **Build My Own System** flow.
2. Add one or more appliances.
3. Attempt to use **Clear All**.

### Expected Result

The **Clear All** action should become available and remove all selected appliances.

### Actual Result

The **Clear All** action remains disabled despite appliances being present.

### Business Impact

Users cannot efficiently reset their selections and may need to remove items individually or restart the process, increasing friction.

**Evidence:** See `Screenshots/SF-004-Clear-All.png`
