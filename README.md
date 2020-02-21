# EZVETERAN-JavaSwingProject
Java Application aims at providing help and assistance to veterans

<b>Problem Statement:</b><br>
Veterans face following problems after they leave Armed Forces:<br>
Relocating, living independently for the first time<br>
No access to adequate mental healthcare<br>
No access to adequate Higher Education<br>
These  major  life  changes  are  challenging  for  military  veterans,  just  as  they  are challenging for anyone. <br>
The challenges associated with these changes are not easily studied or  represented, in  part  because  they  are  not  captured  by medical  diagnoses,  and in  part because it is  difficult  to  draw meaningful lines  between  physiological, psychological,  and social problems. 
Moreover, this stuff of everyday life tends to be overshadowed by veterans’ other,  more  extreme,  experiences  in  combat.<br>
<br>

<b>Solution:</b>
Develop, design and deploy a multi-party organization that can connect the veteran to one or more organizations<br>
Incorporate Medical, Education, Employment & Housing Enterprises.<br> 
Multiple organizations under the said enterprises under which the veteran can apply for training, seek medical help etc<br>
Organizational users can review applications/requests and approve/reject the same - or if required route them to other organizations under a different enterprise
<br>

<b>Features:</b><br>
<b>Ease of Access</b> : User can raise multiple requests, under multiple categories - Medical, Education or Housing. The user can perform all this straight from the User Dashboard
<br>
<b>Real Time Notifications </b>: User is notified of all requests raised, updates to requests raised - in real time via Notifications delivered through Telegram & Email. Telegram’s API and SMTP Protocol has been leveraged to push notifications in real time.
<br>
<b>Real Time Reporting </b> : PowerBI has been leveraged to enable real time reporting. The Sysadmin can view the total number of requests raised, requests pending resolutions etc from a Web Browser or Smartphone
<br>
<b>User Tracking</b> : All Admins can view and track the veteran location using a single click. This has been done by using Google Map’s API

This is a java project executed in order to provide basic services to veterans who , for whatsoever reason are not able to avail these services. So, this project contains six organization in and between which service requests are raised by the user that is the veteran and resolved by the admins of each respective organizations. These organizations are MentalHealthCare PhysicalHealthCare VocationalEducation GraduateEducation PermanentHousing TemporaryHousing

The end user is a veteran or a guest who can register a veteran on their behalf.

How to execute the project?

Install and setup netbeans on your system.

File -> Open Project -> EZVeteran

You will find there are errors in the project. This error is due to a jar file we have used for implementing email. If you create a veteran login with your email you will receive emails of service requests raised by you. So, to resolve this error you will have to right click on the project name on the left tab in netbeans -> properties -> libraries -> Add jar folder -> Add the mail.jar file present in the folder downloaded-> ok -> Clean and build the project and the errors should be resolved.

Run the project

The database used by us is DB4O. We have saved a few logins to save the trouble for you to create all admins and logins and because of this reason due to an exception you will not be able to access the admin page to create all the enterprise and organizational admins. The following are the usernames and passwords foreach admin :

Mental healthcare admin login Username : mhc Pwd : mhc

Physical healthcare admin login Username : phc Pwd : phc

Vocational Education admin login Username : vs Pwd : vs

Graduate Education admin login Username : gs Pwd : gs

Permanent Housing admin login Username : ph Pwd : ph

Temporary Housing admin login Username : th Pwd : th

Veteran login Username : a Pwd : a

If you want to access the admin and create all these admins from the scratch just delete the databank.Db4o file and clean and build and run the project again.

