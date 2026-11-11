# Awesome-Cloud-Identity-User-Authentication

## Top Cloud Identity & User Authentication Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Single Sign-On, Multi-Factor Authentication & Customer Identity Access Management*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Identity & User Authentication**. These tools help organizations manage user identities, enforce secure authentication, and control access to applications—covering workforce SSO, customer identity (CIAM), passwordless login, MFA, and fine-grained authorization.

**Examples** include Okta, Microsoft Entra ID, Auth0, Ping Identity, JumpCloud, OneLogin, Stytch, Clerk, Descope, and Freshworks Identity (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted identity providers, open-source authentication servers, and community-driven IAM platforms—ideal for developers, platform engineers, and organizations seeking transparent, vendor-neutral identity infrastructure without per-MAU pricing cliffs.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Okta](https://www.okta.com/)** | Enterprise workforce and customer identity platform. Workforce Identity sold as per-user suites (Starter, Essentials, Professional, Enterprise). Customer Identity requires Enterprise base platform plus B2C/B2B suites . | Workforce Starter: $6/user/month (annual); Essentials: $17/user/month; Customer Identity base: $3,000/month (annual) | No free tier for workforce; $1,500 annual contract minimum; trial available via sales |
| **[Microsoft Entra ID](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)** | Microsoft's cloud IAM (formerly Azure AD). Free edition included with Azure/M365 subscriptions; P1 adds Conditional Access, SSPR, hybrid identity; P2 adds Identity Protection and PIM . | P1: $6/user/month; P2: $9/user/month | **Free edition**: basic directory, user/group management, security defaults MFA, included with Azure/M365 subscriptions  |
| **[Auth0](https://auth0.com/)** | Developer-first CIAM platform with extensibility via Actions, Organizations for B2B multi-tenancy, and broad SDK coverage. Acquired by Okta but operates as separate product line . | Essentials: $35/month (up to 500 MAU); Professional: $240/month (up to 1,000 MAU); Enterprise: ~$30,000/year  | **Free tier**: ~25,000 MAU, unlimited logins, no credit card required  |
| **[Ping Identity](https://www.pingidentity.com/)** | Enterprise identity platform for workforce and customer IAM with strong federation and API security capabilities. | Quote-only (enterprise contract) | Trial via sales; no self-serve free tier |
| **[JumpCloud](https://jumpcloud.com/)** | Directory platform combining identity, device management, and access control. Popular for MSPs and mid-market organizations managing hybrid workforces. | Quote-only (per-user, per-device pricing) | Free trial available; free tier for up to 10 users (limited features) |
| **[OneLogin](https://www.onelogin.com/)** | Cloud-based SSO and identity management (now part of One Identity). Role-based app access provisioning and directory integration. | Quote-only (per-user pricing) | Free trial available; no permanent free tier |
| **[Stytch](https://stytch.com/)** | API-first authentication platform with passwordless, OAuth, SSO, and fraud prevention. Pricing includes generous free MAU allowance and transparent overages . | Pay-as-you-go; base $0/month with 10,000 free MAU | **Always free**: 10,000 MAU, 5 SSO/SCIM connections, 1,000 M2M tokens, full authn/authz features  |
| **[Clerk](https://clerk.com/)** | Drop-in authentication and user management for React/Next.js with prebuilt UI components, B2B Organizations, and billing integration . | Pro: $25/month (50,000 included users per app, $0.02/mo each additional); Business: higher tier | **Hobby (free)**: 50,000 users per app, unlimited applications, 3 dashboard seats, core auth features  |
| **[Descope](https://www.descope.com/)** | No-code/low-code CIAM with visual workflow builder, passwordless, SSO, and M2M/agentic identity support . | Pro: starts at $249/month (10,000 MAU, 5 SSO connections) | **Free Forever**: 7,500 MAU, 3 SSO connections, 1 OIDC federated app, 10,000 M2M exchanges, 99% SLA  |
| **[Freshworks Identity](https://www.freshworks.com/)** | Identity and SSO capabilities within the Freshworks ecosystem (Freshdesk, Freshservice, Freshsales). SSO available on Growth, Pro, and Enterprise plans . | Freshdesk Growth: $19/agent/month (annual) | Free plan for Freshdesk (1–2 agents, 6 months); trial available for paid tiers |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Keycloak](https://github.com/keycloak/keycloak)** | [![Stars](https://img.shields.io/github/stars/keycloak/keycloak?style=social&color=white)](https://github.com/keycloak/keycloak/stargazers) | The most widely adopted open-source IAM solution. Supports OIDC, SAML, OAuth 2.0, LDAP, and social login with RBAC and fine-grained admin permissions. Backed by Red Hat; self-hosted or managed via third parties. |
| **[ZITADEL](https://github.com/zitadel/zitadel)** | [![Stars](https://img.shields.io/github/stars/zitadel/zitadel?style=social&color=white)](https://github.com/zitadel/zitadel/stargazers) | Event-sourced identity platform with OIDC, SAML, and RBAC. Provides audit trails, multi-instance isolation, and a modern API-first architecture. |
| **[Casdoor](https://github.com/casdoor/casdoor)** | [![Stars](https://img.shields.io/github/stars/casdoor/casdoor?style=social&color=white)](https://github.com/casdoor/casdoor/stargazers) | Open-source IAM/SSO platform with web UI supporting OAuth 2.0, OIDC, SAML, CAS, LDAP, and RBAC. Multi-tenancy via organizations. |
| **[SuperTokens](https://github.com/supertokens/supertokens-core)** | [![Stars](https://img.shields.io/github/stars/supertokens/supertokens-core?style=social&color=white)](https://github.com/supertokens/supertokens-core/stargazers) | Open-source authentication with email/password, social login, passwordless, and session management. Self-hosted or managed cloud; positioned as an Auth0 alternative with predictable pricing. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Ory Kratos](https://github.com/ory/kratos)** | [![Stars](https://img.shields.io/github/stars/ory/kratos?style=social&color=white)](https://github.com/ory/kratos/stargazers) | API-first identity server with MFA, passwordless, social login, and OIDC. Designed for cloud-native deployments; part of the Ory ecosystem (Keto, Hydra, Oathkeeper). |
| **[Authelia](https://github.com/authelia/authelia)** | [![Stars](https://img.shields.io/github/stars/authelia/authelia?style=social&color=white)](https://github.com/authelia/authelia/stargazers) | Lightweight SSO and 2FA portal for self-hosted applications. Integrates with reverse proxies (Traefik, Nginx) for authentication enforcement. |
| **[OpenFGA](https://github.com/openfga/openfga)** | [![Stars](https://img.shields.io/github/stars/openfga/openfga?style=social&color=white)](https://github.com/openfga/openfga/stargazers) | Fine-grained authorization inspired by Google Zanzibar. CNCF project; complements identity providers with relationship-based access control. |

**Frameworks for building custom systems**: Combine **Keycloak** or **ZITADEL** for core identity and SSO, **Ory Kratos** for API-first authentication, **OpenFGA** for fine-grained authorization, and **Authelia** for lightweight self-hosted SSO—deployable via Docker Compose or Kubernetes.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Identity platforms handle authentication credentials and personal data; enforce MFA, least-privilege access, and compliance with applicable regulations (GDPR, SOC 2, HIPAA where relevant).
- Free tier limits and per-MAU pricing change frequently; model total cost against projected user growth before committing. Self-hosted open-source IAM requires security hardening, regular updates, and backup of identity data.

---

**Made for developers, platform engineers, security architects, and organizations building identity infrastructure.**  
Let's make cloud identity and authentication more open, secure, and cost-predictable.
