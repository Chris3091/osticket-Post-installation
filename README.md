<img width="440" height="250" alt="image" src="https://github.com/user-attachments/assets/6627290d-9da4-40a3-af30-ec4343ddae01" />

# osTicket Post-Installation

First, you need to login to the osTicket website using the admin login. http://localhost/osTicket/scp/login.php

<img width="669" height="477" alt="image" src="https://github.com/user-attachments/assets/7198bcef-ce0c-43c1-bce7-4e871ec32a6a" /> 

Next, open up a second tab for create and submitting tickets. http://localhost/osTicket

<img width="1112" height="415" alt="image" src="https://github.com/user-attachments/assets/38dc4c5b-69d9-4442-980f-90e4893a2e53" />

Next, You have to acknowledge the panels of Admin and Agents. Admin have more access than agents. Agents have significantly less access than admin.

<img width="1201" height="545" alt="image" src="https://github.com/user-attachments/assets/29667bae-5964-4daa-b3ca-87a483f78e79" />

First, In the Admin panel we are going to assign roles (grouping permissions) Admins -> Agents -> Roles

<img width="1231" height="525" alt="image" src="https://github.com/user-attachments/assets/47936fda-99e7-4063-b241-87ffcce36f9f" />

Next, Make a new role called "Supreme Admin". Click all the boxes under "Tickets, Tasks, and Knowledgebase."

<img width="1069" height="470" alt="image" src="https://github.com/user-attachments/assets/37909a0e-5186-43ae-bde1-0976d12b1bba" />
<img width="702" height="590" alt="image" src="https://github.com/user-attachments/assets/71d3ecb2-3a0d-4282-8a52-b5cf46d2d903" />
<img width="714" height="529" alt="image" src="https://github.com/user-attachments/assets/fc63ef9b-4d55-478f-8a83-164240b1cc0d" />
<img width="852" height="341" alt="image" src="https://github.com/user-attachments/assets/61bf88ca-ee55-4fc9-a155-46c89d313b72" />

Next, Configure Departments  (Ticket Visibility, Help Desk vs SysAdmins, vs Networking) Admin Panel -> Agents -> Departments

<img width="1227" height="442" alt="image" src="https://github.com/user-attachments/assets/4e314639-abdb-4213-9e40-fe263416ca69" />

Next, Add a new Department and the new department will be called SysAdmin and create new department.

<img width="1220" height="644" alt="image" src="https://github.com/user-attachments/assets/06afbe89-14e7-4c5c-b990-9594adfc83a2" />

Once, your done with that your department tab will be looking like this 

<img width="1275" height="437" alt="image" src="https://github.com/user-attachments/assets/be5b16de-abef-4b8e-bc5a-42dac87d3935" />

Next, Configure Teams. Admin Panel -> Agents -> Teams (Pull Agents from different Departments). Add a new team and name it Online Banking

<img width="1279" height="860" alt="image" src="https://github.com/user-attachments/assets/1eb04363-71c1-4e6c-8ba6-678555632bff" />

Next, we going to allow anyone to create a ticket. Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets) and save changes.
Registration Required: Require registration and login to create tickets 

<img width="1292" height="671" alt="image" src="https://github.com/user-attachments/assets/6bd7886b-6a26-4cc2-a131-aa86f8c44952" />

Next, We going to Configure Agents (workers)Admin Panel -> Agents -> Add New. Jane (Dept: SysAdmins). John (Dept: Support)

First, start with Jane and make a password and give her SysAdmin and Supreme admin access.

<img width="1274" height="751" alt="image" src="https://github.com/user-attachments/assets/5a4fce6c-81ad-47c3-9cfa-8570e17b7745" />
<img width="1344" height="694" alt="image" src="https://github.com/user-attachments/assets/6b6ea1e7-7e45-4d13-ab1a-bc555dfd70e0" />

Next, you have to do John and make a passwrod and give him support and view only access.

<img width="1086" height="616" alt="image" src="https://github.com/user-attachments/assets/a9b3a65c-e957-4db1-a3fc-96165ffbb633" />
<img width="1464" height="516" alt="image" src="https://github.com/user-attachments/assets/db3cbcb9-95fe-4afb-af64-acf99cce8baa" />

Next, We are going to configure users and make a new users. Agent Panel -> Users -> Add New

<img width="1038" height="661" alt="image" src="https://github.com/user-attachments/assets/a91a8085-5c27-407f-be05-4c12bf7bd00f" />

Then, do the same for Ken and then we are going to start SLA.

We are going to configure the SLA. Admin Panel -> Manage -> SLA. Create new  Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7) , Sev-C (Grace Period: 8 hours, Business Hours)

 <img width="1321" height="369" alt="image" src="https://github.com/user-attachments/assets/dea9efc5-b6c7-4f8d-b293-6f1884f8b216" />
 <img width="1127" height="487" alt="image" src="https://github.com/user-attachments/assets/fa27391b-3a21-4bd4-9036-325f3cdff194" />
 <img width="1013" height="544" alt="image" src="https://github.com/user-attachments/assets/d63fe1c3-8e7a-4bb9-969e-b84b11317953" />
 <img width="1226" height="552" alt="image" src="https://github.com/user-attachments/assets/6e0bd52e-de71-424d-b5ee-7537fe5359b0" />
 <img width="1269" height="414" alt="image" src="https://github.com/user-attachments/assets/aa707b48-677f-4fbb-9da1-4620a67f5ddf" />

Lastly, we going to configure Help topics. Admin Panel -> Manage -> Help Topics. Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, Other

<img width="1375" height="360" alt="image" src="https://github.com/user-attachments/assets/1d2c505c-6643-4395-9aee-bfad4c7ca195" />

Now, we are going to create 5 new help topics.

<img width="1149" height="685" alt="image" src="https://github.com/user-attachments/assets/b81ec0f4-9a83-439a-9a9b-56b6a8fddae4" />
<img width="1315" height="553" alt="image" src="https://github.com/user-attachments/assets/a0e36e7d-0ead-40b3-863c-e9f5ee18851d" />
<img width="904" height="536" alt="image" src="https://github.com/user-attachments/assets/3deb03b4-3e78-42d0-ac47-47b3dc5f6760" />
<img width="1016" height="555" alt="image" src="https://github.com/user-attachments/assets/3983807a-c350-4ff6-af6c-b3425b76ec2e" />
<img width="913" height="573" alt="image" src="https://github.com/user-attachments/assets/4560480a-e5f0-4511-80b1-d028ff261d32" />
<img width="1044" height="614" alt="image" src="https://github.com/user-attachments/assets/9697f596-aeef-45ba-87df-f2a71e49d725" />

Congrats we are done for part of the osTicket

Visit my Next Repository for more Info https://github.com/Chris3091/osTicket-lifecycle/blob/a3818bcb15c07eebdf4b71c582c30b623e8d5d19/README.md

















