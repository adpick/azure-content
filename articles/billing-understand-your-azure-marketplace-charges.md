<properties
	pageTitle="Understand your Azure Marketplace charges | Microsoft Azure"
	description="Describes how to understand charges related to your Marketplace orders."
	services=""
	documentationCenter=""
	authors="JiangChen79"
	manager="felixwu"
	editor=""
	tags="billing"
	/>

<tags
	ms.service="billing"
	ms.workload="na"
	ms.tgt_pltfrm="na"
	ms.devlang="na"
	ms.topic="article"
	ms.date="08/17/2016"
	ms.author="cjiang"/>

# Understand your Azure External Service Charges

This article aims to demystify the billing of External Services in Azure. Sometimes referred to as Marketplace Orders, these are services that are provided by independent service vendors but are integrated completely within the Azure ecosystem. You'll learn how to identify External Services, understand how the billing differs from other Azure resources, view and track any costs you may be accruing from the use of external services, and finally how to manage external service orders and how you pay for them.

## Important traits of external services

### Identifying External services

When you are provisioning a new resource, you'll see the following warning when you are provisioning an external service:

![Marketplace purchase warning](./media/billing-understand-your-azure-marketplace-charges/marketplace-orders.png)

In most cases these will be services published by companies that are not Microsoft. Certain Microsoft products are also leveraging the Azure Marketplace through the same channel and will also be categorized as External Services.

### External services are billed separately

External services are treated as individual orders within your Azure subscription, accordingly the billing period for each service is determined by when you purchase the service, not the subscription under which you purchased it. You will also receive separate bills and your credit card will be charged as a separate event.

### Payment models

External services require a credit card, you will not be able to purchase them if your subscription uses Invoice pay. Some services are billed in a pay-as-you-go fashion while others use a monthly base payment model.

### Azure Free Credits and External services

If you are using an azure subscription that includes [free credit](https://azure.microsoft.com/en-us/pricing/spending-limits/), you should be aware that this credit cannot be applied to external service bills, this means that you must have a credit card associated with your subscription to purchase them, and this is the card that will be charged.

## Viewing your External Service Spending and History

You can view a list of the external services that are on each subscription within the [Azure Portal](https://portal.azure.com/): 

1. Navigate to the Billing blade
   
  ![Change payment method](./media/billing-understand-your-azure-marketplace-charges/change-payment-method.jpg)

2. Select a subscription
   
  ![Change payment method](./media/billing-understand-your-azure-marketplace-charges/change-payment-method.jpg)

3. Use the External Services command and you'll see each one of your external service orders, the publisher name, service tier you purchased, name you gave the resource, and the current order status.

From here you can view past bill amounts including the tax breakdown.

## How to Manage your Orders and Payments
The summary page in the [Azure Account Center](https://account.windowsazure.com/) has user actions, allowing you to update your payment instrument:

> [AZURE.NOTE] If you are using your organization ID to change personal information you will need to log a ticket with support.

To update your payment method click on the **Change payment method** link on the right side of the page.

![Order summary](./media/billing-understand-your-azure-marketplace-charges/order-summary.png)

This link will bring you to a different portal where you will be able to make changes to your preferred payment method.

To change your payment method, follow these steps:

1. Click on **Change how you pay**.

    ![Subscriptions](./media/billing-understand-your-azure-marketplace-charges/subscriptions.jpg)

2. Select the payment method you want to change to. The **Pay with** option allows you to select your credit card. The **Add a new way to pay** option allows you add a new credit card.

    ![Change payment method](./media/billing-understand-your-azure-marketplace-charges/change-payment-method.jpg)
    
If you wish to cancel your external service order, you need to delete the resource in the [Azure Portal](https://portal.azure.com).

     ![Delete Resource](./media/billing-understand-your-azure-marketplace-charges/change-payment-method.jpg)

> [AZURE.NOTE] If you still have further questions, please [contact support](https://portal.azure.com/?#blade/Microsoft_Azure_Support/HelpAndSupportBlade) to get your issue resolved quickly.
