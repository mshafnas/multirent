How to run the application
Step 1: Create the database using the database script in phpMyAdmin.
Step 2: Add the following text "127.0.0.1 localhost 
                                127.0.0.1 multirent.lk"  in C:\Windows\System32\drivers\etc\hosts file.
Step 3: Run MYSQL Server.
Step 4: Delete storage file in project "App\Public" and Run "php artisan storage:link" command in using CMD.
Step 5: Run "php artisan serve" command to run the project. then simply copy the url and paste it on the browser.
