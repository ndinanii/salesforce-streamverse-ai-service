# Knowledge Data Categories

## Category Group: Support Topics

**Purpose:** Structure Knowledge articles to align with Case Classification categories and control visibility on the Experience Site.

### Category Structure

```
Support Topics (Support_Topics)
├── Billing
├── Technical
├── Retention Policy (Retention_Policy)
└── General FAQ (General_FAQ)
```

### Categories Description

| Category | API Name | Purpose |
|----------|----------|---------|
| Billing | Billing | Articles related to billing, payments, invoices, and account charges |
| Technical | Technical | Technical troubleshooting, system issues, and product functionality |
| Retention Policy | Retention_Policy | Articles designed to prevent churn and address customer retention concerns |
| General FAQ | General_FAQ | High-volume, simple articles like password resets and basic navigation |

### Visibility Settings

#### Guest User Profile (Public Portal)
All categories set to **Visible (V)** to enable customer self-service deflection:
- ✓ Billing
- ✓ Technical
- ✓ Retention_Policy
- ✓ General_FAQ

#### Service Agent Profile
All categories set to **Visible (V)** for full access to support content.

### Integration Points

**Phase 1 - Deflection:** Guest users search only visible categories for self-service.

**Phase 2 - Intelligent Triage:** Case classification values match category names, enabling context-aware article suggestions for agents.

**Security Principle:** Least Privilege - Only public-facing articles are exposed to unauthenticated users.

