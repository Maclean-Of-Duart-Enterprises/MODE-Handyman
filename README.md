MODE Handyman

Native Android CRM, Contractor Management, and Business Operations Application

Version: 2.2.2
Version Code: 49
Platform: Android
Developer: Maclean Of Duart Enterprises Corp
License: GNU Affero General Public License v3.0 (AGPL-3.0-only)

Overview

MODE Handyman is a native Kotlin Android business-management application developed by Maclean Of Duart Enterprises Corp.

MODE stands for Maclean Of Duart Enterprises, while the name also references the Russian word "мода" (moda), meaning fashion or style.

Designed primarily for handymen, contractors, tradespeople, property maintenance professionals, and independent service providers, MODE Handyman is also suitable for other small businesses requiring customer relationship management, job organization, financial records, employee management, and business documentation.

The application combines customer management, job tracking, quotations, invoicing, payments, materials, suppliers, employees, subcontractors, payroll, timecards, scheduling, receipts, expenses, travel records, project calculations, signatures, and business reporting.

MODE Handyman emphasizes:

- Local data ownership and privacy.
- Offline-first business operations.
- Native Android performance.
- Support for multiple independent businesses.
- Professional document creation.
- Practical field-service management.
- Open-source software and independence from mandatory cloud subscriptions.

Main Features

1. Business Profiles and Settings

- Manage up to five independent business profiles.
- Maintain separate business records for each profile.
- Configure business names, addresses, phone numbers, email addresses, and other contact details.
- Upload business logos.
- Customize business branding, including colors, accents, and patterns.
- Upload custom background patterns.
- Choose business-specific document layouts.
- Select metric or US customary measurements.
- Configure business-specific financial and document preferences.
- Maintain separate customer follow-up settings.
- Switch businesses through the business-profile selector.
- Long-press the Home button to open the business-profile selector.
- Access local backup and restoration.
- Configure the floating calculator.
- View application version and licensing information.

Business-profile separation applies to customers, jobs, financial records, materials, employees, and other supported business data.

2. Customer and Contact Management

- Create, edit, search, and delete customers.
- Manage individual and business contacts.
- Store names, customer numbers, telephone numbers, and email addresses.
- Maintain business, billing, and service addresses.
- Attach customer photographs.
- Record customer notes and custom fields.
- Associate customers with jobs, quotes, invoices, and related records.
- Maintain additional contact names and information.
- Import and export contacts in JSON and CSV formats.
- Export individual contacts or complete contact collections.
- Select duplicate-handling policies: skip, update, or create separately.
- Transfer supported contact information between business profiles.
- Exclude selected customers from automatic follow-up draft creation.

Customer contact exports are separate from complete financial and business backups.

3. Jobs and Work Orders

- Create, edit, and manage jobs.
- Assign jobs to existing customers.
- Maintain editable alphanumeric job numbers.
- Record job descriptions, work details, and status.
- Associate jobs with quotes, invoices, expenses, and documentation.
- Maintain job-site addresses.
- Use saved job-site destinations for navigation and employee assignments.
- Track work activities and related appointments.
- Record completed and unfinished jobs.
- Mark jobs Finished or Completed.
- Generate customer follow-up drafts when qualifying jobs are finished.
- Maintain stable job references across related business records.

Job numbers are used when generating related quote and invoice identifiers.

4. Quotes and Estimates

- Create detailed customer quotations.
- Add itemized labor, materials, quantities, and additional charges.
- Select materials from the local catalog.
- Edit quantities, prices, and descriptions.
- Convert estimates into quotations.
- Calculate subtotals, taxes, discounts, and totals.
- Apply percentage-based or fixed-amount discounts.
- Customize discount labels and descriptions.
- Preserve saved prices independently of subsequent catalog changes.
- Associate quotations with jobs and customers.
- Capture customer signatures.
- Support quotation-linked contract approvals.
- Generate branded PDF quotations.
- Export quotations as JPG images.
- Share documents through Android's sharing system.
- Convert quotations into invoices while retaining applicable pricing, discounts, tax settings, and terms.

5. Invoices and Payments

- Create itemized invoices.
- Add labor, materials, and other billable charges.
- Generate invoices from existing quotations or job items.
- Maintain invoice numbers and associated job references.
- Edit invoice items, discounts, and tax information.
- Record partial and full payments.
- Track invoice totals, payments, and outstanding balances.
- Display paid balances appropriately.
- Maintain historical prices and payment information.
- Include customer signatures on supported invoice documents.
- Generate branded PDF invoices.
- Export invoices as JPG images.
- Share invoices through supported Android applications.
- Create customer follow-up drafts when invoices transition to paid status.

