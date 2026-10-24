# MODE-Handyman
CRM app for handymen and contractors. MODE is Maclean Of Duart Enterprises , and mode as in Russian for stylish. Manage clients, create quotes and invoices, materials and suppliers, take notes, material calculator for volume etc, receipts, trip records, client signatures and more. 
MODE Handyman

Version 2.0.7 — Native Android Business Management

A division of Maclean Of Duart Enterprises Corp

Overview

MODE Handyman is a native Kotlin Android application designed for handyman contractors, independent tradespeople, property maintenance professionals, and small service businesses.

The application provides an integrated, offline-first system for managing customers, projects, quotations, invoices, payments, suppliers, materials, expenses, schedules, and business records.

MODE Handyman emphasizes local data ownership, privacy, practical field operations, and independence from proprietary cloud services.

Main Features

1. Business Profiles and Settings

- Support for up to five independent business profiles.
- Separate customers, jobs, materials, and financial records for each profile.
- Custom business names, contact information, addresses, and branding.
- Business logo upload for branded documents.
- Imperial/US customary and metric measurement preferences.
- Local backup and restoration.
- Configurable floating calculator.
- Business-specific document and financial settings.

2. Customer and Contact Management

- Create, edit, search, and manage customer records.
- Store individual and business contact information.
- Record phone numbers, email addresses, billing addresses, and service addresses.
- Maintain customer notes, custom contact information, and photographs.
- Associate customers with jobs, quotations, and related records.
- Copy customer contact information between business profiles.
- Import and export customer contact records using JSON or CSV.
- Support duplicate-handling policies during import.
- Preserve business-profile separation and exclude financial records from contact transfers.

3. Jobs and Work Orders

- Create and manage customer jobs.
- Record project descriptions and work details.
- Associate jobs with existing customers.
- Track job activities and appointments.
- Manage related quotations, expenses, and documentation.
- Maintain stable job references for related project tools.

4. Quotes and Estimates

- Create customer quotations with itemized charges.
- Calculate labor, materials, quantities, unit prices, and totals.
- Select materials from the existing catalog.
- Convert estimates into quotations.
- Retain recorded prices independently of later catalog changes.
- Generate branded PDF quotations.
- Share exported documents through Android's share menu.
- Support quotation-linked contract approval workflows.

5. Invoices and Payments

- Generate itemized customer invoices.
- Add labor, materials, and other billable items.
- Record customer payments.
- Support partial and full payment tracking.
- Display invoice total, amount paid, and outstanding balance separately.
- Maintain historical pricing information.
- Export and share invoice PDFs.
- Edit, copy, and manage invoice records.

6. Suppliers, Manufacturers, and Materials

Maintain locally stored supplier and manufacturer information, including:

- Business and contact names.
- Telephone numbers and email addresses.
- Physical addresses.
- Website links.
- Notes and supplier information.

The materials catalog supports:

- Material descriptions and product identification.
- Manufacturers and SKU/product numbers.
- Measurement units.
- Purchase and selling prices.
- Markup calculations.
- Supplier associations.
- Preferred suppliers.
- Supplier-specific product URLs.
- Material selection for project estimates and invoice lines.

Product and supplier website links can be opened in an external Android browser. Catalog information remains locally accessible without an internet connection.

7. Smart Project Tools

The application includes a dedicated Smart Project Tools section containing:

Smart Job Estimator: Calculate project pricing from material costs, labor hours, hourly rates, and markup.

Construction Calculators: Perform calculations for concrete, gravel, area, paint, and drywall quantities.

Material Price Library: Maintain reusable material prices, suppliers, and product information.

Project Expenses: Record costs associated with jobs, including materials, labor, equipment, mileage, and other expenses.

Job Documentation: Associate photographs and handwritten signatures with verified job records.

Contract Approvals: Record customer consent and handwritten signatures, link approvals to quotations, and generate signed contract documents.

8. Floating Calculator

MODE Handyman includes a compact calculator accessible throughout the application.

- Movable floating calculator button.
- Default positioning near the bottom-right of the screen.
- Small calculator window rather than a full-screen interface.
- Addition, subtraction, multiplication, division, decimals, and parentheses.
- Close the calculator without losing the current expression.
- Save calculator state and floating-button position.
- Enable or disable the floating widget in Settings.
- Access the calculator separately through Smart Project Tools.

The calculator operates inside the application without requiring Android's system-wide overlay permission.

9. Work Notes and Photographs

- Create, edit, and delete work notes.
- Associate notes with customer contacts.
- Insert multiple photographs into notes.
- Display photographs inline with surrounding text.
- Preserve photograph references and placement when notes are saved.
- Store photographs locally.
- Include supported note data and images in application backups.

10. Receipts and Expenses

