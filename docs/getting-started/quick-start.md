# Quick Start Guide

Get your organization up and running with Kosentral in just 15 minutes! This guide walks you through the essential steps to start managing your members and finances effectively.

## Before You Begin

Ensure you have:

- [x] Completed organization registration
- [x] Verified your email address  
- [x] Logged into your Kosentral dashboard
- [x] Admin or Manager role permissions

## Step 1: Configure Organization Settings (3 minutes)

### Update Organization Information

1. Navigate to **Settings** from the main menu
2. Click on **Organization Information** tab
3. Complete your organization details:
   - Upload your organization logo
   - Add complete address information  
   - Set contact details
   - Add website and description

### Configure Membership Settings

1. Switch to **Membership Settings** tab
2. Set essential configurations:
   - **Default Monthly Fee**: Set your standard membership fee (e.g., RM50.00)
   - **Require Approval**: Toggle member approval requirements
   - **Invoice Frequency**: Choose Monthly, Quarterly, or Yearly
   - **Grace Period**: Set days before late fees apply

!!! tip "Recommended Settings"
    
    For new organizations, we recommend:
    
    - Monthly fee: Based on your organization's budget
    - Require approval: ON (for quality control)
    - Invoice frequency: Monthly (easier cash flow management)
    - Grace period: 7-14 days

## Step 2: Create Your First Members (5 minutes)

### Add Individual Members

1. Navigate to **Members** → **Create New Member**
2. Complete the six-tab form:

=== "Personal Info"
    - Full name and IC number
    - Contact details (email and phone)
    - Date of birth and gender

=== "Address"
    - Residential address (required)
    - Correspondence address if different

=== "Banking"
    - Bank name and account number
    - Account holder name

=== "Employment"
    - Employer name
    - Job title and income range

=== "Dependents"
    - Spouse information (if applicable)
    - Executor details (for Islamic members)

=== "Review"
    - Verify all information
    - Add internal notes
    - Submit

### Bulk Import (Alternative)

For multiple members:

1. Go to **Members** → **Actions** → **Import CSV**
2. Download the template
3. Fill in member data
4. Upload completed CSV file

!!! example "Sample Member Data"
    
    Create test members with these details:
    
    - **John Doe** - 123456-78-9012 - john@email.com
    - **Jane Smith** - 234567-89-0123 - jane@email.com
    - **Ahmad Rahman** - 345678-90-1234 - ahmad@email.com

## Step 3: Approve Pending Members (2 minutes)

If you enabled member approval:

1. Go to **Members** index page
2. Look for members with "Pending" status
3. Click on member name or **View Details**
4. Click **Approve** button to activate
5. Confirm approval in modal dialog

Members are now active and can receive invoices and make transactions.

## Step 4: Create Your First Invoice (3 minutes)

### Generate Membership Fee Invoice

1. Navigate to **Invoices** → **Create Invoice**
2. Select invoice type: **Member Fee Invoice**
3. Choose the member from dropdown
4. Add invoice items:
   - Item: "Monthly Membership Fee"  
   - Amount: RM50.00 (or your set amount)
   - Quantity: 1
5. Review and click **Create Invoice**

### View Invoice Details

1. Go to **Invoices** index to see your created invoice
2. Click invoice number to view details
3. Options available:
   - **Download PDF**: Generate printable invoice
   - **Pay Invoice**: Process payment
   - **Email Invoice**: Send to member

!!! success "Invoice Created!"
    
    Your first invoice is now ready. Members can view this through their portal or you can send it via email.

## Step 5: Process Your First Transaction (2 minutes)

### Record a Payment

1. Navigate to **Transactions** → **Membership** → **Add Payments**
2. Select the member who's paying
3. The pending invoice will appear - click **Add** to include it
4. Review transaction details:
   - Payment date (defaults to today)
   - Amount (auto-filled from invoice)
   - Description (auto-generated)
5. Click **Create Transaction**

### Generate Receipt

After transaction creation:
- Receipt is automatically generated
- Email sent to member (if email provided)
- Invoice status changes to "Paid"
- Member's account is updated

!!! tip "Payment Methods"
    
    For Malaysian organizations, integrate Billplz for online payments:
    
    1. Go to **Settings** → **Payment Gateway**
    2. Add Billplz API credentials
    3. Enable online payment links in invoices

## Quick Verification Checklist

Verify your setup is complete:

- [x] Organization settings configured
- [x] Members created and approved  
- [x] First invoice generated
- [x] Payment processed successfully
- [x] Receipt generated and emailed

## What's Next?

Now that you have the basics set up, explore these features:

### Advanced Member Management
- **[Search & Filter](../members/search-filter.md)**: Find members quickly
- **[Statistics](../members/statistics.md)**: Analyze member demographics
- **[Import/Export](../members/import-export.md)**: Bulk operations

### Financial Operations  
- **[Share Transactions](../transactions/share-transactions.md)**: Handle share purchases
- **[Reports](../reports/membership-reports.md)**: Generate financial reports
- **[Statements](../reports/account-statements.md)**: Member account summaries

### User Management
- **[User Invitations](../settings/user-management.md)**: Add team members
- **[Role Management](../settings/user-management.md)**: Control access levels

### System Features
- **[Global Search](../features/global-search.md)**: Quick navigation
- **[Help & Support](../features/help-support.md)**: Get assistance

## Common Quick Start Issues

### Members Not Appearing
- Check if approval is required in settings
- Verify member status is "Active"
- Refresh the members list

### Invoice Creation Fails
- Ensure member is active/approved
- Check required fields are completed
- Verify amounts are positive numbers

### Payment Processing Issues
- Confirm member has active invoices
- Check transaction amounts match invoice totals
- Verify member's banking details

### Email Notifications Not Sent
- Check organization email settings
- Verify member email addresses are valid
- Confirm SMTP configuration in settings

## Getting Help

If you run into issues during quick start:

1. **Documentation**: Check relevant help sections
2. **Support Portal**: Use in-app help system
3. **Email Support**: Contact support@kosentral.com
4. **Live Chat**: Available during business hours

---

!!! success "Congratulations! 🎉"
    
    You've successfully set up Kosentral and processed your first member transaction. Your organization is now ready to leverage all of Kosentral's powerful features for efficient management.

!!! info "Pro Tips"
    
    - Set up automated monthly invoicing to save time
    - Use member tags for easy categorization
    - Export data regularly for backup purposes
    - Invite team members to share the workload

!!! question "Need More Help?"
    
    Explore our complete documentation or contact our friendly support team. We're here to help you succeed with Kosentral!
