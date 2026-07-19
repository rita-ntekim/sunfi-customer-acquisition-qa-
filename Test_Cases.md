# Test Cases

## Project

**SunFi Customer Acquisition Journey – Manual QA Assessment**

---

| Test Case ID | Test Scenario | Preconditions | Test Steps | Expected Result | Status |
|--------------|---------------|---------------|------------|-----------------|--------|
| TC-001 | Verify user can start the customer acquisition journey | User is on the SunFi homepage | Click **Get Started** from the homepage | User is directed to the first step of the customer acquisition flow | ✅ Pass |
| TC-002 | Verify users can select a building type | User has started the customer acquisition journey | Select a building type (Home, Shop, or Business) and continue | Selected building type is accepted and user proceeds to the next step | ✅ Pass |
| TC-003 | Verify users can select a solar solution | User has selected a building type | Select a preferred solar solution and continue | User proceeds to the lead information form | ✅ Pass |
| TC-004 | Verify required field validation | User is on the lead information form | Leave one or more required fields empty and attempt to continue | Validation messages are displayed and submission is prevented | ✅ Pass |
| TC-005 | Verify email address validation | User is completing the lead information form | Enter an invalid email address and continue | System displays an email validation error and prevents submission | ✅ Pass |
| TC-006 | Verify successful lead information submission | User has entered valid information in all required fields | Complete the form and submit | Lead information is accepted and user proceeds to the recommendation flow | ✅ Pass |
| TC-007 | Verify customer feedback survey can be dismissed | User reaches the solutions page and the survey appears | Close the survey using the **X** button | Survey closes successfully and user continues browsing | ✅ Pass |
| TC-008 | Verify recommendation is generated after completing the journey | User has completed all required steps | Submit all required information | System generates a tailored solar recommendation | ✅ Pass |
| TC-009 | Verify in-app Back navigation preserves customer journey | User has progressed through multiple steps | Click the **Go Back** button | User returns to the immediately previous step while preserving progress | ❌ Fail (SF-001) |
| TC-010 | Verify Need Help / Chat with Us widget functionality | User is on a page displaying the support widget | Click **Need Help / Chat with Us** | Support interface opens and allows user interaction | ❌ Fail (SF-002) |
| TC-011 | Verify recommendation review modal is scrollable | User has opened the recommendation review modal | Attempt to scroll through the modal using the mouse wheel | User can scroll through all modal content without scrolling the background page | ❌ Fail (SF-003) |
| TC-012 | Verify Clear All removes selected appliances | User has added one or more appliances in the **Build My Own System** flow | Click **Clear All** | All selected appliances are removed and the selection resets | ❌ Fail (SF-004) |

---

## Test Summary

| Metric | Count |
|--------|------:|
| Total Test Cases | 12 |
| Passed | 8 |
| Failed | 4 |
| Blocked | 0 |
| Not Executed | 0 |
