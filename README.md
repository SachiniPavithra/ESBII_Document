# ESBII_Document

#01 Creating Windows Instance using AWS account

1.First user has to login to the AWS account using correct username and password. 

![screenshot 208](https://cloud.githubusercontent.com/assets/20767123/17290036/1caf7cb4-57fa-11e6-8043-7b272dcdc21a.png)

2. 	Then click “Launch Instance” button and from the list of AMI s appeared on the screen select “Microsoft Windows Server 2012 R2 Base” AMI to create windows instance.

![screenshot 210](https://cloud.githubusercontent.com/assets/20767123/17290316/7c8c283e-57fb-11e6-93d8-80ed2bf86eec.png)

3.	Select the default instance type given and click “Preview and Launch” button

![screenshot 211](https://cloud.githubusercontent.com/assets/20767123/17290346/a075b008-57fb-11e6-8842-0b5cbfe982d1.png)

![screenshot 212](https://cloud.githubusercontent.com/assets/20767123/17290380/c2d0b724-57fb-11e6-85a9-c9a0f3620dda.png)

4.	Then after creating the instance next step is reviewing the instance created. Click the “Launch” button to continue. 

![screenshot 213](https://cloud.githubusercontent.com/assets/20767123/17290484/3f5d316e-57fc-11e6-9f49-d4e277a28406.png)

5.	Next user has to create a new key pair to launch the newly created instance by providing a name to the key pair. 

![screenshot 214](https://cloud.githubusercontent.com/assets/20767123/17290511/66790df4-57fc-11e6-844d-3a4b31449330.png)

6.	Next click “Download Key pair” button to download the key pair to your system and “Sachini.pem” file will be downloaded. 

![screenshot 214](https://cloud.githubusercontent.com/assets/20767123/17290511/66790df4-57fc-11e6-844d-3a4b31449330.png)

7.	Then created instance will be launched as shown below and click the “View instance” button to view the instance you created. 

![screenshot 215](https://cloud.githubusercontent.com/assets/20767123/17290567/b9bc03a4-57fc-11e6-8be0-c11dfa3d2a0b.png)

8.Then to connect to the instance click “Connect” button. To get connect to the instance first user should get a password. 

![screenshot 217](https://cloud.githubusercontent.com/assets/20767123/17290588/d93dab56-57fc-11e6-9ca9-c7a02f6bf9e1.png)

9. Next to get the password should provide the path of “Sachini.pem” file and decrypt the password. 

![screenshot 218](https://cloud.githubusercontent.com/assets/20767123/17290618/09d780a2-57fd-11e6-89b4-650d3e6d6881.png)

![screenshot 219](https://cloud.githubusercontent.com/assets/20767123/17290649/303d1fa4-57fd-11e6-912d-c3d6359d40ac.png)

10.Then user can get the password to access the instance and click “Download Remote Desktop File” button to download the file. 

![screenshot 220](https://cloud.githubusercontent.com/assets/20767123/17290686/5bc9159c-57fd-11e6-9f88-d42fe0c57aab.png)

11. Then user can access to the created Windows instance AMI.

![capture](https://cloud.githubusercontent.com/assets/20767123/17290835/1ab080ee-57fe-11e6-8135-cbf911a3cb3c.PNG)

#02 Creating Linux Instance using AWS account. 

1.	First user has to login to the AWS account and then click “Launch Instance” button and from the list of AMI s appeared on the screen select “Amazon Linux AMI 2016.03.3 (HVM)” AMI to create linux instance. 

![screenshot 221](https://cloud.githubusercontent.com/assets/20767123/17290896/58fdd414-57fe-11e6-9ddf-86e97256adf8.png)

2.	Select the default instance type given and click “Preview and Launch” button. 

![screenshot 222](https://cloud.githubusercontent.com/assets/20767123/17290918/80d4e0ae-57fe-11e6-9fca-4e02179c3d61.png)

3. Then after creating the instance next step is reviewing the instance created. Click the “Launch” button to continue.

![screenshot 223](https://cloud.githubusercontent.com/assets/20767123/17290962/d44e5a8a-57fe-11e6-8625-b0d7de33f329.png)

4.Next user has to create a new key pair to launch the newly created instance by providing a name to the key pair and then click “Download Key pair” button to download the key pair to your system and “Sachini_Linux.pem” file will be downloaded.

![screenshot 225](https://cloud.githubusercontent.com/assets/20767123/17290999/01b02b98-57ff-11e6-94fa-84db60ddac1c.png)

5. Then created instance will be launched as shown below and click the “View instance” button to view the instance you created. 

![screenshot 226](https://cloud.githubusercontent.com/assets/20767123/17291032/2822e720-57ff-11e6-8d84-77c3c975f612.png)

![screenshot 227](https://cloud.githubusercontent.com/assets/20767123/17291051/44a8d29c-57ff-11e6-82c9-55b900b905b2.png)

6. Then download putty.exe and puttygen.exe files. 

![screenshot 228](https://cloud.githubusercontent.com/assets/20767123/17291081/745e61aa-57ff-11e6-9217-eac7b8057fd9.png)

7. Next open the puttygen.exe file and click “Generate” button to get the putty key. Under type of key to generate, select SSH-2 RSA. 

![screenshot 249](https://cloud.githubusercontent.com/assets/20767123/17291124/b67f1340-57ff-11e6-8e60-55f7ed83a1cb.png)

8.Click “Load” button and locate Sachini.pem file and click “Open”. 

![screenshot 229](https://cloud.githubusercontent.com/assets/20767123/17291158/d5f0136e-57ff-11e6-99c9-7c18408c4edd.png)

9. After generating the putty key it should be saved by clicking “Save Private Key” to use it in putty. Click “Yes” to continue and define the place where the putty key should be saved. 

![screenshot 230](https://cloud.githubusercontent.com/assets/20767123/17291180/f7ac6b56-57ff-11e6-9ea0-908fececa12a.png)

10. Then open the putty.exe file to connect to the linux instance and give the public DNS as hostname and provide a name to save the creating session and click “Save”. 

![screenshot 231](https://cloud.githubusercontent.com/assets/20767123/17291202/1b86b43c-5800-11e6-811e-6028ef30ddf0.png)

11. Then go to Connection- SSH – Auth to control SSH authentication. 

![screenshot 232](https://cloud.githubusercontent.com/assets/20767123/17291222/428cf078-5800-11e6-96f1-aa5837b740d3.png)

12. Then locate the saved private key to start the linux instance with putty. 

![screenshot 233](https://cloud.githubusercontent.com/assets/20767123/17291282/96439ce4-5800-11e6-9d26-fc87f33a78b6.png)

13. Then the console will appear and user has to login as “ec2-user” to launch the Linux AMI instance.

![screenshot 234](https://cloud.githubusercontent.com/assets/20767123/17291305/b75c8850-5800-11e6-9d42-b307007c454f.png)

![screenshot 236](https://cloud.githubusercontent.com/assets/20767123/17291330/da3d9f76-5800-11e6-8c9a-d9730295850b.png)

#03 Create DB instance using RDS.

1. Click on RDS button

![screenshot 237](https://cloud.githubusercontent.com/assets/20767123/17291353/fbd2c4d6-5800-11e6-9635-36bc6712030b.png)

2 Select MySql and click the select button 

![screenshot 238](https://cloud.githubusercontent.com/assets/20767123/17291373/15f508e2-5801-11e6-8789-baa593df61c4.png)

3 Configure the settings given below

![screenshot 241](https://cloud.githubusercontent.com/assets/20767123/17291403/397cf680-5801-11e6-9cd8-f717700c727f.png)

4 Configure the settings given below and Launch DB Instance.

![screenshot 243](https://cloud.githubusercontent.com/assets/20767123/17291427/6b950ba8-5801-11e6-90dd-e2898e21ee6b.png)

5. User can view the instance by clicking the “View Your DB instance” button 

![screenshot 244](https://cloud.githubusercontent.com/assets/20767123/17291438/891ef1f2-5801-11e6-9415-1d178ab50afe.png)

6 User has to wait for few minutes.

![screenshot 248](https://cloud.githubusercontent.com/assets/20767123/17291456/af6a3ace-5801-11e6-8bfc-3b22b6dd8189.png)

7. Finally user can login to the DB using the given user name and the password

![screenshot 246](https://cloud.githubusercontent.com/assets/20767123/17291486/dc18ce82-5801-11e6-83ba-b49b35d0c25d.png)

![capture2](https://cloud.githubusercontent.com/assets/20767123/17291523/14bc4534-5802-11e6-8904-8b2eda3a0666.PNG)

