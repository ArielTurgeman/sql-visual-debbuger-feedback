# SQL Visual Debugger
## Privacy Policy

**Version:** 1.0  
**Effective Date:** August 25, 2026

This Privacy Policy explains how SQL Visual Debugger processes information when you install or use the SQL Visual Debugger extension for Visual Studio Code.

This Policy applies to SQL Visual Debugger itself. Third-party services, including Lemon Squeezy, Microsoft/Visual Studio Marketplace, GitHub, database providers, and other services you choose to use are governed by their own privacy policies.

## 1. Optional Limited Usage Telemetry

When telemetry is enabled, SQL Visual Debugger may collect limited usage telemetry to help understand how the extension is used and to improve the product.

SQL Visual Debugger uses **PostHog** as a third-party analytics provider to receive and analyze these limited usage events.

The telemetry is designed to collect high-level product-usage information rather than the contents of a user's SQL queries, databases, files, or credentials.

Telemetry may include information such as:

- use of particular extension features or commands;
- clicks or interactions with product functionality;
- high-level SQL construct or debugging categories used within the extension;
- the installed SQL Visual Debugger extension version; and
- similar high-level usage events used to understand feature adoption and improve the product.

SQL Visual Debugger does **not intentionally include** the following in usage telemetry sent for product analytics:

- SQL query text;
- database contents or query results;
- table names;
- column names;
- database names;
- database passwords or other database credentials;
- database hostnames;
- user-defined SQL object names;
- file contents; or
- file paths.

PostHog may independently process technical information associated with telemetry requests, such as an IP address or device/network information, in accordance with PostHog's own service operation and privacy practices.

Telemetry is not used by SQL Visual Debugger to sell personal information, build advertising profiles, or track the contents of a user's database activity.

**PostHog Privacy Policy:**  
https://posthog.com/privacy

### Telemetry Controls

Users may disable SQL Visual Debugger telemetry at any time by running:

`SQL Visual Debugger: Disable Telemetry`

When telemetry is disabled, SQL Visual Debugger does not intentionally send optional product-usage events to PostHog.

Disabling optional usage telemetry does not disable communications that are technically necessary for separate functions requested or used by the user, such as Premium license activation or validation, or an update check through GitHub Pages.

## 2. SQL Queries, Files, and Database Data

SQL Visual Debugger is designed around a direct/local debugging architecture.

For local data sources such as Excel, CSV, and SQLite, the relevant file or database data is read and processed locally on the user's device.

For remote databases, the connection is made directly from the user's device / Visual Studio Code environment to the database server or provider selected by the user.

To provide debugging functionality, SQL Visual Debugger may process within the extension, or directly with the user-selected database environment:

- SQL query text;
- schema information;
- table and column information;
- query results and intermediate results;
- database connection information; and
- information required to generate debugging steps, previews, filters, or explanations.

SQL Visual Debugger does not route SQL query text, schema information, table or column information, query results, database contents, or database credentials through servers or cloud infrastructure operated by Ariel Turgeman as part of the debugging process.

SQL Visual Debugger does not intentionally transmit SQL query text, database contents, query results, table names, column names, or database credentials to Ariel Turgeman for analytics or tracking purposes.

When the user connects to a remote database, information necessary to execute the requested query or read-only helper queries is necessarily transmitted directly between the user's device and the database server or provider selected by the user.

The privacy and security practices of that database server or provider are governed by the provider or operator of that database environment.

## 3. Database Credentials

SQL Visual Debugger may require database credentials when connecting to supported databases.

SQL Visual Debugger does **not save database passwords**.

Passwords are kept only in session memory for the period reasonably necessary to establish and use the requested database connection.

Users remain responsible for the security of the credentials and database accounts they choose to use with the Software.

For sensitive or production environments, using a database account restricted to appropriate read-only permissions is strongly recommended.

## 4. Read-Only Database Operation

SQL Visual Debugger is designed for read-only debugging.

The Software may execute supported read-only queries and additional read-only helper queries where needed to generate previews, intermediate results, or debugging explanations.

Remote database operations may create network traffic and database resource usage beyond execution of the original query alone.

## 5. Premium License Activation and Validation

If you purchase or use a Premium license, SQL Visual Debugger communicates with the licensing service used to activate and validate that license.

Information transmitted for this purpose may include:

- the Premium license key;
- license activation or validation information;
- activation status; and
- limited technical instance information required by the licensing system to manage permitted device activations.

