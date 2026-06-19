# Privacy Policy for Outfit Finder

**Last updated: June 17, 2026**

This Privacy Policy explains how the **Outfit Finder** mobile application ("Outfit
Finder," "the App," "we," "us," or "our") collects, uses, shares, and protects
information when you use the App. Outfit Finder lets you take or select a photo
of an outfit and finds shoppable products that match the clothing in the image.

By downloading or using Outfit Finder, you agree to the practices described in
this Privacy Policy. If you do not agree, please do not use the App.

---

## 1. Summary

- We **do not require you to create an account**, and we **do not collect your
  name, email address, phone number, or any other directly identifying personal
  information.**
- The photos you submit are uploaded **temporarily** so they can be analyzed,
  and the image file is **deleted from our storage immediately after the
  analysis completes.**
- We assign your device a **random, anonymous identifier** used only for rate
  limiting, saving favorites, and basic analytics. It is not linked to your
  real-world identity.
- We share images and search queries with third-party AI and search providers
  (OpenAI and Google/SerpAPI) solely to produce your results.

---

## 2. Information We Collect

### 2.1 Photos and images you submit

When you ask Outfit Finder to analyze an outfit, the App sends the photo you
capture, choose from your photo library, or share into the App to our backend
service. The image is used only to detect garments and find matching products.

- The image is stored **temporarily** on our cloud storage (Supabase Storage)
  so that our AI and visual-search providers can access it.
- After the analysis finishes (or fails), the image file is **deleted from our
  storage.** We do not retain the image file after your result is produced.
- We do **not** use your photos to train AI models, and we do not sell them.

### 2.2 Anonymous device identifier

On first launch, the App generates a **random identifier (a UUID)** and stores
it securely on your device. This identifier:

- Is **not** derived from your name, email, account, or any hardware identifier.
- Is used to enforce daily usage limits, to associate your saved products
  ("favorites") with your device, and to record anonymous usage events.
- Is removed if you delete the App (it is stored in the device keychain, which
  the operating system clears on uninstall).

### 2.3 Analysis records

For each analysis we create a record on our backend that may include:

- The anonymous device identifier.
- The detected outfit details and the matching products returned (descriptions,
  categories, prices, merchant names, product links, and product image URLs).
- Technical metadata such as the time taken to process the request and whether
  it succeeded or failed.

This record does **not** contain the photo file itself (which is deleted as
described above).

### 2.4 Saved products (favorites)

If you save a product, we store the product details (title, price, merchant,
product image URL, and purchase link) on our backend, associated with your
anonymous device identifier, so your favorites are available the next time you
open the App.

### 2.5 Usage and analytics events

We log basic, anonymous events (for example, when an analysis is requested or a
product is saved) together with the anonymous device identifier and optional
non-personal context (such as event metadata). These are used to understand how
the App is used and to improve it.

### 2.6 Information we do **not** collect

- We do not collect your name, email address, postal address, or phone number.
- We do not collect precise geolocation.
- We do not require or use third-party advertising identifiers.
- We do not knowingly collect biometric identifiers; while photos may contain
  people, we use them only to identify clothing and we delete the image files
  after processing.

---

## 3. Device Permissions

Outfit Finder may ask for the following permissions:

- **Photo library access** — so you can choose an existing photo to analyze.
- **Shared images** — so you can share an image from another app into Outfit
  Finder for analysis.

You can grant or revoke these permissions at any time in your device settings.
Denying a permission may limit related features (for example, you will not be
able to select a photo from your library).

---

## 4. How We Use Your Information

We use the information described above to:

- Analyze your submitted image and detect the garments in it.
- Find and display shoppable products that match the detected garments.
- Save and display your favorite products.
- Enforce daily usage limits and prevent abuse of the service.
- Monitor, maintain, debug, and improve the performance and quality of the App.

We rely on your submission of a photo as your request for us to process it for
these purposes.

---

## 5. How We Share Your Information

We do **not** sell your personal information. We share information only with the
service providers necessary to operate the App:

| Provider | Purpose | What is shared |
| --- | --- | --- |
| **OpenAI** | AI vision analysis of the outfit | The submitted image (via a temporary URL) |
| **SerpAPI / Google Lens** | Visual product search | The submitted image (via a temporary URL) |
| **Google Programmable Search (Custom Search)** | Text-based product search | Text descriptions of the detected garments |
| **Supabase** | Cloud storage and database hosting | The temporary image, analysis records, saved products, anonymous device identifier, and usage events |

These providers process the data on our behalf to deliver the App's features.
Their handling of data is governed by their own privacy policies. We encourage
you to review them:

- OpenAI: https://openai.com/policies/privacy-policy
- SerpAPI: https://serpapi.com/legal/privacy
- Google: https://policies.google.com/privacy
- Supabase: https://supabase.com/privacy

We may also disclose information if required to do so by law, or to protect the
rights, property, or safety of our users or others.

---

## 6. Data Retention

- **Submitted image files:** deleted from our storage immediately after the
  analysis completes or fails. In rare error cases an orphaned file may persist
  briefly before cleanup.
- **Analysis records, saved products, usage events, and rate-limit counters:**
  retained while associated with your anonymous device identifier so that
  features such as favorites continue to work. You can request deletion as
  described below.

---

## 7. Security

We use industry-standard measures to protect your information, including:

- Encrypted storage of the device identifier in the device's secure keychain.
- Transmission of data to our backend and providers over secured connections.
- Access controls on our backend service.

No method of transmission or storage is completely secure, and we cannot
guarantee absolute security.

---

## 8. Children's Privacy

Outfit Finder is not directed to children under the age of 13 (or the minimum
age required in your jurisdiction). We do not knowingly collect personal
information from children. If you believe a child has provided us with
information, please contact us so we can delete it.

---

## 9. Your Rights and Choices

Depending on where you live, you may have rights regarding your information,
including the right to access, correct, or delete it.

Because we do not collect directly identifying information, we identify your
data by your **anonymous device identifier**. To exercise your rights:

- **Delete your data on your device:** uninstalling the App removes the device
  identifier stored on your device.
- **Delete your data on our backend:** contact us at the email below with a
  request. To help us locate your records, you may include your device
  identifier where available.
- **Stop further collection:** stop using the App and revoke its permissions in
  your device settings.

Residents of the EEA/UK (GDPR) and California (CCPA/CPRA) may have additional
rights, including the right to lodge a complaint with a supervisory authority.
We do not sell or "share" personal information for cross-context behavioral
advertising.

---

## 10. International Data Transfers

Our service providers may process and store information in countries other than
your own, including the United States. Where required, we rely on appropriate
safeguards for such transfers.

---

## 11. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we do, we will revise
the "Last updated" date at the top of this page. Material changes will be
reflected in the App or on the page where this policy is hosted. Your continued
use of the App after changes take effect constitutes acceptance of the updated
policy.

---

## 12. Contact Us

If you have questions, requests, or concerns about this Privacy Policy or your
data, please contact us:

- **App name:** Popout-Outfit Finder
- **Developer:** Bishal Thapa
- **Email:** bishalth77@gmail.com

---

*This document is provided to support App Store submission. It describes the
data practices of the Outfit Finder app as of the "Last updated" date above.*
