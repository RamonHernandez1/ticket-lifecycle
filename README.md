<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - LifeCycle Examples Setup</h1>
</p>
In this last section of the osTicket project, I go through the life cycle of a ticket from creation, to resolution. I make changes to the tickets when necessary like assigning the tickets, changing the SLA (Service Level Agreement), and commenting to create a thread of clear communication.

</p><h1>Environments and utilities used</h1>
</p>
</p>
<p>
osTicket
</p><h1>Project Guide</h1></p>
</p> First, I will navigate to the end user site of osTicket to be able to create a new ticket in the virtual machine:
</p>http://localhost/osTicket 
<img width="1440" height="900" alt="Screenshot 2026-02-10 at 10 13 22 PM" src="https://github.com/user-attachments/assets/4b9bc31d-b95e-4c9f-ab06-e86f43ee75ba" />

</p>I will open two new tickets and fill out the users information along with the technical issues:
<br />
<p>
</p><img width="1440" height="900" alt="Screenshot 2026-02-11 at 10 02 03 AM" src="https://github.com/user-attachments/assets/a60a59d8-a465-4922-aedf-8e0c1e9070e6" />

<p>
</p><img width="2824" height="1632" alt="image" src="https://github.com/user-attachments/assets/a4140113-bd53-43a8-a422-1381bba4e569" />

<br />Next, I will log in as an agent (worker) we created:http://localhost/osTicket/scp/login.php 
<p>
<img width="1440" height="900" alt="Screenshot 2026-02-11 at 10 30 02 AM" src="https://github.com/user-attachments/assets/fe2615b7-640e-467f-8825-89e34c15b3a8" />

</p>I can now see all the open tickets I created in the "Tickets" tab:
<p>
</p>
<img width="1440" height="900" alt="Screenshot 2026-02-11 at 10 45 10 AM" src="https://github.com/user-attachments/assets/85f85084-902e-43ac-8ead-a2422d6a099a" />

</p>When clicking on a ticket I can see all the information about the ticket like its priority, SLA, creation date, and more:
<p>
</p>
<img width="1440" height="900" alt="Screenshot 2026-02-11 at 10 52 47 AM" src="https://github.com/user-attachments/assets/92610137-0ddd-4f19-bb89-ada728979be0" />

</p>I can change the priority level on appropriate tickets by clicking the "Priority" section and can add a note for the change made:
<p>
</p>
<img width="1440" height="900" alt="Screenshot 2026-02-11 at 11 03 31 AM" src="https://github.com/user-attachments/assets/d118a9cb-b5fa-45b1-a072-96091f99a997" />


</p>I can also change the tickets SLA (Service Level Aggrement) of the ticket in the "SLA Plan" section:
<p>
</p>
<img width="1440" height="900" alt="Screenshot 2026-02-11 at 11 10 25 AM" src="https://github.com/user-attachments/assets/07350abd-2b29-41fd-8df6-c34a1d25714a" />


</p>To assign a ticket, click on "Unassigned" next to the "Assigned To" section and select an agent to assign this ticket to:
<p>
</p>
<img width="1440" height="900" alt="Screenshot 2026-02-11 at 11 29 07 AM" src="https://github.com/user-attachments/assets/27721cc7-b6fb-4cd3-a3e3-6481e75dc81f" />


</p></p>Another option I have is to change the tickets department in the "Department" section:
<p>
</p>
<img width="1440" height="900" alt="Screenshot 2026-02-11 at 11 34 45 AM" src="https://github.com/user-attachments/assets/28ccec2b-125c-4999-9973-2d180c4e9517" />



</p>Looking further down I can see a thread of all of the changes made to the ticket:
<p>
</p>
<img width="1440" height="900" alt="Screenshot 2026-02-11 at 11 40 45 AM" src="https://github.com/user-attachments/assets/f69c17f7-7692-43cd-a6fd-0a32942b49a7" />



</p>At the bottom I can post replies communicating updates of the ticket:
<p>
</p>
<img width="1440" height="900" alt="Screenshot 2026-02-11 at 11 47 55 AM" src="https://github.com/user-attachments/assets/6c2867a0-3e99-4887-86d8-c6e8fa6e766d" />



</p>If I go back to see all the open tickets, I can see the changes I made to the ticket:
<p>
</p>
<img width="1440" height="900" alt="Screenshot 2026-02-11 at 11 52 19 AM" src="https://github.com/user-attachments/assets/c4f11e52-8d51-4d3e-86b8-358487da2ff3" />



</p>To resolve a ticket, I can select "Resolved" from the "Ticket Status" menu at the top left of the ticket:
<p>
</p>
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/769324e0-9bca-41d0-b221-3a3a8e120183" />




</p>The resolved ticket will disappear from the open tickets tab and appear in the closed tickets tab:
<p>
</p>
<img width="1440" height="900" alt="Screenshot 2026-02-11 at 12 14 56 PM" src="https://github.com/user-attachments/assets/a3de55c8-82c8-4e4e-93e9-97c05c946933" />