This information is processed only as reasonably necessary to activate, validate, protect, administer, and enforce the permitted use of the Premium license.

Premium purchases and licensing infrastructure may be provided through Lemon Squeezy.

Information processed directly by Lemon Squeezy is governed by Lemon Squeezy's own privacy practices:

**Lemon Squeezy Privacy Policy:**  
https://www.lemonsqueezy.com/privacy

## 6. Purchase, Order, and Terms-Acceptance Information

SQL Visual Debugger does not directly process or store payment card information.

Premium purchases are processed through Lemon Squeezy as Merchant of Record.

During checkout, Lemon Squeezy may collect information such as a purchaser's name, email address, billing information, payment information, tax information, and transaction details in accordance with its own policies.

When a user proceeds to Premium checkout through SQL Visual Debugger, the checkout may also include limited metadata recording that the user completed the required End User License Agreement & Terms of Use acceptance step before checkout. This may include:

- a value indicating that the End User License Agreement & Terms of Use were accepted; and
- the version of those Terms presented at that time.

For example, the checkout may contain metadata equivalent to `terms_accepted=true` and `terms_version=1.3`.

This metadata is used only to document the applicable purchase and licensing flow. SQL Visual Debugger does not intentionally add IP addresses, device fingerprints, precise location, or unrelated personal information to the checkout for the purpose of recording Terms acceptance.

For license administration, customer support, fraud prevention, documenting the purchase flow, or resolving a purchase-related issue, Ariel Turgeman may have access through Lemon Squeezy to limited order or licensing information associated with a purchase, such as customer name, email address, order details, license details, transaction status, and the limited Terms-acceptance metadata described above.

Such information will be used only for legitimate product, licensing, support, security, fraud-prevention, transaction-record, or legal purposes.

## 7. Support Communications

If you contact SQL Visual Debugger support through email, GitHub, the Visual Studio Marketplace, or another support channel, information you voluntarily provide may be received and processed.

This may include:

- your name or username;
- email address;
- the content of your request;
- screenshots;
- logs or diagnostic information you choose to provide; and
- other information included in your communication.

Please do not include database passwords, confidential database contents, private license keys, or other sensitive information in public support requests.

Information submitted through third-party support platforms is also subject to those platforms' privacy policies.

## 8. Information We Do Not Intentionally Collect Through the Extension

Except for the limited usage telemetry described in Section 1, information technically necessary for license activation or validation, and information that you voluntarily provide for support, SQL Visual Debugger is not designed to collect or transmit to Ariel Turgeman:

- SQL query contents;
- database contents or query results;
- table names;
- column names;
- database names;
- database credentials or passwords;
- database hostnames;
- user-defined SQL object names;
- file contents;
- file paths; or
- precise location information.

SQL Visual Debugger does not sell personal information, SQL query data, database contents, database credentials, or usage telemetry.

## 9. Purposes of Processing

Where SQL Visual Debugger processes or accesses information, it is used only as reasonably necessary for purposes such as:

- understanding high-level feature usage and improving the extension;
- identifying broad product-usage patterns and prioritizing product development;
- providing and validating Premium licenses;
- administering device activations;
- fulfilling or supporting a purchase;
- documenting the Terms version associated with the purchase flow;
- responding to support requests;
- protecting the Software and licensing system against fraud or abuse;
- complying with legal obligations; and
- establishing, exercising, or defending legal claims where necessary.

## 10. Legal Bases Where Applicable

Where the GDPR, UK GDPR, or similar law applies and a legal basis is required, processing may be based on one or more of the following, depending on the circumstances:

- performance of a contract or steps requested in connection with a contract, including providing licensed Premium functionality;
- legitimate interests in operating, improving, securing, supporting, and protecting the Software and its licensing system, where those interests are not overridden by applicable rights;
- consent or user choice where required by applicable law;
- compliance with a legal obligation; or
- another legal basis available under applicable law.

Users can disable optional SQL Visual Debugger usage telemetry as described in Section 1.

Lemon Squeezy and other independent third parties determine their own legal bases for information they process as part of their services.

## 11. Data Retention

SQL Visual Debugger seeks to retain information under its control only for as long as reasonably necessary for the purpose for which it was received.

Limited usage telemetry may be retained for a reasonable period for product analysis, improvement, troubleshooting, security, and development planning, subject to the practices of the telemetry infrastructure used.

