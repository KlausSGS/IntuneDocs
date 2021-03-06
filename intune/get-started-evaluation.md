---
# required metadata

title: What can Microsoft Intune do for my company
titleSuffix: 
description: Common business problems that Microsoft Intune helps solve.
keywords:
author: dougeby
ms.author: dougeby
manager: dougeby
ms.date: 01/09/2019
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 6bfab644-c1e2-4154-a254-e95b9a1d75f2

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer:
ms.suite: ems
search.appverid: MET150
#ms.tgt_pltfrm:
ms.custom: intune-azure; get-started
---

# What can Intune do for my company?
Microsoft Intune is a cloud-based enterprise mobility management (EMM) service that helps enable your workforce to be productive while keeping your corporate data protected.

With Intune, you can:

- Manage the mobile devices your workforce uses to access company data.
- Manage the mobile apps your workforce uses.
- Protect your company information by helping to control the way your workforce accesses and shares it.
- Ensure devices and apps are compliant with company security requirements.

## Common business problems that Intune helps solve

* [Protect your on-premises email and data so that it can be accessed by mobile devices](common-scenarios.md#protecting-your-on-premises-email-and-data-so-it-can-be-safely-accessed-by-mobile-devices)
* [Protect your Office 365 mail and data so that it can be safely accessed by mobile devices](common-scenarios.md#protecting-your-office-365-email-and-data-so-it-can-be-safely-accessed-by-mobile-devices)
* [Issue corporate-owned phones to your workforce](common-scenarios.md#issue-corporate-owned-phones-to-your-employees)
* [Offer a bring-your-own-device (BYOD) or personal device program to all employees](common-scenarios.md#offer-a-bring-your-own-device-program-to-all-employees)
* [Enable your employees to securely access Office 365 from an unmanaged public kiosk](common-scenarios.md#enable-your-employees-to-securely-access-office-365-from-an-unmanaged-public-kiosk)
* [Issue limited-use shared tablets to your task workers](common-scenarios.md#issue-limited-use-shared-tablets-to-your-employees)

## Quickstarts

We understand that getting started with managing mobile devices can be difficult, since there are many different decisions that you'll need to make on behalf of your company. The following quickstarts help you get started with Intune, and complete some common tasks, in a minimal amount of time.

You can follow the intended order of the **Quickstarts** using the table of contents on the left side of the page.

- [Try Intune for free](free-trial-sign-up.md) - Create a free subscription to try Intune in a test environment.    
- [Create a user](quickstart-create-user.md) - Add a user to Intune to allow them to access company resources on mobile devices.
- [Create a group](quickstart-create-group.md) - Organize users into groups to make it easier to manage the policies and apps that they can access.
- [Set up automatic enrollment](quickstart-setup-auto-enrollment.md) - Set up Microsoft Intune to automatically enroll devices when specific users sign in to Windows 10 devices.
- [Enroll your device](quickstart-enroll-windows-device.md) - Take the role of an Intune user and enroll your device into Microsoft Intune. Then, return to Intune and confirm the enrolled device.
- [Create a device compliance policy](quickstart-set-password-length-android.md) - Create a device compliance policy and assign a group to the policy.
- [Send notifications to noncompliant devices](quickstart-send-notification.md) - Send an email notification to the members of your workforce that have noncompliant devices by creating and assigning a compliance policy.
- [Add and assign an app](quickstart-add-assign-app.md) - Add and assign a client app to your company's workforce.
- [Create and assign an app protection policy](quickstart-create-assign-app-policy.md) - Create and assign an app protection policy to a client app on an end user's device.
- [Create and assign a custom role](quickstart-create-custom-role.md) - Create and assign a custom role with specific permissions for a security operations department. 
- [Create an email device profile for iOS](quickstart-email-profile.md) - Create an email device profile for iOS devices.

## Prerequisites

Before you start, you must have an Intune admin and tenant account activated. Create a free subscription to [try Intune for free](free-trial-sign-up.md) in a test environment. Current subscribers can also complete these activities in your live tenant. These getting started articles assume that you're working on test devices.

You also need to make sure that you are the global admin for your organization to complete all of the Get Started tasks.

## Intune architecture

Intune is the component of Enterprise Mobility + Security (EMS) that manages mobile devices and apps. It integrates closely with other EMS components like Azure Active Directory (Azure AD) for identity and access control and Azure Information Protection for data protection. When you use it with Office 365, you can enable your workforce to be productive on all their devices, while keeping your organization's information protected.

![High-level architectural diagram for Microsoft Intune](/intune/media/intunearchitecture.svg)

## Next steps

[Get started with using Azure](get-started-azure.md) - Understand the anatomy of the Azure portal and how to make changes to the page you see.

## Learn more

* [What is Intune?](introduction-intune.md)
* [What is the Azure portal?](what-is-intune.md)
* [Device and app lifecycles](introduction-device-app-lifecycles.md)