### [App Name][Stage][Profile Picture]: Double file extension is accepted for profile picture upload.

**Pre-condition:** <br>
User has access to the application and is in the profile settings page.

**Steps to reproduce:**
1. Click the "Upload profile picture" button.
2. Select a file with double extension (e.g., 'image.jpg.png')
3. Click "Upload" button.
4. Observe how the system handles the file.

**Expected Result:** <br>
The system rejects the file and displays an error of "Invalid file format."<br>
[Attached image/recording of expected result]

**Actual Result:** <br>
The system accepts the file with double extension and **does not** display an error of "Invalid file format."<br>
[Attached image/recording of actual result]

**Severity:** Medium <br>
**Priority:** P3 <br>

**Analysis:** <br>
Found during smoke testing for Sprint 123 and might be related to another item's changes (*US123456*).

**Location of Element:** <br>
[Provide the specific link where the bug occured]
