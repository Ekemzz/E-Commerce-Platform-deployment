# E-Commerce-Platform-deployment
I have been tasked with deploying an e-commerce website using a Git for version controoling, AWS EC2 server as website host, and CLI Linux environment to intiate website collation/preparation.

----------------------------------------------------------------------------------------------------------------------------
TASKS
1. Implement version control with Git.
   
   1.1 Initialize git repository.
   A script was created to carryout the initialization. See images below for execution of the script.

   <img width="803" height="451" alt="image" src="https://github.com/user-attachments/assets/b41d2e37-59b9-429d-ae68-d3476d213300" />
   <img width="808" height="451" alt="image" src="https://github.com/user-attachments/assets/140d6b59-c960-4c61-9186-c0cd5cbbabd1" />
   <img width="797" height="454" alt="image" src="https://github.com/user-attachments/assets/aea4ba16-d53f-4705-8ab9-fca3094ddc6a" />
   <img width="806" height="451" alt="image" src="https://github.com/user-attachments/assets/a1126a00-5ecb-42e3-90dd-ba333ffda9d9" />




***********************************************************************
   Troubleshooting pages for 1.1 Initialize git repository.
   1. Git was unavailable and so the scirpt didnt run. The error was read and git was installed. see image below.

      <img width="803" height="452" alt="image" src="https://github.com/user-attachments/assets/06ee2d72-c016-4289-ab4a-2aea1334db19" />
      <img width="803" height="449" alt="image" src="https://github.com/user-attachments/assets/7ecab2bb-8938-4200-b947-b2abc6ab2d19" />
********************************************************************************
   1.2 Obtain and prepare the e-commerce website template
   Download of the template was initiated. The zipped file was extracted to the project directory.
   <img width="956" height="404" alt="image" src="https://github.com/user-attachments/assets/9eb45a02-0794-40b8-a53a-04c9074ec8b9" />
   <img width="954" height="407" alt="image" src="https://github.com/user-attachments/assets/757422d8-9e9d-4aac-818f-d91ee9f6bb98" />
   <img width="803" height="455" alt="image" src="https://github.com/user-attachments/assets/0728229d-7283-49d1-9d3b-a1cc9eb7ca5b" />
   <img width="805" height="452" alt="image" src="https://github.com/user-attachments/assets/8581675c-3bbb-4cbb-8000-991f1c224409" />

****************************************************************************************
   1.3 Stage and commit the Template to Git.
   Template was added, git global configurations done and the add was commited. 

   <img width="807" height="451" alt="image" src="https://github.com/user-attachments/assets/1a5b607e-c3e4-4f12-b372-d7c00f060295" />
   <img width="816" height="464" alt="image" src="https://github.com/user-attachments/assets/c1690b6a-bfad-4653-8541-9b9055328109" />

*******************************************************************************************

   1.4 Push your code to github repository.
   i. create remote repo on github
   
   <img width="957" height="473" alt="image" src="https://github.com/user-attachments/assets/a820f717-eb6c-4086-8228-6ace8eefbaf0" />

   ii. link your local repo to github

   <img width="809" height="465" alt="image" src="https://github.com/user-attachments/assets/daf3f3eb-a3ab-4a00-9a6e-3f08a30cbb6a" />

   iii. push your code to github. I didnt have authentication to push. so i had to trouble shoot before pushing.
   
   <img width="809" height="465" alt="image" src="https://github.com/user-attachments/assets/54a7aef9-a1a9-418a-acd7-60f96d2a803f" />
   
   <img width="817" height="467" alt="image" src="https://github.com/user-attachments/assets/c1145271-53a3-4f14-b31c-6b396ddb0335" />

   <img width="811" height="469" alt="image" src="https://github.com/user-attachments/assets/483fb199-aa9f-4e32-91c8-904c1c8fa082" />

**************************************************************************************************************************************
2. AWS deployment
   
   2.1 Setup an AWS EC2 instance and connect to it using ssh
   <img width="938" height="439" alt="image" src="https://github.com/user-attachments/assets/ebad90ac-1249-4d14-a099-3d7ecb12ae60" />
   <img width="941" height="358" alt="image" src="https://github.com/user-attachments/assets/d324ad92-75ba-4ea6-a6e3-bee8085dc27e" />
   <img width="959" height="467" alt="image" src="https://github.com/user-attachments/assets/cda44ab5-fa09-44f6-b799-02a94e0a3f8e" />
   <img width="959" height="431" alt="image" src="https://github.com/user-attachments/assets/f4e1f71f-8900-4c92-aa10-cf1b10876a53" />
   
   <img width="959" height="503" alt="image" src="https://github.com/user-attachments/assets/10ac8b5f-d97a-4a56-bbed-50244b9afc75" />
