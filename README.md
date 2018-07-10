# Dynatrace Managed Autologin

Simple HTML page to perform automatic login and redirect to Dashboard. Edit the HTML and supply:

* *$URL* with your Dynatrace Managed tenant URL such as https://dynatrace/e/01234567-1234-abcd-1234-1234567890ab/login
* *$USER* with your username such as admin
* *$PASSWORD* with user password
* *$BACKURI* with the URL part of the dashboard link such as #dashboard;id=abcdef12-3456-7890-1234-abcdef123456;gtf=l\_2\_HOURS

Page then performs HTML post to login to Dynatrace Managed instance and redirects to the dashboard of your choice.