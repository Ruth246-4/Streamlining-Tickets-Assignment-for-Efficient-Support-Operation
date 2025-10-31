# Streamlining-Tickets-Assignment-for-Efficient-Support-Operation

#Objective: 
The objective is to optimize the ticket assignment process to ensure faster response times and balanced workloads across support teams.
It aims to automate ticket routing based on priority, expertise, and availability, minimizing manual intervention.
Ultimately, the goal is to enhance customer satisfaction and improve overall support efficiency.

#Project Overview:
This project focuses on developing an intelligent system to streamline ticket assignment within support operations. By leveraging automation and data-driven decision-making, the system efficiently routes tickets to the most suitable agents based on skill, priority, and workload. The solution aims to reduce resolution time, improve team productivity, and enhance the overall customer support experience.

#Implementation Steps:
1. Create Users

    Navigate to All → Users → New
    Add new users (e.g., Katherine Pierce, Manne Niranjan) and submit

2. Create Groups

    Navigate to All → Groups → New
    Create groups like Platform and Certificates

3. Create Roles

    Navigate to All → Roles → New
    Create roles Platform_Role and Certificate_Role

4. Create Table

    Go to System Definition → Tables → New
    Label: Operations Related
    Check Create Module and Create Mobile Module
    Add fields like Issue, Description, Assigned Group

5. Assign Users & Roles to Groups

    Add users and their respective roles under each group

6. Set Access Controls (ACLs)

    Go to System Security → Access Control (ACL)
    Restrict access to authorized roles only

7. Create Flows in Flow Designer

    Use Flow Designer to automate ticket assignment:
        If Issue = Regarding Certificates → Assign to Certificates Group
        If Issue = Login / 404 / Expired → Assign to Platform Group

   #Outcome
By leveraging ServiceNow Flow Designer, this system automatically assigns tickets to the appropriate support team, significantly reducing response time and manual workload.

  # Screenshots
User Creation
Group Creation 
Flow Setup
Auto Assignment Output


# Team Members

  Ruth Maria Paul
  Sneha P
  Stephin Suby
  Vibish Vincent V

# Conclusion 
 In conclusion, the project ensures a smarter and faster ticket assignment process that enhances efficiency and customer satisfaction. It minimizes manual effort while optimizing team performance. Overall, it contributes to a more responsive and effective support system.