Invoice conversion preserves saved quotation adjustments rather than recalculating them from current material catalog prices.

6. Suppliers, Manufacturers, and Materials

Maintain supplier and manufacturer records containing:

- Business names and contact names.
- Telephone numbers.
- Email addresses.
- Physical addresses.
- Website links.
- Notes and additional supplier information.

The materials library supports:

- Material names and descriptions.
- Manufacturers and product identification.
- SKU and product numbers.
- Measurement units.
- Purchase prices and selling prices.
- Markup calculations.
- Supplier associations.
- Preferred suppliers.
- Supplier-specific product URLs.
- Material selection for job estimates, quotations, and invoices.

Selected catalog information is copied into editable document fields, preserving saved financial values when catalog prices subsequently change.

External product and supplier links open through supported Android browsers.

7. Employee and Subcontractor Management

Accessible through:

People and materials → Employee and Subcontractor

Manage employee and subcontractor profiles independently within the active business.

Features include:

- Employee and subcontractor contact records.
- Worker-specific payroll settings.
- Configurable pay rates and increments.
- Fixed-period pay configurations.
- Tax and deduction settings.
- Separate employer contribution records.
- Employee timecards.
- Manual time entry.
- Imported time records.
- Payroll calculations.
- Paystub management.
- Time and payroll reports.
- Employee-specific job assignments.
- Exportable employee setup files for the companion Time application.

Employee and subcontractor records are maintained within the relevant business profile.

8. Timecards and Work-Hour Tracking

- Create employee timecards.
- Record work dates and shifts.
- Enter clock-in and clock-out times.
- Enter worked hours directly.
- Record unpaid breaks.
- Apply supported premium pay multipliers.
- Associate worked hours with jobs.
- Import time records using UTF-8 CSV files.
- Edit individual time entries.
- Delete selected shifts.
- Delete entire pay-period timecards.
- Review worked hours by employee, job, and pay period.
- Export approved timecards.
- Export approved hours by individual job or across selected jobs.

Deleting entries from an approved timecard supersedes its previous paystub and returns the remaining time to draft for review.

Deleting an entire timecard preserves previously issued paystubs as separate historical documents.

Original imported CSV files are not deleted when associated timecard records are removed.

9. Payroll and Paystubs

MODE Handyman includes local payroll record management and paystub generation.

Features include:

- Pay-rate configuration.
- Fixed-period pay.
- Configurable pay increments.
- Tax and deduction entries.
- Employer contribution tracking.
- Premium multipliers.
- Calculated paystub previews.
- Paystub approval and rejection.
- Approved paystub snapshots.
- Superseded paystub revision history.
- Year-to-date payroll totals.
- Branded paystub PDF exports.
- JPG paystub exports.
- Timecard and payroll reports.

Approved paystubs are maintained as separate records, preserving issued documents even when underlying timecards are subsequently changed or deleted.

Payroll records are included in the application's supported backup and restoration processes.

Payroll calculations and tax settings require appropriate review by the business. The application should not be assumed to provide automated tax filing or regulatory compliance.

10. Time App Integration

MODE Handyman supports transferring employee, subcontractor, and job information to the companion Time Android timekeeping application.

Under an employee or subcontractor profile, select:

Employee setup / export for Time

The setup creator supports:

- Employee name and contact information.
- Employee pay rate.
- Pay basis and pay increment.
- Exact pay amount represented in cents.
- Selected job assignments.
- Job numbers and stable job identifiers.
- Job-site addresses.
- Optional latitude and longitude.
- Navigation destination information.
- Job-specific clock-in pay multipliers.
- Assigned job hours.
- Optional daily or weekly hour limits.
- Optional receiving-device admin PIN authorization.

Each employee's selected job settings can be saved independently.

The application can export:

- Employee setup JSON.
- Individual employee profile CSV.
- Selected jobs CSV.
- Individual job profile CSV.
- Approved timecard CSV.
- Approved hours reports.

Employee setup JSON is intended for importing into the Time application, where supported employee and job information can be created or updated.

Stable identifiers help prevent job duplication when existing jobs are renamed.

Hour limits in the documented Time 1.0.4 integration are informational and do not automatically stop timers or calculate overtime.

