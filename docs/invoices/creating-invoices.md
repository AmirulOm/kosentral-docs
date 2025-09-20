# Creating Invoices

Learn how to create and manage invoices for your members in Kosentral.

## Overview

Kosentral supports multiple invoice types for different organizational needs:

- **Standard Invoice**: General invoices for goods/services
- **Proforma Invoice**: Advance invoices before delivery
- **Credit Note**: Reduce amounts owed by customers  
- **Debit Note**: Increase amounts owed by customers
- **Member Fee Invoice**: Specific for membership fees

## Creating a New Invoice

### Prerequisites
- Admin, Manager, or Officer role permissions
- Active members in your organization
- Configured organization settings

### Step 1: Access Invoice Creation
1. Navigate to **Invoices** from the main menu
2. Click **"Create Invoice"** button
3. Choose your invoice type

### Step 2: Invoice Details

#### Select Recipient Member
- Use the "Invoice To" search bar
- Search by member name or IC number
- Select member from dropdown results
- Member details auto-populate

#### Invoice Information
- **Invoice Number**: Auto-generated unique identifier
- **Invoice Type**: Select from dropdown options
- **Invoice Date**: Defaults to today's date
- **Due Date**: Defaults to 30 days from invoice date

### Step 3: Add Invoice Items

#### Item Details
For each invoice item, specify:

- **Item Name**: Description of goods/services
- **Amount**: Price per unit
- **Quantity**: Number of units (default: 1)

#### Managing Items
- Click **"New Invoice Item"** to add more lines
- Use **"Remove"** button to delete items
- Real-time calculation of subtotal and total

#### Invoice Description
- Add general description for entire invoice
- Optional field for additional context

### Step 4: Review and Submit
1. Review all invoice details
2. Verify member information
3. Check item calculations
4. Click **"Create Invoice"**
5. Confirmation and redirect to invoice details

## Invoice Types in Detail

=== "Standard Invoice"

    **Use Case**: Regular billing for goods or services
    
    **Features**:

    - Standard payment terms
    - Multiple line items supported
    - Automatic calculations
    - PDF generation

=== "Member Fee Invoice"

    **Use Case**: Monthly/quarterly membership fees
    
    **Features**:

    - Pre-configured fee amounts
    - Recurring invoice capability
    - Member-specific calculations
    - Automated processing

=== "Proforma Invoice"

    **Use Case**: Advance billing before service delivery
    
    **Features**:

    - No immediate payment required
    - Estimate or quotation format
    - Convertible to standard invoice

=== "Credit Note"

    **Use Case**: Refunds or billing corrections
    
    **Features**:

    - Reduces member account balance
    - Links to original invoice
    - Automatic adjustment calculations

## Invoice Management

### Viewing Invoice Details
1. Go to **Invoices** index page
2. Click invoice number or **"View Details"**
3. Access full invoice information

### Available Actions

#### Download PDF
- Generate printable invoice format
- Professional layout with organization branding
- Suitable for official records

#### Print Invoice
- Direct browser printing
- Optimized print layout
- Quick physical copy generation

#### Process Payment
- Redirect to payment processing
- Pre-populate transaction details
- Link invoice to payment record

#### Cancel Invoice
- Mark unpaid invoices as cancelled
- Requires confirmation
- Maintains audit trail

## Bulk Invoice Operations

### Creating Multiple Invoices
- Select multiple members
- Apply same invoice template
- Bulk generation process
- Individual customization options

### Invoice Templates
- Save frequently used invoice formats
- Quick application to new invoices
- Customizable item lists
- Standardized descriptions

## Invoice Status Management

### Status Types
- **Unpaid**: Invoice created, payment pending
- **Paid**: Payment received and processed
- **Overdue**: Past due date without payment
- **Cancelled**: Invoice voided or cancelled
- **Refunded**: Payment returned to member

### Automatic Status Updates
- Payment processing updates status
- Due date monitoring for overdue
- Email notifications for status changes

## Financial Integration

### Payment Processing
- Direct link to transaction creation
- Automatic invoice marking
- Receipt generation
- Member account updates

### Reporting Integration
- Include in financial reports
- Revenue recognition
- Outstanding invoice tracking
- Payment analysis

---

!!! tip "Invoice Best Practices"
    
    - Use clear, descriptive item names
    - Set reasonable payment terms
    - Include contact information
    - Send invoices promptly

!!! info "Automation Options"
    
    Set up recurring invoices for membership fees to save time and ensure consistent billing cycles.
