# PHASE 6: PROJECT TESTING

## Testing Objective

The purpose of testing is to verify that employee data is imported correctly and that existing records are handled properly when the spreadsheet is imported again.

## Test Case 1: New Employee

**Input:** New Employee ID

**Expected Result:** A new employee record should be created.

**Status:** Passed / To be updated after testing
![Test flow](<Screenshot 2026-09-28 172819.png>)

## Test Case 2: Existing Employee with Changed Information

**Input:** Existing Employee ID with changed name or email.
![Test flow](<Screenshot 2026-09-28 192957.png>)
**Expected Result:** The existing employee record should be updated because Coalesce is enabled.

**Status:** Passed / To be updated after testing
![Test flow](<Screenshot 2026-09-28 173128.png>)
## Test Case 3: Same Data Imported Again

**Input:** Previously imported identical data.

**Expected Result:** The records should not create unnecessary duplicate records.

**Status:** Passed / To be updated after testing
![Test flow](<Screenshot 2026-09-28 173335.png>)
## Test Case 4: Reports
![Test flow](<Screenshot 2026-09-28 192533.png>)
Verify that:

* Department report displays employee distribution.
* Location report displays employee distribution.
* Employee List Report displays employee information.
![Test flow](<Screenshot 2026-09-28 173633.png>)
## Testing Result
![Test flow](<Screenshot 2026-09-28 174247.png>)
The project document demonstrates inserted, updated and ignored records through Transform History after testing repeated imports.
![Test flow](<Screenshot 2026-09-28 175010.png>)
