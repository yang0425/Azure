### Case-1.

Humongous Insurance is an insurance company that has three offices in Miami, Tokyo and Bangkok. Each office has 5.000 users.

Existing Environment

Active Directory Environment

Humongous Insurance has a single-domain Active Directory forest named humongousinsurance.com. The functional level of the forest is Windows Server 2012.

You recently provisioned an Azure Active Directory (Azure AD) tenant.

Network Infrastructure

Each office has a local data center that contains all the servers for that office. Each office has a dedicated connection to the Internet.

Each office has several link load balancers that provide access to the servers.

Active Directory Issue

Several users in humongousinsurance.com have UPNs that contain special characters.

You suspect that some of the characters are unsupported in Azure AD.

Licensing Issue

You attempt to assign a license in Azure to several users and receive the following error message: "Licenses not assigned. License agreement failed for one user."

You verify that the Azure subscription has the available licenses.

Requirements

Planned Changes

Humongous Insurance plans to open a new office in Paris. The Paris office will contain 1,000 users who will be hired during the next 12 months. All the resources used by the Paris office users will be hosted in Azure.

Planned Azure AD Infrastructure

The on-premises Active Directory domain will be synchronized to Azure AD.

All client computers in the Paris office will be joined to an Azure AD domain.

Planned Azure Networking Infrastructure

You plan to create the following networking resources in a resource group named All_Resources:

- Default Azure system routes that will be the only routes used to route traffic

- A virtual network named Paris-VNet that will contain two subnets named Subnet1 and Subnet2

- A virtual network named ClientResources-VNet that will contain one subnet named ClientSubnet

- A virtual network named AllOffices-VNet that will contain two subnets named Subnet3 and Subnet4

You plan to enable peering between Paris-VNet and AllOffices-VNet. You will enable the Use remote gateways setting for the Paris-VNet peerings.

You plan to create a private DNS zone named humongousinsurance.local and set the registration network to the ClientResources-VNet virtual network.

Planned Azure Computer Infrastructure

Each subnet will contain several virtual machines that will run either Windows Server 2012 R2, Windows Server 2016, or Red Hat Linux.

Department Requirements

Humongous Insurance identifies the following requirements for the company's departments:

- Web administrators will deploy Azure web apps for the marketing department. Each web app will be added to a separate resource group. The initial configuration of the web apps will be identical. The web administrators have permission to deploy web apps to resource groups.

- During the testing phase, auditors in the finance department must be able to review all Azure costs from the past week.

Authentication Requirements

Users in the Miami office must use Azure Active Directory Seamless Single Sign-on (Azure AD Seamless SSO) when accessing resources in Azure.