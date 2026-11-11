# Awesome-Cloud-Identity-User-Authentication

## Top Cloud Identity & User Authentication Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Single Sign-On, Multi-Factor Authentication & Customer Identity Access Management*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Identity & User Authentication**. These tools help organizations manage user identities, enforce secure authentication, and control access to applications—covering workforce SSO, customer identity (CIAM), passwordless login, MFA, and fine-grained authorization.

---

## Sector Overview & Market Dynamics

The global Identity and Access Management (IAM) market is estimated between **$25.6 billion and $29.7 billion in 2026**, expanding at a compound annual growth rate (CAGR) of 11%–17% toward an anticipated $60+ billion by the early 2030s. The sector is **moderately concentrated** at the enterprise foundation—dominated by cloud and security mega-vendors like Microsoft (Entra ID holding >16% market share) alongside consolidated pillars like Okta, CyberArk, and Ping Identity—while remaining **highly fragmented** across specialized sub-segments such as non-human/machine identity management, Identity Threat Detection and Response (ITDR), developer-first CIAM, and fine-grained authorization (ReBAC/Zanzibar).

---

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## SaaS/Hosted Platforms

| Product | Company Scale (Valuation / Revenue) | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|------------------------------------|-------------|-------------------|--------------------------|
| **[Microsoft Entra ID](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)** | **~$4.0T Market Cap** / ~$245B+ Annual Revenue | Enterprise cloud IAM (formerly Azure AD). Deeply embedded in Microsoft 365 and Azure environments with advanced conditional access and governance. | **$6/user/month** (P1 plan; P2 at $9/user/month) | **Free edition (perpetual)**: Basic directory, user/group management, self-service password reset for cloud apps, and security defaults MFA included with Azure/M365 accounts |
| **[Okta](https://www.okta.com/)** | **~$28B–$30B Market Cap** / ~$3.0B Annual Revenue | Market-leading independent enterprise workforce and customer identity platform supporting hybrid IT, lifecycle management, and Zero Trust. | **$6/user/month** (Workforce Starter; Essentials $17/user/mo; CIAM base from $3,000/mo) | **30-day free trial** (Workforce); no perpetual free tier for workforce (requires $1,500/year contract minimum) |
| **[Auth0](https://auth0.com/)** | **Part of Okta (~$28B–$30B Market Cap)** / Acquired for $6.5B | Developer-first CIAM platform with extensibility via Actions, universal login, B2B Organizations multi-tenancy, and SDKs. | **$35/month** (Essentials plan; includes up to 500 MAU; Professional from $240/month) | **Free Forever**: 25,000 MAU, unlimited logins, standard social connections, and community support with no credit card required |
| **[Freshworks Identity](https://www.freshworks.com/)** | **~$3.2B–$3.5B Market Cap** / ~$900M+ ARR | Identity, SSO, and user lifecycle directory unified across the Freshworks business software suite. | **$19/agent/month** (Freshdesk Growth annual plan; enables custom SSO and SAML) | **Free Forever plan**: 2 agents free on Freshdesk; 14-day full-featured free trial for paid tiers |
| **[Ping Identity](https://www.pingidentity.com/)** | **~$2.8B Acquisition Valuation** / ~$800M ARR | Enterprise-grade hybrid identity federation, intelligent access controls, and customer identity engine (merged with ForgeRock). | **$3/user/month** (PingOne for Workforce Essential tier; CIAM packages starting ~$20,000/year) | **30-day free trial**: Sandbox environment supports up to 1,000 active identities across test environments |
| **[JumpCloud](https://jumpcloud.com/)** | **~$2.6B Valuation** / ~$150M+ ARR | Cloud directory platform unifying device management (MDM for Mac/Windows/Linux), SSO, and conditional access. | **$9/user/month** (Device Management plan; SSO package at $11/user/mo; combined identity + device at $13/user/mo) | **30-day free trial**: Full access to all platform features; standalone feature fair-use trials up to 30 days |
| **[OneLogin](https://www.onelogin.com/)** | **Part of One Identity / Quest (~$5.4B PE Acquisition)** | Enterprise identity and access management platform offering unified SSO, adaptive MFA, and smart user lifecycle provisioning. | **$3/user/month** (Basic plan; Essentials at $6/user/month; Business at $10/user/month) | **30-day free trial**: Full feature evaluation across directory connectors and SSO portals |
| **[Stytch](https://stytch.com/)** | **~$1.0B Peak Valuation** (Acquired by Twilio) | API-first authentication infrastructure for modern web applications and AI agents, specializing in passwordless and passkeys. | **$0 base + usage** ($0.05/MAU after free allowance; B2B SSO starts with 5 included connections) | **Free Forever**: 10,000 monthly active users (MAU), 5 SSO/SCIM connections, 1,000 M2M tokens, and full auth features |
| **[Clerk](https://clerk.com/)** | **~$250M–$330M Valuation** / ~$20M–$30M ARR | Complete user authentication and organization management platform built natively for React, Next.js, and modern full-stack frameworks. | **$25/month** (Pro plan; includes 50,000 MAU + $0.02 per additional MAU; customized Enterprise) | **Free Forever (Hobby)**: 50,000 monthly active users per app, unlimited applications, 3 team dashboard seats, and core authentication |
| **[Descope](https://www.descope.com/)** | **~$250M–$500M Valuation** / $88M Total Funding | Visual drag-and-drop workflow CIAM platform covering passwordless, biometrics, SSO, and machine-to-machine (M2M)/agentic IAM. | **$249/month** (Pro plan; includes 10,000 MAU, 5 SSO connections, and production SLA) | **Free Forever**: 7,500 MAU, 3 SSO connections, 1 OIDC federated app, and 10,000 M2M token exchanges |

---

## Open-Source GitHub Projects

Curated open-source identity providers, authentication engines, and access control platforms sorted by GitHub star count:

| Project | Stars | Description |
|---------|-------|-------------|
| **[Keycloak](https://github.com/keycloak/keycloak)** | [![Stars](https://img.shields.io/github/stars/keycloak/keycloak?style=social&color=white)](https://github.com/keycloak/keycloak/stargazers) | The industry standard open-source IAM solution backed by Red Hat. Comprehensive support for OpenID Connect, SAML 2.0, OAuth 2.0, LDAP federation, user federation, and fine-grained role-based access control. |
| **[Authelia](https://github.com/authelia/authelia)** | [![Stars](https://img.shields.io/github/stars/authelia/authelia?style=social&color=white)](https://github.com/authelia/authelia/stargazers) | Lightweight authentication and authorization server providing two-factor authentication and single sign-on for reverse proxies (Nginx, Traefik, Caddy, Envoy). |
| **[authentik](https://github.com/goauthentik/authentik)** | [![Stars](https://img.shields.io/github/stars/goauthentik/authentik?style=social&color=white)](https://github.com/goauthentik/authentik/stargazers) | Versatile, self-hosted Identity Provider designed for flexibility. Supports OAuth2/OIDC, SAML, LDAP, SCIM, and proxy authentication with an extensible policy engine and modern UI. |
| **[Ory Hydra](https://github.com/ory/hydra)** | [![Stars](https://img.shields.io/github/stars/ory/hydra?style=social&color=white)](https://github.com/ory/hydra/stargazers) | Hardened, OpenID Certified OAuth 2.0 and OpenID Connect (OIDC) engine written in Go. Connects to existing user directories without managing user databases directly. |
| **[ZITADEL](https://github.com/zitadel/zitadel)** | [![Stars](https://img.shields.io/github/stars/zitadel/zitadel?style=social&color=white)](https://github.com/zitadel/zitadel/stargazers) | Modern cloud-native identity platform built with event-sourcing in Go. Features multi-tenancy, turnkey audit trails, B2B self-service organizations, Passkeys, and OIDC/SAML. |
| **[SuperTokens](https://github.com/supertokens/supertokens-core)** | [![Stars](https://img.shields.io/github/stars/supertokens/supertokens-core?style=social&color=white)](https://github.com/supertokens/supertokens-core/stargazers) | Open-source alternative to Auth0 and Firebase Auth. Offers modular recipes for session management, social login, passwordless OTP/magic links, MFA, and user management with pre-built frontend SDKs. |
| **[Logto](https://github.com/logto-io/logto)** | [![Stars](https://img.shields.io/github/stars/logto-io/logto?style=social&color=white)](https://github.com/logto-io/logto/stargazers) | Modern, developer-centric alternative to Auth0 with out-of-the-box sign-in experience, multi-tenant B2B support, Passkey authentication, and webhook automation. |
| **[Casdoor](https://github.com/casdoor/casdoor)** | [![Stars](https://img.shields.io/github/stars/casdoor/casdoor?style=social&color=white)](https://github.com/casdoor/casdoor/stargazers) | UI-first IAM and SSO platform built in Go and React. Supports OAuth 2.0, OIDC, SAML, CAS, LDAP, social log-in providers, and granular permission architectures. |
| **[Ory Kratos](https://github.com/ory/kratos)** | [![Stars](https://img.shields.io/github/stars/ory/kratos?style=social&color=white)](https://github.com/ory/kratos/stargazers) | Headless, API-first identity and user management service. Provides robust authentication, multi-factor authentication (MFA/TOTP/WebAuthn), account verification, and profile management. |
| **[Dex IdP](https://github.com/dexidp/dex)** | [![Stars](https://img.shields.io/github/stars/dexidp/dex?style=social&color=white)](https://github.com/dexidp/dex/stargazers) | Pluggable OpenID Connect (OIDC) identity provider. Acts as an authentication portal that proxies identity requests to upstream providers like LDAP, SAML, GitHub, Google, and GitLab; standard in Kubernetes deployments. |
| **[OpenFGA](https://github.com/openfga/openfga)** | [![Stars](https://img.shields.io/github/stars/openfga/openfga?style=social&color=white)](https://github.com/openfga/openfga/stargazers) | CNCF fine-grained authorization engine inspired by Google Zanzibar. Implements Relationship-Based Access Control (ReBAC) designed for high-throughput, low-latency authorization checks. |
| **[Cerbos](https://github.com/cerbos/cerbos)** | [![Stars](https://img.shields.io/github/stars/cerbos/cerbos?style=social&color=white)](https://github.com/cerbos/cerbos/stargazers) | Lightweight, stateless authorization policy engine. Decouples role- and attribute-based access control (RBAC/ABAC) logic from code using declarative YAML policies. |

---

## How to Contribute

1. Fork the repo.
2. Add/edit entries in [README.md](file:///C:/Users/ishan/Documents/Projects/Awesome-Cloud-Identity-User-Authentication/README.md) (follow existing table schemas and badge formats).
3. Include: name, link, specific pricing/limits or verified GitHub star links, and accurate company scale or open-source descriptions.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

---

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Identity platforms handle sensitive authentication credentials and personal data; enforce MFA, least-privilege access, and compliance with applicable regulations (GDPR, SOC 2, HIPAA where relevant).
- Free tier limits and per-MAU pricing change frequently; model total cost against projected user growth before committing. Self-hosted open-source IAM requires security hardening, regular updates, and backup of identity data.

---

**Made for developers, platform engineers, security architects, and organizations building identity infrastructure.**  
Let's make cloud identity and authentication more open, secure, and cost-predictable.
