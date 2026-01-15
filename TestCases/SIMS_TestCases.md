# SIMS Test Cases (Sample)

## Module: Login

| TC ID | Scenario | Steps | Expected Result |
|------|----------|-------|----------------|
| TC_01 | Valid login | Enter valid username & password → Click Login | User should login successfully |
| TC_02 | Invalid password | Enter valid username + wrong password → Login | Error message should display |
| TC_03 | Blank username | Keep username blank → Login | Validation message should display |
| TC_04 | Blank password | Keep password blank → Login | Validation message should display |
| TC_05 | Password masking | Type password | Password should be masked |
| TC_06 | Logout | Click logout | User should logout and redirect to login page |

---

## Module: Student Creation (Admin)

| TC ID | Scenario | Steps | Expected Result |
|------|----------|-------|----------------|
| TC_07 | Add student with valid data | Fill mandatory fields → Save | Student should be created successfully |
| TC_08 | Mandatory field validation | Keep mandatory field blank → Save | Validation message should display |
| TC_09 | Duplicate mobile/email | Add student with existing mobile/email | Proper error should display |
| TC_10 | Search student | Search by name/ID | Correct student record should display |

---

## Module: Fees Payment

| TC ID | Scenario | Steps | Expected Result |
|------|----------|-------|----------------|
| TC_11 | Fees submit | Enter amount → Submit | Payment/fees should be recorded |
| TC_12 | Invalid amount | Enter invalid amount (0/negative) | Validation message should display |
| TC_13 | Receipt generation | Complete fees payment | Receipt should generate/download |
