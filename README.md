<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (25H2)

<h2>List of Prerequisites</h2>

- Functional computer
- Adequate storage space

<h2>Installation Steps</h2>

<p>
<img width="794" height="197" alt="image" src="https://github.com/user-attachments/assets/f936c173-4343-4fc7-a286-16b08669766f" />

</p>
<p>
  <img width="194" height="44" alt="image" src="https://github.com/user-attachments/assets/9ed83504-380e-45fb-97ce-e007052f14a6" />

First, download the files from the following link on the device you would like osTicket to be installed on. <a href="https://drive.usercontent.google.com/download?id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD&export=download&authuser=0">osTicket-Installation-Files.zip</a>.</h1>
</p>
<br />

<p>
<img width="726" height="630" alt="image" src="https://github.com/user-attachments/assets/64eefb69-c1bb-48b6-8fd9-2c9dda7e0429" />


</p>
<p>
Next, search "Control Panel" in the Windows search bar and run the program.
</p>
<br />

<p>
<img width="1035" height="580" alt="image" src="https://github.com/user-attachments/assets/8ce98859-ebec-438a-b5f9-7c472ded2f3b" />
  
<img width="269" height="90" alt="image" src="https://github.com/user-attachments/assets/075a7409-786f-448d-8bed-576b605487de" />
</p>
<p>
Third, you can go to "Uninstall a program" and open it.
</p>
<br />
</p>
<br />

<p>
<img width="1037" height="587" alt="image" src="https://github.com/user-attachments/assets/816e544f-ab11-4b44-b700-3c60bca3849c" />
</p>
<p>
The next step is to click on "Turn Windows features on or off"
</p>
<br />
</p>
<br />

<p>
<img width="393" height="286" alt="image" src="https://github.com/user-attachments/assets/d541539c-b5f0-4824-83cb-20645ab2a01b" />
<p>
<img width="378" height="197" alt="image" src="https://github.com/user-attachments/assets/83c59ca5-178b-4616-bfc1-f24cfeeb5a01" />
<p>
<img width="389" height="339" alt="image" src="https://github.com/user-attachments/assets/70c245b8-c4dd-4398-9592-c4a740760ba3" />



<p>
After that, you can check "Internet Information Services". There is a plus to the left side that you can click and expand the category. Then you can click the plus next to World Wide Web Services, then the plus next to Application Development Features and select CGI.
</p>
<br />
</p>
<br />

<p>
<img width="409" height="198" alt="image" src="https://github.com/user-attachments/assets/e03b3822-9a83-4458-b224-496b1853682c" />
</p>
<p>
Go to the file that we downloaded before and double click and install the PHPManager file.
</p>
<br />
</p>
<br />



<p>
<img width="407" height="196" alt="image" src="https://github.com/user-attachments/assets/b1e10b36-2d69-43b1-b14f-625d038d5b7b" />
</p>
<p>
You then have to install the rewrite module as shown in the picture.
</p>
<br />



<p>
<img width="396" height="548" alt="image" src="https://github.com/user-attachments/assets/f2952caf-6cce-40fd-9128-f7c7c991b329" />
</p>
<p>
Then, open a separate file explorer window and go to your C: drive. You need to create a file and name it "PHP".
</p>
<br />



<p>
<img width="395" height="302" alt="image" src="https://github.com/user-attachments/assets/ca2688ed-b5ae-4d22-ac47-371d91580d03" />
<p>
<img width="415" height="373" alt="image" src="https://github.com/user-attachments/assets/200dd050-33fd-464f-b7d0-cbb8dd2705ed" />
</p>
<p>
Open the previously downloaded files and extract the zipped php file into that folder we just created.
</p>
<br />



<p>
<img width="403" height="236" alt="image" src="https://github.com/user-attachments/assets/07cd3bdc-feb9-48a6-a625-bc6124f3f46c" />
</p>
<p>
Double click and install the VC_redist file in the collected files
</p>
<br />



<p>
<img width="399" height="149" alt="image" src="https://github.com/user-attachments/assets/715020fa-a261-4846-b5c9-a684cf3d4440" />
<p>
<img width="452" height="354" alt="image" src="https://github.com/user-attachments/assets/f2c499fa-e675-4622-b962-c2c4c7b43589" />
</p>
<p>
<img width="460" height="348" alt="image" src="https://github.com/user-attachments/assets/b04195fd-ef29-4071-8476-d099e47af281" />
<p>
Then double click and install the MySQL file. When it asks what type of setup you want to do, choose "Typical". Launch the app and chose "Standard configuration".
</p>
<br />



