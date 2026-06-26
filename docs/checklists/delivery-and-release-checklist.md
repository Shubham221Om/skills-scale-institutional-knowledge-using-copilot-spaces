# Delivery & Release Checklist

Purpose: A compact checklist for Delivery Leads, PMs, and Release Owners to confirm readiness for staging/production.

Pre-release (before staging)
- [ ] Acceptance criteria met for all planned work
- [ ] Unit, integration, and E2E smoke tests passing
- [ ] Security and compliance checks completed (or a documented mitigation exists)
- [ ] Data instrumentation in place for success metrics
- [ ] Release notes drafted and reviewed
- [ ] Rollback/mitigation plan documented

Staging (before production)
- [ ] Deploy to staging and run smoke tests
- [ ] Performance and load checks (if applicable)
- [ ] Observability dashboards and alerts enabled
- [ ] SRE and Platform sign-off for production readiness
- [ ] Stakeholder sign-off received for launch

Production (release window)
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Post-deploy smoke tests passed
- [ ] Monitoring and alerts verified
- [ ] Communication/announcement sent to stakeholders and support
- [ ] Post-release review scheduled

Owners & Contacts
- Delivery Lead:
- Project Manager:
- Product Manager:
- SRE / Platform Contact:
- Security Contact:
