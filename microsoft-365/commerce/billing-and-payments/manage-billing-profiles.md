---
title: Understand billing profiles
author: cmcatee-MSFT
ms.author: cmcatee
manager: scotv
ms.reviewer: amberb, vikdesai
audience: Admin
ms.topic: article
f1.keywords:
- 'MACBillingBillsPaymentsBillingProfiles'
ms.service: microsoft-365-business
ms.localizationpriority: medium
ms.collection:
- Tier1
- scotvorg
- M365-subscription-management
- Adm_O365
ms.custom: 
- commerce_billing
- AdminSurgePortfolio
- AdminTemplateSet
search.appverid: MET150
description: "Learn how billing profiles support invoices."
ms.date: 04/02/2021 
---

# Understand billing profiles

A billing profile contains a payment method, Bill-to information, and other invoice settings, such as purchase order number and email invoice preference. You use a billing profile to pay for the products that you buy from Microsoft. Billing profiles are automatically created, and each are invoiced separately. 

> [!NOTE]
>
> Not all accounts have a billing profile. If you're not sure if you have a one, you can [view a list of your billing profiles](manage-billing-profiles.md#view-my-billing-profiles).

## What are billing profile roles?

Roles on billing profiles have permissions to control purchases, and view and manage invoices. Assign these roles to users who track, organize, and pay invoices. For example, members of the procurement team in your organization.

| Role                         | Description                                                                      |
|----------------------------- |--------------------------------------------------------------------------------- |
| Billing profile owner        | Manage everything for a billing profile                                          |
| Billing profile contributor  | Manage everything except permissions in a billing profile                        |
| Billing profile reader       | Read-only view of everything in a billing profile                                |
| Invoice manager              | View and pay bills, and has a read-only view of everything in a billing profile  |

## View my billing profiles

> [!NOTE]
>
> If you follow these steps and the billing profiles list is empty, it means that you don’t have a billing profile, and can’t use this feature.

1. In the admin center, go to the **Billing** \> <a href="https://go.microsoft.com/fwlink/p/?linkid=2102895" target="_blank">Bills & payments</a> page.
2. Select the **Billing profile** tab, then select a billing profile from the list.

Each billing profile includes the following information:

- **Billing profile name and status** &ndash; The unique name of the billing profile, and whether the billing profile is active or disabled for purchasing.
- **Invoice settings** &ndash; Currency based on the country of the billing account, information about invoice frequency and date, the option to receive invoices as email attachments, and an optional PO number field
- **Payment methods** &ndash; Shows the primary and backup payment method, if any, for the profile
- **Billing account** &ndash; Name of the billing account the profile is related to. For more information about billing accounts, see [Understand billing accounts](../manage-billing-accounts.md).
- **Contact information** &ndash; Billing address and contact name and email address
- **Billing profile roles** &ndash; A list of people who are assigned one of the billing profile roles to do things for that profile. For example, pay bills, add a PO number, or replace the payment method that is used to make purchases.

> [!NOTE]
>
> You can only assign billing profile roles to users in your organization.

## Need help? Contact support

If you have questions or need help with your Azure charges, <a href="https://portal.azure.com/#blade/Microsoft_Azure_Support/HelpAndSupportBlade/newsupportrequest" target="_blank">create a support request with Azure support</a>.

If you have questions or need help with your billing profile in Microsoft 365 admin center, [contact support](../../admin/get-help-support.md).

## Related content

[How to pay for your subscription with a billing profile](pay-for-subscription-billing-profile.md) (article)\
[Understand billing accounts](../manage-billing-accounts.md) (article)\
[Manage payment methods](manage-payment-methods.md) (article)