- Record business receipts and expenses.
- Edit and delete receipt records.
- Attach photographs of receipts.
- View and manage stored receipt photographs.
- Record receipt totals and taxes.
- Preserve tax information when editing receipts.
- Associate expenses with business operations and financial reporting.

11. Trips and Mileage

- Record business travel.
- Track travel distances.
- Display distances according to the selected measurement system.
- Support miles for US customary measurements and kilometers for metric measurements.
- Store distance values internally in a consistent measurement format.

12. Scheduling and Tasks

- Schedule appointments associated with jobs.
- Record appointment start and end times.
- Maintain task lists.
- Add task descriptions, due dates, and priorities.
- Configure supported local task reminders.
- Review upcoming work and scheduled activities.

13. Reports and PDF Documents

Generate and export business documents, including:

- Customer quotations.
- Invoices.
- Financial reports.
- Signed contracts.

Supported PDF features include business identification, optional business logos, itemized financial information, and local document sharing.

Financial reporting covers business revenue, expenses, and receivables.

14. Backup, Restore, and Data Protection

MODE Handyman provides local backup and restoration capabilities covering its business databases and supported private application documents.

The source includes backup validation and recovery procedures designed to reduce the risk of data loss during restoration.

The application uses separate storage for its main business records and Smart Project Tools data.

Users should retain independent copies of important business backups.

Privacy and Offline Operation

MODE Handyman is designed to operate without requiring a cloud account or continuous internet connection.

The inspected source project:

- Uses local SQLite databases.
- Does not declare the Android INTERNET permission.
- Does not include Firebase, Sentry, advertising, or analytics integrations.
- Does not require Google Play Services.
- Does not contain a built-in SMTP sender or SMS-template workflow.
- Uses Android's document picker and share mechanisms for supported exports.
- Stores local crash reports without automatically uploading them.

External websites opened through Android's browser may require internet connectivity.

Technical Information

Property| Value
Application| MODE Handyman
Version| 2.0.7
Version code| 13
Android package| "com.macleanofduartenterprises.modehandyman"
Programming language| Kotlin
Platform| Native Android
Minimum Android version| Android 11 (API 30)
Target Android API| 36
Database| SQLite
PDF generation| Android PdfDocument
File import/export| Android Storage Access Framework
Architecture| Offline-first
Development environment| Android Studio / Gradle

Source Architecture

The project includes the following major components:

- "MainActivity.kt" — Main application navigation and business-management screens.
- "SmartToolsActivity.kt" — Estimator, materials, suppliers, construction tools, project documentation, and approvals.
- "ModeRepository.kt" — Business record operations.
- "DatabaseManager.kt" — Main database initialization and migrations.
- "SmartToolsStore.kt" — Smart Tools database.
- "BusinessProfiles.kt" — Business-profile management.
- "CustomerTransfer.kt" — Customer contact import/export functionality.
- "PdfGenerator.kt" — Local PDF generation.
- "BackupManager.kt" — Backup and restoration.
- "FloatingCalculator.kt" — Compact calculator.
- "LocalCrashReporter.kt" — Local crash reporting.

What's New in Version 2.0.7

Version 2.0.7 addresses an application crash encountered when associating suppliers with materials and product links.

Problem

Android crash reports identified the following exception:

"java.lang.IllegalArgumentException: parameter must be a descendant of this view"

The crash occurred when the application attempted to scroll to a text field belonging to a dialog rather than the main page's ScrollView.

Correction

- Removed the unsafe delayed focus-scrolling callback from Smart Tools.
- Retained Android's normal keyboard and scrolling behavior.
- Preserved existing supplier and product-link functionality.
- Made no destructive supplier or material database changes as part of the correction.

The source-level correction has been applied, but physical-device verification remains necessary.

Building the Application

The source project specifies:

- JDK 17.
- Android SDK Platform 36.
- Android Build Tools 36.
- Gradle 8.13.

The project includes Gradle configuration and verification utilities.

Release signing requires the developer's own keystore and signing credentials, supplied outside the source code.

Do not commit private signing keys or passwords to a public repository.

Testing and Verification

The version 2.0.7 source update was reviewed against the reported crash, and the source archive passed ZIP integrity verification.

Android compilation, physical-device testing, and complete regression testing were not performed as part of that update.

Before a production release, verify supplier/product-link editing, database upgrades, customer import/export, receipt management, business-profile isolation, document generation, backup/restore, and keyboard behavior throughout the application.

Project Identity

MODE Handyman
A division of Maclean Of Duart Enterprises Corp

A locally focused, offline-first Android business-management application designed to help independent service providers organize customers, projects, materials, finances, and documentation.

Version: 2.0.7
Platform: Android
Development: Native Kotlin
Data model: Local-first, multi-business-profile management
