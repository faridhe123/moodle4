
MOODLE 4.x PROJECT

[//]: # (1. postgres)

[//]: # (2. admin)

[//]: # (3. admin@admin.com)

[//]: # (4. enable no auth)

[//]: # (5. create user = user : User1234_ )

[//]: # (6. Enrol > Self > Allow existing enrolments = Yes)



### Create New Auth Plugins

#### Component
1. Blank structure plate = auth/none
2. ExternalDB structure plate = auth/db
3. DB asbtraction layer = lib/ADOdb

#### Function
1. user_login($username, $password)
2. 

#### Kolom Wajib untuk External DB Authentication
1. username
2. password --> tambahkan hash
3. Firstname
4. Surname
5. email address --> MATIKAN EMAIL CONFIRMATION

#### Extra Steps
1. Email change confirmation --> NO