# Outlineify Privacy Policy

Last updated: October 26, 2026

This policy explains what information Outlineify collects through the app and its website, getoutlineify.app, why, who it is shared with, how long it is kept and how you can delete it. Outlineify is an app for iPhone, iPad and Android phones and tablets that turns a photo into a printable color-by-number page.

## Who we are

Outlineify is provided by İhsan Oktar Kara, an individual developer based in Türkiye ("we", "us"). We are responsible for your information as described in this policy. You can reach us at [agensgratu@gmail.com](mailto:agensgratu@gmail.com).

## Who Outlineify is for

Outlineify is for adults aged 18 or over, such as parents and guardians. It is not directed at children, and children should not create an account or use the app themselves. Photos you upload may show your family; you should only upload photos you have the right to use.

## What we collect and why

| Information                                                                                                                                                                          | Why we use it                                                                             |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------- |
| An anonymous user identifier, created when you first open the app                                                                                                                    | To keep your account, drawings and subscription together without asking for a form        |
| Your Apple identity, only if you choose to link Sign in with Apple (iPhone and iPad only)                                                                                            | To let you restore your account on another device                                         |
| Subscription status from the App Store or Google Play, received through RevenueCat                                                                                                   | To know whether your subscription is active and to apply the weekly limit                 |
| The photos you choose to convert                                                                                                                                                     | To create your coloring pages                                                             |
| Your conversions and finished pages                                                                                                                                                  | To show your drawings in the app and let you print or download them again                 |
| A notification token for your device, only if you allow notifications                                                                                                                | To tell you when your page is ready                                                       |
| Crash and performance reports that include only your anonymous user identifier (no photos, names or contact details)                                                                 | To find and fix errors and slow screens in the app                                        |
| If you report a page: the reason you choose, the note you write if you add one, the page's conversion identifier and your anonymous user identifier                                  | To review pages reported as offensive, wrong or unsafe, and to improve how pages are made |
| App usage events, such as the screens you open and the steps you take, with your anonymous user identifier                                                                           | To understand how the app is used and improve it                                          |
| An app instance identifier and the value of a purchase, sent to Google Analytics for Firebase                                                                                        | To measure which of our ads, including Google Ads, bring people who use and buy the app   |
| Website visits: the page you open, the site or campaign link that sent you, your browser, device type and country, and Google Analytics cookie identifiers where cookies are allowed | To learn which pages and links bring visitors to the website and to the App Store         |
| If you downloaded the iPhone or iPad app after tapping an Apple Search Ads ad: the campaign, ad group and keyword Apple reports for that download, received through RevenueCat       | To learn which of our App Store ads bring people who subscribe                            |

We do not collect your name, email address, contacts or precise location. We do not use your photos to train AI models, and we do not sell your information.

## How your photos are handled

1. **On your device.** Before upload, the app re-encodes the photo and removes location and other metadata.
2. **Upload.** The photo is uploaded to our private storage on Amazon Web Services (AWS) in the European Union (Ireland).
3. **Processing by third-party AI providers.** To create your page, the photo is processed by AI models reached through fal.ai, in two steps:
   - **Color brief.** Claude Haiku, an AI model by Anthropic, reached through OpenRouter, looks at the photo and lists the things in it with suggested crayon colors. This list guides the drawing and is not stored by us.
   - **Drawing.** AI image models provided by OpenAI (our primary provider) and, if that fails, Meta (our fallback provider) draw the page.

   The photo is passed to these models as a short-lived link, and request history at fal.ai is turned off for our account. Anthropic states that it does not use API inputs and outputs to train its models and deletes them within 30 days, except where needed to enforce its usage policy or required by law. OpenRouter states that it does not keep the content of requests by default. OpenRouter may run Claude Haiku on Anthropic's own service or on Amazon Web Services, Google Cloud or Microsoft Azure.

4. **Deletion of the photo.** The uploaded photo is deleted from our storage as soon as its conversion finishes, fails or is cancelled, and in any case within one day.

## How long we keep information

