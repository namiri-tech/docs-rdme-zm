---
title: Start using the API
excerpt: All you need to start using the API
deprecated: false
hidden: false
metadata:
  robots: index
---
## DigiTax suite of products

Namiri Technologies, through our DigiTax Platform, have developed a suite of solutions:

* DigiTax App (Mobile PWA),
* DigiTax Dashboard (Web Browser-based Desktop application) AND
* DigiTax API

> The first two are powered by the DigiTax API :tada:

Below are the steps required to get up and running

## Prerequisites

The following are the steps to getting a sandbox business (for testing before you go LIVE)

1. [Sign up on DigiTax](https://digitax.tech/sign-up)
2. Create a profile and select the appropriate country.
3. Create a business with a sample correctly formatted TPIN (Tax Payer Identification Number) like `2002720806` and **set it as a SANDBOX business**, with that, you can now transact on the dashboard.
4. Create the API Key under the "Integrations" tab.

Use the **X-API-Key** in your header when making API calls through the interactive API docs [here](/reference) OR via your integration during testing. This has a quick turn-around of a matter of hours. Do not wait for days 😊.

## Going LIVE

To go LIVE on the API, commercial conversations must be complete. If you wish to start those, email [info@namiri.tech](mailto:info@namiri.tech).

Create another business with your TPIN (Tax Payer Identification Number) like `2002720806` and **set it as a LIVE business**.

Follow the steps shared in the email sent by the DigiTax system to your inbox as soon as you successfully create a business.

Once that business goes LIVE, you can go ahead and generate an API Key under the "Integrations" tab. See screenshots below:

Navigate to the "Integrations" menu.\
Then select "Add API KEY"

<Image align="center" src="https://files.readme.io/b97314a806049fc3042278a8abada343b28117206f44a2539a2c3ef33d29fc59-Integrations.png" />

Enter a name and select "Api key". *Use "License key for DigiTax plugins*

<Image align="center" width="360px" src="https://files.readme.io/39b934dd7778737ed94d8ec97daf8bdee27e4750abf6b04b4841a80245014e95-API-key.png" />

Please copy the value that you generate for later use, as you will not see it from the dashboard on subsequent visits. Save it securely.

> 👍 Your integration is LIVE 🎉
>
> Using the LIVE X-API-Key, you'll now be interacting with the production environment of ZRA Smart Invoice System

## API Keys management

Once you generate an API key, you have the option to deactivate them (when necessary).

Navigate to the "Integrations" menu and click on the "padlock" icon under the "Action" column.

<Image align="center" src="https://files.readme.io/5ea35d2d4c3aacade4d37cb8d95797e68256a4af37472ce47b16f77e64c44669-A.png" />

Click "Deactivate key" if you'd like to invalidate the key for API use.

<Image align="center" width="360px" src="https://files.readme.io/5b994f64ef75fa1b2013be019cb7c444e20c750b1d57df44ba140cbf54f88df8-B.png" />

*To making tax compliance less taxing.*