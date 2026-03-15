## Bug Report Format: *[App][Accessibility][Environment][Feature]: Short description of the bug.*

### [App Name][Accessibility][Stage][Add Admin]: Add admin button is not visible on 320x256 screen size.

**Pre-condition:** <br>
User has access to the application and is in the administrators page. <br>
Screen size is set to 320x256 (from developer tools simulator). <br>
![320x256 setup](images/320x256-setup.png)
![320x256 developer tools simulator](images/320x256.png)

**Steps to reproduce:**
1. Go to the administrators page.
2. Set the screen size to 320x256 using developer tools simulator.
3. Observe the visibility of the "Add admin" button.

**Expected Result:** <br>
The "Add admin" button is visible. <br>
[Attached image/recording of expected result]

**Actual Result:** <br>
The "Add admin" button is **not** visible. <br>
[Attached image/recording of actual result]

**Analysis:** <br>
Found during accessibility testing for Sprint 123.

**Location of Element:** <br>
[Provide the specific link where the bug occured]
