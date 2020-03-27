### Question 201

**SCENARIO:**

TESTLET-7.

Case Study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Contoso, Ltd. is a consulting company that has a main office in Montreal and two branch offices in Seattle

and New York.

The Montreal office has 2,000 employees. The Seattle office has 1,000 employees. The New York office

has 200 employees.

All the resources used by Contoso are hosted on-premises.

Contoso created a new Azure subscription. The Azure Active Directory (Azure AD) tenant uses a domain

named contoso.onmicrosoft.com. The tenant uses the P1 pricing tier.

Existing Environment

The network contains an Active Directory forest named contoso.com. All domain controllers are configured

as DNS servers and host the contoso.com DNS zone.

Contoso has finance, human resources, sales, research, and information technology departments. Each

department has an organizational unit (OU) that contains all the accounts of that respective department. All

the user accounts have the department attribute set to their respective department. New users are added

frequently.

Contoso.com contains a user named User1.

All the offices connect by using private links.

Contoso has data centers in the Montreal and Seattle offices. Each data center has a firewall that can be

configured as a VPN device.

All infrastructure servers are virtualized. The virtualization environment contains the servers in the following

table.

![](image/image-538.webp)

Contoso uses two web applications named App1 and App2. Each instance on each web application

requires 1 GB of memory.

The Azure subscription contains the resources in the following table.

![](image/image-539.webp)

The network security team implements several network security groups (NSGs).

Requirements

Planned Changes

Contoso plans to implement the following changes:

	- Deploy Azure ExpressRoute to the Montreal office

	- Migrate the virtual machine hosted on Server1 and Server2 to Azure

	- Synchronize on-premises Active Directory to Azure Active Directory (Azure AD)

	- Migrate App1 and App2 to two Azure web apps named WebApp1 and WebApp2.

Technical Requirements

Contoso must meet the following technical requirements:

	- Ensure that WebApp1 can adjust the number of instances automatically based on the load and can

scale up to five instances

	- Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in

the Montreal office

	- Ensure that routing information is exchanged automatically between Azure and the routers in the

Montreal office

	- Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only

	- Ensure that webapp2.azurewebsites.net can be accessed by using the name app2.contoso.com

	- Connect the New York office to VNet1 over the Internet by using an encrypted connection

	- Create a workflow to send an email message when the settings of VM4 are modified

	- Create a custom Azure role named Role1 that is based on the Reader role

	- Minimize costs whenever possible

HOTSPOT

You are developing an Azure Web App. You configure TLS mutual authentication for the web app.

You need to validate the client certificate in the web app. To answer, select the appropriate options in the

answer area.

NOTE: Each correct selection is worth one point.

Hot Area:

![](image/image-576.webp)

