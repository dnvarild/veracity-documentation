---
author: Veracity
description: Give a general description of the Veracity Identity Service.
---

# Veracity Identity
Veracity Identity is the Identity Provider (IDP) for the Veracity Platform. It provides a secure authentication mechansim for 1st and 3rd party services as well as authorization for 1st parties. The service is built upon Microsoft Azure B2C and uses common industry standards such as **OpenID Connect** and **Authorization code flow** to authenticate users.

The Veracity Identity Provider (IDP) also provides federation services other industry leading companies in order to allow single-sign-on for users accross the sector. Using the Veracity IDP allows you not only to securely authenticate your own users, but you can also instantly provide access to users of other companies federated with Veracity.

This documentation contains information about how the Veracity IDP works, how to integrate with it and some general information about the underlying protocols used. You can read more about the core protocols on the Azure documentation pages [here](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-app-types).

If you want to jump straight into implementations you can find a detailed tutorial in the [tutorials section](nodejs-webapp-ts/1-introduction.md) as well as helpful libraries on our [Veracity GitHub page](https://github.com/veracity).

If you are a customer with Veracity and are having issues with authentication you can email support at [support@veracity.com](mailto:support@veracity.com)