<p>
<img width="464" height="353" alt="image" src="https://github.com/user-attachments/assets/a4d0ac2b-f9a0-4826-946d-9f2f88316fe8" />
</p>
<p>
When you get to this screen type "root" all lowercase in both boxes (typically you would not do this in real life but this is a demonstration). Then just finish installing it and click "Execute" and click "Finish" once it's done.
</p>
<br />



<p>
<img width="412" height="339" alt="image" src="https://github.com/user-attachments/assets/fd9a51f0-c335-40f8-9c2c-3cd3548d7115" />
</p>
<p>
<img width="860" height="574" alt="image" src="https://github.com/user-attachments/assets/fe01a518-de4e-45a4-bde4-3d645e30a54e" />
<p>
<img width="658" height="285" alt="image" src="https://github.com/user-attachments/assets/de6c91c5-f107-4db4-8e5e-ffe95fc6e33e" />

Click the windows start menu and type "iis" and run the program shown as an administrator. Then click on the PHP Manager box as shown. Click "Register new PHP version" and click the three dots.
</p>
<br />



<p>
<img width="860" height="574" alt="image" src="https://github.com/user-attachments/assets/fe01a518-de4e-45a4-bde4-3d645e30a54e" />
</p>
<p>
<img width="658" height="285" alt="image" src="https://github.com/user-attachments/assets/de6c91c5-f107-4db4-8e5e-ffe95fc6e33e" />
<p>
<img width="472" height="185" alt="image" src="https://github.com/user-attachments/assets/e1f3b797-42d0-45da-b52b-bc1bab28305a" />
<p>
<img width="396" height="436" alt="image" src="https://github.com/user-attachments/assets/92acf79e-d2ab-43a4-bb0f-ee357df3f3bb" />
<p>
Then click on the PHP Manager box as shown. Click "Register new PHP version" and click the three dots. Open the PHP folder in your C: drive and double click the "php-cgi" file and click "ok".
</p>
<br />


<a id="top"></a>
<p>
<img width="284" height="423" alt="image" src="https://github.com/user-attachments/assets/230ababd-5fe0-4c8f-868f-4f4f1c3206c6" />
</p>
<img width="307" height="378" alt="image" src="https://github.com/user-attachments/assets/268bcd07-dd38-42dc-b7c7-dfdfe5739b7e" />
<p>
Now, we need to reload IIS, right click the osticket-vm and shown and click "Stop". Wait a couple seconds for it to stop and right click it again and click "Start"
</p>
<br />



<p>
<img width="394" height="229" alt="image" src="https://github.com/user-attachments/assets/30080cda-c4b0-4068-b34b-f0418f2fefa7" />
</p>
<p>
Extract the osTicket zip folder into the same folder with all the files and open it. 
</p>
<br />



<p>
<img width="406" height="175" alt="image" src="https://github.com/user-attachments/assets/82f4ec4b-8bf4-4db4-9d5b-8dfe1dd07aa9" />
</p>
<img width="512" height="152" alt="image" src="https://github.com/user-attachments/assets/5b2c4e90-849c-4098-89b1-4c9fa8f9001a" />
<p>
  <img width="399" height="206" alt="image" src="https://github.com/user-attachments/assets/9f41cf4c-6385-40e8-8c9d-87f0b7297c73" />

We then have to open the folder location as shown in the picture, and copy the upload folder from the previous folder. Remane the upload folder to "osTicket". Then reload the IIS server [as shown previously](#top).
</p>
<br />



<p>
<img width="856" height="277" alt="image" src="https://github.com/user-attachments/assets/4a392883-b66b-4e68-93c7-c84a5e129f0d" />
</p>
<img width="793" height="743" alt="image" src="https://github.com/user-attachments/assets/487f2d24-6323-48cf-9994-88c21df1b82a" />
<p>
Press the down arrow of osticket-vm, Sites, Default web site, and click on osTicket.  On the right side of the screen, there is a button that is called Browse. Click it and it should open a page in your preferred search engine. 
</p>
<br />



<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
