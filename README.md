# ticket-lifecycle
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<!-- <h2>Video Demonstration</h2> -->

<!-- - ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com) -->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>
<p>Link for end user to create tickets: (http://localhost/osTicket/)</p>
<p>Intake</p>
<p>
<img width="965" alt="Screen Shot 2023-04-13 at 1 46 26 PM" src="https://user-images.githubusercontent.com/88648101/231908384-0d9a9f20-c174-4658-aac9-14fe9f5aa093.png">
<img width="1565" alt="Screen Shot 2023-04-13 at 2 00 59 PM" src="https://user-images.githubusercontent.com/88648101/231908583-e3938aec-57a8-494c-a9d9-2904274241bc.png">
<img width="1126" alt="Screen Shot 2023-04-13 at 2 01 53 PM" src="https://user-images.githubusercontent.com/88648101/231908592-be1c1a18-743b-4406-8216-7906efcf38b1.png">
<img width="1182" alt="Screen Shot 2023-04-13 at 2 04 26 PM" src="https://user-images.githubusercontent.com/88648101/231908611-95364998-1264-41d2-9999-2b0ac168c719.png">
</p>
<p>
Create a couple tickets with the agents we created. 
</p>
<br />

<p>Assigning Tickets and Commnunication</p>
<p>url to log in as a help desk professional/agent: http://localhost/osTicket/scp/login.php</p>
<p>
<img width="943" alt="Screen Shot 2023-04-13 at 2 16 20 PM" src="https://user-images.githubusercontent.com/88648101/231920816-9d508288-9eeb-47ba-b6b5-d4025e8bb210.png">
<img width="1027" alt="Screen Shot 2023-04-13 at 9 52 36 PM" src="https://user-images.githubusercontent.com/88648101/231921144-e034c526-b496-4393-aeb1-9766b293c82e.png">
<img width="1203" alt="Screen Shot 2023-04-13 at 10 06 00 PM" src="https://user-images.githubusercontent.com/88648101/231923519-921e4ae6-a091-40dd-a795-740adcb5835b.png">
<img width="979" alt="Screen Shot 2023-04-13 at 10 06 35 PM" src="https://user-images.githubusercontent.com/88648101/231923554-ac11d943-bd51-4f8c-88af-34b3476f0a71.png">
<img width="1045" alt="Screen Shot 2023-04-13 at 10 09 02 PM" src="https://user-images.githubusercontent.com/88648101/231923700-02d1dd72-a784-4bdc-83ee-5955f6c8b7ba.png">
</p>
<p>
Log In as Jane Doe. In this lab She will be playing the role of an escalation engineer.Lets take a look at the ticket with mobile banking down. This sounds like a business impacting issue. Change priority to Emergency. Since this a high impact ticket and want to make sure it is resolved, assign the ticket to yourself in my case Jane Doe. Change the SLA to SEV A; the highest severity. Change the departments from support to System Administrators. Post a reply to the tickets and return to opened tickets. You can see that the Priority has changed and Jane Doe is assigned the ticket. You can also see that under  Ticket Thread, every changes you made was automatically communicated. This can help jumpstart other agents joining the ticket halfway if needed.
</p>
<br />

<p>Working the Issue</p>
<p>Since Jane assigned the ticket directly to herself, she will coordinate with the Sys Admin Team and make sure the issue is resolved. Any changes or findings will be communicated and seen in the Ticket Thread.</p>
<br />

<p>Resolution</p>
<p>
<img width="1169" alt="Screen Shot 2023-04-14 at 10 32 38 AM" src="https://user-images.githubusercontent.com/88648101/232074377-21f63ceb-3402-4099-ac0f-900b1d313e41.png">
<img width="1085" alt="Screen Shot 2023-04-14 at 10 34 02 AM" src="https://user-images.githubusercontent.com/88648101/232074416-46d49cb7-3017-42a4-9fe3-c371a8572e11.png">
</p>
<p>
After the Issue Have been resolved, Jane will provide a brief overview of how it was resolved and then change Ticket Status from open to "Resolved". This will close the ticket and remove it from the list of open tickets. You can also view closed tickets by going to closed. This can be very helpful if faced with an issue that has been resolved before. 
</p>
<br />

<p>This brings us to the end of the ticket-cycle. Please take time to practice by assigning and resolving the remaining tickets we created in the begining. This Time try asigning the ticket to someone else other than jane. Try to practice any event you could imagine happening eg: downgrading a ticket, reasigning to a different department or even reopening a closed ticket. Thank you and have great day. <p>
