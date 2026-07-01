# Property Management & Leasing ERP Engine

A comprehensive real estate vertical solution configured on Dynamics 365 and the Power Platform to automate the complete leasing lifecycle, track complex assets, and manage property finances.

##  Key Features

*   **Lease Lifecycle Automation:** Integrated automated workflows to handle incoming tenants (`rentaunitbase`) and structural move-out configurations (`vacateaunit`).
*   **Financial & Price Calculation Engines:** Automated back-end rules for dynamic agreement values (`calculateContractPrice`), tax visibility states, and automated invoicing loops (`InvoiceReminder`).
*   **Structured Business Process Flows (BPF):** Multi-stage interactive phase layouts governing compliance rules for legal contract approvals, featuring built-in duration tracking.
*   **State Locking Controls:** Strict validation handling (`LockInstallment`, `LockUnitBase`) designed to freeze active inventory listings and payment schedules during processing flags.

##  Repository Structure

*   `/src`: Extracted configuration files, Business Process Flow structures, form script resources, and system entity metadata.
*   `/release`: Compiled solution package artifacts prepared for target sandbox or production deployments.