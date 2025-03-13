# jenkins-scm
 # The Project is freestyle project 
 
 ##  Project  Objective 
 
 The obective of this freestyle project is to automate tasks such as building , testing ,and deploying applications with minimal setup.
 
 ## Step 1 creating a freestyle Project
 - From the dashboard menu on the left side , click on new item
 ![New](./img/1.%20New.png)
 
 - Create a freestyle project and name it "my-first-job
 ![my-first-job](./img/2.%20my%20-first-job.png)
 
  
 ## Step 2 Connecting Jenkins to our source code management
 - Create a new github repository named jenkins-scm with a README.me file
 ![jenkins-scm](./img/3.%20jenkins-scm.png)
 
 - Connect jenkins to jenkins-scm repository 
 ![url](./img/4%20url%20and%20main.png)
 
 ## Step 3 Run Build
 
 - Run build now to connect jenkins to our repository
 
 ![build](./img/5.%20build%20now.png)
 
 - My first build 
 
 ![my first build](./img/6.%20my%20first%20build.png)
 
 
 ## Step 4  Configure Build Trigger
 
 - Click Configure your job and add this configurations
 
 ![build](./img/7.%20build%20triggers.png)
 
 - configure github  webhook on github
 ![github](./img/8.%20github-%20webhook.png)