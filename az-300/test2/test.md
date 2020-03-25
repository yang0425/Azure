### Question 1
You have an Azure subscription that contains a resource group named RG1. RG1 contains 100 virtual
machines.

Your company has three cost centers named Manufacturing, Sales, and Finance.

You need to associate each virtual machine to a specific cost center.

What should you do?

* A: Add an extension to the virtual machines
* B: Modify the inventory settings of the virtual machine
* C: Assign tags to the virtual machines
* D: Configure locks for the virtual machine

[See the answer](#answer-1)

### Question 2
Your company has a virtualization environment that contains the virtualization hosts shown in the following
table.

![](image/q-2-1.webp)

The virtual machines are configured as shown in the following table.

![](image/q-2-2.webp)

All the virtual machines use basic disks. VM1 is protected by using BitLocker Drive Encryption (BitLocker).
You plan to migrate the virtual machines to Azure by using Azure Site Recovery.
You need to identify which virtual machines can be migrated.

Which virtual machines should you identify for each server? To answer, select the appropriate options in the
answer area.

![](image/q-2-3.webp)

[See the answer](#answer-2)

### Question 3
You have an Azure subscription that contains multiple resource groups. You create an availability set as
shown in the following exhibit.

![](image/q-3-1.webp)

You deploy 10 virtual machines to AS1.
Use the drop-down menus to select the answer choice that completes each statement based on the information presented in the graphic.

![](image/q-3-2.webp)

[See the answer](#answer-3)

### Question 4
You have an Azure subscription that contains two storage accounts named storagecontoso1 and
storagecontoso2. Each storage account contains a queue service, a table service, and a blob service.
You develop two apps named App1 and App2. You need to configure the apps to store different types of
data to all the storage services on both the storage accounts.

How many endpoints should you configure for each app?

* A: 2
* B: 3
* C: 6
* D: 12

[See the answer](#answer-4)

### Question 5
You have an Azure subscription named Subscription1.

You have a virtualization environment that contains the virtualization servers in the following table.

![](image/q-5-1.webp)

The virtual machines are configured as shown in the following table.

![](image/q-5-2.webp)

All the virtual machines use basic disks. VM1 is protected by using BitLocker Drive Encryption (BitLocker).

You plan to use Azure Site Recovery to migrate the virtual machines to Azure. 

Which virtual machines can you migrate? To answer, select the appropriate options in the answer area.

![](image/q-5-3.webp)

[See the answer](#answer-5)

### Question 6
You plan to migrate a large amount of corporate data to Azure Storage and to back up files stored on old
hardware to Azure Storage.

You need to create a storage account named corpdata8548984n1, in the corpdatalod8548984 resource
group. The solution must meet the following requirements:
- corpdata8548984n1 must be able to host the virtual disk files for Azure virtual machines
- The cost of accessing the files must be minimized
- Replication costs must be minimized

What should you do from the Azure portal?

[See the answer](#answer-6)

### Answer 1

**CORRECT ANSWER:** C

**Explanation:**

You apply tags to your Azure resources to logically organize them into a taxonomy. Each tag consists of a
name and a value pair. After you apply tags, you can retrieve all the resources in your subscription with that
tag name and value. 
Tags enable you to retrieve related resources from different resource groups. 
This approach is helpful when you need to organize resources for billing or management.

**Reference:**
* https://docs.microsoft.com/en-us/azure/billing/billing-getting-started
* https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-using-tags

[Back to question](#question-1)

### Answer 2

**CORRECT ANSWER:**

![](image/a-2-1.webp)

**Explanation:**

Incorrect Answers:
* VM1 cannot be migrates as it has BitLocker enabled.
* VM2 cannot be migrates as the OS disk on VM2 is larger than 2TB.
* VMC cannot be migrates as the Data disk on VMC is larger than 4TB.

**Reference:**
* https://docs.microsoft.com/en-us/azure/site-recovery/hyper-v-azure-support-matrix#azure-vm-requirements

[Back to question](#question-2)

### Answer 3

**CORRECT ANSWER:**

![](image/a-3-1.webp)

**Explanation:**

Box 1: 6

Two out of three update domains would be available, each with at least 3 VMs.
An update domain is a group of VMs and underlying physical hardware that can be rebooted at the same
time.
As you create VMs within an availability set, the Azure platform automatically distributes your VMs across
these update domains. This approach ensures that at least one instance of your application always remains
running as the Azure platform undergoes periodic maintenance.

Box 2: the West Europe region and the RG1 resource group

**Reference:**
* https://docs.microsoft.com/en-us/azure/virtual-machines/windows/regions

[Back to question](#question-3)

### Answer 4

**CORRECT ANSWER:** A

**Explanation:**

Each app needs a service endpoint in each Storage Account.

**Reference:**
* https://docs.microsoft.com/en-us/azure/storage/common/storage-network-security

[Back to question](#question-4)

### Answer 5

**CORRECT ANSWER:**

![](image/a-5-1.webp)

**Explanation:**

Incorrect Answers:
* VM1 cannot be migrates as it has BitLocker enabled.
* VM2 cannot be migrates as the OS disk on VM2 is larger than 2TB.
* VMC cannot be migrates as the Data disk on VMC is larger than 4TB.

**Reference:**
* https://docs.microsoft.com/en-us/azure/site-recovery/hyper-v-azure-support-matrix#azure-vm-requirements

[Back to question](#question-5)

### Answer 6

**CORRECT ANSWER:**

1. In the Azure portal, click All services. In the list of resources, type Storage Accounts. As you begin
typing, the list filters based on your input. Select Storage Accounts.
2. On the Storage Accounts window that appears, choose Add.
3. Select the subscription in which to create the storage account.
4. Under the Resource group field, select corpdatalod8548984.
![](image/a-6-1.webp)
5. Enter a name for your storage account: corpdata8548984n1
6. For Account kind select: General-purpose v2 accounts (recommended for most scenarios)
General-purpose v2 accounts is recommended for most scenarios. General-purpose v2 accounts deliver
the lowest per-gigabyte capacity prices for Azure Storage, as well as industry-competitive transaction
prices.
7. For replication select: Read-access geo-redundant storage (RA-GRS)
Read-access geo-redundant storage (RA-GRS) maximizes availability for your storage account. RA-GRS
provides read-only access to the data in the secondary location, in addition to geo-replication across two
regions.

**Reference:**
* https://docs.microsoft.com/en-us/azure/storage/common/storage-quickstart-create-account
* https://docs.microsoft.com/en-us/azure/storage/common/storage-account-overview

[Back to question](#question-6)