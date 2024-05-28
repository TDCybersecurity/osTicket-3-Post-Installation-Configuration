<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# **osTicket: 3 Post-Installation Configuration**
![Ticket 3 1](https://github.com/TDCybersecurity/osTicket-3-Post-Installation-Configuration/assets/142702123/4b13bdbd-70e6-46ce-bdae-541325a808bc)

## **Configure Roles**

Click Agents \> Roles \> +Add New Role \> in Name: **Supreme Admin**\> Permissions.

Click Permissions and under **Tickets**, **Tasks**, and **Knowledge Base**, check all boxes in each category. Add Role
![Ticket 3 2](https://github.com/TDCybersecurity/osTicket-3-Post-Installation-Configuration/assets/142702123/72fc8a3f-66ab-40bd-b4e3-80b77cf33285)


## **Configure Departments**

Click on Agents \> Departments \> +Add New Departments \> in Name: **System Administrator**\> Create Dept

![Ticket 3 3](https://github.com/TDCybersecurity/osTicket-3-Post-Installation-Configuration/assets/142702123/dc96d888-b944-408b-ba96-d60d3ff8341c)

## **Configure Teams**

Click on Teams \> +Add New Team \> in Name: **Level II Support**\> Click Members \> Select Agent: Terry Davis \> Create Teams

## **Allow anyone to Create Tickets**

Click on Agents \> +Add New Agent \>

Name: **Jane Doe** Email: [**jane.doe@osticket.com**](mailto:jane.doe@osticket.com) Username: **jane.doe** Password: **Password1**

Click on Set Password\> uncheck Send the agent a password reset email.

New Password:/Confirm Password: Password1

Uncheck Require password change at next login \> Set \>

![Ticket 3 4](https://github.com/TDCybersecurity/osTicket-3-Post-Installation-Configuration/assets/142702123/458b2e24-49d5-42d6-b078-c992d3cb7c75)



Access tab \> Fill out these three sections below \> Click **Create**

| **Primary Department**| **Role**| **Extended Access**|
| --- | --- | --- |
| System Administration | Supreme Admin | System Administration |

![Ticket 3 5](https://github.com/TDCybersecurity/osTicket-3-Post-Installation-Configuration/assets/142702123/4ce9eab1-2f5f-4a5f-862f-bc87c45dff82)



Access Permissions tab \> leave defaults in place

Access Teams tab \> Assigned Teams Level II Support \> Add \> Create Jane Does has been created.
![Ticket 3 6](https://github.com/TDCybersecurity/osTicket-3-Post-Installation-Configuration/assets/142702123/1687f3f4-1913-4df4-9be8-db96858af30b)


## **Click on Agents \> +Add New Agent \>

Name: **John Doe** Email:[**john.doe@osticket.com**](mailto:john.doe@osticket.com) Username: **john.doe** Password: **Password1**

Access tab\> Fill out these three sections below \> Click **Create**

| **Primary Department**| **Role**| **Extended Access**|
| --- | --- | --- |
| Support | View only | Support |

![Ticket 3 7](https://github.com/TDCybersecurity/osTicket-3-Post-Installation-Configuration/assets/142702123/a0e25325-e875-47e3-b171-17574bdc2778)

## **Configure Users/Customers**

Go to Agent Panel \> Users \> +Add User \>

| **Email Address**| **Full Name**|
| --- | --- |
| [karen@osticket.com](mailto:karen@osticket.com) | Karen Baren |
| [ken@osticket.com](mailto:ken@osticket.com) | Ken Ben |

![Ticket 3 8](https://github.com/TDCybersecurity/osTicket-3-Post-Installation-Configuration/assets/142702123/57b4a3f7-16d1-48db-a807-8045c4e01ca4)

## **Configure (SLA) Service Level Agreement Plans**

Go Admin Panel \> Manage \> SLA \> + Add New SLA Plan

| **Name**| **Grace Period**| **Schedule**|
| --- | --- | --- |
| Sev A | 1 | 24/7 |
| Sev B | 4 | 24/7 |
| Sev C | 8 | Mon – Fri 8am-5pm with US Holidays |

![Ticket 3 9](https://github.com/TDCybersecurity/osTicket-3-Post-Installation-Configuration/assets/142702123/76dea2e3-ae11-4c6d-a79d-66eb5efb8ffa)

## **Configure Help Topics**

Go to Admin Panel \> Manage \> Help Topics\> +Add New Help Topic

| **Topic**| **Status**| **Type**| **Parent Topic**|
| --- | --- | --- | --- |
| Business Critical Outage | Active | Public | Top-Level Topic |
| Personal Computer Issues | Active | Public | Top-Level Topic |
| Equipment Request | Active | Public | Top-Level Topic |
| Password Reset | Active | Public | Top-Level Topic |

![Ticket 3 10](https://github.com/TDCybersecurity/osTicket-3-Post-Installation-Configuration/assets/142702123/0995d83a-8242-44b4-9aa2-2dab08104604)

# **This lab provides practical experience in Post-Installation Configuration**
