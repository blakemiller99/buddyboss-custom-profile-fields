# buddyboss-custom-profile-fields
Adds custom profile fields into the Members directory feed and also the profile page. 

This example adds 2 fields "Company" and "Title" underneath the user's name, but just above the 'last-activity'

1. Add or Create members-loop.php to your child theme: /buddypress/members/members-loop.php
2. Starting at line Add desired fields 'xprofile_get_field_data'
3. Each field is wrapped in a div class to style it accordingly.
4. Add custom css styling div class(es). You can add it to the child theme style.css, or the site customizer CSS or other area such as Custom CSS plugin.
