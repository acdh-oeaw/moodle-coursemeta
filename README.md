Course META module for moodle 3.1
Created By Norbert Czirjak

This module is based on the following custom extension:

https://github.com/silecs/moodle-course-custom-fields



Install steps:

1. You need to copy the coursemeta directory to the enrol directory
2. You need to copy the custominfo directory to the lib directory
3. Log on to your site admin and go to the Notifications menupoint. Here the new module will be available, so please click to the "Upgrade Moodle database now" button.
4. Go to the site admin/plugins/enrolments/Manage enrol plugins
5. Search the "Course Custom Fields" line and enable this module. 
6. If you allowed the module then you can reach the module backend menu if you click to the Settings button in the manage enrol plugins menu or now you can find a new admin menupoint: site administration/plugins/enrolments/Course Custom Fields
7. here you can add new fields which will be available on the course editing/adding page.

The Frontend Part:

Go to the courses and add a new course or edit an existing course:
- you will find a Course Custom Fields option in this editing form
- the Course Custom Fields contains the fields what you added to the module in the backend (site administration/plugins/enrolments/Course Custom Fields) 