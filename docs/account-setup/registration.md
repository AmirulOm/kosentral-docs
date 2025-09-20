# Registering a New Organization and User

This guide walks you through the complete process of registering your organization and creating your first user account in Kosentral.

## Overview

The registration process involves creating both a user account and an organization profile in a single workflow. Upon completion, your organization will have its own isolated database schema, and you'll be set up as the primary administrator.

## Prerequisites

Before starting the registration process, ensure you have:

- A valid email address for account verification
- Your organization's official registration number
- Basic organization details (name, contact information)
- Agreement to Kosentral's Terms of Service and Privacy Policy

## Step-by-Step Registration Process

### 1. Accessing the Registration Page

1. Navigate to the Kosentral registration page at `/Account/Register`
2. You'll see a clean, professional registration form with two main sections:
   - **User Account Information**
   - **Organization Details**

### 2. User Account Creation

#### 2a. Personal Information

Fill in your personal details as the primary administrator:

- **Full Name**: Enter your complete legal name as it appears on official documents
- **Email Address**: 
    - Must be a valid, accessible email address
    - Will be used for login and system notifications
    - Cannot be changed after registration
- **Password**: 
    - Minimum 8 characters
    - Must include uppercase, lowercase, number, and special character
    - Use a strong, unique password for security

!!! warning "Password Requirements"
    
    Your password must meet the following criteria:
    
    - At least 8 characters long
    - Contains uppercase letters (A-Z)
    - Contains lowercase letters (a-z)  
    - Contains numbers (0-9)
    - Contains special characters (!@#$%^&*)

### 3. Organization Details Entry

#### 3a. Required Information

**Organization Name**

- Full legal name of your organization
- Will appear on all generated documents and reports
- Can be updated later in organization settings

**Short Name** 

- Maximum 32 characters 
- Used for database schema naming (e.g., `org_shortname`)   
- Must be unique across the entire platform. 
- Cannot be changed after registration.   
- Use only letters, numbers, and underscores.   

!!! important "Short Name Guidelines"
    
    The short name becomes part of your database schema and cannot be modified after registration. Choose carefully and ensure it's:
    
    - Descriptive of your organization
    - Easy to remember
    - Professional (avoid special characters)

**Registration Number**

- Your organization's official registration number
- Required for compliance and verification
- Used for official documentation

**Contact Information**

- **Organization Email**: Official contact email for the organization
- **Phone Number**: Primary contact number
- **Website**: Organization website URL (optional)
- **Description**: Brief description of your organization's purpose (optional)

#### 3b. Optional Information

- **Website**: Your organization's official website
- **Description**: A brief description of your organization's mission or purpose

### 4. Agreement and Submission

#### 4a. Terms and Conditions

Before submitting your registration, you must:

1. **Read and Accept Terms of Service**
    - Review Kosentral's terms of service carefully
    - Check the acceptance box to proceed

2. **Privacy Policy Agreement**
    - Understand how your data will be handled
    - Agree to the privacy policy terms

#### 4b. Completing Registration

1. **Review Your Information**
    - Double-check all entered details for accuracy
    - Ensure email address is correct for verification

2. **Submit Registration**
    - Click "Register Organization" to submit your application
    - The system will validate all information

3. **Processing**
    - Account creation is immediate
    - Database schema is automatically created
    - Initial data seeding occurs

## What Happens After Registration

### Immediate Actions

1. **Email Confirmation**
    - Verification email sent to your registered email address
    - Click the confirmation link to activate your account
    - Email may take 5-10 minutes to arrive

2. **Schema Creation**
    - Unique database schema created for your organization
    - Example: `org_yourshortname`
    - Complete data isolation from other organizations

3. **Initial Setup**
    - Default invoice types created
    - Transaction types initialized
    - Basic organization settings configured

### First Login

Once email verification is complete:

1. **Navigate to Login Page**: Go to `/Account/Login`
2. **Enter Credentials**: Use your email and password
3. **Dashboard Access**: You'll be redirected to your organization dashboard
4. **Setup Wizard**: Follow the guided setup for additional configuration

## Common Registration Issues

### Email Not Received

If you don't receive the verification email:

- Check your spam/junk folder
- Verify the email address was entered correctly
- Wait 10-15 minutes for delivery
- Contact support if issues persist

### Short Name Already Taken

If your desired short name is unavailable:

- Try variations with numbers or abbreviations
- Use your organization's acronym
- Add location or type identifiers
- Contact support for assistance

### Validation Errors

Common validation issues:

- **Password Strength**: Ensure password meets all requirements
- **Email Format**: Use a valid email format (user@domain.com)
- **Required Fields**: All mandatory fields must be completed
- **Registration Number**: Use only alphanumeric characters

## Post-Registration Setup

After successful registration, consider these next steps:

1. **[Organization Settings](../settings/organization-settings.md)**: Configure advanced options
2. **[User Management](../settings/user-management.md)**: Invite additional users
3. **[Member Creation](../members/creating-members.md)**: Add your first members
4. **[System Configuration](../settings/organization-settings.md)**: Set up billing and preferences

## Security Best Practices

### Account Security

- Use a strong, unique password
- Enable two-factor authentication when available
- Keep login credentials confidential
- Log out of shared devices

### Organization Security

- Regularly review user access
- Monitor system activity logs
- Keep organization information updated
- Report suspicious activity immediately

---

!!! success "Registration Complete!"
    
    Congratulations! Your organization is now set up in Kosentral. You can begin adding members, creating invoices, and managing your organization's operations immediately.

!!! tip "Next Steps"
    
    Ready to start using Kosentral? Check out our [Quick Start Guide](../getting-started/quick-start.md) to get up and running with your first members and transactions.

!!! question "Need Help?"
    
    If you encounter any issues during registration, our support team is here to help. Contact us through the [Help & Support](../features/help-support.md) portal or email support@kosentral.com.