[See the answer](#answer-201)

### Question 202

**SCENARIO:**

TESTLET-7.

Case Study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Contoso, Ltd. is a consulting company that has a main office in Montreal and two branch offices in Seattle

and New York.

The Montreal office has 2,000 employees. The Seattle office has 1,000 employees. The New York office

has 200 employees.

All the resources used by Contoso are hosted on-premises.

Contoso created a new Azure subscription. The Azure Active Directory (Azure AD) tenant uses a domain

named contoso.onmicrosoft.com. The tenant uses the P1 pricing tier.

Existing Environment

The network contains an Active Directory forest named contoso.com. All domain controllers are configured

as DNS servers and host the contoso.com DNS zone.

Contoso has finance, human resources, sales, research, and information technology departments. Each

department has an organizational unit (OU) that contains all the accounts of that respective department. All

the user accounts have the department attribute set to their respective department. New users are added

frequently.

Contoso.com contains a user named User1.

All the offices connect by using private links.

Contoso has data centers in the Montreal and Seattle offices. Each data center has a firewall that can be

configured as a VPN device.

All infrastructure servers are virtualized. The virtualization environment contains the servers in the following

table.

![](image/image-538.webp)

Contoso uses two web applications named App1 and App2. Each instance on each web application

requires 1 GB of memory.

The Azure subscription contains the resources in the following table.

![](image/image-539.webp)

The network security team implements several network security groups (NSGs).

Requirements

Planned Changes

Contoso plans to implement the following changes:

	- Deploy Azure ExpressRoute to the Montreal office

	- Migrate the virtual machine hosted on Server1 and Server2 to Azure

	- Synchronize on-premises Active Directory to Azure Active Directory (Azure AD)

	- Migrate App1 and App2 to two Azure web apps named WebApp1 and WebApp2.

Technical Requirements

Contoso must meet the following technical requirements:

	- Ensure that WebApp1 can adjust the number of instances automatically based on the load and can

scale up to five instances

	- Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in

the Montreal office

	- Ensure that routing information is exchanged automatically between Azure and the routers in the

Montreal office

	- Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only

	- Ensure that webapp2.azurewebsites.net can be accessed by using the name app2.contoso.com

	- Connect the New York office to VNet1 over the Internet by using an encrypted connection

	- Create a workflow to send an email message when the settings of VM4 are modified

	- Create a custom Azure role named Role1 that is based on the Reader role

	- Minimize costs whenever possible

You have a Recovery Service vault that you use to test backups. The test backups contain two protected

virtual machines.

You need to delete the Recovery Services vault.

What should you do first?

* A: From the Recovery Service vault, delete the backup data

* B: Modify the disaster recovery properties of each virtual machines

* C: Modify the locks of each virtual machine

* D: From the Recovery Service vault, stop the backup of each backup item

[See the answer](#answer-202)

### Question 203

**SCENARIO:**

TESTLET-7.

Case Study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Contoso, Ltd. is a consulting company that has a main office in Montreal and two branch offices in Seattle

and New York.

The Montreal office has 2,000 employees. The Seattle office has 1,000 employees. The New York office

has 200 employees.

All the resources used by Contoso are hosted on-premises.

Contoso created a new Azure subscription. The Azure Active Directory (Azure AD) tenant uses a domain

named contoso.onmicrosoft.com. The tenant uses the P1 pricing tier.

Existing Environment

The network contains an Active Directory forest named contoso.com. All domain controllers are configured

as DNS servers and host the contoso.com DNS zone.

Contoso has finance, human resources, sales, research, and information technology departments. Each

department has an organizational unit (OU) that contains all the accounts of that respective department. All

the user accounts have the department attribute set to their respective department. New users are added

frequently.

Contoso.com contains a user named User1.

All the offices connect by using private links.

Contoso has data centers in the Montreal and Seattle offices. Each data center has a firewall that can be

configured as a VPN device.

All infrastructure servers are virtualized. The virtualization environment contains the servers in the following

table.

![](image/image-538.webp)

Contoso uses two web applications named App1 and App2. Each instance on each web application

requires 1 GB of memory.

The Azure subscription contains the resources in the following table.

![](image/image-539.webp)

The network security team implements several network security groups (NSGs).

Requirements

Planned Changes

Contoso plans to implement the following changes:

	- Deploy Azure ExpressRoute to the Montreal office

	- Migrate the virtual machine hosted on Server1 and Server2 to Azure

	- Synchronize on-premises Active Directory to Azure Active Directory (Azure AD)

	- Migrate App1 and App2 to two Azure web apps named WebApp1 and WebApp2.

Technical Requirements

Contoso must meet the following technical requirements:

	- Ensure that WebApp1 can adjust the number of instances automatically based on the load and can

scale up to five instances

	- Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in

the Montreal office

	- Ensure that routing information is exchanged automatically between Azure and the routers in the

Montreal office

	- Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only

	- Ensure that webapp2.azurewebsites.net can be accessed by using the name app2.contoso.com

	- Connect the New York office to VNet1 over the Internet by using an encrypted connection

	- Create a workflow to send an email message when the settings of VM4 are modified

	- Create a custom Azure role named Role1 that is based on the Reader role

	- Minimize costs whenever possible

Note: This question is part of series of questions that present the same scenario. Each question in

the series contains a unique solution that might meet the stated goals. Some question sets might

have more than one correct solution, while others might not have a correct solution.

After you answer a question in this section, you will NOT be able to return to it. As a result, these

questions will not appear in the review screen.

Your network contains an Active Directory forest named fabrikam.com. The forest contains two child

domains named corp.fabrikam.com and research.fabrikam.com.

You have an Azure subscription that contains an Azure Active Directory (Azure AD) tenant named

contoso.com.

You install Azure AD Connect and sync all the on-premises user accounts to the Azure AD tenant. You

implement seamless single sign-on (SSO).

You plan to change the source of authority for all the user accounts in research.fabrikam.com to Azure AD.

You need to prevent research.fabrikam.com from resyncing to Azure AD.

Solution: You use Active Directory Domains and Trusts from a computer joined to fabrikam.com.

Does this meet the goal?

* A: Yes

* B: No

[See the answer](#answer-203)

### Question 204

**SCENARIO:**

TESTLET-7.

Case Study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Contoso, Ltd. is a consulting company that has a main office in Montreal and two branch offices in Seattle

and New York.

The Montreal office has 2,000 employees. The Seattle office has 1,000 employees. The New York office

has 200 employees.

All the resources used by Contoso are hosted on-premises.

Contoso created a new Azure subscription. The Azure Active Directory (Azure AD) tenant uses a domain

named contoso.onmicrosoft.com. The tenant uses the P1 pricing tier.

Existing Environment

The network contains an Active Directory forest named contoso.com. All domain controllers are configured

as DNS servers and host the contoso.com DNS zone.

Contoso has finance, human resources, sales, research, and information technology departments. Each

department has an organizational unit (OU) that contains all the accounts of that respective department. All

the user accounts have the department attribute set to their respective department. New users are added

frequently.

Contoso.com contains a user named User1.

All the offices connect by using private links.

Contoso has data centers in the Montreal and Seattle offices. Each data center has a firewall that can be

configured as a VPN device.

All infrastructure servers are virtualized. The virtualization environment contains the servers in the following

table.

![](image/image-538.webp)

Contoso uses two web applications named App1 and App2. Each instance on each web application

requires 1 GB of memory.

The Azure subscription contains the resources in the following table.

![](image/image-539.webp)

The network security team implements several network security groups (NSGs).

Requirements

Planned Changes

Contoso plans to implement the following changes:

	- Deploy Azure ExpressRoute to the Montreal office

	- Migrate the virtual machine hosted on Server1 and Server2 to Azure

	- Synchronize on-premises Active Directory to Azure Active Directory (Azure AD)

	- Migrate App1 and App2 to two Azure web apps named WebApp1 and WebApp2.

Technical Requirements

Contoso must meet the following technical requirements:

	- Ensure that WebApp1 can adjust the number of instances automatically based on the load and can

scale up to five instances

	- Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in

the Montreal office

	- Ensure that routing information is exchanged automatically between Azure and the routers in the

Montreal office

	- Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only

	- Ensure that webapp2.azurewebsites.net can be accessed by using the name app2.contoso.com

	- Connect the New York office to VNet1 over the Internet by using an encrypted connection

	- Create a workflow to send an email message when the settings of VM4 are modified

	- Create a custom Azure role named Role1 that is based on the Reader role

	- Minimize costs whenever possible

HOTSPOT

Your organization has developed and deployed several Azure App Service Web and API applications. The

applications use Azure SQL Database to store and retrieve data. Several departments have the following

requests to support the applications:

![](image/image-582.webp)

You need to recommend the appropriate Azure service for each department request.

What should you recommend? To answer, configure the appropriate options in the dialog box in the answer

area.

NOTE: Each correct selection is worth one point.

Hot Area:

![](image/image-583.webp)

[See the answer](#answer-204)

### Question 205

**SCENARIO:**

TESTLET-7.

Case Study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Contoso, Ltd. is a consulting company that has a main office in Montreal and two branch offices in Seattle

and New York.

The Montreal office has 2,000 employees. The Seattle office has 1,000 employees. The New York office

has 200 employees.

All the resources used by Contoso are hosted on-premises.

Contoso created a new Azure subscription. The Azure Active Directory (Azure AD) tenant uses a domain

named contoso.onmicrosoft.com. The tenant uses the P1 pricing tier.

Existing Environment

The network contains an Active Directory forest named contoso.com. All domain controllers are configured

as DNS servers and host the contoso.com DNS zone.

Contoso has finance, human resources, sales, research, and information technology departments. Each

department has an organizational unit (OU) that contains all the accounts of that respective department. All

the user accounts have the department attribute set to their respective department. New users are added

frequently.

Contoso.com contains a user named User1.

All the offices connect by using private links.

Contoso has data centers in the Montreal and Seattle offices. Each data center has a firewall that can be

configured as a VPN device.

All infrastructure servers are virtualized. The virtualization environment contains the servers in the following

table.

![](image/image-538.webp)

Contoso uses two web applications named App1 and App2. Each instance on each web application

requires 1 GB of memory.

The Azure subscription contains the resources in the following table.

![](image/image-539.webp)

The network security team implements several network security groups (NSGs).

Requirements

Planned Changes

Contoso plans to implement the following changes:

	- Deploy Azure ExpressRoute to the Montreal office

	- Migrate the virtual machine hosted on Server1 and Server2 to Azure

	- Synchronize on-premises Active Directory to Azure Active Directory (Azure AD)

	- Migrate App1 and App2 to two Azure web apps named WebApp1 and WebApp2.

Technical Requirements

Contoso must meet the following technical requirements:

	- Ensure that WebApp1 can adjust the number of instances automatically based on the load and can

scale up to five instances

	- Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in

the Montreal office

	- Ensure that routing information is exchanged automatically between Azure and the routers in the

Montreal office

	- Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only

	- Ensure that webapp2.azurewebsites.net can be accessed by using the name app2.contoso.com

	- Connect the New York office to VNet1 over the Internet by using an encrypted connection

	- Create a workflow to send an email message when the settings of VM4 are modified

	- Create a custom Azure role named Role1 that is based on the Reader role

	- Minimize costs whenever possible

You have the Azure virtual machines shown in the following table.

![](image/image-585.webp)

You have a Recovery Services vault that protects VM1 and VM2.

You need to protect VM3 and VM4 by using Recovery Services.

What should you do first?

* A: Create a new backup policy

* B: Create a new Recovery Services vault

* C: Configure the extensions for VM3 and VM4

* D: Create a storage account

[See the answer](#answer-205)

### Question 206

**SCENARIO:**

TESTLET-7.

Case Study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Contoso, Ltd. is a consulting company that has a main office in Montreal and two branch offices in Seattle

and New York.

The Montreal office has 2,000 employees. The Seattle office has 1,000 employees. The New York office

has 200 employees.

All the resources used by Contoso are hosted on-premises.

Contoso created a new Azure subscription. The Azure Active Directory (Azure AD) tenant uses a domain

named contoso.onmicrosoft.com. The tenant uses the P1 pricing tier.

Existing Environment

The network contains an Active Directory forest named contoso.com. All domain controllers are configured

as DNS servers and host the contoso.com DNS zone.

Contoso has finance, human resources, sales, research, and information technology departments. Each

department has an organizational unit (OU) that contains all the accounts of that respective department. All

the user accounts have the department attribute set to their respective department. New users are added

frequently.

Contoso.com contains a user named User1.

All the offices connect by using private links.

Contoso has data centers in the Montreal and Seattle offices. Each data center has a firewall that can be

configured as a VPN device.

All infrastructure servers are virtualized. The virtualization environment contains the servers in the following

table.

![](image/image-538.webp)

Contoso uses two web applications named App1 and App2. Each instance on each web application

requires 1 GB of memory.

The Azure subscription contains the resources in the following table.

![](image/image-539.webp)

The network security team implements several network security groups (NSGs).

Requirements

Planned Changes

Contoso plans to implement the following changes:

	- Deploy Azure ExpressRoute to the Montreal office

	- Migrate the virtual machine hosted on Server1 and Server2 to Azure

	- Synchronize on-premises Active Directory to Azure Active Directory (Azure AD)

	- Migrate App1 and App2 to two Azure web apps named WebApp1 and WebApp2.

Technical Requirements

Contoso must meet the following technical requirements:

	- Ensure that WebApp1 can adjust the number of instances automatically based on the load and can

scale up to five instances

	- Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in

the Montreal office

	- Ensure that routing information is exchanged automatically between Azure and the routers in the

Montreal office

	- Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only

	- Ensure that webapp2.azurewebsites.net can be accessed by using the name app2.contoso.com

	- Connect the New York office to VNet1 over the Internet by using an encrypted connection

	- Create a workflow to send an email message when the settings of VM4 are modified

	- Create a custom Azure role named Role1 that is based on the Reader role

	- Minimize costs whenever possible

You have an Azure Active Directory (Azure AD) domain that contains 5,000 user accounts. You create a

new user account named AdminUser1.

You need to assign the User administrator administrative role to AdminUser1.

What should you do from the user account properties?

* A: From the Directory role blade, modify the directory role

* B: From the Licenses blade, assign a new license

* C: From the Groups blade, invite the user account to a new group

[See the answer](#answer-206)

### Question 207

**SCENARIO:**

TESTLET-7.

Case Study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Contoso, Ltd. is a consulting company that has a main office in Montreal and two branch offices in Seattle

and New York.

The Montreal office has 2,000 employees. The Seattle office has 1,000 employees. The New York office

has 200 employees.

All the resources used by Contoso are hosted on-premises.

Contoso created a new Azure subscription. The Azure Active Directory (Azure AD) tenant uses a domain

named contoso.onmicrosoft.com. The tenant uses the P1 pricing tier.

Existing Environment

The network contains an Active Directory forest named contoso.com. All domain controllers are configured

as DNS servers and host the contoso.com DNS zone.

Contoso has finance, human resources, sales, research, and information technology departments. Each

department has an organizational unit (OU) that contains all the accounts of that respective department. All

the user accounts have the department attribute set to their respective department. New users are added

frequently.

Contoso.com contains a user named User1.

All the offices connect by using private links.

Contoso has data centers in the Montreal and Seattle offices. Each data center has a firewall that can be

configured as a VPN device.

All infrastructure servers are virtualized. The virtualization environment contains the servers in the following

table.

![](image/image-538.webp)

Contoso uses two web applications named App1 and App2. Each instance on each web application

requires 1 GB of memory.

The Azure subscription contains the resources in the following table.

![](image/image-539.webp)

The network security team implements several network security groups (NSGs).

Requirements

Planned Changes

Contoso plans to implement the following changes:

	- Deploy Azure ExpressRoute to the Montreal office

	- Migrate the virtual machine hosted on Server1 and Server2 to Azure

	- Synchronize on-premises Active Directory to Azure Active Directory (Azure AD)

	- Migrate App1 and App2 to two Azure web apps named WebApp1 and WebApp2.

Technical Requirements

Contoso must meet the following technical requirements:

	- Ensure that WebApp1 can adjust the number of instances automatically based on the load and can

scale up to five instances

	- Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in

the Montreal office

	- Ensure that routing information is exchanged automatically between Azure and the routers in the

Montreal office

	- Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only

	- Ensure that webapp2.azurewebsites.net can be accessed by using the name app2.contoso.com

	- Connect the New York office to VNet1 over the Internet by using an encrypted connection

	- Create a workflow to send an email message when the settings of VM4 are modified

	- Create a custom Azure role named Role1 that is based on the Reader role

	- Minimize costs whenever possible

SIMULATION

Click to expand each objective. To connect to the Azure portal, type https://portal.azure.com in the browser

address bar.

![](image/image-586.webp)

![](image/image-587.webp)

![](image/image-588.webp)

![](image/image-589.webp)

![](image/image-590.webp)

![](image/image-591.webp)

When you are finished performing all the tasks, click the ‘Next’ button.

Note that you cannot return to the lab once you click the ‘Next’ button. Scoring occur in the background

while you complete the rest of the exam.

Overview 

The following section of the exam is a lab. In this section, you will perform a set of tasks in a live

environment. While most functionality will be available to you as it would be in a live environment, some

functionality (e.g., copy and paste, ability to navigate to external websites) will not be possible by design.

Scoring is based on the outcome of performing the tasks stated in the lab. In other words, it doesn’t matter

how you accomplish the task, if you successfully perform it, you will earn credit for that task.

Labs are not timed separately, and this exam may have more than one lab that you must complete. You

can use as much time as you would like to complete each lab. But, you should manage your time

appropriately to ensure that you are able to complete the lab(s) and all other sections of the exam in the

time provided.

Please note that once you submit your work by clicking the Next button within a lab, you will NOT be able to

return to the lab.

To start the lab

You may start the lab by clicking the Next button.

You plan to prevent users from accidentally deleting blob data from Azure.

You need to ensure that administrators can recover any blob data that is deleted accidentally from the

storagelod8322489 storage account for 14 days after the deletion occurred.

What should you do from the Azure portal?

[See the answer](#answer-207)

### Question 208

**SCENARIO:**

TESTLET-7.

Case Study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Contoso, Ltd. is a consulting company that has a main office in Montreal and two branch offices in Seattle

and New York.

The Montreal office has 2,000 employees. The Seattle office has 1,000 employees. The New York office

has 200 employees.

All the resources used by Contoso are hosted on-premises.

Contoso created a new Azure subscription. The Azure Active Directory (Azure AD) tenant uses a domain

named contoso.onmicrosoft.com. The tenant uses the P1 pricing tier.

Existing Environment

The network contains an Active Directory forest named contoso.com. All domain controllers are configured

as DNS servers and host the contoso.com DNS zone.

Contoso has finance, human resources, sales, research, and information technology departments. Each

department has an organizational unit (OU) that contains all the accounts of that respective department. All

the user accounts have the department attribute set to their respective department. New users are added

frequently.

Contoso.com contains a user named User1.

All the offices connect by using private links.

Contoso has data centers in the Montreal and Seattle offices. Each data center has a firewall that can be

configured as a VPN device.

All infrastructure servers are virtualized. The virtualization environment contains the servers in the following

table.

![](image/image-538.webp)

Contoso uses two web applications named App1 and App2. Each instance on each web application

requires 1 GB of memory.

The Azure subscription contains the resources in the following table.

![](image/image-539.webp)

The network security team implements several network security groups (NSGs).

Requirements

Planned Changes

Contoso plans to implement the following changes:

	- Deploy Azure ExpressRoute to the Montreal office

	- Migrate the virtual machine hosted on Server1 and Server2 to Azure

	- Synchronize on-premises Active Directory to Azure Active Directory (Azure AD)

	- Migrate App1 and App2 to two Azure web apps named WebApp1 and WebApp2.

Technical Requirements

Contoso must meet the following technical requirements:

	- Ensure that WebApp1 can adjust the number of instances automatically based on the load and can

scale up to five instances

	- Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in

the Montreal office

	- Ensure that routing information is exchanged automatically between Azure and the routers in the

Montreal office

	- Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only

	- Ensure that webapp2.azurewebsites.net can be accessed by using the name app2.contoso.com

	- Connect the New York office to VNet1 over the Internet by using an encrypted connection

	- Create a workflow to send an email message when the settings of VM4 are modified

	- Create a custom Azure role named Role1 that is based on the Reader role

	- Minimize costs whenever possible

You have an Azure subscription that contains the Azure virtual machines shown in the following table.

![](image/image-600.webp)

You create an Azure key vault named Vault1 in the East US location.

You need to identify which virtual machines can enable Azure Disk Encryption by using Vault1.

Which virtual machines should you identify?

* A: VM2 and VM3 only

* B: VM1, VM2, and VM4 only

* C: VM1, VM2, and VM3 only

* D: VM3 only

[See the answer](#answer-208)

### Question 209

**SCENARIO:**

TESTLET-7.

Case Study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Contoso, Ltd. is a consulting company that has a main office in Montreal and two branch offices in Seattle

and New York.

The Montreal office has 2,000 employees. The Seattle office has 1,000 employees. The New York office

has 200 employees.

All the resources used by Contoso are hosted on-premises.

Contoso created a new Azure subscription. The Azure Active Directory (Azure AD) tenant uses a domain

named contoso.onmicrosoft.com. The tenant uses the P1 pricing tier.

Existing Environment

The network contains an Active Directory forest named contoso.com. All domain controllers are configured

as DNS servers and host the contoso.com DNS zone.

Contoso has finance, human resources, sales, research, and information technology departments. Each

department has an organizational unit (OU) that contains all the accounts of that respective department. All

the user accounts have the department attribute set to their respective department. New users are added

frequently.

Contoso.com contains a user named User1.

All the offices connect by using private links.

Contoso has data centers in the Montreal and Seattle offices. Each data center has a firewall that can be

configured as a VPN device.

All infrastructure servers are virtualized. The virtualization environment contains the servers in the following

table.

![](image/image-538.webp)

Contoso uses two web applications named App1 and App2. Each instance on each web application

requires 1 GB of memory.

The Azure subscription contains the resources in the following table.

![](image/image-539.webp)

The network security team implements several network security groups (NSGs).

Requirements

Planned Changes

Contoso plans to implement the following changes:

	- Deploy Azure ExpressRoute to the Montreal office

	- Migrate the virtual machine hosted on Server1 and Server2 to Azure

	- Synchronize on-premises Active Directory to Azure Active Directory (Azure AD)

	- Migrate App1 and App2 to two Azure web apps named WebApp1 and WebApp2.

Technical Requirements

Contoso must meet the following technical requirements:

	- Ensure that WebApp1 can adjust the number of instances automatically based on the load and can

scale up to five instances

	- Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in

the Montreal office

	- Ensure that routing information is exchanged automatically between Azure and the routers in the

Montreal office

	- Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only

	- Ensure that webapp2.azurewebsites.net can be accessed by using the name app2.contoso.com

	- Connect the New York office to VNet1 over the Internet by using an encrypted connection

	- Create a workflow to send an email message when the settings of VM4 are modified

	- Create a custom Azure role named Role1 that is based on the Reader role

	- Minimize costs whenever possible

You have two Azure Active Directory (Azure AD) tenants named contoso.com and fabrikam.com.

You have a Microsoft account that you use to sign in to both tenants.

You need to configure the default sign-in tenant for the Azure portal.

What should you do?

* A: From the Azure portal, configure the portal settings

* B: From the Azure portal, change the directory

* C: From Azure Cloud Shell, run Set-AzureRmContext

* D: From Azure Cloud Shell, run Set-AzureRmSubscription

[See the answer](#answer-209)

### Question 210

**SCENARIO:**

TESTLET-7.

Case Study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Contoso, Ltd. is a consulting company that has a main office in Montreal and two branch offices in Seattle

and New York.

The Montreal office has 2,000 employees. The Seattle office has 1,000 employees. The New York office

has 200 employees.

All the resources used by Contoso are hosted on-premises.

Contoso created a new Azure subscription. The Azure Active Directory (Azure AD) tenant uses a domain

named contoso.onmicrosoft.com. The tenant uses the P1 pricing tier.

Existing Environment

The network contains an Active Directory forest named contoso.com. All domain controllers are configured

as DNS servers and host the contoso.com DNS zone.

Contoso has finance, human resources, sales, research, and information technology departments. Each

department has an organizational unit (OU) that contains all the accounts of that respective department. All

the user accounts have the department attribute set to their respective department. New users are added

frequently.

Contoso.com contains a user named User1.

All the offices connect by using private links.

Contoso has data centers in the Montreal and Seattle offices. Each data center has a firewall that can be

configured as a VPN device.

All infrastructure servers are virtualized. The virtualization environment contains the servers in the following

table.

![](image/image-538.webp)

Contoso uses two web applications named App1 and App2. Each instance on each web application

requires 1 GB of memory.

The Azure subscription contains the resources in the following table.

![](image/image-539.webp)

The network security team implements several network security groups (NSGs).

Requirements

Planned Changes

Contoso plans to implement the following changes:

	- Deploy Azure ExpressRoute to the Montreal office

	- Migrate the virtual machine hosted on Server1 and Server2 to Azure

	- Synchronize on-premises Active Directory to Azure Active Directory (Azure AD)

	- Migrate App1 and App2 to two Azure web apps named WebApp1 and WebApp2.

Technical Requirements

Contoso must meet the following technical requirements:

	- Ensure that WebApp1 can adjust the number of instances automatically based on the load and can

scale up to five instances

	- Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in

the Montreal office

	- Ensure that routing information is exchanged automatically between Azure and the routers in the

Montreal office

	- Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only

	- Ensure that webapp2.azurewebsites.net can be accessed by using the name app2.contoso.com

	- Connect the New York office to VNet1 over the Internet by using an encrypted connection

	- Create a workflow to send an email message when the settings of VM4 are modified

	- Create a custom Azure role named Role1 that is based on the Reader role

	- Minimize costs whenever possible

HOTSPOT

You network contains an Active Directory domain named adatum.com and an Azure Active Directory (Azure

AD) tenant named adatum.onmicrosoft.com.

Adatum.com contains the user accounts in the following table.

![](image/image-601.webp)

Adatum.onmicrosoft.com contains the user accounts in the following table.

![](image/image-602.webp)

You need to implement Azure AD Connect. The solution must follow the principle of least privilege.

Which user accounts should you use? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

Hot Area:

![](image/image-603.webp)

[See the answer](#answer-210)

### Question 211

**SCENARIO:**

TESTLET-7.

Case Study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Contoso, Ltd. is a consulting company that has a main office in Montreal and two branch offices in Seattle

and New York.

The Montreal office has 2,000 employees. The Seattle office has 1,000 employees. The New York office

has 200 employees.

All the resources used by Contoso are hosted on-premises.

Contoso created a new Azure subscription. The Azure Active Directory (Azure AD) tenant uses a domain

named contoso.onmicrosoft.com. The tenant uses the P1 pricing tier.

Existing Environment

The network contains an Active Directory forest named contoso.com. All domain controllers are configured

as DNS servers and host the contoso.com DNS zone.

Contoso has finance, human resources, sales, research, and information technology departments. Each

department has an organizational unit (OU) that contains all the accounts of that respective department. All

the user accounts have the department attribute set to their respective department. New users are added

frequently.

Contoso.com contains a user named User1.

All the offices connect by using private links.

Contoso has data centers in the Montreal and Seattle offices. Each data center has a firewall that can be

configured as a VPN device.

All infrastructure servers are virtualized. The virtualization environment contains the servers in the following

table.

![](image/image-538.webp)

Contoso uses two web applications named App1 and App2. Each instance on each web application

requires 1 GB of memory.

The Azure subscription contains the resources in the following table.

![](image/image-539.webp)

The network security team implements several network security groups (NSGs).

Requirements

Planned Changes

Contoso plans to implement the following changes:

	- Deploy Azure ExpressRoute to the Montreal office

	- Migrate the virtual machine hosted on Server1 and Server2 to Azure

	- Synchronize on-premises Active Directory to Azure Active Directory (Azure AD)

	- Migrate App1 and App2 to two Azure web apps named WebApp1 and WebApp2.

Technical Requirements

Contoso must meet the following technical requirements:

	- Ensure that WebApp1 can adjust the number of instances automatically based on the load and can

scale up to five instances

	- Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in

the Montreal office

	- Ensure that routing information is exchanged automatically between Azure and the routers in the

Montreal office

	- Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only

	- Ensure that webapp2.azurewebsites.net can be accessed by using the name app2.contoso.com

	- Connect the New York office to VNet1 over the Internet by using an encrypted connection

	- Create a workflow to send an email message when the settings of VM4 are modified

	- Create a custom Azure role named Role1 that is based on the Reader role

	- Minimize costs whenever possible

You sign up for Azure Active Directory (Azure AD) Premium.

You need to add a user named admin1@contoso.com ad an administrator on all the computers that will be

joined to the Azure AD domain.

What should you configure in Azure AD?

* A: Providers from the MFA Server blade

* B: General settings from the Groups blade

* C: Device settings from the Devices blade

* D: User settings from the Users blade

[See the answer](#answer-211)

### Question 212

**SCENARIO:**

TESTLET-8.

Case Study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Humongous Insurance is an insurance company that has three offices in Miami, Tokyo and Bangkok. Each

office has 5.000 users.

Existing Environment

Active Directory Environment

Humongous Insurance has a single-domain Active Directory forest named humongousinsurance.com. The

functional level of the forest is Windows Server 2012.

You recently provisioned an Azure Active Directory (Azure AD) tenant.

Network Infrastructure

Each office has a local data center that contains all the servers for that office. Each office has a dedicated

connection to the Internet.

Each office has several link load balancers that provide access to the servers.

Active Directory Issue

Several users in humongousinsurance.com have UPNs that contain special characters.

You suspect that some of the characters are unsupported in Azure AD.

Licensing Issue

You attempt to assign a license in Azure to several users and receive the following error message:

"Licenses not assigned. License agreement failed for one user."

You verify that the Azure subscription has the available licenses.

Requirements

Planned Changes

Humongous Insurance plans to open a new office in Paris. The Paris office will contain 1,000 users who will

be hired during the next 12 months. All the resources used by the Paris office users will be hosted in Azure.

Planned Azure AD Infrastructure

The on-premises Active Directory domain will be synchronized to Azure AD.

All client computers in the Paris office will be joined to an Azure AD domain.

Planned Azure Networking Infrastructure

You plan to create the following networking resources in a resource group named All_Resources:

	- Default Azure system routes that will be the only routes used to route traffic

	- A virtual network named Paris-VNet that will contain two subnets named Subnet1 and Subnet2

	- A virtual network named ClientResources-VNet that will contain one subnet named ClientSubnet

	- A virtual network named AllOffices-VNet that will contain two subnets named Subnet3 and Subnet4

You plan to enable peering between Paris-VNet and AllOffices-VNet. You will enable the Use remote

gateways setting for the Paris-VNet peerings.

You plan to create a private DNS zone named humongousinsurance.local and set the registration network

to the ClientResources-VNet virtual network.

Planned Azure Computer Infrastructure

Each subnet will contain several virtual machines that will run either Windows Server 2012 R2, Windows

Server 2016, or Red Hat Linux.

Department Requirements

Humongous Insurance identifies the following requirements for the company's departments:

	- Web administrators will deploy Azure web apps for the marketing department. Each web app will be

added to a separate resource group. The initial configuration of the web apps will be identical. The web

administrators have permission to deploy web apps to resource groups.

	- During the testing phase, auditors in the finance department must be able to review all Azure costs from

the past week.

Authentication Requirements

Users in the Miami office must use Azure Active Directory Seamless Single Sign-on (Azure AD Seamless

SSO) when accessing resources in Azure.

SIMULATION

Click to expand each objective. To connect to the Azure portal, type https://portal.azure.com in the browser

address bar.

![](image/image-608.webp)

![](image/image-609.webp)

![](image/image-610.webp)

![](image/image-611.webp)

![](image/image-612.webp)

![](image/image-613.webp)

When you are finished performing all the tasks, click the ‘Next’ button.

Note that you cannot return to the lab once you click the ‘Next’ button. Scoring occur in the background

while you complete the rest of the exam.

Overview 

The following section of the exam is a lab. In this section, you will perform a set of tasks in a live

environment. While most functionality will be available to you as it would be in a live environment, some

functionality (e.g., copy and paste, ability to navigate to external websites) will not be possible by design.

Scoring is based on the outcome of performing the tasks stated in the lab. In other words, it doesn’t matter

how you accomplish the task, if you successfully perform it, you will earn credit for that task.

Labs are not timed separately, and this exam may have more than one lab that you must complete. You

can use as much time as you would like to complete each lab. But, you should manage your time

appropriately to ensure that you are able to complete the lab(s) and all other sections of the exam in the

time provided.

Please note that once you submit your work by clicking the Next button within a lab, you will NOT be able to

return to the lab.

To start the lab

You may start the lab by clicking the Next button.

You plan to protect on-premises virtual machines and Azure virtual machines by using Azure Backup.

You need to prepare the backup infrastructure in Azure. The solution must minimize the cost of storing the

backups in Azure.

What should you do from the Azure portal?

[See the answer](#answer-212)

### Question 213

**SCENARIO:**

TESTLET-8.

Case Study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Humongous Insurance is an insurance company that has three offices in Miami, Tokyo and Bangkok. Each

office has 5.000 users.

Existing Environment

Active Directory Environment

Humongous Insurance has a single-domain Active Directory forest named humongousinsurance.com. The

functional level of the forest is Windows Server 2012.

You recently provisioned an Azure Active Directory (Azure AD) tenant.

Network Infrastructure

Each office has a local data center that contains all the servers for that office. Each office has a dedicated

connection to the Internet.

Each office has several link load balancers that provide access to the servers.

Active Directory Issue

Several users in humongousinsurance.com have UPNs that contain special characters.

You suspect that some of the characters are unsupported in Azure AD.

Licensing Issue

You attempt to assign a license in Azure to several users and receive the following error message:

"Licenses not assigned. License agreement failed for one user."

You verify that the Azure subscription has the available licenses.

Requirements

Planned Changes

Humongous Insurance plans to open a new office in Paris. The Paris office will contain 1,000 users who will

be hired during the next 12 months. All the resources used by the Paris office users will be hosted in Azure.

Planned Azure AD Infrastructure

The on-premises Active Directory domain will be synchronized to Azure AD.

All client computers in the Paris office will be joined to an Azure AD domain.

Planned Azure Networking Infrastructure

You plan to create the following networking resources in a resource group named All_Resources:

	- Default Azure system routes that will be the only routes used to route traffic

	- A virtual network named Paris-VNet that will contain two subnets named Subnet1 and Subnet2

	- A virtual network named ClientResources-VNet that will contain one subnet named ClientSubnet

	- A virtual network named AllOffices-VNet that will contain two subnets named Subnet3 and Subnet4

You plan to enable peering between Paris-VNet and AllOffices-VNet. You will enable the Use remote

gateways setting for the Paris-VNet peerings.

You plan to create a private DNS zone named humongousinsurance.local and set the registration network

to the ClientResources-VNet virtual network.

Planned Azure Computer Infrastructure

Each subnet will contain several virtual machines that will run either Windows Server 2012 R2, Windows

Server 2016, or Red Hat Linux.

Department Requirements

Humongous Insurance identifies the following requirements for the company's departments:

	- Web administrators will deploy Azure web apps for the marketing department. Each web app will be

added to a separate resource group. The initial configuration of the web apps will be identical. The web

administrators have permission to deploy web apps to resource groups.

	- During the testing phase, auditors in the finance department must be able to review all Azure costs from

the past week.

Authentication Requirements

Users in the Miami office must use Azure Active Directory Seamless Single Sign-on (Azure AD Seamless

SSO) when accessing resources in Azure.

You need to prepare the environment to meet the authentication requirements.

Which two actions should you perform? Each correct answer presents part of the solution

NOTE: Each correct selection is worth one point.

* A: Allow inbound TCP port 8080 to the domain controllers in the Miami office

* B: Install Azure AD Connect on a server in the Miami office and enable Pass-through Authentication

* C: Install the Active Directory Federation Services (AD FS) role on a domain controller in the Miami office

* D: Join the client computers in the Miami office to Azure AD

* E: Add http://autologon.microsoftazuread-sso.com to the intranet zone of each client computer in the Miami

office.

[See the answer](#answer-213)

### Question 214

**SCENARIO:**

TESTLET-9.

Case study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Contoso, Ltd. is a consulting company that has a main office in Montreal and two branch offices in Seattle

and New York.

The Montreal office has 2,000 employees. The Seattle office has 1,000 employees. The New York office

has 200 employees.

All the resources used by Contoso are hosted on-premises.

Contoso creates a new Azure subscription. The Azure Active Directory (Azure AD) tenant uses a domain

named contoso.onmicrosoft.com. The tenant uses the P1 pricing tier.

Existing Environment

The network contains an Active Directory forest named contoso.com. All domain controllers are configured

as DNS servers and host the contoso.com DNS zone.

Contoso has finance, human resources, sales, research, and information technology departments. Each

department has an organizational unit (OU) that contains all the accounts of that respective department. All

the user accounts have the department attribute set to their respective department. New users are added

frequently.

Contoso.com contains a user named User1.

All the offices connect by using private links.

Contoso has data centers in the Montreal and Seattle offices. Each data center has a firewall that can be

configured as a VPN device.

All infrastructure servers are virtualized. The virtualization environment contains the servers in the following

table.

![](image/image-623.webp)

Contoso uses two web applications named App1 and App2. Each instance on each web application

requires 1GB of memory.

The Azure subscription contains the resources in the following table.

![](image/image-624.webp)

The network security team implements several network security groups (NSGs).

Planned Changes

Contoso plans to implement the following changes:

	- Deploy Azure ExpressRoute to the Montreal office.

	- Migrate the virtual machines hosted on Server1 and Server2 to Azure.

	- Synchronize on-premises Active Directory to Azure Active Directory (Azure AD).

	- Migrate App1 and App2 to two Azure web apps named WebApp1 and WebApp2.

Technical Requirements

Contoso must meet the following technical requirements:

	- Ensure that WebApp1 can adjust the number of instances automatically based on the load and can

scale up to five instances.

	- Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in

the Montreal office.

	- Ensure that routing information is exchanged automatically between Azure and the routers in the

Montreal office.

	- Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only.

	- Ensure that webapp2.azurewebsites.net can be accessed by using the name app2.contoso.com

	- Connect the New York office to VNet1 over the Internet by using an encrypted connection.

	- Create a workflow to send an email message when the settings of VM4 are modified.

	- Create a custom Azure role named Role1 that is based on the Reader role.

	- Minimize costs whenever possible.

Which blade should you instruct the finance department auditors to use?

* A: Partner information

* B: Cost analysis

* C: Resource providers

* D: Invoices

[See the answer](#answer-214)

### Question 215

**SCENARIO:**

TESTLET-9.

Case study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Contoso, Ltd. is a consulting company that has a main office in Montreal and two branch offices in Seattle

and New York.

The Montreal office has 2,000 employees. The Seattle office has 1,000 employees. The New York office

has 200 employees.

All the resources used by Contoso are hosted on-premises.

Contoso creates a new Azure subscription. The Azure Active Directory (Azure AD) tenant uses a domain

named contoso.onmicrosoft.com. The tenant uses the P1 pricing tier.

Existing Environment

The network contains an Active Directory forest named contoso.com. All domain controllers are configured

as DNS servers and host the contoso.com DNS zone.

Contoso has finance, human resources, sales, research, and information technology departments. Each

department has an organizational unit (OU) that contains all the accounts of that respective department. All

the user accounts have the department attribute set to their respective department. New users are added

frequently.

Contoso.com contains a user named User1.

All the offices connect by using private links.

Contoso has data centers in the Montreal and Seattle offices. Each data center has a firewall that can be

configured as a VPN device.

All infrastructure servers are virtualized. The virtualization environment contains the servers in the following

table.

![](image/image-623.webp)

Contoso uses two web applications named App1 and App2. Each instance on each web application

requires 1GB of memory.

The Azure subscription contains the resources in the following table.

![](image/image-624.webp)

The network security team implements several network security groups (NSGs).

Planned Changes

Contoso plans to implement the following changes:

	- Deploy Azure ExpressRoute to the Montreal office.

	- Migrate the virtual machines hosted on Server1 and Server2 to Azure.

	- Synchronize on-premises Active Directory to Azure Active Directory (Azure AD).

	- Migrate App1 and App2 to two Azure web apps named WebApp1 and WebApp2.

Technical Requirements

Contoso must meet the following technical requirements:

	- Ensure that WebApp1 can adjust the number of instances automatically based on the load and can

scale up to five instances.

	- Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in

the Montreal office.

	- Ensure that routing information is exchanged automatically between Azure and the routers in the

Montreal office.

	- Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only.

	- Ensure that webapp2.azurewebsites.net can be accessed by using the name app2.contoso.com

	- Connect the New York office to VNet1 over the Internet by using an encrypted connection.

	- Create a workflow to send an email message when the settings of VM4 are modified.

	- Create a custom Azure role named Role1 that is based on the Reader role.

	- Minimize costs whenever possible.

You need to recommend a solution to automate the configuration for the finance department users. The

solution must meet the technical requirements.

What should you include in the recommendation?

* A: an Azure logic app and the Microsoft Identity Management (MIM) client

* B: Azure AD Identity Protection

* C: dynamic groups and conditional access policies

* D: Azure AD B2C

[See the answer](#answer-215)

### Question 216

**SCENARIO:**

TESTLET-9.

Case study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Contoso, Ltd. is a consulting company that has a main office in Montreal and two branch offices in Seattle

and New York.

The Montreal office has 2,000 employees. The Seattle office has 1,000 employees. The New York office

has 200 employees.

All the resources used by Contoso are hosted on-premises.

Contoso creates a new Azure subscription. The Azure Active Directory (Azure AD) tenant uses a domain

named contoso.onmicrosoft.com. The tenant uses the P1 pricing tier.

Existing Environment

The network contains an Active Directory forest named contoso.com. All domain controllers are configured

as DNS servers and host the contoso.com DNS zone.

Contoso has finance, human resources, sales, research, and information technology departments. Each

department has an organizational unit (OU) that contains all the accounts of that respective department. All

the user accounts have the department attribute set to their respective department. New users are added

frequently.

Contoso.com contains a user named User1.

All the offices connect by using private links.

Contoso has data centers in the Montreal and Seattle offices. Each data center has a firewall that can be

configured as a VPN device.

All infrastructure servers are virtualized. The virtualization environment contains the servers in the following

table.

![](image/image-623.webp)

Contoso uses two web applications named App1 and App2. Each instance on each web application

requires 1GB of memory.

The Azure subscription contains the resources in the following table.

![](image/image-624.webp)

The network security team implements several network security groups (NSGs).

Planned Changes

Contoso plans to implement the following changes:

	- Deploy Azure ExpressRoute to the Montreal office.

	- Migrate the virtual machines hosted on Server1 and Server2 to Azure.

	- Synchronize on-premises Active Directory to Azure Active Directory (Azure AD).

	- Migrate App1 and App2 to two Azure web apps named WebApp1 and WebApp2.

Technical Requirements

Contoso must meet the following technical requirements:

	- Ensure that WebApp1 can adjust the number of instances automatically based on the load and can

scale up to five instances.

	- Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in

the Montreal office.

	- Ensure that routing information is exchanged automatically between Azure and the routers in the

Montreal office.

	- Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only.

	- Ensure that webapp2.azurewebsites.net can be accessed by using the name app2.contoso.com

	- Connect the New York office to VNet1 over the Internet by using an encrypted connection.

	- Create a workflow to send an email message when the settings of VM4 are modified.

	- Create a custom Azure role named Role1 that is based on the Reader role.

	- Minimize costs whenever possible.

HOTSPOT

You need to prepare the environment to implement the planned changes for Server2.

What should you do? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

Hot Area:

![](image/image-638.webp)

[See the answer](#answer-216)

### Question 217

**SCENARIO:**

TESTLET-9.

Case study

This is a case study. Case studies are not timed separately. You can use as much exam time as you

would like to complete each case. However, there may be additional case studies and sections on this

exam. You must manage your time to ensure that you are able to complete all questions included on this

exam in the time provided.

To answer the questions included in a case study, you will need to reference information that is provided in

the case study. Case studies might contain exhibits and other resources that provide more information

about the scenario that is described in the case study. Each question is independent of the other questions

in this case study.

At the end of this case study, a review screen will appear. This screen allows you to review your answers

and to make changes before you move to the next section of the exam. After you begin a new section, you

cannot return to this section.

To start the case study

To display the first question in this case study, click the Next button. Use the buttons in the left pane to

explore the content of the case study before you answer the questions. Clicking these buttons displays

information such as business requirements, existing environment, and problem statements. If the case

study has an All Information tab, note that the information displayed is identical to the information

displayed on the subsequent tabs. When you are ready to answer a question, click the Question button to

return to the question.

Overview

Contoso, Ltd. is a consulting company that has a main office in Montreal and two branch offices in Seattle

and New York.

The Montreal office has 2,000 employees. The Seattle office has 1,000 employees. The New York office

has 200 employees.

All the resources used by Contoso are hosted on-premises.

Contoso creates a new Azure subscription. The Azure Active Directory (Azure AD) tenant uses a domain

named contoso.onmicrosoft.com. The tenant uses the P1 pricing tier.

Existing Environment

The network contains an Active Directory forest named contoso.com. All domain controllers are configured

as DNS servers and host the contoso.com DNS zone.

Contoso has finance, human resources, sales, research, and information technology departments. Each

department has an organizational unit (OU) that contains all the accounts of that respective department. All

the user accounts have the department attribute set to their respective department. New users are added

frequently.

Contoso.com contains a user named User1.

All the offices connect by using private links.

Contoso has data centers in the Montreal and Seattle offices. Each data center has a firewall that can be

configured as a VPN device.

All infrastructure servers are virtualized. The virtualization environment contains the servers in the following

table.

![](image/image-623.webp)

Contoso uses two web applications named App1 and App2. Each instance on each web application

requires 1GB of memory.

The Azure subscription contains the resources in the following table.

![](image/image-624.webp)

The network security team implements several network security groups (NSGs).

Planned Changes

Contoso plans to implement the following changes:

	- Deploy Azure ExpressRoute to the Montreal office.

	- Migrate the virtual machines hosted on Server1 and Server2 to Azure.

	- Synchronize on-premises Active Directory to Azure Active Directory (Azure AD).

	- Migrate App1 and App2 to two Azure web apps named WebApp1 and WebApp2.

Technical Requirements

Contoso must meet the following technical requirements:

	- Ensure that WebApp1 can adjust the number of instances automatically based on the load and can

scale up to five instances.

	- Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in

the Montreal office.

	- Ensure that routing information is exchanged automatically between Azure and the routers in the

Montreal office.

	- Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only.

	- Ensure that webapp2.azurewebsites.net can be accessed by using the name app2.contoso.com

	- Connect the New York office to VNet1 over the Internet by using an encrypted connection.

	- Create a workflow to send an email message when the settings of VM4 are modified.

	- Create a custom Azure role named Role1 that is based on the Reader role.

	- Minimize costs whenever possible.

You discover that VM3 does NOT meet the technical requirements.

You need to verify whether the issue relates to the NSGs.

What should you use?

* A: Diagram in VNet1

* B: Diagnostic settings in Azure Monitor

* C: IP flow verify in Azure Network Watcher

* D: Diagnose and solve problems in Traffic Manager profiles

* E: the security recommendations in Azure Advisor

[See the answer](#answer-217)

### Question 218

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

HOTSPOT

You need to implement Role1.

Which command should you run before you create Role1? To answer, select the appropriate options in the

answer area.

NOTE: Each correct selection is worth one point.

Hot Area:

![](image/image-640.webp)

[See the answer](#answer-218)

### Question 219

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

Note: This question is part of a series of questions that present the same scenario. Each question

in the series contains a unique solution. Determine whether the solution meets the stated goals.

You need to meet the vendor notification requirement.

Solution: Update the Delivery API to send emails by using a Microsoft Office 365 SMTP server.

Does the solution meet the goal?

* A: Yes

* B: No

[See the answer](#answer-219)

### Question 220

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

Note: This question is part of a series of questions that present the same scenario. Each question

in the series contains a unique solution. Determine whether the solution meets the stated goals.

You need to meet the vendor notification requirement.

Solution: Configure notifications in the Azure API Management instance.

Does the solution meet the goal?

* A: Yes

* B: No

[See the answer](#answer-220)

### Question 221

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

Note: This question is part of a series of questions that present the same scenario. Each question

in the series contains a unique solution. Determine whether the solution meets the stated goals.

You need to meet the vendor notification requirement.

Solution: Update the Delivery API to send emails by using a cloud-based email service.

Does the solution meet the goal?

* A: Yes

* B: No

[See the answer](#answer-221)

### Question 222

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

You need to meet the vendor notification requirement.

Solution: Create and apply a custom outbound Azure API Management policy.

Does the solution meet the goal?

* A: Yes

* B: No

[See the answer](#answer-222)

### Question 223

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

You need to resolve the delivery API error.

What should you do?

* A: Implement simple retry by using the EnableRetryOnFailure feature of Entity Framework.

* B: Implement exponential backoff by using the EnableRetryOnFailure feature of Entity Framework.

* C: Implement a Circuit Breaker pattern by using the EnableRetryOnFailure feature of Entity Framework.

* D: Invoke a custom execution strategy in Entity Framework.

[See the answer](#answer-223)

### Question 224

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

You need to implement the purchase requirement.

What should you do?

* A: Use the Bot Framework REST API conversation operations to send the user’s voice and the Speech

Service API to recognize intents.

* B: Use the Direct Line REST API to send the user’s voice and the Speech Service API to recognize intents.

* C: Use the Speech Service API to send the user’s voice and the Bot Framework REST API conversation

operations to recognize intents.

* D: Use the Bot Framework REST API attachment operations to send the user’s voice and the Speech

Service API to recognize intents.

[See the answer](#answer-224)

### Question 225

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

You need to meet the security requirements.

What should you use?

* A: HTTP Strict Transport Security (HSTS)

* B: Direct Line API

* C: Multi-Factor Authentication (MFA)

* D: Bot Framework Portal

* E: Bot Framework authentication

[See the answer](#answer-225)

### Question 226

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

SIMULATION

Click to expand each objective. To connect to the Azure portal, type https://portal.azure.com in the browser

address bar.

![](image/image-658.webp)

![](image/image-659.webp)

![](image/image-660.webp)

![](image/image-661.webp)

![](image/image-662.webp)

![](image/image-663.webp)

When you are finished performing all the tasks, click the ‘Next’ button.

Note that you cannot return to the lab once you click the ‘Next’ button. Scoring occur in the background

while you complete the rest of the exam.

Overview 

The following section of the exam is a lab. In this section, you will perform a set of tasks in a live

environment. While most functionality will be available to you as it would be in a live environment, some

functionality (e.g., copy and paste, ability to navigate to external websites) will not be possible by design.

Scoring is based on the outcome of performing the tasks stated in the lab. In other words, it doesn’t matter

how you accomplish the task, if you successfully perform it, you will earn credit for that task.

Labs are not timed separately, and this exam may have more than one lab that you must complete. You

can use as much time as you would like to complete each lab. But, you should manage your time

appropriately to ensure that you are able to complete the lab(s) and all other sections of the exam in the

time provided.

Please note that once you submit your work by clicking the Next button within a lab, you will NOT be able to

return to the lab.

To start the lab

You may start the lab by clicking the Next button.

You need to create a web app named corp10217507n2 that can be scaled horizontally. The solution must

use the lowest possible pricing tier for the App Service plan.

What should you do from the Azure portal?

[See the answer](#answer-226)

### Question 227

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

SIMULATION

Click to expand each objective. To connect to the Azure portal, type https://portal.azure.com in the browser

address bar.

![](image/image-664.webp)

![](image/image-665.webp)

![](image/image-666.webp)

![](image/image-667.webp)

![](image/image-668.webp)

![](image/image-669.webp)

When you are finished performing all the tasks, click the ‘Next’ button.

Note that you cannot return to the lab once you click the ‘Next’ button. Scoring occur in the background

while you complete the rest of the exam.

Overview 

The following section of the exam is a lab. In this section, you will perform a set of tasks in a live

environment. While most functionality will be available to you as it would be in a live environment, some

functionality (e.g., copy and paste, ability to navigate to external websites) will not be possible by design.

Scoring is based on the outcome of performing the tasks stated in the lab. In other words, it doesn’t matter

how you accomplish the task, if you successfully perform it, you will earn credit for that task.

Labs are not timed separately, and this exam may have more than one lab that you must complete. You

can use as much time as you would like to complete each lab. But, you should manage your time

appropriately to ensure that you are able to complete the lab(s) and all other sections of the exam in the

time provided.

Please note that once you submit your work by clicking the Next button within a lab, you will NOT be able to

return to the lab.

To start the lab

You may start the lab by clicking the Next button.

You need to deploy an application gateway named appgw1015 to meet the following requirements:

	- Load balance internal IP traffic to the Azure virtual machines connected to subnet0.

	- Provide a Service Level Agreement (SLA) of 99,99 percent availability for the Azure virtual machines.

What should you do from the Azure portal?

[See the answer](#answer-227)

### Question 228

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

SIMULATION

Click to expand each objective. To connect to the Azure portal, type https://portal.azure.com in the browser

address bar.

![](image/image-673.webp)

![](image/image-674.webp)

![](image/image-675.webp)

![](image/image-676.webp)

![](image/image-677.webp)

![](image/image-678.webp)

When you are finished performing all the tasks, click the ‘Next’ button.

Note that you cannot return to the lab once you click the ‘Next’ button. Scoring occur in the background

while you complete the rest of the exam.

Overview 

The following section of the exam is a lab. In this section, you will perform a set of tasks in a live

environment. While most functionality will be available to you as it would be in a live environment, some

functionality (e.g., copy and paste, ability to navigate to external websites) will not be possible by design.

Scoring is based on the outcome of performing the tasks stated in the lab. In other words, it doesn’t matter

how you accomplish the task, if you successfully perform it, you will earn credit for that task.

Labs are not timed separately, and this exam may have more than one lab that you must complete. You

can use as much time as you would like to complete each lab. But, you should manage your time

appropriately to ensure that you are able to complete the lab(s) and all other sections of the exam in the

time provided.

Please note that once you submit your work by clicking the Next button within a lab, you will NOT be able to

return to the lab.

To start the lab

You may start the lab by clicking the Next button.

You need to deploy an Azure load balancer named ib1016 to your Azure subscription. The solution must

meet the following requirements:

	- Support the load balancing of IP traffic from the Internet to Azure virtual machines connected to

VNET1016\subnet0.

	- Provide a Service Level Agreement (SLA) of 99,99 percent availability for the Azure virtual machines.

	- Minimize Azure-related costs.

What should you do from the Azure portal?

To complete this task, you do NOT need to wait for the deployment to complete. Once the

deployment starts in Azure, you can move to the next task.

[See the answer](#answer-228)

### Question 229

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

Your company is developing an e-commerce Azure App Service Web App to support hundreds of

restaurant locations around the world.

You are designing the messaging solution architecture to support the e-commerce transactions and

messages. The solution will include the following features:

![](image/image-682.webp)

You need to design a solution for the Inventory Distribution feature.

Which Azure service should you use?

* A: Azure Service Bus

* B: Azure Relay

* C: Azure Event Grid

* D: Azure Event Hub

[See the answer](#answer-229)

### Question 230

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

You are responsible for mobile app development for a company. The company develops apps on Windows

Mobile, IOS, and Android.

You plan to integrate push notifications into every app.

You need to be able to send users alerts from a backend server.

Which two options can you use to achieve this goal? Each correct answer presents a complete solution.

NOTE: Each correct selection is worth one point.

* A: Azure Web App

* B: Azure Mobile App Service

* C: Azure SQL Database

* D: Azure Notification Hubs

* E: a virtual machine

[See the answer](#answer-230)

### Question 231

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

HOTSPOT

You are developing an Azure Function that will be triggered using a webhook from an external application.

The Azure Function will receive JSON data in the body of the request.

Calling applications send an account ID as part of the URL. The number at the end of the URL is an integer.

The format for the URL resembles the following: /api/account/1

The Azure Function must accept all incoming requests without requiring keys or tokens.

You need to complete the attributes for the Azure Function.

How should you complete the code? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

Hot Area:

![](image/image-688.webp)

[See the answer](#answer-231)

### Question 232

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

HOTSPOT

You are developing a workflow solution using Azure technologies.

What should you implement to meet each requirement? To answer, select the appropriate options in the

answer area.

NOTE: Each correct selection is worth one point.

Hot Area:

![](image/image-690.webp)

[See the answer](#answer-232)

### Question 233

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

HOTSPOT

You are developing a SMS-based testing solution. The solution sends users a question by using SMS. Early

responders may qualify for prizes.

Users must respond with an answer choice within 90 seconds. You must be able to track how long it takes

each user to respond. You create a durable Azure Function named SendSmsQuizQuestion that uses Twilio

to send messages.

You need to write the code for MessageQuiz.

How should you complete the code? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

Hot Area:

![](image/image-692.webp)

[See the answer](#answer-233)

### Question 234

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

HOTSPOT

You are developing a solution that requires serverless code execution in Azure.

The solution has two functions that must run in a specific order.

You need to ensure that the second function can use the output from the first function.

How should you complete the code? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

Hot Area:

![](image/image-694.webp)

[See the answer](#answer-234)

### Question 235

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

You are developing an app that references data which is sharded across multiple Azure SQL databases.

The app must guarantee transactional consistency for changes across several different sharding key

values.

You need to manage the transactions.

What should you implement?

* A: Elastic database transactions with horizontal partitioning.

* B: Distributed transactions coordinated by Microsoft Distributed Transaction Coordinator (MSDTC).

* C: Server-coordinated transactions from .NET application.

* D: Elastic database transactions with vertical partitioning.

[See the answer](#answer-235)

### Question 236

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

HOTSPOT

You are creating a bot for a company by using QnA Maker.

You need to ensure that the company can update the bot without third-party assistance.

What should you use? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

Hot Area:

![](image/image-696.webp)

[See the answer](#answer-236)

### Question 237

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

You are developing a speech-enabled home automation control bot.

The bot interprets some spoken words incorrectly.

You need to improve the spoken word recognition for the bot.

What should you implement?

* A: The Skype for Business Channel and use scorable dialogs for improving conversation flow.

* B: The Web Chat Channel and Speech priming using a Bing Speech Service and LUIS app.

* C: The Skype Channel and use scorable dialogs for improving conversation flow.

* D: The Cortana Channel and use scorable dialogs for improving conversation flow.

[See the answer](#answer-237)

### Question 238

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

DRAG DROP

Your company develops a bot that uses QnA Maker knowledge bases and Language Understanding

Intelligence Services  (LUIS). You create the QnA Maker service, knowledge bases, and the LUIS app.

The bot application must use LUIS to determine which QnA Maker knowledge base to use.

You need to integrate LUIS with the QnA Maker knowledge bases and maximize the effectiveness for

selecting the QnA Maker knowledge bases before testing the bot.

Which four actions should you perform in sequence? To answer, move the appropriate actions from the list

of actions to the answer area and arrange them in the correct order.

Select and Place:

![](image/image-698.webp)

[See the answer](#answer-238)

### Question 239

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

HOTSPOT

You create a virtual machine scale set named Scale1. Scale1 is configured as shown in the following

exhibit.

![](image/image-700.webp)

Use the drop-down menus to select the answer choice that completes each statement based on the

information presented in the graphic.

NOTE: Each correct selection is worth one point.

Hot Area:

![](image/image-701.webp)

[See the answer](#answer-239)

### Question 240

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

HOTSPOT

Your company hosts multiple website by using Azure virtual machine scale sets (VMSS) that run Internet

Information Server (IIS).

All network communications must be secured by using end to end Secure Socket Layer (SSL) encryption.

User sessions must be routed to the same server by using cookie-based session affinity.

The image shown depicts the network traffic flow for the web sites to the VMSS.

![](image/image-703.webp)

Use the drop-down menus to select the answer choice that answers each question.

NOTE: Each correct selection is worth one point.

Hot Area:

![](image/image-704.webp)

[See the answer](#answer-240)

### Question 241

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

SIMULATION

Click to expand each objective. To connect to the Azure portal, type https://portal.azure.com in the browser

address bar.

![](image/image-707.webp)

![](image/image-708.webp)

![](image/image-709.webp)

![](image/image-710.webp)

![](image/image-711.webp)

![](image/image-712.webp)

When you are finished performing all the tasks, click the ‘Next’ button.

Note that you cannot return to the lab once you click the ‘Next’ button. Scoring occur in the background

while you complete the rest of the exam.

Overview 

The following section of the exam is a lab. In this section, you will perform a set of tasks in a live

environment. While most functionality will be available to you as it would be in a live environment, some

functionality (e.g., copy and paste, ability to navigate to external websites) will not be possible by design.

Scoring is based on the outcome of performing the tasks stated in the lab. In other words, it doesn’t matter

how you accomplish the task, if you successfully perform it, you will earn credit for that task.

Labs are not timed separately, and this exam may have more than one lab that you must complete. You

can use as much time as you would like to complete each lab. But, you should manage your time

appropriately to ensure that you are able to complete the lab(s) and all other sections of the exam in the

time provided.

Please note that once you submit your work by clicking the Next button within a lab, you will NOT be able to

return to the lab.

To start the lab

You may start the lab by clicking the Next button.

You need to create a virtual network named VNET1008 that contains three subnets named subnet0,

subnet1, and subnet2. The solution must meet the following requirements:

	- Connections from any of the subnets to the Internet must be blocked

	- Connections from the Internet to any of the subnets must be blocked

	- The number of network security groups (NSGs) and NSG rules must be minimized

What should you do from the Azure portal?

[See the answer](#answer-241)

### Question 242

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

A company is migrating an existing on-premises third-party website to Azure. The website is stateless.

The company does not have access to the source code for the website. They do not have the original

installer.

The number of visitors at the website varies throughout the year. The on-premises infrastructure was

resized to accommodate peaks but the extra capacity was not used.

You need to implement a virtual machine scale set instance.

What should you do?

* A: Use an autoscale setting to scale instances vertically

* B: Create 100 autoscale settings per resource

* C: Scale out by one instance when the average CPU usage of one of the instances is over 80 percent

* D: Use Azure Monitor to create autoscale settings using custom metrics

* E: Use an autoscale setting with unlimited maximum number of instances

* F: Use a webhook to log autoscale failures

[See the answer](#answer-242)

### Question 243

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

You have an Azure subscription named Subscription1.

You create several Azure virtual machines in Subscription1. All of the virtual machines belong to the same

virtual network.

You have an on-premises Hyper-V server named Server1. Server1 hosts a virtual machine named VM1.

You plan to replicate VM1 to Azure.

You need to create additional objects in Subscription1 to support the planned deployment.

Which three objects should you create? Each correct answer presents part of the solution.

NOTE: Each correct selection is worth one point.

* A: Hyper-V site

* B: Azure Recovery Services Vault

* C: storage account

* D: replication policy

* E: Azure Traffic Manager instance

* F: endpoint

[See the answer](#answer-243)

### Question 244

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

Your company is developing an e-commerce Azure App Service Web App to support hundreds of

restaurant locations around the world.

You are designing the messaging solution architecture to support the e-commerce transactions and

messages. The e-commerce application has the following features and requirements:

![](image/image-716.webp)

You need to choose the Azure messaging solution to support the Restaurant Telemetry feature. 

Which Azure service should you use?

* A: Azure Relay

* B: Azure Event Grid

* C: Azure Event Hub

* D: Azure Service Bus

[See the answer](#answer-244)

### Question 245

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

A company is migrating an existing on-premises third-party website to Azure. The website is stateless.

The company does not have access to the source code for the website. They have the original installer.

The number of visitors at the website varies throughout the year. The on-premises infrastructure was

resized to accommodate peaks but the extra capacity was not used.

You need to implement a virtual machine scale set instance.

What should you do

* A: Use a webhook to log autoscale failures.

* B: Use an autoscale setting to scale instances vertically.

* C: Use only default diagnostics metrics to trigger autoscaling

* D: Use an autoscale setting to define more profiles that have one or more autoscale rules.

[See the answer](#answer-245)

### Question 246

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

Note: This question is part of series of questions that present the same scenario. Each question in

the series contains a unique solution that might meet the stated goals. Some question sets might

have more than one correct solution, while others might not have a correct solution.

After you answer a question in this section, you will NOT be able to return to it. As a result, these

questions will not appear in the review screen.

You have an Azure Cosmos DB database that contains a container named Container1. The partition key for

Container1 is set to /day. Container1 contains the items shown in the following table.

![](image/image-721.webp)

You need to programmatically query Azure Cosmos DB and retrieve Item1 and Item2 only.

Solution: You run the following query.

![](image/image-722.webp)

You set the EnableCrossPartitionQuery property to False.

Does this meet the goal?

* A: Yes

* B: No

[See the answer](#answer-246)

### Question 247

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

Note: This question is part of series of questions that present the same scenario. Each question in

the series contains a unique solution that might meet the stated goals. Some question sets might

have more than one correct solution, while others might not have a correct solution.

After you answer a question in this section, you will NOT be able to return to it. As a result, these

questions will not appear in the review screen.

You have an Azure Cosmos DB database that contains a container named Container1. The partition key for

Container1 is set to /day. Container1 contains the items shown in the following table.

![](image/image-723.webp)

You need to programmatically query Azure Cosmos DB and retrieve Item1 and Item2 only.

Solution: You run the following query.

![](image/image-724.webp)

You set the EnableCrossPartitionQuery property to True.

Does this meet the goal?

* A: Yes

* B: No

[See the answer](#answer-247)

### Question 248

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

Note: This question is part of series of questions that present the same scenario. Each question in

the series contains a unique solution that might meet the stated goals. Some question sets might

have more than one correct solution, while others might not have a correct solution.

After you answer a question in this section, you will NOT be able to return to it. As a result, these

questions will not appear in the review screen.

You have an Azure Cosmos DB database that contains a container named Container1. The partition key for

Container1 is set to /day. Container1 contains the items shown in the following table.

![](image/image-725.webp)

You need to programmatically query Azure Cosmos DB and retrieve Item1 and Item2 only.

Solution: You run the following query.

![](image/image-726.webp)

You set the EnableCrossPartitionQuery property to True.

Does this meet the goal?

* A: Yes

* B: No

[See the answer](#answer-248)

### Question 249

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

HOTSPOT

From Azure Cosmos DB, you create the containers shown in the following table.

![](image/image-727.webp)

You add the following item to Container1.

![](image/image-728.webp)

You plan to add items to Azure Cosmos DB as shown in the following table.

![](image/image-729.webp)

You need to identify which items can be added successfully to Container1 and Container2.

What should you identify for each container? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

Hot Area:

![](image/image-730.webp)

[See the answer](#answer-249)

### Question 250

**SCENARIO:**

TESTLET-10.

Case Study

Background

Best For You Organics Company is a global restaurant franchise that has multiple locations. The company

wants to enhance user experiences and vendor integrations. The company plans to implement automated

mobile ordering and delivery services.

Best For You Organics hosts an Azure web app at the URL https://www.bestforyouorganics.com. Users can

use the web app to browse restaurant location, menu items, nutritional information, and company

information. The company developed and deployed a cross-platform mobile app.

Requirements

Chatbot

You must develop a chatbot by using the Bot Builder SDK and Language Understanding Intelligence

Service (LUIS). The chatbot must allow users to order food for pickup or delivery.

The chatbot must meet the following requirements:

	- Ensure that chatbot is secure by using the Bot Framework connector.

	- Use natural language processing and speech recognition so that users can interact with the chatbot by

using text and voice. Processing must be server-based.

	- Alert users about promotions at local restaurants.

	- Enable users to place an order for delivery or pickup by using their voice.

	- Greet the user upon sign-in by displaying a graphical interface that contains action buttons.

	- The chatbot greeting interface must match the formatting of the following example:

![](image/image-648.webp)

Vendor API

Vendors receive and provide updates for the restaurant inventory and delivery services by using Azure API

Management hosted APIs. Each vendor uses their own subscription to access each of the APIs.

APIs must meet the following conditions:

	- API usage must not exceed 5,000 calls and 50,000 kilobytes of bandwidth per hour per vendor.

	- If a vendor is nearing the number of calls or bandwidth limit, the API must trigger email notifications to

the vendor.

	- API must prevent API usage spikes on a per-subscription basis by limiting the call rate to 100 calls per

minute.

	- The Inventory API must be written by using ASP.NET Core and Node.js.

	- The API must be updated to provide an interface to Azure SQL Database objects must be managed by

using code.

	- The Delivery API must be protected by using the OAuth 2.0 protocol with Azure Active Directory (Azure

AD) when called from the Azure web app. You register the Delivery API and web app in Azure AD. You

enable OAuth 2.0 in the web app.

	- The delivery API must update the Products table, the Vendor transactions table, and the Billing table in a

single transaction.

The Best For You Organics Company architecture team has created the following diagram depicting the

expected deployments into Azure:

![](image/image-656.webp)

Architecture

Issues

Delivery API

The Delivery API intermittently throws the following exception:

"System.Data.Entity.Core.EntityCommandExecutionException: An error occurred

while executing the command definition. See the inner exception for details. --

>System.Data.SqlClient.SqlException: A transport-level error has occurred when

receiving results from the server. (provider: Session Provider, error: 19 –

Physical connection is not usable)"

Chatbot greeting

The chatbot’s greeting does not show the user’s name. You need to debug the chatbot locally.

Language processing

Users report that the bot fails to understand when a customer attempts to order dishes that use Italian

names.

App code

Relevant portions of the app files are shown below. Line numbers are included for reference only and

include a two-character prefix that denotes the specific file to which they belong.

![](image/image-657.webp)

Note: This question is part of series of questions that present the same scenario. Each question in

the series contains a unique solution that might meet the stated goals. Some question sets might

have more than one correct solution, while others might not have a correct solution.

After you answer a question in this section, you will NOT be able to return to it. As a result, these

questions will not appear in the review screen.

You have an Azure Cosmos DB database that contains a container named Container1. The partition key for

Container1 is set to /day. Container1 contains the items shown in the following table.

![](image/image-732.webp)

You need to programmatically query Azure Cosmos DB and retrieve Item1 and Item2 only.

Solution: You run the following query.

![](image/image-733.webp)

You set the EnableCrossPartitionQuery property to False.

Does this meet the goal?

* A: Yes

* B: No

[See the answer](#answer-250)

### Answer 201

**CORRECT ANSWER:**

![](image/image-577.webp)

**Explanation:**

[Back to question](#question-201)

### Answer 202

**CORRECT ANSWER:** D

**Explanation:**

You can't delete a Recovery Services vault if it is registered to a server and holds backup data. If you try to

delete a vault, but can't, the vault is still configured to receive backup data.

Remove vault dependencies and delete vault

In the vault dashboard menu, scroll down to the Protected Items section, and click Backup Items. In this

menu, you can stop and delete Azure File Servers, SQL Servers in Azure VM, and Azure virtual machines.

![](image/image-578.webp)

References:

https://docs.microsoft.com/en-us/azure/backup/backup-azure-delete-vault

[Back to question](#question-202)

### Answer 203

**CORRECT ANSWER:** B

**Explanation:**

Explanation: 

Instead you should customize the default synchronization rule.

Note: 

To delete a custom domain name, you must first ensure that no resources in your directory rely on the

domain name. You can't delete a domain name from your directory if:

	- Any user has a user name, email address, or proxy address that includes the domain name.

-Any group has an email address or proxy address that includes the domain name.-

Any application in your Azure AD has an app ID URI that includes the domain name.

References:

https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-create-custom-sync-rule

[Back to question](#question-203)

### Answer 204

**CORRECT ANSWER:**

![](image/image-584.webp)

**Explanation:**

References:

https://docs.microsoft.com/en-us/azure/sql-database/transparent-data-encryption-azure-sql

[Back to question](#question-204)

### Answer 205

**CORRECT ANSWER:** B

**Explanation:**

A Recovery Services vault is a storage entity in Azure that houses data. The data is typically copies of data,

or configuration information for virtual machines (VMs), workloads, servers, or workstations. You can use

Recovery Services vaults to hold backup data for various Azure services

References:

https://docs.microsoft.com/en-us/azure/site-recovery/azure-to-azure-tutorial-enable-replication

[Back to question](#question-205)

### Answer 206

**CORRECT ANSWER:** A

**Explanation:**

Assign a role to a user

1. Sign in to the Azure portal with an account that's a global admin or privileged role admin for the

directory.

2. Select Azure Active Directory, select Users, and then select a specific user from the list.

3. For the selected user, select Directory role, select Add role, and then pick the appropriate admin roles

from the Directory roles list, such as Conditional access administrator.

4. Press Select to save.

References:

https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-users-assign-role-

azure-portal

[Back to question](#question-206)

### Answer 207

**CORRECT ANSWER:** A

**Explanation:**

Task A: Create a Recovery Services vault (if a vault already exists skip this task, go to Task B below)

A1. From Azure Portal, On the Hub menu, click All services and in the list of resources, type Recovery

Services and click Recovery Services vaults.

![](image/image-592.webp)

If there are recovery services vaults in the subscription, the vaults are listed.

A2. On the Recovery Services vaults menu, click Add.

![](image/image-593.webp)

A3. The Recovery Services vault blade opens, prompting you to provide a Name, Subscription, Resource

group, and Location

Task B. Create a backup goal

B1. On the Recovery Services vault blade (for the vault you just created), in the Getting Started section,

click Backup, then on the Getting Started with Backup blade, select Backup goal.

![](image/image-594.webp)

The Backup Goal blade opens. If the Recovery Services vault has been previously configured, then the

Backup Goal blades opens when you click Backup on the Recovery Services vault blade.

B2. From the Where is your workload running? drop-down menu, select Azure.

![](image/image-595.webp)

B3. From the What do you want to backup? menu, select Blob Storage, and click OK.

B4. Finish the Wizard.

Task C. create a backup schedule

C1. Open the Microsoft Azure Backup agent. You can find it by searching your machine for Microsoft Azure

Backup.

![](image/image-596.webp)

C2. In the Backup agent's Actions pane, click Schedule Backup to launch the Schedule Backup Wizard.

![](image/image-597.webp)

C3. On the Getting started page of the Schedule Backup Wizard, click Next.

C4. On the Select Items to Backup page, click Add Items.

The Select Items dialog opens.

C5. Select Blob Storage you want to protect, and then click OK.

C6.In the Select Items to Backup page, click Next.

On the Specify Backup Schedule page, specify Schedule a backup every day, and click Next.

![](image/image-598.webp)

C7. On the Select Retention Policy page, set it to 14 days, and click Next.

![](image/image-599.webp)

C8. Finish the Wizard.

References:

https://docs.microsoft.com/en-us/azure/backup/backup-configure-vault

[Back to question](#question-207)

### Answer 208

**CORRECT ANSWER:** B

**Explanation:**

Your key vault and VMs must reside in the same Azure region and subscription.

References:

https://docs.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-overview

[Back to question](#question-208)

### Answer 209

**CORRECT ANSWER:** B

**Explanation:**

Change the subscription directory in the Azure portal.

The classic portal feature Edit Directory, that allows you to associate an existing subscription to your Azure

Active Directory (AAD), is now available in Azure portal. It used to be available only to Service Admins with

Microsoft accounts, but now it's available to users with AAD accounts as well.

To get started:

1. Go to Subscriptions.

2. Select a subscription.

3. Select Change directory.

Incorrect Answers:

C: The Set-AzureRmContext cmdlet sets authentication information for cmdlets that you run in the current

session. The context includes tenant, subscription, and environment information.

References:

https://azure.microsoft.com/en-us/updates/edit-directory-now-in-new-portal/

[Back to question](#question-209)

### Answer 210

**CORRECT ANSWER:**

![](image/image-604.webp)

**Explanation:**

Box 1: User5

In Express settings, the installation wizard asks for the following:

AD DS Enterprise Administrator credentials

Azure AD Global Administrator credentials

The AD DS Enterprise Admin account is used to configure your on-premises Active Directory. These

credentials are only used during the installation and are not used after the installation has completed. The

Enterprise Admin, not the Domain Admin should make sure the permissions in Active Directory can be set

in all domains.

Box 2: UserA

Azure AD Global Admin credentials are only used during the installation and are not used after the

installation has completed. It is used to create the Azure AD Connector account used for synchronizing

changes to Azure AD. The account also enables sync as a feature in Azure AD.

References:

https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-accounts-

permissions

[Back to question](#question-210)

### Answer 211

**CORRECT ANSWER:** D

**Explanation:**

When you connect a Windows device with Azure AD using an Azure AD join, Azure AD adds the following

security principles to the local administrators group on the device:

	- The Azure AD global administrator role

	- The Azure AD device administrator role

	- The user performing the Azure AD join

In the Azure portal, you can manage the device administrator role on the Devices page. To open the

Devices page:

1. Sign in to your Azure portal as a global administrator or device administrator.

2. On the left navbar, click Azure Active Directory.

3. In the Manage section, click Devices.

4. On the Devices page, click Device settings.

5. To modify the device administrator role, configure Additional local administrators on Azure AD joined

devices.

References:

https://docs.microsoft.com/en-us/azure/active-directory/devices/assign-local-admin

[Back to question](#question-211)

### Answer 212

**CORRECT ANSWER:** A

**Explanation:**

First, create Recovery Services vault.

Step 1: On the left-hand menu, select All services and in the services list, type Recovery Services. As you

type, the list of resources filters. When you see Recovery Services vaults in the list, select it to open the

Recovery Services vaults menu.

![](image/image-614.webp)

Step 2: In the Recovery Services vaults menu, click Add to open the Recovery Services vault menu.

![](image/image-615.webp)

Step 3: In the Recovery Services vault menu, for example, 

Type myRecoveryServicesVault in Name.

The current subscription ID appears in Subscription. If you have additional subscriptions, you could choose

another subscription for the new vault.

For Resource group select Use existing and choose myResourceGroup. If myResourceGroup doesn't exist,

select Create new and type myResourceGroup.

From the Location drop-down menu, choose West Europe.

Click Create to create your Recovery Services vault.

References:

https://docs.microsoft.com/en-us/azure/backup/tutorial-backup-vm-at-scale

[Back to question](#question-212)

### Answer 213

**CORRECT ANSWER:** B, E

**Explanation:**

B: Seamless SSO works with any method of cloud authentication - Password Hash Synchronization or

Pass-through Authentication, and can be enabled via Azure AD Connect.

E: You can gradually roll out Seamless SSO to your users. You start by adding the following Azure AD URL

to all or selected users' Intranet zone settings by using Group Policy in Active Directory: https://

autologon.microsoftazuread-sso.com

Incorrect Answers:

A: Azure AD connect does not port 8080. It uses port 443.

C: Seamless SSO is not applicable to Active Directory Federation Services (ADFS).

D: Seamless SSO needs the user's device to be domain-joined, but doesn't need for the device to be Azure

AD Joined.

Scenario: Users in the Miami office must use Azure Active Directory Seamless Single Sign-on (Azure AD

Seamless SSO) when accessing resources in Azure.

Planned Azure AD Infrastructure include: The on-premises Active Directory domain will be synchronized to

Azure AD.

References:

https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start

[Back to question](#question-213)

### Answer 214

**CORRECT ANSWER:** D

**Explanation:**

You can opt in and configure additional recipients to receive your Azure invoice in an email. This feature

may not be available for certain subscriptions such as support offers, Enterprise Agreements, or Azure in

Open.

1. Select your subscription from the Subscriptions page. Opt-in for each subscription you own. Click

Invoices then Email my invoice.

![](image/image-622.webp)

2. Click Opt in and accept the terms.

Scenario: During the testing phase, auditors in the finance department must be able to review all Azure

costs from the past week.

References:

https://docs.microsoft.com/en-us/azure/billing/billing-download-azure-invoice-daily-usage-date

[Back to question](#question-214)

### Answer 215

**CORRECT ANSWER:** C

**Explanation:**

Scenario: Enable Azure Multi-Factor Authentication (MFA) for the users in the finance department only.

The recommendation is to use conditional access policies that can then be targeted to groups of users,

specific applications, or other conditions.

References:

https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-userstates

[Back to question](#question-215)

### Answer 216

**CORRECT ANSWER:**

![](image/image-639.webp)

**Explanation:**

Box 1: Create a Recovery Services vault

Create a Recovery Services vault on the Azure Portal.

Box 2: Install the Azure Site Recovery Provider

Azure Site Recovery can be used to manage migration of on-premises machines to Azure.

Scenario: Migrate the virtual machines hosted on Server1 and Server2 to Azure.

Server2 has the Hyper-V host role.

References:

https://docs.microsoft.com/en-us/azure/site-recovery/migrate-tutorial-on-premises-azure

[Back to question](#question-216)

### Answer 217

**CORRECT ANSWER:** C

**Explanation:**

Scenario: Contoso must meet technical requirements including:

Ensure that VM3 can establish outbound connections over TCP port 8080 to the applications servers in the

Montreal office.

IP flow verify checks if a packet is allowed or denied to or from a virtual machine. The information consists

of direction, protocol, local IP, remote IP, local port, and remote port. If the packet is denied by a security

group, the name of the rule that denied the packet is returned. While any source or destination IP can be

chosen, IP flow verify helps administrators quickly diagnose connectivity issues from or to the internet and

from or to the on-premises environment.

References:

https://docs.microsoft.com/en-us/azure/network-watcher/network-watcher-ip-flow-verify-overview

[Back to question](#question-217)

### Answer 218

**CORRECT ANSWER:**

![](image/image-641.webp)

**Explanation:**

[Back to question](#question-218)

### Answer 219

**CORRECT ANSWER:** B

**Explanation:**

References:

https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-configure-notifications

[Back to question](#question-219)

### Answer 220

**CORRECT ANSWER:** A

**Explanation:**

References:

https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-configure-notifications

[Back to question](#question-220)

### Answer 221

**CORRECT ANSWER:** B

**Explanation:**

References:

https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-configure-notifications

[Back to question](#question-221)

### Answer 222

**CORRECT ANSWER:** B

**Explanation:**

References:

https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-configure-notifications

[Back to question](#question-222)

### Answer 223

**CORRECT ANSWER:** B

**Explanation:**

References:

https://docs.microsoft.com/en-us/azure/sql-database/sql-database-develop-error-messages

[Back to question](#question-223)

### Answer 224

**CORRECT ANSWER:** A



[Back to question](#question-224)

### Answer 225

**CORRECT ANSWER:** E

**Explanation:**

Question Set 2

[Back to question](#question-225)

### Answer 226

**CORRECT ANSWER:** A

**Explanation:**

Step 1:

In the Azure Portal, click Create a resource > Web + Mobile > Web App.

Step 2:

Use the Webb app settings as listed below.

Web App name:             corp10217507n2

Hosting plan:                 Azure App Service plan

Pricing tier of the Pricing Tier:     Standard

Change your hosting plan to Standard, you can't setup auto-scaling below standard tier.

Step 3:

Select Create to provision and deploy the Web app.

References:

https://docs.microsoft.com/en-us/azure/app-service/environment/app-service-web-how-to-create-a-web-

app-in-an-ase

https://azure.microsoft.com/en-us/pricing/details/app-service/plans/

[Back to question](#question-226)

### Answer 227

**CORRECT ANSWER:** A

**Explanation:**

Step 1:

Click New found on the upper left-hand corner of the Azure portal.

Step 2:

Select Networking and then select Application Gateway in the Featured list.

Step 3:

Enter these values for the application gateway:

appgw1015 - for the name of the application gateway.

SKU Size: Standard_V2

The new SKU [Standard_V2] offers autoscaling and other critical performance enhancements.

![](image/image-672.webp)

Step 4:

Accept the default values for the other settings and then click OK.

Step 5:

Click Choose a virtual network, and select subnet0.

References:

https://docs.microsoft.com/en-us/azure/application-gateway/application-gateway-create-gateway-portal

[Back to question](#question-227)

### Answer 228

**CORRECT ANSWER:** A

**Explanation:**

Step 1:

On the top left-hand side of the screen, click Create a resource > Networking > Load Balancer.

Step 2:

In the Create a load balancer page enter these values for the load balancer:

myLoadBalancer - for the name of the load balancer.

Internal - for the type of the load balancer.

Basic - for SKU version.

Microsoft guarantees that apps running in a customer subscription will be available 99.99% of the time.

VNET1016\subnet0 - for subnet that you choose from the list of existing subnets.

Step 3: Accept the default values for the other settings and click Create to create the load balancer.

[Back to question](#question-228)

### Answer 229

**CORRECT ANSWER:** A

**Explanation:**

Microsoft Azure Service Bus is a fully managed enterprise integration message broker. Service Bus is most

commonly used to decouple applications and services from each other, and is a reliable and secure

platform for asynchronous data and state transfer.

One common messaging scenario is Messaging: transfer business data, such as sales or purchase orders,

journals, or inventory movements.

Incorrect Answers:

B: The Azure Relay service enables you to securely expose services that run in your corporate network to

the public cloud.

**Reference:**

https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-messaging-overview

[Back to question](#question-229)

### Answer 230

**CORRECT ANSWER:** B, D

**Explanation:**

The Mobile Apps client enables you to register for push notifications with Azure Notification Hubs.

The following platforms are supported:

	- Xamarin Android releases for API 19 through 24 (KitKat through Nougat)

	- Xamarin iOS releases for iOS versions 8.0 and later

	- Universal Windows Platform

	- Windows Phone 8.1

	- Windows Phone 8.0 except for Silverlight applications

References:

https://docs.microsoft.com/en-us/azure/app-service-mobile/app-service-mobile-dotnet-how-to-use-client-

library

[Back to question](#question-230)

### Answer 231

**CORRECT ANSWER:**

![](image/image-689.webp)

**Explanation:**

[Back to question](#question-231)

### Answer 232

**CORRECT ANSWER:**

![](image/image-691.webp)

**Explanation:**

[Back to question](#question-232)

### Answer 233

**CORRECT ANSWER:**

![](image/image-693.webp)

**Explanation:**

[Back to question](#question-233)

### Answer 234

**CORRECT ANSWER:**

![](image/image-695.webp)

**Explanation:**

[Back to question](#question-234)

### Answer 235

**CORRECT ANSWER:** A

**Explanation:**

References:

https://docs.microsoft.com/mt-mt/azure/sql-database/sql-database-elastic-transactions-overview?

view=azurermps-6.13.0

[Back to question](#question-235)

### Answer 236

**CORRECT ANSWER:**

![](image/image-697.webp)

**Explanation:**

References:

https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/overview/overview

[Back to question](#question-236)

### Answer 237

**CORRECT ANSWER:** B



[Back to question](#question-237)

### Answer 238

**CORRECT ANSWER:**

![](image/image-699.webp)

**Explanation:**

[Back to question](#question-238)

### Answer 239

**CORRECT ANSWER:**

![](image/image-702.webp)

**Explanation:**

Box 1:

The Autoscale scale out rule increases the number of VMs by 2 if the CPU threshold is 80% or higher. The

initial instance count is 4 and rises to 6 when the 2 extra instances of VMs are added.

Box 2:

The Autoscale scale in rule decreases the number of VMs by 4 if the CPU threshold is 30% or lower. The

initial instance count is 4 and thus cannot be reduced to 0 as the minimum instances is set to 2. Instances

are only added when the CPU threshold reaches 80%.

References:

https://docs.microsoft.com/en-us/azure/azure-monitor/platform/autoscale-overview

https://docs.microsoft.com/en-us/azure/azure-monitor/platform/autoscale-best-practices

https://docs.microsoft.com/en-us/azure/azure-monitor/platform/autoscale-common-scale-patterns

[Back to question](#question-239)

### Answer 240

**CORRECT ANSWER:**

![](image/image-705.webp)

**Explanation:**

Box 1: Public

The following example shows site traffic coming from both ports 8080 and 8081 and being directed to the

same backend pools.

![](image/image-706.webp)

Box 2: Application Gateway

You can create an application gateway with URL path-based redirection using Azure PowerShell.

Box 3: Path-based redirection and Websockets

References:

https://docs.microsoft.com/bs-latn-ba/azure//application-gateway/tutorial-url-redirect-powershell

[Back to question](#question-240)

### Answer 241

**CORRECT ANSWER:** A

**Explanation:**

Step 1: Click Create a resource in the portal.

Step 2: Enter Virtual network in the Search the Marketplace box at the top of the New pane that appears.

Click Virtual network when it appears in the search results.

Step 3: Select Classic in the Select a deployment model box in the Virtual Network pane that appears, then

click Create.

Step 4: Enter the following values on the Create virtual network (classic) pane and then click Create:

Name:                                 VNET1008

Address space:                   10.0.0.0/16

Subnet name:                      subnet0

Resource group:                   Create new

Subnet address range:          10.0.0.0/24

Subscription and location:     Select your subscription and location.

Step 5: In the portal, you can create only one subnet when you create a virtual network. Click Subnets (in

the SETTINGS section) on the Create virtual network (classic) pane that appears.

Click +Add on the VNET1008 - Subnets pane that appears.

Step 6: Enter subnet1 for Name on the Add subnet pane. Enter 10.0.1.0/24 for Address range. Click OK.

Step 7: Create the third subnet: Click +Add on the VNET1008 - Subnets pane that appears. Enter subnet2

for Name on the Add subnet pane. Enter 10.0.2.0/24 for Address range. Click OK.

References:

https://docs.microsoft.com/en-us/azure/virtual-network/create-virtual-network-classic

[Back to question](#question-241)

### Answer 242

**CORRECT ANSWER:** D

**Explanation:**

Explanation: 

Azure Monitor autoscale can be used on Virtual Machine Scale Sets.

References:

https://docs.microsoft.com/en-us/azure/azure-monitor/platform/autoscale-custom-metric

[Back to question](#question-242)

### Answer 243

**CORRECT ANSWER:** A, B, D



[Back to question](#question-243)

### Answer 244

**CORRECT ANSWER:** C

**Explanation:**

Explanation: 

Azure Event Hubs is a big data pipeline. It facilitates the capture, retention, and replay of telemetry and

event stream data. The data can come from many concurrent sources. Event Hubs allows telemetry and

event data to be made available to a variety of stream-processing infrastructures and analytics services. It

is available either as data streams or bundled event batches. This service provides a single solution that

enables rapid data retrieval for real-time processing as well as repeated replay of stored raw data. It can

capture the streaming data into a file for processing and analysis.

It has the following characteristics:

	- low latency

	- capable of receiving and processing millions of events per second

	- at least once delivery

Note: Comparison of services

![](image/image-720.webp)

References:

https://docs.microsoft.com/en-us/azure/event-grid/compare-messaging-services

[Back to question](#question-244)

### Answer 245

**CORRECT ANSWER:** C

**Explanation:**

Explanation: 

In-guest VM metrics with the Azure diagnostics extension

The Azure diagnostics extension is an agent that runs inside a VM instance. The agent monitors and saves

performance metrics to Azure storage. These performance metrics contain more detailed information about

the status of the VM, such as AverageReadTime for disks or PercentIdleTime for CPU. You can create

autoscale rules based on a more detailed awareness of the VM performance, not just the percentage of

CPU usage or memory consumption.

**Reference:**

https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-autoscale-

overview

[Back to question](#question-245)

### Answer 246

**CORRECT ANSWER:** B

**Explanation:**

Returns Item1 only as EnableCrossPartitionQuery property to False. If EnableCrossPartitionQuery property

is set to true, it will return Item1 and Item3.

**Reference:**

https://docs.microsoft.com/en-us/azure/cosmos-db/sql-query-where

https://docs.microsoft.com/en-us/dotnet/api/

microsoft.azure.documents.client.feedoptions.enablecrosspartitionquery?view=azure-dotnet

[Back to question](#question-246)

### Answer 247

**CORRECT ANSWER:** B

**Explanation:**

Returns Item1, Item2, Item3, and Item4.

**Reference:**

https://docs.microsoft.com/en-us/azure/cosmos-db/sql-query-where

https://docs.microsoft.com/en-us/dotnet/api/

microsoft.azure.documents.client.feedoptions.enablecrosspartitionquery?view=azure-dotnet

[Back to question](#question-247)

### Answer 248

**CORRECT ANSWER:** A

**Explanation:**

Returns Item1 and Item2 only.

**Reference:**

https://docs.microsoft.com/en-us/azure/cosmos-db/sql-query-where

https://docs.microsoft.com/en-us/dotnet/api/

microsoft.azure.documents.client.feedoptions.enablecrosspartitionquery?view=azure-dotnet

[Back to question](#question-248)

### Answer 249

**CORRECT ANSWER:**

![](image/image-731.webp)

**Explanation:**

[Back to question](#question-249)

### Answer 250

**CORRECT ANSWER:** B

**Explanation:**

Returns Item1 only as EnableCrossPartitionQuery property to False. If EnableCrossPartitionQuery property

is set to true, it will return Item1, Item2, and Item3.

**Reference:**

https://docs.microsoft.com/en-us/azure/cosmos-db/sql-query-where

https://docs.microsoft.com/en-us/dotnet/api/

microsoft.azure.documents.client.feedoptions.enablecrosspartitionquery?view=azure-dotnet

[Back to question](#question-250)

