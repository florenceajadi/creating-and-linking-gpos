<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Creating and Linking GPOs</h1>
This tutorial outlines the implementation of creating and linking GPOs in Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create and link GPOs](https://youtu.be/cG7M3Z-Cek4)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
  
<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a new GPO
- Link GPO to a domain
- Link an existing GPO to two domain folders
- Add user to GPO delegations and set permission level


<h2>Deployment and Configuration Steps</h2>

<p>
<img src="" height="80%" width="80%""/>


</p>
<p>
Diagram
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/3331bdfe-e7fc-4c60-8382-7cdc5b633d25" height="80%" width="80%""/>
<img src="https://github.com/user-attachments/assets/1b9dcd7d-d744-451a-a2fd-46e3b0ea1872" height="80%" width="80%"" />


</p>
<p>
Created a new GPO within mycybercat.com domain. You can see the new GPO 'TestGPO' is also in Group Policy Object folder.
</p>
<br />

<p>
  <img src="https://github.com/user-attachments/assets/32f4d038-ce09-4596-b3dd-b6c287ad33dd" height="80%" width="80%" />
</p>
<p>
Created a new GPO within the GPO folder and named it 'TestGPO'. I am going to link mycybercat.com domain to TestGPO.
</p>
<p>
   <img src="https://github.com/user-attachments/assets/0caa11a0-4507-477d-8063-3247ae5b097a" height="80%" width="80%""/>
</p>
<p> It is now linked!</p>
<br />

<p>
  <img src="https://github.com/user-attachments/assets/b63ffe74-b091-4dc5-a5c0-7d627e6a0758" height="80%" width="80%""/>
  <img src="https://github.com/user-attachments/assets/1dc40a57-ae8c-4234-be23-dea5cf2edd56" height="80%" width="80%""/>
</p>

<p>
  I am also going to Link an Existing GPO on Domain Computers and Domain Users to 'TestGPO'.
</p>
<p>
  <img src="https://github.com/user-attachments/assets/ea5d706f-a3d0-4873-8095-eb0cb1b27a58" height="80%" width="80%" />

</p>
<p> We also want to apply filtering to Adminstrators as well </p>
<br />


<p>
<img src="https://github.com/user-attachments/assets/d703cf4d-054e-4f85-bd66-89384c6dc25d" height="80%" width="80%""/>  
<img src="https://github.com/user-attachments/assets/0de71c39-9ffe-4af4-970b-381d08c44c6a" height="80%" width="80%" />
<img src="https://github.com/user-attachments/assets/9056abe7-c1d3-4166-9298-673427d8c2b3" height="80%" width="80%" />
</p>

  
<p>
We want to add the user Jeremy Collins and assign permission level. Jeremy Collins is now in charge of editing settings. </p>