Admin PIN security: Version 2.2.2 allows the receiving Time device's current 6–12 digit admin PIN to be included in an employee setup JSON file. The receiving app verifies the PIN during import. Leading zeroes are preserved.

The PIN is not retained in MODE's employee settings, profile CSV exports, or backups of generated files. However, the exported JSON itself contains the readable PIN and must be handled securely.

11. Smart Project Tools

The integrated Smart Project Tools system provides additional field-service and construction functionality.

Smart Job Estimator

- Calculate labor and material costs.
- Enter hourly rates and estimated labor hours.
- Apply material pricing and markups.
- Estimate project totals.
- Reuse material catalog information.

Construction Calculators

- Concrete volume.
- Gravel quantities.
- Area calculations.
- Paint quantities.
- Drywall estimates.
- Related construction measurements.

Material Price Library

- Maintain reusable material records.
- Track purchase and selling prices.
- Associate products with suppliers.
- Reuse catalog entries in estimates and documents.

Project Expenses

- Record job-related material expenses.
- Track labor and equipment costs.
- Maintain additional job expenses.
- Associate expenses with projects.

Job Documentation

- Attach project photographs.
- Maintain handwritten signatures.
- Link documentation to jobs.
- Preserve supported attachments in local backups.

Contract Approvals

- Record customer approvals.
- Capture handwritten signatures.
- Associate approvals with quotations.
- Generate signed contract documents.

12. Floating Calculator

A compact calculator is available within the application.

- Movable floating calculator launcher.
- Small calculator window.
- Addition, subtraction, multiplication, and division.
- Decimal calculations and parentheses.
- Saved calculator expression.
- Persistent launcher position.
- Enable or disable through Settings.
- Access through Smart Project Tools.

The calculator operates within MODE Handyman without requiring Android's system-wide overlay permission.

13. Work Notes and Photographs

- Create, edit, and delete work notes.
- Associate notes with customer records.
- Insert multiple photographs.
- Display photographs inline with text.
- Preserve supported image placement.
- Store photographs locally.
- Include supported notes and attachments in application backups.

14. Receipts and Expenses

- Create receipt records.
- Edit and delete receipts.
- Attach receipt photographs.
- View locally stored receipt images.
- Record receipt amounts.
- Maintain tax information.
- Associate expenses with business operations.
- Use recorded expenses in supported financial reporting.

15. Trips, Mileage, and Navigation

- Record business travel.
- Maintain trip records.
- Track travel distances.
- Display miles or kilometers according to business preferences.
- Store distances internally using a consistent metric representation.
- Use requested online routing and address geocoding.
- Maintain job-site destinations for supported navigation workflows.
- Export job-site destination information to the companion Time app.

Internet connectivity is required for online routing and geocoding operations.

16. Scheduling, Tasks, and Reminders

- Maintain scheduled appointments.
- Associate appointments with jobs.
- Record appointment dates and times.
- Maintain task lists.
- Configure task priorities and due dates.
- Support recurring schedule entries.
- Configure supported reminder intervals.
- Manage upcoming activities.
- Use local Android notifications.
- Restore supported reminder scheduling after device restart or application replacement.

Supported recurrence options include weekly, biweekly, monthly, quarterly, semiannual, and annual schedules.

17. Coupons and Promotional Offers

Create and manage coupons within each business profile.

- Create custom coupon codes.
- Maintain unique coupon identifiers.
- Configure promotional offers.
- Add expiration dates.
- Enter terms and conditions.
- Edit existing coupons.
- Mark coupons as used.
- Reactivate supported coupons.
- Associate coupons with individual customers.
- Create general coupons without customer assignment.
- Export coupons as branded PDFs.
- Export coupons as JPG images.
- Share coupons using Android applications.

Used coupons remain in the application for recordkeeping rather than being automatically deleted.

18. Business Branding and Documents

MODE Handyman supports customizable branding for business profiles and generated documents.

Branding options include:

- Business logos.
- Primary and accent colors.
- Color customization controls.
- Built-in background patterns.
- Uploaded custom patterns.
- Business-specific interface styling.
- Document header styling.
- Branded document exports.

Quotation and invoice PDF layouts include:

White Background: A white document with configured branding.

Full Background: A white document with a faint branded background pattern.

Header Only: A branded header with a white document body.

Document exports support appropriate business identification, dates, itemized financial information, and multiple-page layouts.

Supported document types include:

- Quotes.
- Invoices.
- Coupons.
- Paystubs.
- Timecards.
- Financial reports.
- Signed contracts.

PDF generation occurs locally using Android's native document facilities.

Supported documents can also be exported as JPG images.

19. Customer Follow-Up Messages

MODE Handyman supports customer follow-up drafts for completed jobs and paid invoices.

Configure through:

Settings → Customer follow-up messages

Features include:

- Trigger drafts when invoices are paid.
- Trigger drafts when jobs are finished.
- Configure either or both event types.
- Customize follow-up message templates.
- Include Facebook page links.
- Include Google Maps review links.
- Use customer, business, job, invoice, and event placeholders.
- Maintain settings independently for each business.
- Exclude individual customers.
- Prevent unwanted duplicate follow-ups.
- Maintain local message history.

The dashboard provides access to saved follow-up messages.

Users can review and edit messages before sharing them through:

- SMS or messaging applications.
- Email.
- Google Voice, where supported.
- Other compatible Android applications.
- Copy-to-clipboard functionality.

MODE Handyman does not automatically send these messages. The user completes transmission through the selected application.

Opening a message in another application does not establish successful delivery.

20. Reports and Financial Records

Generate reports covering supported business activities.

- Revenue.
- Expenses.
- Outstanding receivables.
- Customer invoices and payments.
- Employee timecards.
- Approved worked hours.
- Payroll and paystub records.
- Year-to-date payroll totals.

Employee reporting supports:

- Weekly periods.
- Biweekly periods.
- Custom date ranges.
- Full-year views.
- Job filtering.
- Status filtering.
- Newest-first and oldest-first sorting.

Supported reports can be exported or shared as PDF, JPG, or CSV according to report type.

21. Backup, Restore, and Data Protection

MODE Handyman provides local backup and restoration functionality.

Supported backups cover:

- Main business database.
- Smart Project Tools database.
- Business profiles.
- Customers and contacts.
- Jobs and financial records.
- Employee and payroll records.
- Application preferences.
- Supported private documents.
- Photographs and attachments.
- Generated documents included in the backup process.

The backup system includes database checkpointing, validation, and recovery procedures.

Database upgrades use transactional migrations and pre-migration recovery copies.

Restoration includes safeguards intended to reduce the risk of losing existing data.

Users should maintain independent copies of important backups.

Privacy and Offline Operation

MODE Handyman is designed around local data ownership and offline-first operation.

The inspected source uses:

- Native SQLite databases.
- Local application storage.
- Android's Storage Access Framework.
- Android share intents.
- Local PDF generation.
- Locally stored crash reports.

The project does not include:

- Firebase.
- Sentry.
- Advertising integrations.
- Analytics integrations.
- Mandatory Google Play Services.
- Mandatory cloud synchronization.
- Built-in SMTP email sending.

Internet access is declared for requested network operations, including routing and geocoding.

The application also declares notification and boot-completion permissions for supported reminder functionality.

External applications selected for document sharing or customer messages are responsible for their own transmission and privacy practices.

Local crash reporting retains a limited number of redacted reports without an automatic upload endpoint.

Technical Information

Property| Value
Application| MODE Handyman
Version| 2.2.2
Version code| 49
Android package| com.macleanofduartenterprises.modehandyman
Programming language| Kotlin
User interface| Native Android Views / XML
Minimum Android| Android 11 (API 30)
Target Android API| 36
Compile SDK| 36
Java / JDK| 17
Gradle| 8.13
Android Build Tools| 35.0.0
Main database| SQLite
Main database schema| 238
Smart Tools database| SQLite, schema 4
PDF generation| Android PdfDocument
File import/export| Android Storage Access Framework
Architecture| Offline-first, native Android
License| AGPL-3.0-only
Development environment| Android Studio / Gradle

Source Architecture

The source project includes these major components:

- MainActivity.kt — Main navigation and business-management interface.
- SmartToolsActivity.kt — Estimator, construction calculators, materials, suppliers, documentation, and approvals.
- ModeRepository.kt — Business record operations and related data management.
- DatabaseManager.kt — Main SQLite database initialization, migrations, and integrity checks.
- SmartToolsStore.kt — Smart Project Tools database operations.
- SmartToolsLogic.kt — Project reconciliation and estimate calculations.
- BusinessProfiles.kt — Multi-business-profile management.
- CustomerTransfer.kt — Customer contact import/export.
- PdfGenerator.kt — Local document generation.
- BackupManager.kt — Backup, validation, and restoration.
- FloatingCalculator.kt — In-app calculator.
- LocalCrashReporter.kt — Local diagnostic reporting.

Additional source components implement employee management, timecards, payroll, paystub history, CSV transfers, employee setup exports, customer follow-up drafts, coupons, and business branding.

What's New in Version 2.2.2

Version 2.2.2 extends the employee setup export system introduced in earlier 2.2.x releases.

Employee Pay-Rate Export

Employee setup JSON now includes:

- Current employee pay rate.
- Exact pay amount in cents.
- Pay basis.
- Pay increment.

This allows compatible versions of the Time application to display the worker's pay-rate information after importing the employee setup.

Optional Admin PIN Authorization

The employee setup creator includes:

Time admin PIN for this JSON

The administrator can enter the receiving Time device's existing 6–12 digit admin PIN before exporting.

When the JSON is imported, Time verifies the included PIN during the Apply operation.

- Leading zeroes are preserved.
- Leaving the field empty uses the normal Time import authorization process.
- The PIN is not saved in MODE's employee settings.
- The PIN is excluded from profile CSV exports.
- The PIN is excluded from MODE's backup of generated files.

Because the exported JSON contains the readable PIN, it must be protected against unauthorized access.

Features Added in Version 2.2.1

- Delete selected timecard entries.
- Delete entire pay-period timecards.
- Preserve issued paystubs when timecards are deleted.
- Maintain superseded paystub revisions.
- Export employee setup JSON for Time.
- Configure selected employee job assignments.
- Include job-site routing addresses or coordinates.
- Configure job-specific pay multipliers.
- Configure assigned job hours.
- Include optional daily and weekly hour limits.
- Export employee profile CSV files.
- Export selected job CSV files.
- Export individual job profile CSV files.
- Export approved worked hours by employee or job.

Features Added in Version 2.2.0

- Employee and Subcontractor management.
- Employee contact and payroll profiles.
- Pay rates, increments, taxes, and deductions.
- Manual and imported timecards.
- Editable work-hour records.
- Payroll calculation previews.
- Approved paystub snapshots.
- Paystub revision history.
- PDF/JPG paystub exports.
- Payroll and timecard reporting.
- Approved hours CSV exports.
- Companion timekeeping application integration.

Building the Application

The source project specifies:

- JDK 17.
- Android SDK Platform 36.
- Android Build Tools 35.0.0.
- Gradle 8.13.

Release signing requires the developer's signing keystore and credentials.

The source uses these environment variables:

- "MODE_KEYSTORE"
- "MODE_KEY_ALIAS"
- "MODE_STORE_PASSWORD"
- "MODE_KEY_PASSWORD"

Build and verification commands:

./gradlew testReleaseUnitTest lintRelease assembleRelease

python3 tools/verify_database.py
python3 tools/verify_followup.py
python3 tools/verify_payroll.py

The release APK output is:

"app/build/outputs/apk/release/app-release.apk"

Private signing keys and credentials should not be committed to public repositories.

Testing and Verification

The attached version 2.2.2 source archive and signed APK were inspected for this documentation update.

The source confirms the current version metadata, build configuration, permissions, architecture, and documented changes.

This README review does not constitute a complete physical-device regression test.

Production verification should include:

- Employee setup JSON import into Time.
- Pay-rate transfer.
- Admin PIN authorization.
- Timecard editing and deletion.
- Paystub preservation.
- CSV import/export.
- Business-profile separation.
- Document generation.
- Backup and restoration.
- Database migrations.
- Navigation and reminders.
- Customer follow-up drafts.

License and Source Code

MODE Handyman is licensed under the GNU Affero General Public License version 3.0 (AGPL-3.0-only).

License information:

https://www.gnu.org/licenses/agpl-3.0.html

Source code and releases:

https://github.com/Maclean-Of-Duart-Enterprises/MODE-Handyman/releases

Company website:

https://macleanofduartenterprises.com

Project Identity

MODE Handyman
Developed by Maclean Of Duart Enterprises Corp

A native, offline-first Android business-management application designed to help contractors, tradespeople, and small businesses organize customers, jobs, employees, finances, materials, schedules, and documentation without depending on proprietary cloud services.

Version: 2.2.2
Platform: Android
Development: Native Kotlin
Data Architecture: Local-first, multi-business-profile management
License: AGPL-3.0-only
