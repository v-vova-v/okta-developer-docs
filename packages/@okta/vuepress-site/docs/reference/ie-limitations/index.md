---
title: Classic features not supported in Identity Engine
excerpt: The Okta Identity Engine introduces a lot of changes to the Okta platform. Some of these changes result in a lack of support for previously available features.
---

The Okta Identity Engine introduces a lot of changes to the Okta platform. Some of these changes result in a lack of support for previously available features. In some cases, features may have future support.

#### Okta Verify

**What Changed:**  

* Multiple Okta Verify Push factors for the same user may not be enrolled
* The FIPS compliance requirement for enrollments is not enforced
* The User Verification requirement for enrollments is not enforced
* New enrollments are not mapped to a device

**Future Support:** No  
**Further Information:** [Factors API](/docs/reference/api/factors/)  

***

#### Sign-In Widget Customization

**What Changed:** The following feature flags are no longer supported:  

* `features.idpDiscovery`
* `features.autoPush`
* `features.smsRecovery`
* `features.emailRecovery`
* `features.callRecovery`
* `features.multiOptionalFactorEnroll`
* `features.webauthn`
* `features.selfServiceUnlock`
* `features.registration`

**Future Support:** No  
**Further Information:** [Okta Sign-In Widget Feature Flags](https://github.com/okta/okta-signin-widget#feature-flags)  

***

#### Okta Mobile

**What Changed:** Feature removed. Users in an Identity Engine org will not be able to sign in to Okta Mobile.  
**Future Support:** Yes (Date??)  
**Further Information:** [??](??)  
