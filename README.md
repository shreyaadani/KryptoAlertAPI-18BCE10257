# KyptoAlertAPI-18BCE10257
## ASSESSMENT GIVEN BY KRYPTO COMPANY 
<hr>
Repository consists for 4 files:
  <ol>
  <li> KyptoAlertAPI.ipynb
  <li> MarketPriceCheckandAlert.ipynb
  <li> EmailSender.ipynb
  <li> DATABASE SETUP (.txt) </ol>
  
  
 ## INSTALLATION
 Pull the repository and Check out all the files in your local directory
 ## DATABASE SETUP
 <ul> Create Database Username= postgres and Password=postgres</ul>
 <ul>
  <li>Run PGAdmin(Postgresql)</li>
  <li> Connect to the DB server</li>
  <li> Open query window</li>
  <li> Run all the query provided in DATABASE SETUP file</li> </ul>
        
 <h3>DATABASE CONTENTS</h3>
  <ol>
  <li> TABLE USERDATA : it will hold user credentials and email id
  <li> TABLE ALERT    : it holds all the alerts set by each user and their status
  <li> TABLE ALERTQ   : this table simulates the queue functionality between MarketPriceCheckandAlert and EmailSender
   </ol> 
   
 ## PYTHON APPLICATION SETUP
 
 <ul>
  <li> Start Jupyter Notebook
  <li> Make sure your Jupyter Notebook is running on same system as postgres server
  <li> Open Each Notebook provided in the repostitory and execute </ul>
  
  
  ## TESTING THE API
  
  <h4> CREATALERT API </h4>
  SYNTAX : http://127.0.0.1:5000/alert/create/uid/price
  EXAMPLE : http://127.0.0.1:5000/alert/create/9/778373
  
   
  <h4> DELETEALERT API </h4>
  SYNTAX : http://127.0.0.1:5000/alert/delete/uid/aid
  EXAMPLE : http://127.0.0.1:5000/alert/delete/9/107
  
   
  <h4> LIST ALERTS API </h4>
  SYNTAX : http://127.0.0.1:5000/alert/myalter/uid
  EXAMPLE : http://127.0.0.1:5000/alert/myalert/9
  
  
  
  
  ## INSTRUCTION FOR EMAIL SETUP
<pre> 
Either generate a new email for this purpose 
Go to your Google Account.
On the left navigation panel, choose Security.
On the 'Signing in to Google' panel, choose App passwords. If you don’t see this option:
2-Step Verification is not set up for your account
2-Step Verification is set up for security keys only
Your account is through work, school or other organisation
You’ve turned on Advanced Protection for your account
At the bottom, choose Select app and choose the app that you’re using.
Choose Select device and choose the device that you're using.
Choose Generate.
Follow the instructions to enter the app password. The app password is the 16-character code in the yellow bar on your device.
Choose Done.
</pre>
 <ul>
<li> Update Sender email id and secret key in EmailSender Notebook before execution</ul> 
  
        
 
 