Because order and licensing information may be maintained through Lemon Squeezy, retention of information within Lemon Squeezy is also subject to Lemon Squeezy's policies and legal obligations.

Purchase and Terms-acceptance records may be retained for as long as reasonably necessary for licensing administration, transaction records, dispute resolution, fraud prevention, enforcement of agreements, and legal obligations.

Support communications may be retained for as long as reasonably necessary to resolve the request, maintain support history, prevent abuse, or comply with legal requirements.

## 12. Third-Party Services

Depending on how you use SQL Visual Debugger, third-party services may be involved in providing certain functionality.

These may include:

- **Lemon Squeezy** for Premium purchases, license activation, and license validation;
- **PostHog** for the optional limited usage telemetry described in Section 1 when telemetry is enabled;
- **GitHub / GitHub Pages** for hosting Terms and privacy notices, feedback or issue reporting, and update checks;
- **Microsoft and Visual Studio Marketplace** for distribution of the extension and Visual Studio Code platform functionality;
- the database server, cloud database provider, or infrastructure selected by the user; and
- technical libraries, drivers, or infrastructure necessary to operate the Software.

The update check to GitHub Pages is separate from SQL debugging and does not intentionally include SQL query text, schema information, table names, column names, query results, database contents, database credentials, or file contents.

As with ordinary network requests, GitHub may receive technical connection information associated with a request to its services in accordance with GitHub's own privacy practices.

**PostHog Privacy Policy:**  
https://posthog.com/privacy

**GitHub Privacy Statement:**  
https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement

Those services are governed by their own terms and privacy policies.

Their independent collection and processing practices are outside the scope of this Privacy Policy.

## 13. International Processing

Third-party services used in connection with SQL Visual Debugger may process information in countries other than the country in which a user resides.

Where a third party processes information, its applicable privacy policy, contractual commitments, and legal obligations govern that processing.

## 14. Security

Reasonable technical and organizational measures appropriate to the nature of the Software are used to reduce the risk of unauthorized access, disclosure, alteration, or misuse of information under our control.

However, no software, device, network, database connection, or electronic transmission can be guaranteed to be completely secure.

Users are responsible for securing their own devices, Visual Studio Code environment, database accounts, credentials, networks, and systems.

## 15. User Rights and Requests

Depending on applicable law and the information involved, users may have rights relating to personal information, which may include rights to request access, correction, deletion, restriction, portability, objection, or information about processing.

Requests concerning information under the control of SQL Visual Debugger may be sent to the contact address below.

Where applicable, users may also withdraw consent or disable optional usage telemetry through the controls described in Section 1. Disabling telemetry does not affect the lawfulness of processing that occurred before the setting was changed where applicable law provides otherwise.

For information collected directly by Lemon Squeezy, Microsoft, GitHub, a database provider, telemetry provider, or another independent third party, requests may need to be directed to that provider in accordance with its privacy policy.

## 16. Children's Privacy

SQL Visual Debugger is a developer tool and is not directed specifically at children.

We do not knowingly design the Software to collect personal information from children.

## 17. Changes to This Privacy Policy

This Privacy Policy may be updated from time to time to reflect changes to SQL Visual Debugger, telemetry practices, licensing infrastructure, third-party services, legal requirements, or privacy practices.

The current version and its effective date will be made publicly available.

Where reasonably appropriate, material changes may be communicated through the Software, Marketplace listing, repository, or another reasonable channel.

## 18. Contact and Responsible Party

For the personal information processed directly in connection with SQL Visual Debugger, the responsible party is:

**Ariel Turgeman**  
**Country:** Israel  
**Privacy / support email:** arielturgi@gmail.com

Questions or requests concerning this Privacy Policy or personal information under our control may be sent to the email address above.

SQL Visual Debugger Marketplace listing:  
https://marketplace.visualstudio.com/items?itemName=arieldev.sql-visual-debugger

## 19. Related Documents

**SQL Visual Debugger End User License Agreement & Terms of Use**  
https://github.com/ArielTurgeman/sql-visual-debbuger-feedback/blob/main/TERMS.md

**Lemon Squeezy Privacy Policy**  
https://www.lemonsqueezy.com/privacy

**Lemon Squeezy Buyer Terms**  
https://www.lemonsqueezy.com/buyer-terms

**PostHog Privacy Policy**  
https://posthog.com/privacy

**GitHub Privacy Statement**  
https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement
