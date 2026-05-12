# Privacy Policy

**Last Updated: May 12, 2026**

This Privacy Policy explains how **FRM**, a product of **Cubicle #6** ("FRM," "Cubicle #6," "we," "us," or "our"), collects, uses, shares, and protects information when you use the FRM web application and related services (the "Service"). FRM is a customer relationship management ("CRM") platform built for nonprofit fundraisers.

By using the Service, you agree to this Privacy Policy. If you do not agree, do not use the Service.

---

## 1. Who This Policy Applies To

This Policy covers:

- **Account Users** — fundraisers, staff, and administrators who sign in to FRM.
- **Donors and Contacts** — individuals whose information our customers (account users) upload into FRM.
- **Visitors** — people who visit fundraising pages or websites our customers build with FRM, or who interact with FRM-powered communications.

If you are a donor or contact and want your information removed or corrected, please contact the FRM customer (the organization) that uploaded your information. We act on their behalf and will route requests to them. You may also contact us using the details in Section 13.

---

## 2. Information We Collect

### 2.1 Information You Provide

- **Account Information:** name, email, password (hashed), organization name, role, profile preferences.
- **Billing Information:** processed and stored by Stripe; we receive limited metadata (e.g., subscription status, last 4 digits of card, customer/subscription IDs).
- **Donor and Contact Data You Upload:** names, emails, phone numbers, addresses, donation history, pledges, tags, notes, relationships, custom fields, CSV imports, and attachments.
- **Communications Content:** emails drafted, sent, or received through the Service; SMS messages; notes; call talking points; reminders.
- **AI Prompts and Outputs:** content you submit to AI features and the resulting outputs.
- **Support Communications:** information you share with us when you request support or send feedback.

### 2.2 Information From Connected Integrations

When you connect a third-party account, we receive information from that provider based on the scopes you approve. Examples:

- **Gmail / Google:** With your OAuth consent, we access your Gmail account to send mail on your behalf, read messages, and subscribe to mailbox updates (Gmail history watches/push notifications) so we can sync messages relevant to your donors. We process message metadata (from, to, date, subject, thread/message IDs, labels, history IDs) and message bodies/attachments as needed to display, match, and organize emails inside FRM.
- **Stripe:** customer IDs, subscription state, payment intents, charge metadata, billing portal events.
- **Twilio:** outbound/inbound SMS message metadata and content.
- **Supabase:** authentication tokens, session metadata, and stored records (Supabase is our backend infrastructure provider).
- **Webhooks:** event payloads you configure to be sent to or from FRM.

### 2.3 Information Collected Automatically

- **Usage Data:** pages viewed, features used, clicks, timestamps, referring URLs.
- **Device & Log Data:** IP address, browser type, operating system, device identifiers, crash logs, performance metrics.
- **Cookies & Similar Technologies:** session cookies for authentication, preference cookies, and limited analytics. You can control cookies in your browser, but disabling them may break parts of the Service.

We do **not** sell personal information, and we do **not** use donor data to train third-party AI models for general-purpose use.

---

## 3. How We Use Information

We use information to:

- Provide, operate, maintain, and secure the Service.
- Authenticate users and protect against fraud and abuse.
- Process donations and subscription payments (via Stripe).
- Send emails and SMS on your behalf through your connected accounts.
- Sync, match, and display messages from Gmail to relevant donor records.
- Generate AI-assisted drafts, talking points, suggested tasks, and chat responses.
- Provide analytics, reporting, and dashboards to you.
- Communicate with you about your account, updates, and support.
- Comply with legal obligations and enforce our Terms.
- Improve and develop the Service (using aggregated or de-identified data wherever practical).

---

## 4. Legal Bases (EEA/UK Users)

Where the GDPR or UK GDPR applies, we rely on the following legal bases:

- **Contract** — to provide the Service you requested.
- **Legitimate Interests** — to secure the Service, prevent fraud, improve features, and operate our business.
- **Consent** — for optional features (e.g., certain integrations, marketing communications). You may withdraw consent at any time.
- **Legal Obligation** — to meet our compliance requirements.

For donor and contact data uploaded by our customers, **the customer is the data controller** and FRM is the **data processor**. Donors should direct rights requests to the relevant organization first.

---

## 5. How We Share Information

We share information only as described below. We do not sell personal information.

### 5.1 Service Providers / Sub-processors

We share information with vendors that help us operate the Service, under contracts that limit their use of the data. Current sub-processors include:

| Provider | Purpose |
| --- | --- |
| Supabase | Authentication, database, storage, edge functions |
| Stripe | Payments, subscriptions, billing portal |
| Google (Gmail / Google APIs) | Email send/read/sync per your OAuth scopes |
| Google Generative AI (Gemini) | AI features (drafting, chat, suggestions) |
| OpenAI or compatible LLM providers | AI features (where applicable) |
| Twilio | SMS messaging |
| Netlify | Web hosting / static asset delivery |
| Email/notification providers | Transactional email |
| Logging and error-monitoring tools | Diagnostics, uptime, performance |

We may update this list from time to time and will keep this section current.

### 5.2 Within Your Organization

Account users in your organization can access and edit shared donor data, notes, communications, and account configuration based on roles you assign.

### 5.3 Legal and Safety

We may share information to (a) comply with law or valid legal process, (b) enforce our Terms, (c) protect the rights, safety, or property of FRM, our users, or others, or (d) investigate fraud or security incidents.

### 5.4 Business Transfers

If FRM is involved in a merger, acquisition, financing, reorganization, or sale of assets, information may be transferred as part of that transaction, subject to standard confidentiality protections.

### 5.5 Aggregated / De-identified Data

We may share aggregated or de-identified information that cannot reasonably be used to identify you.

---

## 6. Google API Services User Data Policy

FRM's use and transfer to any other app of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the **Limited Use** requirements. Specifically:

- We use Gmail and Google account data **only** to provide and improve user-facing FRM features (sending mail on your behalf, syncing messages relevant to your donors, displaying email content within FRM, and supporting workflows you initiate).
- We **do not** use Gmail data for serving advertisements.
- We **do not** transfer Gmail data to third parties except as necessary to provide the Service, to comply with applicable law, or as part of a merger/acquisition with appropriate notice.
- We **do not** allow humans to read Gmail data unless (a) we have your explicit consent for a specific message, (b) it is necessary for security (e.g., investigating abuse), (c) it is necessary to comply with law, or (d) the data has been aggregated and de-identified for internal operations.
- Gmail data is **not** used to train generalized/non-personalized AI/ML models. AI features may pass message content to AI providers strictly to generate the user-facing output you requested, under contracts that prohibit the provider from using your content to train their models for other customers.

You can revoke FRM's Gmail access at any time at [https://myaccount.google.com/permissions](https://myaccount.google.com/permissions).

---

## 7. AI Features and Data Handling

When you use FRM's AI features, the prompt context (which may include donor data, your message, or selected records) is sent to a third-party AI provider so the model can generate the requested output. We choose providers with privacy terms that:

- Prohibit using your prompts/outputs to train their general models.
- Limit retention to what is necessary to deliver the response, with short or zero-retention windows where available.

You should still avoid pasting highly sensitive information (e.g., government IDs, payment card data, health data) into AI prompts.

---

## 8. Data Retention

- **Account Data:** retained while your account is active and for a reasonable period after closure.
- **Donor & Communication Data:** retained until you delete it or close your account. After account closure, we retain backups for up to **90 days** (or as required by law) before purging.
- **Billing Records:** retained for the period required by tax/accounting laws (typically 7 years).
- **Logs:** typically retained for up to **90 days**, longer where needed for security investigations.

You can export your data via the in-app CSV export tools at any time.

---

## 9. Security

We implement administrative, technical, and physical safeguards designed to protect your information, including:

- TLS encryption in transit.
- Encryption at rest for databases and storage (provided by Supabase / Stripe / Google as applicable).
- Role-based access controls, row-level security policies, and least-privilege principles.
- Secret management for API keys and OAuth tokens.
- Monitoring and logging for anomalous activity.

No system is 100% secure. If we become aware of a security incident affecting your information, we will notify you and applicable regulators as required by law.

---

## 10. International Data Transfers

FRM is operated from the **United States** (New York), and we use vendors located in the United States and other countries. If you access the Service from outside your country, your information may be transferred to, stored, and processed in countries with different data-protection laws. Where required, we use appropriate safeguards (e.g., Standard Contractual Clauses) for international transfers.

---

## 11. Your Rights

Depending on where you live, you may have the right to:

- **Access** the personal information we hold about you.
- **Correct** inaccurate information.
- **Delete** your information (subject to legal retention requirements).
- **Restrict** or **object** to certain processing.
- **Portability** — receive a copy in a machine-readable format.
- **Withdraw consent** where processing is based on consent.
- **Lodge a complaint** with your local data protection authority.
- **Opt out** of "sales" or "sharing" of personal information (California) — we do not sell or share for cross-context behavioral advertising.

To exercise rights regarding your **account**, contact us at the address in Section 13. To exercise rights regarding **donor data**, contact the organization that uploaded your information (they control that data); we will assist them as needed.

---

## 12. Children's Privacy

The Service is not directed to children under 13 (or 16 in the EEA/UK). We do not knowingly collect personal information from children. If you believe a child has provided information through the Service, contact us and we will delete it.

---

## 13. Changes to This Policy

We may update this Privacy Policy from time to time. When we make material changes, we will notify you (e.g., by email or in-app notice) and update the "Last Updated" date above.

---

## 14. Contact Us

**FRM — a product of Cubicle #6**
Email: **app.getfrm@gmail.com**
Address: **125 Lawrence Ave., Lawrence, NY 11559, USA**
Data Protection Contact: **app.getfrm@gmail.com**

If you are in the EEA/UK and we don't resolve your concern, you may contact your local supervisory authority.
