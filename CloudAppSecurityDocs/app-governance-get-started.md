---
title: Get Started with app governance
ms.date: 11/09/2021
ms.topic: how-to
description: Get started with app governance capabilities to govern your apps.
---
# Get started with app governance

[Microsoft 365 security & compliance licensing guidance for app governance.](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance)

[![Sign up for the free trial of app governance](media/app-governance/large-app-governance-banner.png)](https://aka.ms/appgovernancetrial)

To get started using the app governance add-on to Defender for Cloud Apps, you need the right [admin role](#administrator-roles) and [license](#licensing-for-app-governance). 

1. You must have one of the [administrator roles](#administrator-roles) listed below to access the app governance pages in the portal.
1. Your organization's billing address must be in a WW region or in GBR, CAN, JPN, or AUS go-local region to activate the free trial.


## Sign up for the trial
Existing Defender for Cloud Apps customers can navigate to the [sign up page for the free trial](https://aka.ms/appgovernancetrial) and complete the steps to add app governance to your tenant.

If you aren't already a Defender for Cloud Apps customer, you can sign up for a free trial by navigating to the [sign up page for the free trial](https://www.microsoft.com/security/business/cloud-apps-defender) and complete the steps for sign-up. Then, navigate to the [sign up page for the free trial for app governance](https://aka.ms/appgovernancetrial) and complete the steps to add a free trial of app governance to your tenant.

Only Global Admin, Company Admin, or Billing Admin role can activate the app governance free trial.

## Get a license
App governance is an add-on feature for Defender for Cloud Apps, and so Defender for Cloud Apps must be present in your account as either a standalone product or as part of the various license packages. To purchase a subscription of app governance, reach out to your sales account team. You can also sign up for the trial to explore app governance for a limited period.

Before you get started with app governance, you should confirm your [Microsoft 365 admin center - subscriptions](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/subscriptions) and any add-ons. App governance is available as an add-on to organizations with:

- Microsoft Defender for Cloud Apps (standalone)
- Enterprise Mobility + Security E5/A5
- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 Security
- Microsoft 365 E5/A5 Compliance
- Microsoft 365 E5/A5 Information Protection and Governance
- Microsoft 365 F5 Security add-on
- Microsoft 365 F5 Compliance add-on
- Microsoft 365 F5 Security + Compliance add-on





### Cancel the trial

If you would like to cancel your trial of app governance, use these steps:

1. In the Microsoft 365 admin center, go to **Billing** > [Your products](https://go.microsoft.com/fwlink/p/?linkid=842054).
1. Navigate to the app governance trial, select the three dots, and select **Cancel subscription**.
1. In the resulting fly-out pane, provide a reason for cancellation, any additional feedback, and select **Cancel subscription**.
1. Select **Cancel subscription** in the resulting pop-up screen. Your trial is canceled, you'll lose access to app governance, and your app governance data will be deleted (log data that is used to create the app governance insights and detections - no emails or other files will be affected).

## Turn on integration with Defender for Cloud Apps
To start using app governance, it needs to integrate with Defender for Cloud Apps. Before turning on integration ensure the following are in place: 

- Office 365 is connected in Defender for Cloud Apps.
- Office 365 Azure AD apps are enabled.
- You're a Global Admin, Company Admin, or Billing Admin.

To enable app governance sync with Defender for Cloud Apps, follow these steps:

1. Go to your Defender for Cloud Apps portal – [https://portal.cloudappsecurity.com](https://portal.cloudappsecurity.com)
1. Select the gear icon (top-right corner) and select **Settings**.
1. Under **Threat Protection**, select **App Governance**.
1. Select **Enable App Governance integration**, and then select **Save**.

### Verify integration
To verify the integration with Defender for Cloud Apps is active, look for the app governance policies listed below to appear in Defender for Cloud Apps. The new policies might take few minutes to appear once integration is enabled.

- Microsoft 365 OAuth app Reputation
- Microsoft 365 OAuth Phishing Detection
- Microsoft 365 OAuth App Governance

> [!NOTE]
> App governance alerts will not flow to Microsoft 365 Defender until app governance is enabled in Defender for Cloud Apps and you have provisioned both Defender for Cloud Apps and Microsoft 365 Defender by accessing their respective portals at least once.

## Required administrator roles
One of the following administrator roles is required to see app governance pages or manage policies and settings:

- Application Administrator
- Cloud Application Administrator
- Company or Global Administrator
- Compliance Administrator
- Compliance Data Administrator
- Global Reader
- Security Administrator
- Security Operator
- Security Reader (read-only)

> [!NOTE]
> Only Global Admin, Company Admin, or Billing Admin role can activate the app governance free trial.

Here are the capabilities for each role.

| Role | Read the dashboard | Read all apps |Read policies | Create, update, or delete policies | Read alerts | Update alerts | Read settings | Update settings | Read Remediation | Update Remediation |
|:-------|:-----|:-------|:-------|:-------|:-------|:-------|:-------|:-------|:-------|:-------|
| Application Administrator | ![Check mark.](media\checkmark.png) | ![Check mark.](media\checkmark.png) | ![Check mark.](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) |
| Cloud Application Administrator | ![Check mark](media\checkmark.png) | | | | | | | | | |
| Company or Global Administrator | ![Check mark.](media\checkmark.png) | ![Check mark.](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) |
| Compliance Administrator | ![Check mark.](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) |  | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | |
| Compliance Data Administrator | ![Check mark.](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) |  | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | |
| Global Reader  | ![Check mark.](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) |  | ![Check mark](media\checkmark.png) |  | ![Check mark](media\checkmark.png) |  | | |
| Security Administrator | ![Check mark.](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) |  | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | |
| Security Operator | ![Check mark.](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) | |
| Security Reader  | ![Check mark.](media\checkmark.png) | ![Check mark](media\checkmark.png) | ![Check mark](media\checkmark.png) |  | ![Check mark](media\checkmark.png) |  | ![Check mark](media\checkmark.png) |  | ![Check mark](media\checkmark.png) | |
|||||||||| | |

For more information about each role, see [Administrator role permissions](/azure/active-directory/roles/permissions-reference).



