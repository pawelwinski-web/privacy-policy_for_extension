# Privacy Policy for Scout

**Last updated:** October 20, 2026  
**Developer:** Paweł Wiński  
**Contact:** pawel.winski@olx.pl

---

## 1. Introduction

This Privacy Policy describes how the Scout Chrome extension (“Scout”, “the extension”, “we”) collects, uses, stores, and shares user data.

Scout is a private, internal Chrome extension used exclusively by authorized employees of the organization to automate operational Customer Support / Customer Service workflows.

Scout is not intended for the general public. Installing or using Scout indicates that you have read this Privacy Policy and consent to the data practices described below.

---

## 2. Data Collection (What we collect and how)

Scout may collect or access the following categories of user and operational data when you use its features:

### 2.1 Operational case / ticket data
Data already present in the organization’s internal systems (primarily Salesforce and related internal tools), which Scout may read or transfer as part of a workflow initiated by the user, including for example:

- ticket number (`ticketNumber`)
- internal account ID (`accountID`)
- full name (`fullName`)
- compensation amount (`compensationAmount`)
- bank account number (`bankAccountNumber`)
- other case-related fields displayed on authorized internal pages that are needed to complete a specific workflow (e.g. order or payment identifiers, comments, status values)

### 2.2 Website and page content
When you use Scout on pages where it is active (authorized internal / work-related sites), Scout may read content from the active tab or page (DOM / form values / visible case data) solely to perform the feature you triggered.

### 2.3 Screenshots and on-screen content
If you use screenshot-related features (e.g. Scoutshot and/or OCR), Scout may capture an image of the visible browser tab / selected screen area. That image may contain whatever is visible on screen at that moment, including personal or confidential operational data. OCR, if used, processes the image locally inside the extension to extract text.

### 2.4 Clipboard data
With your interaction (copy / paste helpers), Scout may read from or write to the system clipboard to move operational text between internal tools.

### 2.5 Chrome account identifier
Scout may access your Chrome profile email address (via Chrome Identity APIs) to identify the authorized employee using the extension for internal audit, routing, or feature gating purposes.

### 2.6 Extension settings and usage state
Scout stores preferences and temporary operational state needed for the product to work, for example:

- feature toggles and UI preferences
- temporary workflow payloads / pending actions
- short-lived caches (e.g. lookup lists used by internal tools)
- local counters or status flags related to extension features

### 2.7 What we do not collect
Scout does not collect data for advertising, marketing analytics, cross-context tracking, or sale to third parties. Scout is not directed at children under 13.

---

## 3. Data Processing / Use (How we use data)

Scout processes the data described above solely to:

- automate internal operational workflows between organization-controlled systems
- reduce manual copy-paste and repetitive case-handling steps
- fill forms, prepare comments, generate internal exports, or submit data to organization-approved destinations when you trigger a feature
- improve case-handling efficiency for authorized employees
- operate extension settings, caches, and feature gates

Scout does **not** use data for:

- advertising or remarketing
- marketing analytics
- user profiling for commercial purposes
- selling, renting, or monetizing personal data
- automated decision-making that produces legal or similarly significant effects about individuals outside the supported internal workflow

---

## 4. Data Storage (Where and for how long)

### 4.1 Local storage on the user’s device
Scout stores certain data locally in the browser using Chrome extension storage (`chrome.storage.local` and/or `chrome.storage.sync`), and may keep temporary data in memory while a feature runs (e.g. a screenshot held briefly for OCR or annotation).

Locally stored items typically include settings, caches, and short-lived workflow state. They remain on the device / Chrome profile unless cleared by the user, removed by the extension logic, or deleted when the extension is uninstalled (subject to Chrome behavior).

### 4.2 No independent Scout database
Scout does not operate a separate consumer-facing Scout database for personal data. Scout acts as a technical bridge between organization systems.

### 4.3 Storage in organization systems
When you use a feature that sends data to an organization-controlled destination (for example Google Sheets / Google Workspace, Salesforce, or internal automation endpoints), retention of that data is governed by the organization’s policies for those systems, not by a separate Scout cloud database.

### 4.4 Retention
- **Local extension storage:** retained only as long as needed for the feature (settings until changed/uninstalled; temporary caches/payloads until completed, expired, or cleared).
- **Organization systems (Salesforce, Google Workspace, internal tools):** retained according to the organization’s internal data retention and GDPR policies.

---

## 5. Data Sharing / Disclosure (Who receives data)

Scout shares or transmits data only as required to perform a user-initiated internal workflow, and only to infrastructure controlled by or contracted for the organization, which may include:

- **Salesforce** (and related Lightning / Visualforce environments used by the organization)
- **Google Workspace / Google Sheets / Google APIs** (for internal spreadsheets and related automation)
- **Internal automation / tooling endpoints** used by the organization (for example internal n8n webhooks and other approved internal services)
- **Other authorized internal tools** that the organization configures Scout to integrate with for case handling (for example internal admin panels, Retool, or similar work systems)

Data is transmitted over HTTPS.

Scout:

- does **not** sell personal data
- does **not** share data with unrelated third-party advertisers
- does **not** make case data publicly available
- limits access to authorized employees and organization-controlled systems

Only authorized personnel with access to those organization systems can view the transferred data, subject to internal access controls.

---

## 6. Google API Limited Use disclosure

Scout’s use of information received from Google APIs (including Google Sheets / Google Workspace–related APIs, where applicable) will adhere to the [Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/user-data), including the Limited Use requirements.

---

## 7. Security

- Data in transit is sent over secure HTTPS connections.
- Access to organization systems is limited to authorized personnel.
- Scout does not intentionally expose operational data on public websites.
- Users should use Scout only on authorized work devices and accounts, in line with organization security policies.

---

## 8. Consent and prominent disclosure

Before using Scout’s data-handling features, users are informed that Scout processes operational and user-related data as described in this Privacy Policy and in the Chrome Web Store listing.

By installing Scout and/or continuing to use its features after being shown the in-product privacy notice (where presented), you provide affirmative consent to the collection, use, storage, and sharing practices described here, limited to the extension’s single internal operational purpose.

If you do not agree, do not install or use Scout, or uninstall the extension and stop using related features.

---

## 9. Your choices and requests

Authorized users may:

- review and change extension settings inside Scout
- clear site/extension data via Chrome settings, or uninstall Scout to remove local extension storage (subject to Chrome)
- contact the developer (below) to ask questions about this policy or to request assistance regarding access, correction, or deletion of personal data held in organization systems (such requests may also need to go through the organization’s internal privacy / IT channels for Salesforce and Google Workspace records)

---

## 10. Compliance

Scout operates within the organization’s data protection framework and complies with applicable GDPR requirements where relevant.

Scout does not perform commercial profiling or advertising-related automated decision-making.

---

## 11. Changes to this Privacy Policy

We may update this Privacy Policy from time to time. The “Last updated” date at the top will change when we do. Material changes to data practices will be reflected in this policy and, where required, disclosed prominently in the Chrome Web Store listing and/or in the product.

---

## 12. Contact

For questions about this Privacy Policy or Scout’s data practices:

**Email:** pawel.winski@olx.pl  
**Developer:** Paweł Wiński

---

**Effective date:** October 20, 2026

Using the Scout extension indicates acceptance of this Privacy Policy.
