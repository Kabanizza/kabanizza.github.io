Privacy Policy

Last updated: 16 November 2026

This Privacy Policy explains how Instagram Bot ("the Service", "we", "us") processes personal data when a restaurant or other business ("Client") connects an Instagram professional account and uses the Service to answer Instagram Direct messages.

Data controller: Raman, Grunwaldzka 119, Poland
Contact: romanvodyanitskiy2003@gmail.com
Service address: https://restaurant-soft-a1.onrender.com

1. Who is responsible for the data
For the Client's account, connection and knowledge-base data, the operator of the Service is the data controller.
For messages sent by guests to a Client's Instagram account, the Client is normally the data controller, and we process those messages on the Client's behalf as a data processor.
Meta Platforms (Instagram) processes data under its own terms and privacy policy when a person uses Instagram or authorises an app.
2. What data we process

Client account data

restaurant/business name, city, phone number and booking or website URL;
the Client's Instagram professional account ID, username, account type and granted permissions;
OAuth access tokens and token expiry data. Tokens are stored encrypted at rest;
connection status, token refresh timestamps and portal-link metadata;
the Client's knowledge base: menu, opening hours, policies, parking, pet policy and other information the Client chooses to provide;
names and email addresses of staff who contact us for support, if provided.

Instagram messages

message text, attachments and interaction metadata needed to generate and send a reply;
the Instagram-scoped sender ID and the account ID needed to route the conversation;
short-lived conversation context used to keep replies consistent.

By default, production message text is not stored in our application database. It is processed in memory and kept only for a short period (normally up to 24 hours) for conversation context, then removed or lost when the process restarts. Message text is not written to application logs when LOG_MESSAGES=0 (the default).

Technical data

IP address, request timestamps, user agent, webhook delivery metadata and error information;
security events such as failed admin logins and OAuth errors.

Cookies

portal_session — a signed, HttpOnly cookie used to keep a Client signed in to its portal; up to 7 days;
admin_session — a signed, HttpOnly cookie used for the internal admin panel; up to 12 hours;
admin_flash — a short-lived signed cookie used to show a one-time message or portal link after an action.

We do not use advertising, analytics or cross-site tracking cookies on this Service.

3. Why we process data and legal bases

We process data to:

create and maintain the Client's account and Instagram connection;
receive and answer Instagram Direct messages on the Client's behalf;
store and apply the Client's knowledge base;
provide support, security, fraud prevention and troubleshooting;
comply with legal obligations and enforce our terms.

Legal bases under the GDPR, where applicable:

performance of a contract or steps requested before entering a contract (providing the Service);
legitimate interests (security, preventing abuse, improving the Service, limited technical logs);
consent, where required (for example, optional communications or a specific integration);
legal obligation.

Where we process guest messages on behalf of a Client, the Client is responsible for its own legal basis and privacy notice.

4. Who we share data with

We share data only as needed to run the Service:

Meta Platforms / Instagram — to authenticate the Instagram account, subscribe to messaging webhooks, send replies and show the Client's connection status;
Render — cloud hosting for the application;
Supabase — managed PostgreSQL database hosting, when the Client's deployment uses Supabase;
Google (Gemini) and DeepSeek — AI language-model providers used to generate replies; message content and relevant context may be sent to these providers for processing;
professional advisers, authorities or courts where required by law;
a successor entity in a merger, acquisition or transfer of the Service, subject to appropriate safeguards.

We do not sell personal data. We do not share data for advertising.

5. International transfers

Some providers are located outside the European Economic Area, including the United States. Where required, we rely on appropriate safeguards such as the European Commission's Standard Contractual Clauses and provider data-processing terms.

6. How long we keep data
Client account, knowledge base and Instagram connection data: until the Client disconnects the account or asks us to delete the account, plus a short period needed to complete deletion and backups.
Encrypted access tokens: until disconnection, deletion, expiry or revocation. Disconnecting removes the stored token from our database.
Portal links: normally 7 days. OAuth states: normally 10 minutes.
In-memory conversation context: normally up to 24 hours and lost on process restart.
Application logs: limited technical data, kept only as long as needed for security and troubleshooting. Message text is disabled by default.
Legal records: for as long as required by applicable law.

When data is no longer needed, we delete it or anonymise it.

7. Security

We use HTTPS, encrypted storage for Instagram tokens (Fernet), signed HttpOnly session cookies, access controls for the admin panel, short-lived OAuth states and request-size limits. No system is completely secure, but we take reasonable technical and organisational measures to protect data.

8. Your rights

Depending on your location, you may have the right to:

access your personal data;
correct inaccurate data;
delete your data;
restrict or object to processing;
receive your data in a portable format;
withdraw consent at any time, without affecting processing that already took place;
complain to a supervisory authority.

In Poland, the supervisory authority is the President of the Personal Data Protection Office (UODO), ul. Stawki 2, 00-193 Warsaw, Poland.

To exercise your rights, contact us at romanvodyanitskiy2003@gmail.com. We may ask for information needed to verify your identity and the relevant Client account.

9. Guest messages and Instagram

If you are an Instagram user messaging a restaurant, the restaurant is normally responsible for the conversation. You can also:

delete the conversation in Instagram;
remove the app's access in Instagram: Settings → Website permissions → Apps and websites;
contact us at romanvodyanitskiy2003@gmail.com and we will forward your request to the relevant Client or delete data we control.

Meta independently stores Instagram messages under its own policies; we cannot delete Meta's copy.

10. Children

The Service is intended for businesses and is not directed to children. We do not knowingly collect data from children below the minimum age required by Instagram or applicable law. If you believe a child's data was provided, contact us and we will delete it.

11. Changes

We may update this Privacy Policy from time to time. The date at the top shows the latest version. Material changes will be communicated to Clients where required.

12. Contact and data deletion

For privacy questions or deletion requests, see Data Deletion Instructions or contact romanvodyanitskiy2003@gmail.com.
