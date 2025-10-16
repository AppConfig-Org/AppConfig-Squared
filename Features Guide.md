# AppConfig² Suite Features Guide

This guide covers features available in the AppConfig² Suite, organized by tool and functionality.

## 🌟 Core Capabilities (Both Apps)

### Enhanced Portfolio Dashboard
- Application Portfolio Overview - Comprehensive view of all applications with key metrics
- Security Dashboard - Real-time security posture analysis across all applications
- Interactive Metrics - Clickable cards that filter and navigate to specific applications
- Export Capabilities - CSV exports for compliance and reporting needs

### Testing & Authentication
- Multi-Flow Support - Authorization Code, Implicit, Client Credentials, and hybrid flows
- Real-Time Token Analysis - Live token decoding with syntax highlighting
- Claims Inspector - Detailed token claims analysis and validation
- User Context Testing - Test authentication flows as different users

### Advanced Security Analysis
- Attack Surface Analysis - Comprehensive vulnerability assessment and attack vector identification
- Permission Analysis - Detailed API permission review with risk scoring
- Security Scorecard - Overall security posture with actionable recommendations

### Application Lifecycle Tracking
- Creation Tracking - Monitor when and how applications were created
- Ownership Management - Track application owners and management responsibilities
- Quick Statistics - View number of owners, API Permissions, Redirect URIs and App Roles

### Graph Integration & Tools
- Embedded Graph Explorer - Full Microsoft Graph API console integration
- Request Templates - Pre-built queries for common scenarios
- Batch Operations - Execute Graph API calls efficiently (limited to GET method in AppTesting)

### Suite Tools (Available in Both Apps)
- **Token Scope Requester** - Request tokens for Graph or custom APIs with /.default, consent, and tenant authority controls; includes quick GET tester
- **Raw OAuth Tester** - Run implicit flow without MSAL, generate authorize URLs, validate state/nonce, and inspect tokens
- **OData Query Builder** - Build Graph OData queries visually, paginate, and export JSON
- **Secrets & Certificate Expiration Monitor** - Surface expiring/expired secrets and certs (apps/SPs), filter by risk level, and export CSV
- **Entra Endpoints Explorer** - Comprehensive reference guide for Microsoft Entra ID endpoints across all Azure clouds with multi-cloud support, variable substitution, categorized endpoints (OAuth 2.0/OIDC, Graph, Azure Management, B2C, SAML), one-click copying, and direct links to Microsoft documentation
- **MSAL Trace Viewer** - Real-time MSAL.js authentication event monitoring and debugging with live event capture grouped by correlation ID, built-in test actions, interaction type filtering, PII redaction toggle, JSON export, and detailed event payload inspection
- **OIDC Metadata Inspector** - OpenID Connect discovery and JWT validation tool with support for fetching and analyzing OIDC discovery documents, JWKS inspection, JWT decoding with automatic token type detection, signature verification, and key matching.


## 🔧 AppConfig - Full Management Tool

### Complete Application Lifecycle Management
- New Application Registration - Guided creation wizard with template-based setup
- Configuration Management - Comprehensive settings management with backup protection
- User Provisioning - Bulk and individual user provisioning with role assignment
- Credential Management - Client secret and certificate generation with expiration tracking
- Backup & Restore - Automatic configuration backups with one-click restoration
- Delete Application - Securely delete applications when no longer needed
- Restore Deleted Application - Recover deleted applications to minimize accidental loss

### Advanced Configuration Features
- App Roles Management - Dynamic role creation with permission mapping
- API Permissions - Interactive Microsoft Graph permission picker
- API Exposure Management - Configure and manage exposed APIs, scopes, and permissions for your applications
- Optional Claims Management - Add and manage optional claims for tokens to customize app authentication and authorization
- Claims Mapping Policies - Visual policy editor with template library
- Directory Extensions - Custom attribute creation and schema management
- Manifest Editor - Direct application manifest editing with validation

## 🔍 AppTesting - Read-Only Analysis Tool

### Comprehensive Testing Without Changes
- Authentication Flow Testing - Complete OAuth2/OIDC flow validation
- Token Analysis - Advanced JWT decoding and claims inspection
- Permission Analysis - Detailed API permission and risk assessment
- Configuration Review - Read-only access to all application settings
- Security Analysis - Comprehensive security posture evaluation

### Compliance-Ready Operation
- Zero Modification Risk - All configuration change functions disabled
- Policy Compliance - Designed for organizations requiring change control
- Safe Exploration - Explore configurations without modification capabilities

### Advanced Analysis Capabilities
- Conditional Access Insights - View applied policies and their impact
- Service Principal Analysis - Comprehensive service principal information
- Permission Risk Scoring - Automated risk assessment of application permissions

## 📊 Reporting

### Reporting Capabilities
- Export Capabilities - CSV exports for security analysis, lifecycle tracking, and compliance
- Dashboard Integration - Embed metrics and reports in custom dashboards

### Security Reporting
- Attack Surface Reports - Detailed vulnerability assessment reports
- Permission Analysis Reports - Comprehensive API permission and risk reports

## 🎯 Specialized Use Cases

### Development Teams
- Development Environment Setup - Quick setup for dev/test environments
- Authentication Testing - Comprehensive flow testing and validation
- Integration Validation - Test API integrations without production impact
- Token Debugging - Advanced token analysis and troubleshooting

### IT Operations
- Application Portfolio Management - Centralized view and management of all applications
- Lifecycle Management - Track application creation, changes, and ownership
- Security Monitoring - Continuous security posture assessment

### Security Teams
- Security Assessment - Comprehensive security review of application configurations
- Attack Surface Analysis - Identify and evaluate potential security vulnerabilities
- Compliance Verification - Verify applications against security policies and standards
- Incident Response - Quick identification and analysis of security issues

### Support Teams
- Advanced Troubleshooting - Comprehensive tools for diagnosing authentication issues
- Configuration Analysis - Deep dive into application configurations
- Issue Resolution - Quick identification and resolution of common issues

## 📈 Performance & Scalability

### Optimized Performance
- Intelligent Caching - Smart caching strategies for improved performance
- Lazy Loading - On-demand loading of components and data
- Batch Operations - Efficient bulk operations for better performance

### Scalability Features
- Large Tenant Support - Optimized for organizations with hundreds of applications
- Efficient Data Loading - Optimized queries and data loading strategies
- Progressive Enhancement - Features load based on user permissions and needs
- Resource Management - Efficient resource utilization and memory management

---

## 🆕 Recent Enhancements

### Dashboard Improvements
- Enhanced Portfolio View - Comprehensive application portfolio management
- Interactive Security Dashboard - Real-time security metrics with drill-down capabilities
- Advanced Filtering - Multi-criteria filtering with saved filter states
- Export Functions - Enhanced CSV export capabilities for reporting

### New Analysis Tools
- Attack Surface Analyzer - Comprehensive security vulnerability assessment
- Application Lifecycle Tracker - Application history and ownership tracking
- Permission Risk Analyzer - Advanced permission analysis with risk scoring

---

> 💡 Need Help? Contact our support team at support@AppConfig.app for assistance with any feature across the AppConfig² Suite.

> 🔄 Feature Updates This guide reflects the latest features in the AppConfig² Suite. New capabilities are added regularly based on user feedback and industry requirements.