# Introduction to Kosentral

Kosentral is a comprehensive digital command center designed to streamline organizational management for cooperatives, associations, clubs, and member-based organizations. Built with modern web technologies, Kosentral provides a robust, scalable solution for managing members, finances, transactions, and organizational data.

## Core Concepts

### Multi-Tenant Architecture

Kosentral employs a sophisticated multi-tenant architecture where each organization operates in its own isolated schema within a PostgreSQL database. This ensures:

- **Data Isolation**: Complete separation of organizational data
- **Schema Security**: Each organization's data is protected at the database level
- **Scalability**: Support for unlimited organizations on a single platform
- **Customization**: Organization-specific settings and configurations

### User Roles and Permissions

Kosentral implements a comprehensive role-based access control system:

=== "Admin"

    **Full System Access**
    
    - Complete member management (create, edit, approve, delete)
    - Financial operations (invoices, transactions, reports)
    - Organization settings and configuration
    - User management and invitations
    - System-wide reporting and analytics

=== "Manager"

    **Operational Management**
    
    - Member management and approval
    - Financial operations and reporting
    - Transaction processing
    - Limited organization settings
    - User invitation (Officer level only)

=== "Officer"

    **Day-to-day Operations**
    
    - Member management (create, edit)
    - Transaction processing
    - Invoice creation
    - Basic reporting
    - Read-only access to settings

=== "Member"

    **Self-Service Portal**
    
    - View personal profile
    - Access personal statements
    - View transaction history
    - Download personal documents

## Key Features Overview

### Member Management System

The member management system provides comprehensive tools for handling member data:

- **Multi-step Registration**: Structured data collection across 6 tabs
- **Personal Information**: Complete demographic and contact details
- **Employment Details**: Workplace information and income tracking
- **Banking Information**: Secure financial account management
- **Dependent Management**: Spouse and executor information
- **Document Storage**: Profile pictures and supporting documents
- **Approval Workflows**: Configurable member approval processes

### Financial Management

Kosentral's financial management capabilities include:

- **Invoice Generation**: Multiple invoice types (Standard, Proforma, Credit/Debit Notes)
- **Payment Processing**: Integration with Billplz payment gateway
- **Membership Fees**: Automated fee calculation and invoicing
- **Share Management**: Share purchase, withdrawal, and approval workflows
- **Transaction Tracking**: Comprehensive transaction history and categorization

### Reporting and Analytics

Generate professional reports and gain insights:

- **Membership Reports**: Detailed member analytics with PDF export
- **Financial Statements**: Account statements with customizable date ranges
- **Customer Information Forms (CIFs)**: Regulatory compliance documents
- **Statistical Dashboards**: Member demographics and financial summaries
- **Audit Trails**: Complete transaction and activity logging

## Technology Stack

### Backend Architecture

- **Framework**: ASP.NET Core 8.0
- **Language**: C# with modern language features
- **Database**: PostgreSQL with schema-based multi-tenancy
- **ORM**: Entity Framework Core with advanced configurations
- **Authentication**: ASP.NET Core Identity with custom user management

### Frontend Technologies

- **UI Framework**: Razor Pages with server-side rendering
- **CSS Framework**: Bootstrap 5 with custom theming
- **JavaScript**: Modern ES6+ with minimal dependencies
- **Icons**: Bootstrap Icons and Font Awesome
- **Charts**: Chart.js for data visualization

### Infrastructure and Services

- **Email Service**: SMTP-based email delivery
- **File Storage**: Local file system with configurable storage paths
- **PDF Generation**: HTML-to-PDF conversion for reports
- **Payment Gateway**: Billplz integration for Malaysian market
- **Logging**: Structured logging with customizable levels

## Data Security and Privacy

### Data Protection

Kosentral implements multiple layers of data protection:

- **Schema Isolation**: Database-level tenant separation
- **Access Control**: Role-based permissions at application level
- **Input Validation**: Comprehensive data validation and sanitization
- **Audit Logging**: Complete activity tracking for compliance

### Privacy Compliance

- **Data Minimization**: Collect only necessary member information
- **Consent Management**: Clear privacy policy acceptance workflows
- **Data Retention**: Configurable retention policies
- **Export Capabilities**: Member data export for portability

## Subscription Model

### Tier Structure

Kosentral offers four subscription tiers to accommodate different organizational needs:

| Feature | Free | Starter | Standard | Enterprise |
|---------|------|---------|----------|------------|
| **Members** | 20 | 50 | 200 | Unlimited |
| **Users** | 2 | 5 | 25 | Unlimited |
| **Storage** | 1GB | 10GB | 100GB | 1TB |
| **Transactions/Month** | 10 | 100 | 1,000 | Unlimited |
| **Support** | Community | Email | Priority | Dedicated |

### Billing and Payment

- **Flexible Billing**: Monthly or annual payment options
- **Local Payment**: Billplz integration for Malaysian organizations
- **Automated Billing**: Subscription renewals and notifications
- **Coupon Support**: Discount codes and promotional pricing

## Getting Started

To begin using Kosentral:

1. **Organization Registration**: Create your organization account
2. **User Setup**: Configure admin users and invite team members
3. **System Configuration**: Set organization settings and preferences
4. **Member Import**: Add existing members or start fresh
5. **Financial Setup**: Configure payment methods and fee structures

## Next Steps

Ready to dive deeper? Continue with:

- [Quick Start Guide](quick-start.md) - Get up and running in 15 minutes
- [System Requirements](system-requirements.md) - Technical specifications
- [Registration Process](../account-setup/registration.md) - Detailed setup instructions

---

!!! question "Need Help?"
    
    If you have questions about any of these concepts, our support team is ready to help. Contact us through the [Help & Support](../features/help-support.md) portal or email support@kosentral.com.
