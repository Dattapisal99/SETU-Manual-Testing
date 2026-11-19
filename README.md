<h1>SETU Project – Manual Testing</h1>
Project Overview
SETU is a manual software testing project documented in an Excel test execution workbook. This repository is intended to present the QA testing scope, test scenarios, execution results, and defect observations for the Login, Doctor, and Mental Health areas of the application.
Important: Upload this project only if you are authorized to share the workbook and project information. If the application or workbook contains confidential company information, keep the GitHub repository Private and remove sensitive data before sharing it.

Project Details
Item	Details
Project name	SETU
Testing type	Manual Testing
Test documentation	Excel test execution workbook
Test areas	Login, Doctor, Mental Health
Execution dates recorded	10–12 August 2026
Test cases recorded	103
Status recorded	72 Pass, 31 Fail


Modules Covered
1. Login
- Login page and required UI elements
- Mobile number validation
- Invalid and blank mobile number handling
- OTP navigation
- Profile photo options and update flow
2. Doctor
- Doctor listing page and page heading
- Doctor and specialization search
- Symptom-based doctor search
- Gender filtering
- Consultation fee display and consistency
- Price sorting (Low to High and High to Low)
- Clear/reset filter behavior
- Specialization cards and doctor listings
- Consultation/booking navigation
- My Cases card display
3. Mental Health
- Mental Health landing page
- Profile selection flow
- Self-assessment options
- Sleep Quality Assessment
- Happiness Scale
- Anger Assessment
- Assessment results and history
- Stress Quantification Device section
Test Execution Summary
The following counts are calculated from the Status column in the uploaded workbook. They are recorded results, not an independent re-test.
Module	Total	Pass	Fail
Login	14	14	0
Doctor	69	42	27
Mental Health	20	16	4
Total	103	72	31


Defect Areas Observed
Examples of failed observations recorded in the workbook include:
- Doctor page heading displays “Telemedicine” instead of “Doctors”.
- Search can display unrelated specializations for an invalid search term.
- Doctor gender filters do not consistently exclude non-matching doctors.
- Consultation fees can be blank or change after navigation/refresh.
- Price sorting and filter reset behavior do not consistently match expected results.
- Some specialization cards have missing images or no doctor results.
- My Cases consultation cards can be partially cut off.
- Happiness Scale instruction text does not match the assessment.
- Anger Assessment wording/answer options do not match the expected questionnaire.
- The Stress Quantification Device section and its actions appear where the test expectation says they should not.
Refer to the workbook for the exact test steps, expected results, actual results, and recorded status.
Test Case Documentation
The workbook uses these fields:
- Test Scenario ID
- Test Scenario Description
- Test Case ID
- Test Case Description
- Test Steps
- Test Data
- Expected Result
- Actual Result
- Status
- Executed By / Executed Date
- Screenshots
- Developer Remarks and Date
- Developer Screenshot
- Re-Test details and Re-Test Status
Suggested Repository Structure
SETU-Manual-Testing/
├── README.md
├── Test-Cases/
│   └── Setu_10-08-2026.xlsx
├── Test-Summary/
│   └── Test-Execution-Summary.md
├── Bug-Reports/
│   └── Bug-Report-Register.xlsx
└── Screenshots/
    ├── Login/
    ├── Doctor/
    └── Mental-Health/
Only add the folders/files when you have prepared the corresponding materials. Do not upload empty folders or placeholder evidence.
Recommended Testing Documents
1. Test Plan – scope, objectives, approach, environment, entry/exit criteria, and risks.
2. Test Scenarios and Test Cases – the existing Excel workbook.
3. Test Execution Report – module-wise totals, pass/fail counts, and execution dates.
4. Bug/Defect Report – defect ID, title, steps, expected result, actual result, severity, priority, status, and evidence.
5. Screenshots/Evidence – clearly named screenshots linked to the relevant test case or defect.
6. Retesting/Regression Report – fixes retested, results, and regression coverage.
7. Test Closure Report – final status, open defects, limitations, and sign-off, if available.
Notes and Limitations
- The workbook currently records 103 test cases: 72 Pass and 31 Fail.
- The original summary sheet contains formula/reference issues and should be checked before relying on its dashboard.
- Some screenshot cells contain #VALUE! rather than screenshot evidence.
- At least one Login test case and some Mental Health entries have a mismatch between the recorded actual result and Pass/Fail status. Verify these entries before publishing a final report.
- Developer comments and retest fields are largely unfilled in the reviewed workbook. Do not describe defects as fixed or retested unless evidence is added.
- No application version, device/OS matrix, browser matrix, or test environment details were established from the workbook. Add them only if you can verify them.
Tools
- Microsoft Excel – test case documentation and execution tracking
- GitHub – version control and QA portfolio hosting
Author
Manual QA Testing Portfolio – SETU Project

Update this section with your preferred professional profile details before making the repository public.
