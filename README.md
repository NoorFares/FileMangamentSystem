# FileMangamentSystem
# Single-Page Application File repository
When the user makes a request to do service the job controller responds to the request and checks the user permission via the User Auth and it checks from the database the permission and stores the logs for that user, depending on the user permission the request executes. if the user is an admin all services are allowed, if the user is staff limited services are allowed, staff user can classify the files and can Import new version files and export files only. reader users can not do any services they can read only. in the file classification the user can classify on type, size, or custom to both admin and staff.

# API Application
his component contains API and the API contain authentication and security components and the authentication contains key value for each user(username,password)and the key encrypted in the database and the user authenticated himself once and the next time they enter the password only

# DataBASE
the database component contains the file version and the user authentication information and contain the logs
