# Privacy Policy for MyStocky

**Effective Date:** June 2, 2026  
**Last Updated:** June 2, 2026

---

## 1. Introduction

MyStocky ("the App," "we," "our," or "us") is an iOS application for managing home inventory and storage. This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our App, and your rights regarding that information.

We are committed to protecting your privacy and ensuring you have a positive experience on our App. Please read this Privacy Policy carefully. If you have questions about our privacy practices, contact us at [mystocky.app@gmail.com](mailto:mystocky.app@gmail.com).

---

## 2. Information We Collect

### 2.1 Information You Provide Directly

**Account Information** (Premium Users Only)
- Email address: Required to create and manage a Premium subscription account
- Name: Optional, for personalization (displayed in multi-user family sharing contexts)
- Subscription information: Managed by Apple through StoreKit (we do not store your payment card details)

**Inventory Data**
- Item names, descriptions, categories, quantities, locations, and barcodes
- Expiry dates and alert thresholds
- Custom notes and tags you add

**Images**
- Photos of inventory items or storage locations that you capture using the App's camera feature
- These images are stored on your device and, for Premium users, backed up to iCloud

### 2.2 Information Collected Automatically

**Device and Usage Information**
- iOS version and device model
- App version and crash logs
- Language and locale settings
- Feature usage (e.g., how often you use the scanner, how many items you add)
- Error logs and diagnostic information

**Camera Access**
- The App requests permission to access your device's camera for barcode scanning and taking photos
- **We do not access or record video**—only still images you explicitly capture
- Camera access is requested at runtime and you can deny it at any time in Settings

**iCloud / CloudKit** (Premium Sync Only)
- For Premium users, we automatically collect metadata about your iCloud synchronization activity to maintain sync status (e.g., sync timestamp, device identifiers for conflict resolution)
- We do not access your other iCloud data

---

## 3. How We Use Your Information

We use the information we collect to:

