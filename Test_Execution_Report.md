# Test Execution Report

## Project

**SunFi Customer Acquisition Journey – Manual QA Assessment**

| Document | Test Execution Report |
|----------|------------------------|
| Project | SunFi Customer Acquisition Journey |
| Tester | Rita Ntekim |
| Test Type | Manual QA Testing |
| Version | 1.0 |
| Date | July 2026 |
| Status | Completed |

---

## Objective

This report summarizes the outcome of manual testing conducted on SunFi's customer acquisition journey. The objective was to validate key user workflows, identify functional defects, and evaluate the overall user experience across supported environments.

---

## Test Environment

| Item | Details |
|------|---------|
| Testing Type | Manual Functional & Usability Testing |
| Browser 1 | Google Chrome (Latest Stable Version) |
| Browser 2 | Microsoft Edge (Latest Stable Version) |
| Mobile Testing | iPhone 14 Viewport |
| Test Period | July 2026 |

---

## Test Scope

The following areas were covered during testing:

- Customer acquisition journey
- Lead generation workflow
- Form validation
- Navigation behaviour
- Recommendation flow
- Customer support functionality
- Cross-browser compatibility
- Mobile responsiveness
- General usability

---

## Execution Summary

| Metric | Result |
|---------|--------|
| Total Test Cases Executed | 12 |
| Passed | 8 |
| Failed | 4 |
| Blocked | 0 |
| Not Executed | 0 |
| Execution Rate | 100% |
| Pass Rate | 66.7% |

---

## Failed Test Cases

| Test Case ID | Test Scenario | Status | Related Defect |
|--------------|---------------|--------|----------------|
| TC-009 | Verify in-app Back navigation preserves customer journey | ❌ Failed | SF-001 |
| TC-010 | Verify Need Help / Chat with Us widget functionality | ❌ Failed | SF-002 |
| TC-011 | Verify recommendation review modal is scrollable | ❌ Failed | SF-003 |
| TC-012 | Verify Clear All removes selected appliances | ❌ Failed | SF-004 |

---

## Defect Summary

| Severity | Count |
|----------|------:|
| High | 2 |
| Medium | 2 |
| Low | 0 |
| Total | 4 |

---

## Overall Assessment

The primary customer acquisition workflow is functional, allowing users to successfully progress from the landing page through lead submission and recommendation generation.

Testing identified four confirmed defects affecting navigation, customer support accessibility, modal interaction, and appliance selection management. While these issues do not prevent users from completing the overall journey in every case, they introduce unnecessary friction that could impact user confidence and lead conversion.

In addition to the confirmed defects, several usability observations were documented to highlight opportunities for improving clarity, reducing cognitive load, and enhancing the overall customer experience.

---

## Recommendation

Based on the findings from this assessment, the customer acquisition journey is suitable for production use but would benefit from resolving the identified functional defects and addressing the documented usability observations to improve the overall user experience.
