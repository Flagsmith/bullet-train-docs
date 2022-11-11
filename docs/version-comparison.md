---
sidebar_position: 3
---

# Version Comparison

You are free to run the Open Source version of Flagsmith however you see fit! There are some differences between the
Open Source, SaaS hosted and Enterprise versions:

- The Open Source version has **no** API request or Identity limits - you can run as many API instances in a cluster as
  you wish.
- The Open Source version has **no** Dashboard User limits - you can have as many team members as you wish.
- The SaaS and Enterprise versions have [Change Requests and Flag Scheduling](advanced-use/change-requests.md).
- The SaaS and Enterprise versions have [Role-Based Access Controls](advanced-use/permissions.md).
- The SaaS and Enterprise versions have additional [Authentication Providers](/deployment/enterprise-edition).

## SaaS Benefits

Our SaaS platform has a number of benefits:

- You can get up and running right away.
- Our global [Edge API](advanced-use/edge-api.md) provides global low latency flags. We aim to serve all flag requests
  in < 150ms, globally.
- Get real-time flag updates to your clients, the moment they are changed in the dashboard.

### SaaS Architecture

![Image](/img/saas-architecture.svg)

## Enterprise Benefits

You can run our Enterprise version either on-premise, or we can provide private cloud instance dedicated to your
organisation.

- [Role Based Access Controls](advanced-use/permissions.md).
- [SAML, LDAP, ADFS and Okta authentication](deployment/authentication.md), as well as the ability to lock
  authentication to a single provider.
- Additional database engines: Oracle, SQL Server and MySQL.
- Additional deployment and orchestration options as detailed below.

## Open Source Benefits

- Completely Free!
- The Open Source version has **no** API request or Identity limits - you can run as many API instances in a cluster as
  you wish.
- The Open Source version has **no** Dashboard User limits - you can have as many team members as you wish.
- Deploy with one click to a number of different [IaaS and PaaS providers](deployment/overview#one-click-installers).
