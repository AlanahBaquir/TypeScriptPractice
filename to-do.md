# To-Do

First, install **Bootstrap** *(for Angular, not the native)* and **Angular Material**.

## Sitemap

 - **Login Page** - First page to show IF NOT AUTHENTICATED.
    - Should contain the Announcements Component.
    - Should contain the following form:
      - username (input)
      - password (input)
      - login (button) - *redirects to Home Page after logging in.*
      
![Login Page](https://share.balsamiq.com/c/gNpahHPF8Hb2b2bFgmauV2.png)

 - **Home Page** - First page to show IF AUTHENTICATED.
    - Should contain the Navbar Component.
    - Should contain the Announcements Component.

![Home Page](https://share.balsamiq.com/c/eKtboSxPEF55S2bjo6Qo6s.png)
 - **Students List Page** - Displays list of Students
    - Should contain the Navbar Component.
    - Should contain list of students with the following for each student:
      - link (name of student) - *clicking name redirects to Student View Page*.
      - checkbox (marks student to deletion)
    - Should contain an Add Student button.
      - Clicking Add Student should popup dialog.
    - Should contain a Delete Student(s) button. 
      - Enables only when 1 or more checkbox is enabled.
      - Removes the student(s) from the list.

![Students Page](https://share.balsamiq.com/c/fDLSJiSS8mNEpEjTyNQVTF.png)
 - **Student View Page** - Must have 2 modes, View and Edit.
    - Must have a button to switch modes. By default, the button's label should be "Edit" becomes "Save" once clicked.
    - View Mode (default mode)
      - All the student's data in plain text.
    - Edit Mode
      - All the student's data but with inputs.
    - Student properties are: *name, age, gender, and grade*.

![Student View](https://share.balsamiq.com/c/o8r5oXnpEJsyg6icywjebx.png)
## Components

 - **Navbar Component**
    - Home Link that redirects to /home.
    - Student Link that redirects to /student.


 - **Announcements Component**
    - Just a static array of object. Object properties should be:
      - Title 
      - Content

## Dialog

 - **Add Student**
    - Contains a form with the following:
      - name (input)
      - age (input)
      - gender (input)
      - grade (selection) [values: 1,2,3,4,5,6]
      - submit (button)
      - close (button) - should close the entire dialog.

![Add Student Dialog] (https://share.balsamiq.com/c/knQghQ2FnnmN45g3GGUkcR.png)