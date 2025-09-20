# Kosentral Documentation

![kosentral-logo](https://kosentral.com/icons/kosentral.png)

Welcome to **Kosentral**, your comprehensive digital command center for managing organizations, members, finances, and operations with ease and efficiency.

## What is Kosentral?

Kosentral is a powerful web-based platform designed to streamline organizational management. Whether you're running a cooperative, association, club, or any member-based organization, Kosentral provides all the tools you need to:

- **Manage Members**: Complete member lifecycle management with detailed profiles
- **Handle Finances**: Invoice generation, payment processing, and financial tracking  
- **Process Transactions**: Membership fees, share transactions, and comprehensive reporting
- **Generate Reports**: Detailed analytics, statements, and regulatory compliance documents
- **Organize Data**: Advanced search, filtering, and data export capabilities

## Key Features at a Glance

=== "Member Management"

    * Comprehensive member profiles with personal, employment, and banking details
    * Multi-step member registration with approval workflows
    * Bulk import/export capabilities
    * Advanced search and filtering
    * Statistical reporting and analytics


=== "Financial Management"

    * Multi-type invoice generation (Standard, Proforma, Credit/Debit Notes)
    * Automated membership fee invoicing
    * Payment processing and receipt generation
    * Share purchase and withdrawal management
    * Financial reporting and statements

===  "Organization Tools"

    * Multi-tenant architecture with schema isolation
    * Role-based access control (Admin, Manager, Officer, Member)
    * User invitation and management system
    * Customizable organization settings
    * Subscription tier management

===  "Reporting & Analytics"

    * Membership reports with detailed breakdowns
    * Customer Information Forms (CIFs) generation
    * Account statements with date range selection
    * Statistical dashboards
    * PDF export capabilities


## Quick Start

Ready to get started with Kosentral? Follow these simple steps:

1. **[Register Your Organization](account-setup/registration.md)** - Set up your organization account
2. **[Add Your First Members](members/creating-members.md)** - Start building your member database
3. **[Create Invoices](invoices/creating-invoices.md)** - Begin managing your finances
4. **[Process Transactions](transactions/membership-fees.md)** - Handle payments and fees

## System Architecture

Kosentral is built with modern technologies for scalability and reliability:

- **Backend**: ASP.NET Core 8.0 with C#
- **Database**: PostgreSQL with multi-tenant schema architecture
- **Frontend**: Razor Pages with Bootstrap 5
- **Authentication**: ASP.NET Core Identity
- **Payment**: Billplz integration for Malaysian organizations

## Support Tiers

Kosentral offers flexible subscription tiers to match your organization's needs:

| Tier | Members | Users | Storage | Support |
|------|---------|-------|---------|---------|
| **Free** | 20 | 2 | 1GB | Community |
| **Starter** | 50 | 5 | 10GB | Email |
| **Standard** | 200 | 25 | 100GB | Priority |
| **Enterprise** | Unlimited | Unlimited | 1TB | Dedicated |

## Getting Help

Need assistance? We're here to help:

- 📖 Browse this comprehensive documentation
- 💬 Contact our support team through the [Help & Support](features/help-support.md) portal
- 🐛 Report issues on our GitHub repository
- 📧 Email us directly at support@kosentral.com

---

!!! tip "New to Kosentral?"
    
    Start with our [Introduction Guide](getting-started/introduction.md) to understand the core concepts and then follow our [Quick Start](getting-started/quick-start.md) tutorial to get your organization up and running in minutes!

!!! info "Developer Resources"
    
    Building integrations or customizations? Check out our [API Reference](api/overview.md) and [Developer Guide](dev/architecture.md) for technical documentation.