- **Uploaded photos:** deleted when the conversion finishes, fails or is cancelled, and in any case within one day.
- **Finished pages:** kept until you delete the drawing or your account.
- **Account data** (anonymous identifier, optional Apple identity, subscription status, notification token and your conversions): kept until you delete your account.
- **Weekly limit record:** to keep the weekly fair-use limit fair, we keep a coded, one-way reference to your subscription together with that week's page count, even after you delete your account. It cannot be used to identify you, and we erase it automatically about three weeks after that week ends.
- **Pages saved on your device:** the app keeps downloaded pages on your device until you delete the drawing, delete your account or remove the app.
- **Crash and performance reports:** kept by Sentry for a limited period under its standard retention settings.
- **Page reports:** kept by Sentry for a limited period under its standard retention settings, so we can review them.
- **App usage events:** kept by PostHog for a limited period under its standard retention settings. They are linked only to your anonymous user identifier, so they stay after you delete your account but no longer belong to any account; email us if you want them deleted.
- **Website visit events:** kept by PostHog for a limited period under its standard retention settings. They are not linked to you, to an account or to the app.
- **Website visits in Google Analytics:** visit-level event data is kept for 2 months, after which Google deletes it. User-level data, meaning the random browser identifier and the information attached to it, is kept for up to 14 months after your last visit. The Google Analytics cookies on your device expire after 2 years unless you delete them sooner.
- **Your cookie choice:** kept in your browser until you change it or clear the site's data.

## Who we share information with

We share information only with service providers that run Outlineify for us:

| Provider                                                | What it does                                                                                                                                                                                                                         | Location                                                         |
| ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------- |
| Amazon Web Services                                     | Stores uploaded photos and runs the conversion                                                                                                                                                                                       | European Union (Ireland)                                         |
| Supabase                                                | Hosts our database and account sign-in                                                                                                                                                                                               | European Union (Ireland)                                         |
| fal.ai, OpenAI and Meta                                 | Process photos with AI models to create pages                                                                                                                                                                                        | United States                                                    |
| OpenRouter and Anthropic (Claude Haiku), through fal.ai | List the things in a photo and suggest colors for its page                                                                                                                                                                           | United States, and other regions where OpenRouter runs the model |
| RevenueCat                                              | Manages subscription status for App Store and Google Play purchases, and on iPhone and iPad receives from Apple which Apple Search Ads campaign, if any, led to your download                                                        | United States                                                    |
| Expo                                                    | Delivers the "your page is ready" notification, using your notification token and the notification text, through Apple on iPhone and iPad and through Firebase Cloud Messaging on Android                                            | United States                                                    |
| Apple                                                   | On iPhone and iPad: processes payments, delivers notifications and, if you use it, Sign in with Apple                                                                                                                                |
| Google Play and Firebase Cloud Messaging, by Google     | On Android: processes payments and delivers notifications                                                                                                                                                                            | Worldwide                                                        |
| Sentry                                                  | Receives crash and performance reports, and the pages you report, with only your anonymous user identifier                                                                                                                           | United States                                                    |
| PostHog                                                 | Receives app usage events with your anonymous user identifier, and anonymous website visits, for analytics                                                                                                                           | European Union (Germany)                                         |
| Google (Firebase and Google Analytics for Firebase)     | Receives app usage events, purchase value and currency, an app instance identifier and your anonymous user identifier, to measure the app and which of our ads work; and website visits through Google Analytics, as described below | United States                                                    |

Some of these providers are outside the European Economic Area and Türkiye. Where information is transferred internationally, we rely on the safeguards these providers offer, such as the European Commission's Standard Contractual Clauses.

We may also disclose information if the law requires it.

## Tracking, ads and analytics

Outlineify uses PostHog, a product analytics service by PostHog Inc. that stores our data in the European Union, to understand how the app is used and where it can be improved. The app sends usage events, such as the screens you open and steps like choosing a photo, choosing a detail level, viewing the plans, printing a page or completing a purchase (with the plan chosen). Each event carries your anonymous user identifier, the app version, the platform (iOS or Android), the app language, your device's language and region setting, time zone, device type and screen size, and whether you have a subscription.

The app does not send your photos or pages, anything you type, your name, your email address or your Apple identity. PostHog is set not to look up your location from your IP address and not to store it.

On getoutlineify.app, PostHog counts page visits and clicks on the App Store links. Each visit event carries the page, the site that sent you, the campaign source of the link you followed (such as Pinterest or YouTube), your browser, device type and screen size, and the country your visit comes from. PostHog works out the country from your IP address without storing the address. PostHog sets no cookies and uses no browser storage on the website. While you move between its pages, the site remembers the campaign source and a random visit number only within your browser tab, so a visit of several pages counts once. Website visits are not linked to you or to the app. When you tap an App Store link, the link tells Apple the campaign source, so App Store Connect can count downloads per source without identifying you.

The website also uses Google Analytics, by Google, so we can see the website and the app side by side. It records the pages you open, scrolling, clicks on links that leave the site, taps on the App Store links (with the campaign source) and how long you stay, together with your browser, device type, screen size, language and an approximate location (country and city) that Google derives from your IP address. Google Analytics does not store your IP address. To recognise a returning browser, it sets two first-party cookies, `_ga` and `_ga_J0GQ4PB5WQ`, which hold a random identifier and the time of your visit.

