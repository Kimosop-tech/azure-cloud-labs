# Lab 01 – Azure Environment Setup & Resource Group Creation

## Objective

Set up a Microsoft Azure environment by activating an Azure subscription, exploring the Azure Portal, and creating the first Resource Group to organize resources for future cloud labs.

---

## Lab Overview

This lab established the Azure environment that will be used throughout this learning journey. After creating an Azure account and activating the free subscription, a Resource Group was created to serve as the logical container for all Azure resources deployed in subsequent labs.

---

## Skills Acquired

- Creating and configuring an Azure account
- Activating an Azure Free Trial subscription
- Navigating the Azure Portal
- Understanding Azure subscriptions
- Understanding Azure regions
- Creating and managing Resource Groups
- Organizing Azure resources using best practices

---

## Azure Resources Created

| Resource Type | Resource Name | Region |
|--------------|---------------|--------|
| Resource Group | rg-cloudlab-01 | West US 2 |

---

## Deployment Steps

1. Created a Microsoft Azure account.
2. Activated the Azure Free Trial subscription.
3. Signed in to the Azure Portal.
4. Explored the Azure Portal interface.
5. Navigated to **Resource Groups**.
6. Created a new Resource Group:
   - **Name:** `rg-cloudlab-01`
   - **Region:** `West US 2`
7. Verified that the Resource Group was successfully created.

---

## Key Azure Concepts

### Azure Subscription

An Azure subscription provides access to Azure services and defines the billing and management boundary for deployed resources.

### Resource Group

A Resource Group is a logical container used to organize and manage Azure resources that share the same lifecycle.

For this lab, the following Resource Group was created:

- **Resource Group:** `rg-cloudlab-01`

This Resource Group will be used throughout the Azure Cloud Labs project.

### Azure Region

Azure regions are physical locations around the world where Azure services are hosted.

The region selected for these labs is:

- **West US 2**

Using a consistent region helps simplify resource management and avoids compatibility issues between services.

---

## Verification

The following was verified after deployment:

- Azure subscription is active.
- Resource Group `rg-cloudlab-01` was successfully created.
- Resource Group is available in the Azure Portal.
- Azure environment is ready for future deployments.

---

## Screenshots

See the **screenshots** folder.

---

## Lessons Learned

- Azure resources should be organized using Resource Groups.
- Choosing a region is one of the first decisions when deploying Azure resources.
- Resource Groups simplify administration, access control, and resource management.
- Creating a proper Azure environment before deploying resources provides a solid foundation for future labs.

---

## Next Lab

**Lab 02 – Deploy a Windows Server 2025 Virtual Machine**

In the next lab, the virtual machine will be deployed inside the `rg-cloudlab-01` Resource Group created in this lab.
