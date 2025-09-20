# Membership Fee Transactions

Learn how to process membership fee payments and manage member accounts effectively in Kosentral.

## Overview

Membership fee transactions are the core financial operations in Kosentral, allowing you to:

- **Record membership fee payments** from members
- **Link payments to invoices** automatically
- **Generate receipts** for member records
- **Update member account balances** in real-time
- **Send email confirmations** to members

## Prerequisites

Before processing membership fee transactions:

- **User Permissions**: Admin, Manager, or Officer role required
- **Active Members**: Members must be approved and active
- **Outstanding Invoices**: Invoices available for payment (optional)
- **Organization Settings**: Payment processing configured

## Creating Membership Fee Transactions

### Step 1: Access Transaction Creation

1. Navigate to **Transactions** from the main menu
2. Click **"Membership"** to access membership transactions
3. Click **"Add Payments"** to create a new transaction

### Step 2: Transaction Header

**Transaction Date**

- Defaults to current date
- Can be modified for backdated payments
- Must not be in the future

**Receipt Number**

- Automatically generated (format: RCP-YYYY-NNN)
- Sequential numbering by organization
- Cannot be manually modified

### Step 3: Select Member

**Member Selection Process**

1. Use the **"Payment by"** search bar
2. Search by member name or IC number
3. Select member from dropdown results
4. Member details populate automatically

**Member Information Display**

- Full name and membership ID
- IC number for verification
- Email address (if available)
- Phone number for contact
- Current account status

**Pending Invoices Section**

If the selected member has outstanding invoices:

- List displays all unpaid invoices
- Shows invoice number, amount, and due date
- **"Add"** button includes invoice in current transaction
- Automatic description and amount population

### Step 4: Transaction Items

**Payment Allocation**
Each transaction item requires:

- **Description**: Purpose of the payment (e.g., "Monthly Fee", "Annual Dues")
- **Amount**: Payment amount in organization currency (RM)

**Adding Items**

- **From Invoices**: Click "Add" next to pending invoices
- **Manual Entry**: Click "New transaction item" for custom payments
- **Multiple Items**: Add as many payment lines as needed

**Item Management**

- **Edit Amounts**: Modify payment amounts as needed
- **Remove Items**: Click "Remove" to delete payment lines
- **Real-time Totals**: Automatic calculation of subtotal and total

**Transaction Description**

- Optional general description for entire transaction
- Used for internal notes and receipt generation
- Appears on member statements

### Step 5: Review and Submit

**Final Review**

- Verify member information is correct
- Check all payment items and amounts
- Confirm total amount matches payment received
- Review transaction date and description

**Submit Transaction**

1. Click **"Create Transaction"** button
2. System validates all required fields
3. Automatic processing occurs:
    - Receipt number generated
    - Linked invoices marked as "Paid"
    - Member account balance updated
    - Email receipt sent (if email available)

## Transaction Processing

### Automatic Actions

When a membership fee transaction is created:

1. **Invoice Linking**: Associated invoices automatically marked as paid
2. **Status Updates**: Invoice status changes from "Unpaid" to "Paid"
3. **Balance Updates**: Member account reflects new payment
4. **Receipt Generation**: PDF receipt created and stored
5. **Email Notification**: Receipt emailed to member (if email provided)

### Transaction Validation

The system validates:

- **Member Status**: Must be active/approved
- **Amount Validation**: Positive amounts only
- **Date Validation**: Cannot be future-dated
- **Duplicate Prevention**: Checks for potential duplicate transactions

## Invoice Integration

### Linking to Pending Invoices

**Automatic Linking**

- Select member with pending invoices
- Click "Add" next to relevant invoice
- Description and amount auto-populate
- Invoice marked as paid upon transaction creation

**Benefits of Linking**

- Maintains clear audit trail
- Simplifies reconciliation
- Automatic status updates
- Integrated reporting

### Manual Payment Entry

**Custom Payment Items**
For payments not linked to specific invoices:

- Click "New transaction item"
- Enter descriptive payment purpose
- Specify payment amount
- Used for general contributions, donations, or special fees

## Receipt Management

### Automatic Receipt Generation

**Receipt Details Include**:

- Organization information and branding
- Receipt number and transaction date
- Member details and contact information
- Itemized payment breakdown
- Total amount paid
- Payment method (if specified)

### Receipt Distribution

**Email Delivery**

- Automatic email to member (if email available)
- Professional HTML format
- PDF attachment included
- Organization branding applied

**Manual Distribution**

- Print receipts from transaction details page
- Download PDF for manual sending
- Access from transaction history

## Account Statement Integration

### Member Account Updates

Each transaction automatically:

- Updates member's account balance
- Records transaction in member history
- Calculates running balance
- Provides transaction reference

### Statement Generation

Members can access:

- Transaction history with date ranges
- Running account balances
- Payment references and descriptions
- PDF statement generation

## Bulk Payment Processing

### Multiple Members

For processing payments from multiple members:

1. Create individual transactions for each member
2. Use consistent payment descriptions
3. Process in batches for efficiency
4. Generate summary reports for reconciliation

### Recurring Payments

**Setup Recommendations**:

- Create invoice templates for regular fees
- Use consistent payment descriptions
- Set up automated invoice generation
- Establish payment reminder workflows

## Financial Reporting

### Transaction Reports

**Available Reports**:

- Daily/monthly payment summaries
- Member payment history
- Outstanding invoice reports
- Revenue recognition reports

**Report Generation**:

1. Navigate to **Reports** section
2. Select desired report type
3. Choose date range
4. Generate and download PDF

### Integration with Accounting

**Export Capabilities**:

- CSV export of transaction data
- PDF reports for documentation
- Integration with external accounting systems
- API access for custom integrations

## Error Handling and Corrections

### Common Issues

**Payment Allocation Errors**

- Wrong amount entered: Create credit/debit transaction
- Wrong member selected: Contact support for assistance
- Missing payment: Verify all items included

**System Errors**

- Transaction failed: Check network connection and retry
- Email not sent: Verify member email address
- Receipt not generated: Access from transaction details

### Correction Procedures

**For Incorrect Amounts**:

1. Create correcting transaction (positive or negative)
2. Reference original transaction in description
3. Update member account accordingly

**For Wrong Member**:

1. Contact system administrator
2. Provide transaction details for correction
3. May require manual database adjustment

## Mobile Processing

### Mobile-Optimized Interface

**Features Available**:

- Full transaction creation capability
- Member search and selection
- Payment amount entry
- Receipt generation and sharing

**Mobile-Specific Benefits**:

- Process payments on-site
- Immediate receipt generation
- Email sharing capabilities
- Offline transaction queuing

---

!!! success "Transaction Complete!"
    
    Once a membership fee transaction is processed, the member's account is immediately updated, and they receive confirmation of their payment.

!!! tip "Best Practices"
    
    - **Consistent Descriptions**: Use standardized payment descriptions for easy reporting
    - **Timely Processing**: Enter payments promptly for accurate account management
    - **Regular Reconciliation**: Compare transaction reports with bank deposits
    - **Member Communication**: Ensure members receive receipts and confirmations

!!! warning "Important Notes"
    
    - **Cannot Delete Transactions**: Once created, transactions cannot be deleted, only corrected
    - **Email Requirements**: Member email addresses must be valid for automatic receipt delivery
    - **Backup Procedures**: Maintain manual records as backup to digital transactions
