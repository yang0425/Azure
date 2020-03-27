### Question 251

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

You have an Azure SQL database named DB1.

You plan to create the following four tables in DB1 by using the following code.

![](image/image-734.webp)

You need to identify which table must be created last.

What should you identify? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

* A: Table1

* B: Table2

* C: Table3

* D: Table4

[See the answer](#answer-251)

### Question 252

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

You have an Azure subscription that contains the resource groups shown in the following table. 

![](image/image-735.webp)

You have the Azure SQL servers shown in the following table. 

![](image/image-736.webp)

You create an Azure SQL database named DB1 on Sql1 in an elastic pool named Poo11. 

You need to create an Azure SQL database named DB2 in Poo11. 

Where should you deploy DB2?

* A: Sql1

* B: Sql2

* C: Sql3

* D: Sql4

[See the answer](#answer-252)

### Question 253

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

![](image/image-737.webp)

You need to choose the Azure messaging solution to support the Shopping Cart feature. 

Which Azure service should you use?

* A: Azure Service Bus

* B: Azure Relay

* C: Azure Event Grid

* D: Azure Event Hub

[See the answer](#answer-253)

### Question 254

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

![](image/image-738.webp)

![](image/image-739.webp)

![](image/image-740.webp)

![](image/image-741.webp)

![](image/image-742.webp)

![](image/image-743.webp)

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

You need to create a function app named corp10217507n1 that supports sticky sessions. The solution must

minimize the Azure-related costs of the App Service plan.

What should you do from the Azure portal?

[See the answer](#answer-254)

### Question 255

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

You have an Azure web app named App1 that contains the following autoscale conditions: The default auto

created scale condition has a scale mode that has Scale to a specific instance count set to 2.

Scale condition 1 has the following configurations:

	- Scale mode: Scale to a specific instance count

	- Instance count: 3

	- Schedule: Specify start/end dates

	- Start date: August 1, 2019, 06:00

	- End date: September 1, 2019, 18:00

Scale condition 2 has the following configurations:

	- Scale mode: Scale to a specific instance count

	- Instance count: 4

	- Schedule: Repeat specific days

	- Repeat every: Monday

	- Start time: 06:00

	- End time: 18:00

Scale condition 3 has the following configurations:

	- Scale mode: Scale to a specific instance count

	- Instance count: 5

	- Schedule: Repeat specific days

	- Repeat every: Monday

	- Start time: 15:00

	- End time: 20:00

You need to identify the number of running App1 instances.

What should you identify? To answer, select the appropriate options in the answer area.

Hot Area:

![](image/image-761.webp)

[See the answer](#answer-255)

### Question 256

HOTSPOT

You have an Azure web app named App1 that contains the following autoscale conditions:

![](image/image-766.webp)

Every autoscale condition rule is configured to have a duration of 20 minutes and a cool down time of 10

minutes.

At 06:00, WebApp1 is running four instances.

You need to identify how many instances are running on WebApp1 based on the percentage of the CPU

utilization.

How many instances should you identify? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

Hot Area:

![](image/image-767.webp)

[See the answer](#answer-256)

### Answer 251

**CORRECT ANSWER:** B

**Explanation:**

Table1 references Table4. Therefore Table4 must be created before Table1.

Table2 references Table1 and Table3. Therefore Table1 and Table3  must be created before Table2.

Note: FOREIGN KEY REFERENCES is a constraint that provides referential integrity for the data in the

column or columns. FOREIGN KEY constraints require that each value in the column exists in the

corresponding referenced column or columns in the referenced table. FOREIGN KEY constraints can

reference only columns that are PRIMARY KEY or UNIQUE constraints in the referenced table or columns

referenced in a UNIQUE INDEX on the referenced table.

Incorrect Answers:

A: Table1 is referenced by Table2 and should be crated before Table2.

C: Table3 is referenced by Table2 and should be crated before Table2.

D: Table4 is referenced by Table1 and should be crated before Table1.

**Reference:**

https://docs.microsoft.com/en-us/sql/t-sql/statements/create-table-transact-sql?view=sql-server-ver15

[Back to question](#question-251)

### Answer 252

**CORRECT ANSWER:** A

**Explanation:**

The databases in an elastic pool are on a single Azure SQL Database server and share a set number of

resources at a set price.

**Reference:**

https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-pool

[Back to question](#question-252)

### Answer 253

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

References:

https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-messaging-overview

[Back to question](#question-253)

### Answer 254

**CORRECT ANSWER:** A

**Explanation:**

Step 1:

Select the New button found on the upper left-hand corner of the Azure portal, then select Compute >

Function App.

Step 2:

Use the function app settings as listed below.

App name:                    corp10217507n1

Hosting plan:                 Azure App Service plan (required for sticky sessions)

Pricing tier of the App Service plan:     Shared compute: Free

Step 3:

Select Create to provision and deploy the function app.

References:

https://docs.microsoft.com/en-us/azure/azure-functions/functions-create-function-app-portal

[Back to question](#question-254)

### Answer 255

**CORRECT ANSWER:**

![](image/image-762.webp)

**Explanation:**

Box 1: 5

Scale condition 1, Scale condition 2, and Scale condition 3 applies.

Scale condition 3 takes precedence as it the largest increase in the number of instances.

Box 2: 5

Scale condition 1 does not apply as its end date is exceeded.

Scale condition 2 and Scale condition 3 applies.

Scale condition 3 takes precedence as it the largest increase in the number of instances.

When you configure multiple policies and rules, they could conflict with each other. Autoscale uses the

following conflict resolution rules to ensure that there is always a sufficient number of instances running:

	- Scale-out operations always take precedence over scale-in operations.

	- When scale-out operations conflict, the rule that initiates the largest increase in the number of instances

takes precedence.

	- When scale in operations conflict, the rule that initiates the smallest decrease in the number of

instances takes precedence.

References:

https://docs.microsoft.com/en-us/azure/architecture/best-practices/auto-scaling

[Back to question](#question-255)

### Answer 256

**CORRECT ANSWER:**

![](image/image-768.webp)

**Explanation:**

Box 1: 3

At 6:00 the default 4 instances are running. The CPU utilization averages 10% for 25 minutes. The scale in

rules states that 1 instance should be removed when CPU utilization averages 30% or less over a 20

minute period.

Box 2: 6

At 6:00 the default 4 instances are running. The CPU utilization averages 70% for 25 minutes. The scale

out rules states that 3 instances should be added when CPU utilization averages 70% or more over a 20

minute period. However, the maximum number of instances is set at 6.

References:

https://docs.microsoft.com/en-us/azure/architecture/best-practices/auto-scaling

https://docs.microsoft.com/en-us/azure/azure-monitor/platform/autoscale-understanding-settings

[Back to question](#question-256)

