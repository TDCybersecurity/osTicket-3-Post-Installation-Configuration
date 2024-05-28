<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# **osTicket: 3 Post-Installation Configuration**

![](RackMultipart20240528-1-xyqbwa_html_8664ec047e01ec08.png)

**Configure Roles**

Click Agents \> Roles \> +Add New Role \> in Name: **Supreme Admin**\> Permissions.

Click Permissions and under **Tickets**, **Tasks**, and **Knowledge Base**, check all boxes in each category. Add Role

2 ![](RackMultipart20240528-1-xyqbwa_html_8ddf48d63b19088f.png)

**Configure Departments**

Click on Agents \> Departments \> +Add New Departments \> in Name: **System Administrator**\> Create Dept

3

![](RackMultipart20240528-1-xyqbwa_html_12e116bc9b0c4962.png)

**Configure Teams**

Click on Teams \> +Add New Team \> in Name: **Level II Support**\> Click Members \> Select Agent: Terry Davis \> Create Teams

**Allow anyone to Create Tickets**

Click on Agents \> +Add New Agent \>

Name: **Jane Doe** Email: [**jane.doe@osticket.com**](mailto:jane.doe@osticket.com) Username: **jane.doe** Password: **Password1**

Click on Set Password\> uncheck Send the agent a password reset email.

New Password:/Confirm Password: Password1

Uncheck Require password change at next login \> Set \>

4

![](RackMultipart20240528-1-xyqbwa_html_e4d7f3bbccabebb6.png)

Access tab \> Fill out these three sections below \> Click **Create**

| **Primary Department**| **Role**| **Extended Access**|
| --- | --- | --- |
| System Administration | Supreme Admin | System Administration |

5

![](RackMultipart20240528-1-xyqbwa_html_b21de8088d45643e.png)

Access Permissions tab \> leave defaults in place

Access Teams tab \> Assigned Teams Level II Support \> Add \> Create Jane Does has been created.

6 ![](RackMultipart20240528-1-xyqbwa_html_dd8283489f9f5e2.png) ![](RackMultipart20240528-1-xyqbwa_html_48f4b291c13e8653.png)

Click on Agents \> +Add New Agent \>

Name: **John Doe** Email:[**john.doe@osticket.com**](mailto:john.doe@osticket.com) Username: **john.doe** Password: **Password1**

Access tab\> Fill out these three sections below \> Click **Create**

| **Primary Department**| **Role**| **Extended Access**|
| --- | --- | --- |
| Support | View only | Support |

7

![](RackMultipart20240528-1-xyqbwa_html_dd8283489f9f5e2.png)

**Configure Users/Customers**

Go to Agent Panel \> Users \> +Add User \>

| **Email Address**| **Full Name**|
| --- | --- |
| [karen@osticket.com](mailto:karen@osticket.com) | Karen Baren |
| [ken@osticket.com](mailto:ken@osticket.com) | Ken Ben |

8 ![](RackMultipart20240528-1-xyqbwa_html_585526a9c08b2d8b.png)

**Configure (SLA) Service Level Agreement Plans**

Go Admin Panel \> Manage \> SLA \> + Add New SLA Plan

| **Name**| **Grace Period**| **Schedule**|
| --- | --- | --- |
| Sev A | 1 | 24/7 |
| Sev B | 4 | 24/7 |
| Sev C | 8 | Mon – Fri 8am-5pm with US Holidays |

9 ![](RackMultipart20240528-1-xyqbwa_html_e9003efd66d7f7c6.png)

**Configure Help Topics**

Go to Admin Panel \> Manage \> Help Topics\> +Add New Help Topic

| **Topic**| **Status**| **Type**| **Parent Topic**|
| --- | --- | --- | --- |
| Business Critical Outage | Active | Public | Top-Level Topic |
| Personal Computer Issues | Active | Public | Top-Level Topic |
| Equipment Request | Active | Public | Top-Level Topic |
| Password Reset | Active | Public | Top-Level Topic |

10 ![](RackMultipart20240528-1-xyqbwa_html_e90384fce7a98442.png)