If you visit from the European Economic Area, the United Kingdom or Switzerland, the website asks you first, and these cookies are set only if you choose Accept. Until then, or if you choose Decline, Google Analytics receives only a basic signal that a page was viewed, without cookies or identifiers, which Google uses to estimate visit numbers. Elsewhere the cookies are allowed by default. Wherever you are, you can change your choice at any time with Cookie settings at the bottom of every page; the website remembers it in your browser's local storage.

We have turned off ads storage, ads personalization and Google signals for the website, so Google Analytics data from the website is not used for advertising to you. Our Google Analytics property is linked to our Google Ads account, which runs our App Store app campaign, so Google also receives a basic signal of each website visit for ad measurement. Because ads storage and ads personalization stay turned off, this signal carries no advertising cookies and is not used to show you ads. The website does not collect or send any information you type, such as an email address or phone number. Google processes Google Analytics data for us as our processor under its data processing terms. Website visits are not linked to your account or your use of the app.

On iPhone and iPad, if you downloaded Outlineify after tapping an Apple Search Ads ad in the App Store, the app asks Apple's AdServices framework for an attribution token, and RevenueCat exchanges it with Apple for the campaign, ad group and keyword of that ad. Apple provides this without identifying you and without tracking you across other companies' apps or websites, so it needs no App Tracking Transparency permission. We use it only to measure which of our ads lead to downloads and subscriptions.

The app also uses Google Analytics for Firebase, by Google. It sends a small set of events: the first time you open the app, finishing the intro, a page being ready, viewing the plans, being asked for an App Store or Google Play rating, and a purchase with its value and currency. Each event carries an app instance identifier, your anonymous user identifier, your device model, operating system version (iOS or Android) and an approximate region that Google derives from your IP address. On Android, it also records the campaign information Google Play passes on with the download (the install referrer), which shows whether a Google Ads campaign or a link led to it. We use it to understand how people find and use Outlineify and to measure which of our ads, such as Google Ads campaigns, lead to downloads and purchases. The app does not collect the advertising identifier (the IDFA on iPhone and iPad, the advertising ID on Android), we have turned off ads personalization for this data in Google Analytics, and it is not used to track you across other companies' apps or websites.

Outlineify shows no ads, does not track you across apps or websites owned by other companies, and does not share analytics data with advertisers or data brokers. For this reason the app does not ask for App Tracking Transparency permission on iPhone and iPad.

## Deleting your information

The steps below are also on our account deletion page, [getoutlineify.app/delete-account](https://getoutlineify.app/delete-account).

- **Delete a drawing:** delete it in the app. Its finished page is removed from our storage.
- **Pages on your device:** pages the app keeps on your device are removed when you delete the drawing or your account, or when you remove the app.
- **Delete your account:** use Delete account in the app's settings. This removes your files and data from our service, revokes Sign in with Apple if you linked it on iPhone or iPad, and deletes your customer record at RevenueCat. Only the weekly limit record described above is kept, until it is erased.
- Deleting your account does **not** cancel your subscription. To stop future charges, cancel it in your Apple ID settings on iPhone or iPad (Settings → your name → Subscriptions), or in Google Play on Android (Play Store → your profile picture → Payments & subscriptions → Subscriptions).

If you cannot use the app, email us at [agensgratu@gmail.com](mailto:agensgratu@gmail.com) and we will help you.

## Your rights

Depending on where you live, you may have the right to access, correct, delete or receive a copy of your information, to object to or restrict its processing, and to withdraw consent. To use these rights, email [agensgratu@gmail.com](mailto:agensgratu@gmail.com). Because we do not ask for your name or email, we may ask for details that help us find your account, such as the date of your subscription purchase. In most cases the quickest way to delete your data is Delete account in the app.

You also have the right to complain to a data protection authority, such as the authority in your country of residence in the European Union, or the Turkish Personal Data Protection Authority (KVKK).

## Legal basis

Where the GDPR or a similar law applies, we process your information to provide the service you asked for (performance of a contract), to keep the service secure and working and to understand how the app is used so we can improve it (our legitimate interests) and to meet legal obligations. Google Analytics cookies on the website are set in the European Economic Area, the United Kingdom and Switzerland only with your consent, which you can withdraw at any time with Cookie settings.

## Security

Photos and pages are stored privately and transferred over encrypted connections. Only our service and the providers listed above can access them, and only to run Outlineify.

## Changes to this policy

If we change this policy, we will update the date above and, for important changes, tell you in the app.

## Contact

[agensgratu@gmail.com](mailto:agensgratu@gmail.com)
