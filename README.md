NurseApp
========
-- The project is located in PII/NurseApp.
 
-- There is a file called passwords.txt in PII which contains two usernames and passwords:

-- Username: user1
-- Password: password

-- Username: user2
-- Password: password2

--In order to get the saved data from the app, type
* adb pull /data/data/com.example.nurseapp/files/records.txt

-- You can either choose to add a patient through the Add Patient button, or update 
patient's vital signs through the Update Vital Signs button (in Current Patients). The
data is not saved until the Save to File button is clicked.

-- Every time data is saved the older values are retained, and once the data is pulled this
can be seen. After logging in records.txt is automatically loaded.
