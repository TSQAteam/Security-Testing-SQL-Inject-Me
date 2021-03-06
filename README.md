# Security Testing Using SQL Inject Me

- SQL Inject-Me is Firefox Extension used to test for SQL Injection vulnerabilities.
- This vulnerabilites can cause a lot of damage to a web application. 
- A malicious user can possibly view records, delete records, drop tables or gain access to your server. 

# How it works?
 - The tool works by submitting your HTML forms and substituting the form value with strings that are representative of an SQL Injection attack.

 - The tool works by sending database escape strings through the form fields. It then looks for database error messages that are output into the rendered HTML of the page.

 - The tool does not attempting to compromise the security of the given system. It looks for possible entry points for an attack against the system.


# How To Start With SQL Inject Me
For you to start with SQL Inject Me, Just go to your Mozilla Firefox browser and search the SQL   Inject Me addon on google.
   Get add on from here
 https://addons.mozilla.org/en-US/firefox/addon/sql-inject-me/
 
  ![Screenshot of repository size on GitHub](https://github.com/TSQAteam/Security-Testing-SQL-Inject-Me/blob/master/images/1.png)
  
   - Once you are on the said site, Click the Add to Firefox button.Once you are on the said site, Click  the Add to Firefox button.
   - Once the installation was done, message at the top left part of the page will appear to Restart the browser. Click the Restart Now  button.
   
   ![Screenshot of repository size on GitHub](https://github.com/TSQAteam/Security-Testing-SQL-Inject-Me/blob/master/images/1_2.png)
   
   
   Click  the Tools > SQL Inject Me > Open
   
   ![Screenshot of repository size on GitHub](https://github.com/TSQAteam/Security-Testing-SQL-Inject-Me/blob/master/images/2.png)
 
   - After that,  SQL Inject Me Sidebar will appear at the left part of the page.
   - As you notice, It contains several input forms of the website you are currently in and the forms that you're going to inject scripts. 
      
   - Select the available scripts on the dropdown lists that you prefer. 
   - Before executing the test, check the checkbox beside the dropdown list. Once you are done, click the Execute button at the top part to execute the test.
   
   
   
  ![Screenshot of repository size on GitHub](https://github.com/TSQAteam/Security-Testing-SQL-Inject-Me/blob/master/images/3.png)

   - The test scripts are currently running. Once all the scripts were done executing, a new tab will appear to display the results of the test if the website has SQL vulnerability.
   
  ![Screenshot of repository size on GitHub](https://github.com/TSQAteam/Security-Testing-SQL-Inject-Me/blob/master/images/4.png)
  
  
   - And that's it. SQL Injection is now easy. 
   - A new tab will display the result of testing if the website you're testing is vulnerable to sql injection. 
   - It contain number of Failures, Warnings and Passes.
  
  
   ![Screenshot of repository size on GitHub](https://github.com/TSQAteam/Security-Testing-SQL-Inject-Me/blob/master/images/5.png)
   
   - Click  the Tools > SQL Inject Me > Open
   
      ![Screenshot of repository size on GitHub](https://github.com/TSQAteam/Security-Testing-SQL-Inject-Me/blob/master/images/6.png)
      
   -  In Sql injection settings  - It will list all the queries inject on the form. Here we can add / Remove based on our req.
   
   
   # Demo Video:
   
   Check here for demo video
    https://github.com/TSQAteam/Security-Testing-SQL-Inject-Me/blob/master/video/demo_video.mp4
   
   
   # Note:
   - It will not support recent firefox version, Now I have used 56.0.1
   - This SQL Injection Test should be tested only in the test environment. Before performing this testing, Can take Db backup. Since it affects the data in db, large data gets inserted.
   