**************************************************************************************************************
   2.2 Clone the repository to the linux server

   <img width="959" height="448" alt="image" src="https://github.com/user-attachments/assets/f9cf9e6a-07d8-4b8e-9002-0de2a43beb2a" />
   <img width="941" height="437" alt="image" src="https://github.com/user-attachments/assets/afea5258-120c-456a-8169-71fb571f8188" />

   Cloning was not straightforward. There is no git installed in the EC2 server. So, the server was updated and git installed. After which, cloing occurs as seen below.
   <img width="953" height="497" alt="image" src="https://github.com/user-attachments/assets/22f55c4c-a2d9-4fb2-a209-134edefdb970" />
   <img width="952" height="505" alt="image" src="https://github.com/user-attachments/assets/c96c754f-7336-4f07-bae0-f67fd81aea1a" />

******************************************************************************************************************
   2.3 Install a Web server on EC2
   I created a script to run the set of commands to install apache.
   
   <img width="949" height="503" alt="image" src="https://github.com/user-attachments/assets/efcc1d32-b002-4c90-94b4-61a53bce2fe0" />
   <img width="959" height="511" alt="image" src="https://github.com/user-attachments/assets/8436238a-a509-40cb-8a53-922232135134" />
   <img width="965" height="434" alt="image" src="https://github.com/user-attachments/assets/93485838-6fa3-4072-b0cf-410442ba30ba" />

   ****************************************************************************************************************************
   2.4 Configure httpd for website.
   >preparing web directory and reloading httpd
   <img width="959" height="506" alt="image" src="https://github.com/user-attachments/assets/8dafabe1-4800-4063-a7c1-978ccd3391e9" />
   <img width="966" height="506" alt="image" src="https://github.com/user-attachments/assets/3457e5c3-6e5d-4b49-993f-eec0f2708161" />

**************************************************************************************************************************

   2.5 Access website on browser. Troubleshooting occured because the website was timing out(connection timeout). The inbound rules had to be updated to include http and httpd access as well as port 80 and 443 respectively. 
   <img width="959" height="509" alt="image" src="https://github.com/user-attachments/assets/ef1a3019-bc64-447e-921f-42785a2666ac" />
   <img width="959" height="477" alt="image" src="https://github.com/user-attachments/assets/3e05a775-be2b-43c7-af8f-fe1c20167263" />
   <img width="956" height="476" alt="image" src="https://github.com/user-attachments/assets/6eb13a9c-cb83-40d0-badb-4829a75d0950" />
   <img width="959" height="472" alt="image" src="https://github.com/user-attachments/assets/ad3097f0-f843-4077-8038-2a94269774a5" />

   <img width="962" height="503" alt="image" src="https://github.com/user-attachments/assets/973092a0-5bb3-4177-b964-b0e27380a01e" />

**********************************************************************************************************************

3. Continuous integration and deployment workflow

   3.1 Developing new features. I added an error.html file for data on errors encountered.
   
   <img width="803" height="455" alt="image" src="https://github.com/user-attachments/assets/d19ebceb-d9c1-4248-8f63-67ccf14e10f6" />
   <img width="920" height="487" alt="image" src="https://github.com/user-attachments/assets/6999ee3a-e6b4-4c80-a19d-ac037fab949c" />
   <img width="818" height="467" alt="image" src="https://github.com/user-attachments/assets/ee77861a-393e-43a9-921b-e8fa1282b2c7" />

   3.2 Version control with git. Deveopment branch was pushed.
   
   <img width="811" height="468" alt="image" src="https://github.com/user-attachments/assets/0687851f-305b-46fe-b2e7-e83e1c714c9f" />

   3.3 Create a pull request and merge
   <img width="816" height="469" alt="image" src="https://github.com/user-attachments/assets/e4cb020b-914c-4f33-b3e1-88193d679f65" />

   3.4 Deploying updates to the production server
   <img width="961" height="440" alt="image" src="https://github.com/user-attachments/assets/41dd0c91-3129-4079-8540-06b0282783be" />
   <img width="959" height="510" alt="image" src="https://github.com/user-attachments/assets/d5909bf0-824f-4033-b5b5-b70c5952efcc" />

   3.5 Testing. It worked
   <img width="932" height="398" alt="image" src="https://github.com/user-attachments/assets/55a22c67-1360-43a3-97ea-2e6c6623d468" />


