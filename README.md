# Tickets and Ticket Lifecycles

> [!Note]
> In this tutorial, we'll be observing the life cycles of some examples of tickets and issues. We'll also triage some of the examples to show how osTicket works.

> [!Important]
> You will need osTicket set up and configured in order to continue with this tutorial. For assistance in setting up osTicket, please refer to my [Guide for Installing osTicket](https://github.com/EMoniSmall/osInstall) and for help configuring osTicket please refer to my [Guide for Configuring osTicket](https://github.com/EMoniSmall/osPostConfig).
>
> During this Tutorial, we will be using the enviornment that was created with these guides in order to create tickets and solve them. 

<h2>Creating Tickets</h2>

> [!Note]
> We'll be creating a few tickets. Feel free to create your own tickets or you can follow along with the examples.

Step 1: On your Virtual Machine, open a web browser amd visit http://localhost/osTicket/

Step 2: Open a New Ticket and enter the contact information for one of the users you have created during the Post Installation Configuration tutorial. 

Step 3: Select a Help Topic. You'll recognize some of the Help topics you've created earlier.

Step 4: Enter your Ticket Details.

Step 5: Repeat Steps 1-4 til you make a satisfactory amount of tickets for practice.

![mstsc_UPV7svXoiQ](https://github.com/EMoniSmall/osTicketLife/assets/166156618/adc0425b-7e9e-4cb9-a890-2e2679eba927)

<h2>Ticket Triage</h2>

Step 1: Once your tickets, Log into osTicket with your Super Admin User.
> [!Important]
> If you named your Super Admin user something else during the previous tutorial, log into the account that you gave all access to.

> [!Note]
> You should come up on the following screen.
> 
> ![image](https://github.com/EMoniSmall/osTicketLife/assets/166156618/ab473db1-1a1f-4bb1-8094-b8694696e656)
>
> You'll notice on the right that the tickets you've created aren't assigned to anyone. Normally a lead will go through all the tickets and ensure that each ticket is assigned to the correct department and the SLAs are correct.

Step 2: Pick a Ticket to observe and click into it. In this case we'll be look at the Business Critical Outage Ticket we created earlier. 

Step 3: Change the Priority to Emergency. Since the ticket states that their department cannot connect to the network, this implies that all business for this department has halted therefore would be an emergency situation. Enter the reason for change.

Step 4: Change the department to System Admins. In this case, the Support department might not be able to fix the issue so it makes more sense for the Admins to handle this issue. 

Step 5: Assign the Ticket to a team or an individual. In this case, you can assign it to Jane Doe.

Step 6: Change the SLA. Since the Ticket is considered an emergency, the SLA should be changed accordingly. Change it to Sev-A, which is our 1 hour 24/7 SLA Plan. 

> [!Note]
> Below, you'll see a Ticket Thread that's been logging all the changes that have been done to the ticket. Any changes, internal notes will be logged here. When you return to the Tickets page, you'll see that the Ticket has been updated.
> ![image](https://github.com/EMoniSmall/osTicketLife/assets/166156618/0cae9bac-1231-4e58-9417-235f0986839e)

Step 7: Click back into the ticket. Update in the ticket thread that the issue has been fixed and change the Ticket Status to resolved. You'll see back in the Tickets page that the ticket has disappeared. 
