# Outlineify Privacy Policy

Last updated: October 4, 2026

This policy explains what information Outlineify collects, why, who it is shared with, how long it is kept and how you can delete it. Outlineify is an iPhone and iPad app that turns a photo into a printable color-by-number page.

## Who we are

Outlineify is provided by İhsan Oktar Kara, an individual developer based in Türkiye ("we", "us"). We are responsible for your information as described in this policy. You can reach us at [agensgratu@gmail.com](mailto:agensgratu@gmail.com).

## Who Outlineify is for

Outlineify is for adults aged 18 or over, such as parents and guardians. It is not directed at children, and children should not create an account or use the app themselves. Photos you upload may show your family; you should only upload photos you have the right to use.

## What we collect and why

| Information                                                           | Why we use it                                                                      |
| --------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| An anonymous user identifier, created when you first open the app     | To keep your account, drawings and subscription together without asking for a form |
| Your Apple identity, only if you choose to link Sign in with Apple    | To let you restore your account on another device                                  |
| Subscription status from the App Store, received through RevenueCat   | To know whether your subscription is active and to apply the weekly limit          |
| The photos you choose to convert                                      | To create your coloring pages                                                      |
| Your conversions and finished pages                                   | To show your drawings in the app and let you print or download them again          |
| A notification token for your device, only if you allow notifications | To tell you when your page is ready                                                |
| Crash reports that do not contain personal data                       | To find and fix errors in the app                                                  |

We do not collect your name, email address, contacts or location. We do not use your photos to train AI models, and we do not sell your information.

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
- **Pages saved on your device:** the app keeps downloaded pages on your device until you delete the drawing, delete your account or remove the app.
- **Crash reports:** kept by Sentry for a limited period under its standard retention settings.

## Who we share information with

We share information only with service providers that run Outlineify for us:

| Provider                                                | What it does                                                                                            | Location                                                         |
| ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| Amazon Web Services                                     | Stores uploaded photos and runs the conversion                                                          | European Union (Ireland)                                         |
| Supabase                                                | Hosts our database and account sign-in                                                                  | European Union (Ireland)                                         |
| fal.ai, OpenAI and Meta                                 | Process photos with AI models to create pages                                                           | United States                                                    |
| OpenRouter and Anthropic (Claude Haiku), through fal.ai | List the things in a photo and suggest colors for its page                                              | United States, and other regions where OpenRouter runs the model |
| RevenueCat                                              | Manages subscription status                                                                             | United States                                                    |
| Expo                                                    | Delivers the "your page is ready" notification, using your notification token and the notification text | United States                                                    |
| Apple                                                   | Processes payments, delivers notifications and, if you use it, Sign in with Apple                       | Worldwide                                                        |
| Sentry                                                  | Receives crash reports without personal data                                                            | United States                                                    |

Some of these providers are outside the European Economic Area and Türkiye. Where information is transferred internationally, we rely on the safeguards these providers offer, such as the European Commission's Standard Contractual Clauses.

We may also disclose information if the law requires it.

## Tracking, ads and analytics

Outlineify does not track you across apps or websites, shows no ads and uses no third-party analytics. For this reason the app does not ask for App Tracking Transparency permission.

## Deleting your information

- **Delete a drawing:** delete it in the app. Its finished page is removed from our storage.
- **Pages on your device:** pages the app keeps on your device are removed when you delete the drawing or your account, or when you remove the app.
- **Delete your account:** use Delete account in the app's settings. This removes your files and data from our service, revokes Sign in with Apple if you linked it, and deletes your customer record at RevenueCat.
- Deleting your account does **not** cancel an App Store subscription. Cancel it in your Apple ID settings (Settings → your name → Subscriptions) to stop future charges.

If you cannot use the app, email us at [agensgratu@gmail.com](mailto:agensgratu@gmail.com) and we will help you.

## Your rights

Depending on where you live, you may have the right to access, correct, delete or receive a copy of your information, to object to or restrict its processing, and to withdraw consent. To use these rights, email [agensgratu@gmail.com](mailto:agensgratu@gmail.com). Because we do not ask for your name or email, we may ask for details that help us find your account, such as the date of your subscription purchase. In most cases the quickest way to delete your data is Delete account in the app.

You also have the right to complain to a data protection authority, such as the authority in your country of residence in the European Union, or the Turkish Personal Data Protection Authority (KVKK).

## Legal basis

Where the GDPR or a similar law applies, we process your information to provide the service you asked for (performance of a contract), to keep the service secure and working (our legitimate interests) and to meet legal obligations.

## Security

Photos and pages are stored privately and transferred over encrypted connections. Only our service and the providers listed above can access them, and only to run Outlineify.

## Changes to this policy

If we change this policy, we will update the date above and, for important changes, tell you in the app.

## Contact

[agensgratu@gmail.com](mailto:agensgratu@gmail.com)
