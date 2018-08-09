# AdMob

AdMob component allows you to easily montize your app using only drag-and-drop! The AdMob component is for creating Banner Ads. 

To start using AdMob, you'll to have an AdMob account and AdUnitId. To create account and AdUnitId, please follow Steps 1-6 from document [HERE](https://quickappninja.zendesk.com/hc/en-us/articles/115000826865-How-to-create-Banner-Admob-Ad-unit-ID-?mobile_site=true). 

## Ad Guidance:

Please see AdMob video guide below. It is very important to follow their Terms of Service \(ToS\) and guide:

[https://support.google.com/admob/answer/6128877?hl=en](https://support.google.com/admob/answer/6128877?hl=en)

## Basic Setup:

Create a new AppyBuilder project and name it TestAdmob

Once Design Editor opens, from the left Category Palette, select the Monetize category, then drag the AdMob \(visible component\)  and drop into the Layout. You are now able to select this Component and change the Ad-Unit-ID property in the Properties Palette. 

_**NOTE: For testing, you should use TEST AdUnitId. See link**_  [_**HERE**_ ](https://developers.google.com/admob/android/test-ads) _**for these IDs.**_ 

![](../../../.gitbook/assets/bookadmob1%20%282%29.png)

In addition, for the ADs to display, please ensure that you select Screen1 component, and then set the Sizing to Responsive:

![](../../../.gitbook/assets/book-admob-responsive%20%281%29.png)

##  Requesting Consent from European Users

Under the Google [EU User Consent Policy](https://www.google.com/about/company/consentstaging.html), you must make certain disclosures to your users in the European Economic Area \(EEA\) and obtain their consent to use personal data \(such as AdID\) to serve ads. This policy reflects the requirements of the EU ePrivacy Directive and the **General Data Protection Regulation \(GDPR\)**. You can get more information about GDPR and European consent, please visit page [HERE](https://developers.google.com/admob/android/eu-consent).

To support developers in meeting their duties under this policy, AppyBuilder has implemented blocks to help you meet the GDPR requirements.

#### Use block below to determine if user is in Europe:

![](../../../.gitbook/assets/image%20%284%29.png)

#### If user is in Europe, you can use block below to RequestConsentStatus

![](../../../.gitbook/assets/image%20%2837%29.png)

  
Invoking above block will trigger event-handler block ConsentStatusLoaded block below. This block includes parameters below: 

1. isPersonalized: if ad delivery is set to personalized, it will return true, else false
2. isEuropeanUser: returns true if user is in Europe, else false
3. message: Gives status of user consent. If consent not given it will be set to "unknow", if user has consented to personalized data, if be set to "personalized". If user consented to non\_personalized, it will be set to "non\_personalized". 

![](../../../.gitbook/assets/image%20%281%29.png)

  
Revoking Consent. You can use block block below to revoke / cancel the previous consent. This block was added to stay compliant with Google for allowing your app to reset / refresh consent.

![](../../../.gitbook/assets/image%20%2841%29.png)