1. **Provide and operate the App** — Store your inventory data, enable barcode scanning, and deliver features
2. **Sync data across your devices** — For Premium users, sync inventory and basket lists across multiple devices via iCloud/CloudKit
3. **Enable family sharing** — For Premium users, allow family members to view and edit shared inventory
4. **Improve the App** — Analyze usage patterns and crash logs to fix bugs and enhance features
5. **Comply with legal obligations** — Respond to lawful requests from authorities and enforce our Terms of Use
6. **Communication** — Send service updates, security alerts, and subscription renewal notices (via Apple's systems)

We do **not**:
- Sell your data to third parties
- Use your data for targeted advertising
- Share your inventory data with unaffiliated companies
- Use your photos for training AI models or commercial purposes

---

## 4. How We Store and Protect Your Data

### 4.1 Local Storage (Free and Premium Users)

**All inventory data (items, locations, quantities, images) is stored on your device** using the secure, encrypted SwiftData database. This local storage is the primary source of truth for your data.

- **Encryption:** SwiftData on iOS automatically encrypts data at rest using the device's secure enclave
- **Backup:** iOS's native backup and restore feature (iCloud Backup or iTunes) includes App data
- **Offline Capability:** You can fully access and manage your inventory without an internet connection

### 4.2 Cloud Storage (Premium Users Only)

Premium users who opt into family sharing and multi-device sync have their data mirrored to Apple's iCloud using CloudKit:

- **Encryption in Transit:** All data is encrypted using HTTPS and CloudKit's encrypted communication
- **Encryption at Rest:** CloudKit encrypts data at rest within iCloud, protected by your Apple ID
- **Automatic Mirroring:** Your local SwiftData store is automatically mirrored to CloudKit; conflicts are resolved by keeping the most recent change
- **iCloud Container:** Data is stored in an app-specific iCloud container (`iCloud.com.mystocky.app`) isolated from other apps and data
- **No Server Backend:** We do not operate our own servers or cloud database; all Premium sync uses Apple's native CloudKit service

### 4.3 Subscription Data

- Payment information, subscription status, and receipt validation are handled entirely by Apple's StoreKit
- **We do not store, process, or have access to your payment card details**
- Subscription receipts are validated with Apple's servers to confirm your Premium tier

### 4.4 Security Measures

- No plaintext passwords or payment information is stored
- Camera images are stored locally on your device and are not transmitted unless you choose to enable family sharing (Premium)
- All network communication uses industry-standard HTTPS encryption
- We do not share your data with third-party analytics or crash-reporting services that would collect personal information

---

## 5. Data Retention

- **Local Data:** Your inventory data remains on your device until you manually delete it or uninstall the App
- **iCloud Data:** When you delete an item from your device, the deletion syncs to iCloud after reconnection. You can delete your entire iCloud backup through iOS Settings
- **Account Data:** If you cancel a Premium subscription, your account email is retained in our system to process refunds and honor your legal rights, but your inventory data remains only on your device
- **Crash Logs:** Diagnostic data is retained for up to 30 days to diagnose issues, then deleted

---

## 6. Your Privacy Rights

### 6.1 Access and Portability

- You have the right to access, review, and obtain a copy of your personal data
- Your inventory data is stored on your device in a standard iOS app format and can be backed up via iTunes or iCloud Backup

### 6.2 Deletion

- You can delete individual inventory items within the App at any time
- You can delete all data by uninstalling the App or by erasing the App's data in Settings
- For Premium users, you can disable iCloud sync in the Settings tab to stop syncing future changes (existing synced data is not automatically removed from iCloud; remove it through iCloud Settings)

### 6.3 Opt-Out

- **Camera:** Disable camera access in iOS Settings at any time (this disables the barcode scanner feature)
- **Notifications:** Manage notification preferences in iOS Settings and the App Settings tab
- **iCloud Sync:** Premium users can disable sync in the App Settings tab

### 6.4 GDPR and CCPA Rights

**For users in the EU, GDPR grants you:**
- Right to access, correct, and delete your personal data
- Right to restrict processing and object to processing
- Right to data portability

**For users in California, CCPA grants you:**
- Right to know what personal information is collected
- Right to delete personal information
- Right to opt-out of the "sale" of personal information (we do not sell data)
- Right to non-discrimination for exercising your rights

To exercise these rights, contact us at [mystocky.app@gmail.com](mailto:mystocky.app@gmail.com) with:
- Your request (access, deletion, portability, or opt-out)
- Proof of identity (e.g., email associated with your account)

We will respond within 30 days (or as required by law).

---

## 7. Third-Party Sharing

We do **not** share your personal data with third parties except:

1. **Apple Inc.** — For StoreKit subscription processing and iCloud/CloudKit sync
2. **Legal Requirements** — When required by law (e.g., court order, government request) or to protect safety and rights
3. **Service Providers** — We do not use third-party analytics, crash reporting, or advertising networks that collect personal information; diagnostic data is handled locally or through Apple's aggregated reporting

---

## 8. Children's Privacy

MyStocky is not intended for children under 13 years old. We do not knowingly collect personal information from children under 13. If we become aware that a child under 13 has provided us with personal information, we will take steps to delete such information and cancel the child's access to the App. If you believe we have collected personal information from a child under 13, contact us immediately at [mystocky.app@gmail.com](mailto:mystocky.app@gmail.com).

---

## 9. California Privacy Notice (CCPA Supplement)

### 9.1 Categories of Personal Information We Collect

Under CCPA, we collect:
- **Identifiers:** Email address, device identifier
- **Commercial Information:** Subscription status, in-app activity
- **Device Information:** iOS version, device model, app version
- **Geolocation Data:** Device locale (stored locally; not shared)
- **Biometric Information:** None (camera access is user-initiated and image capture is not automatic)
- **Inferences:** Usage patterns inferred from crash logs and feature usage (stored locally)

### 9.2 Use of Sensitive Personal Information

We do not use sensitive personal information (race, ethnicity, political beliefs, union membership, etc.) for any purpose.

### 9.3 Your CCPA Rights

You have the right to:
- **Know** what personal information we collect and how we use it
- **Delete** your personal information (with limited exceptions)
- **Opt-Out** of the "sale" of your personal information (we do not sell data)
- **Non-Discrimination:** We will not discriminate against you for exercising your rights

To submit a CCPA request, email [mystocky.app@gmail.com](mailto:mystocky.app@gmail.com) or complete a verifiable consumer request. We will respond within 45 days.

---

## 10. EU Data Protection (GDPR)

If you are a resident of the EU, the following applies:

### 10.1 Legal Basis for Processing

We process your personal data on the following legal bases:
- **Contract:** To perform our service (provide the App and Premium sync)
- **Legitimate Interest:** To improve the App and provide customer support
- **Consent:** For optional features like family sharing and iCloud sync
- **Legal Obligation:** To comply with laws and protect rights

### 10.2 Data Protection Rights

You have the right to:
- Access, correct, and delete your personal data
- Restrict or object to processing
- Data portability (receive your data in a portable format)
- Withdraw consent at any time (without affecting past processing)
- Lodge a complaint with a supervisory authority

### 10.3 Data Transfers

Your data may be transferred to servers located outside the EU (e.g., Apple's iCloud infrastructure). By using MyStocky, you consent to such transfers. Apple has implemented appropriate safeguards (Standard Contractual Clauses) to protect data in transit.

### 10.4 Data Protection Officer

To contact our data protection representative or raise a privacy concern under GDPR, email [mystocky.app@gmail.com](mailto:mystocky.app@gmail.com).

---

## 11. Cookies and Tracking

MyStocky does **not** use:
- Cookies or web tracking technologies (we are not a web app)
- Third-party analytics or tracking pixels
- Fingerprinting or device identifiers for profiling
- Any persistent tracking across devices

---

## 12. Updates to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of material changes by:
- Posting the updated policy with a new "Last Updated" date in the App
- Sending a notification (if required by law)

Your continued use of the App after changes become effective constitutes acceptance of the updated Privacy Policy. We recommend reviewing this policy periodically to stay informed of how we protect your data.

---

## 13. Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or our privacy practices, please contact us:

**Email:** [mystocky.app@gmail.com](mailto:mystocky.app@gmail.com)  

**Response Time:** We will respond to privacy inquiries within 30 days.

For GDPR-related inquiries, you may also contact the data protection authority in your country.

---

## 14. Additional Disclosures

### 14.1 Apple App Store Privacy Label

This Privacy Policy is consistent with the disclosures we make in the Apple App Store privacy label (visible on the App's listing). The App Store label summarizes the data we collect and how we use it.

### 14.2 Limitation of Liability

To the extent permitted by law, we are not liable for any unauthorized access to or use of your data due to factors beyond our reasonable control (e.g., device loss, malware on your device, or unauthorized access to your iCloud account).

---

**End of Privacy Policy**

---

### Appendix: Camera Permission Explanation

When you first open MyStocky's scanner feature or try to take a photo, iOS will prompt you with:

> "MyStocky" would like to access your camera

**Why we need this:**
- To scan barcodes from product packaging
- To capture photos of inventory items for visual reference

**What we do with camera access:**
- Only images you explicitly capture are stored
- Images are stored on your device (local storage)
- For Premium users, images may be backed up to iCloud
- Images are never shared with third parties or used for any purpose other than your personal inventory management

**You can disable camera access at any time:**
- Go to **Settings → MyStocky → Camera** and toggle **OFF**
- The barcode scanner will no longer be available, but you can still manually add items

---

*This Privacy Policy is provided in English. If there are discrepancies between this version and a translated version, the English version prevails.*
