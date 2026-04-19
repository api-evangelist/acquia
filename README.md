# Acquia (acquia)
Acquia is a leading provider of digital experience management solutions for organizations looking to enhance their online presence. They offer cloud hosting for Drupal, digital asset management, and content management. The Acquia Cloud API enables programmatic management of Drupal applications, environments, teams, and deployments on the Acquia Cloud Platform.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Content, Experience

## Timestamps

- **Created:** 2025-02-17
- **Modified:** 2026-04-19

## APIs

### Acquia Cloud API
The Acquia Cloud API allows developers to programmatically manage Acquia cloud hosting, automate deployments, manage infrastructure, and deploy Drupal applications. It covers 231 endpoints across applications, environments, organizations, teams, SSH keys, notifications, and Cloud IDEs.

**Human URL:** [https://cloudapi-docs.acquia.com/](https://cloudapi-docs.acquia.com/)

#### Tags:

 - Applications, Cloud, Drupal, Environments, Hosting

#### Properties

- [Documentation](https://cloudapi-docs.acquia.com/)
- [OpenAPI - Applications](openapi/acquia-cloud-applications.yml)
- [OpenAPI - Environments](openapi/acquia-cloud-environments.yml)
- [OpenAPI - Organizations](openapi/acquia-cloud-organizations.yml)
- [OpenAPI - Account](openapi/acquia-cloud-account.yml)
- [OpenAPI - Subscriptions](openapi/acquia-cloud-subscriptions.yml)
- [OpenAPI - Teams and Permissions](openapi/acquia-cloud-teams-and-permissions.yml)
- [NaftikoCapability](capabilities/shared/acquia-cloud-applications.yaml)

---

### Acquia Cloud Site Factory API
Acquia Cloud Site Factory API allows developers to manage, customize, and automate multiple Drupal websites from a centralized platform.

**Human URL:** [https://dev.acquia.com/api-documentation/acquia-cloud-site-factory-api](https://dev.acquia.com/api-documentation/acquia-cloud-site-factory-api)

#### Tags:

 - Cloud, Drupal, Multisite, Site Factory

#### Properties

- [Documentation](https://docs.acquia.com/site-factory/extend/api)

---

### Acquia Content Hub API
The Acquia Content Hub API enables distribution and synchronization of Drupal content across multiple sites and digital channels.

**Human URL:** [https://dev.acquia.com/api-documentation/acquia-content-hub-api](https://dev.acquia.com/api-documentation/acquia-content-hub-api)

#### Tags:

 - Content, Content Hub, Drupal, Syndication

#### Properties

- [Documentation](https://docs.acquia.com/drupal-starter-kits/add-ons/content-hub/api)

## Common Properties

- [Portal](https://dev.acquia.com/)
- [Tutorials](https://dev.acquia.com/tutorial)
- [Support](https://docs.acquia.com/service-offerings/support/support-users-guide#contacting-acquia-support)
- [StatusPage](https://status.acquia.com/)
- [Blog](https://www.acquia.com/blog)
- [Partners](https://www.acquia.com/partners)
- [GitHubOrganization](https://github.com/acquia)
- [CLI - Acquia CLI](https://github.com/acquia/cli)

## Features

| Name | Description |
|------|-------------|
| Cloud Hosting | Managed Drupal hosting on Acquia Cloud with auto-scaling, CDN, and DDoS protection. |
| Application Management | Programmatic management of Drupal applications, environments, and deployments via Cloud API. |
| Multi-Site Factory | Acquia Cloud Site Factory for managing hundreds of Drupal sites from a centralized platform. |
| Content Syndication | Acquia Content Hub for distributing and synchronizing Drupal content across multiple sites. |
| Cloud IDE | Browser-based Cloud IDE for remote Drupal development with pre-configured environments. |
| OAuth2 Authentication | Secure API access via OAuth2 authorization code flow with scoped tokens. |

## Use Cases

| Name | Description |
|------|-------------|
| Automated Deployment Pipelines | Integrate Acquia Cloud API into CI/CD pipelines for automated code deployment and cache clearing. |
| Multi-Environment Management | Manage dev, staging, and production Drupal environments programmatically. |
| Platform Administration | Automate team provisioning, SSH key management, and organizational access control. |
| Content Distribution | Use Content Hub API to distribute content across a network of Drupal sites. |
| Headless Drupal | Manage decoupled Drupal applications with Next.js or other frontend frameworks via Acquia APIs. |

## Integrations

| Name | Description |
|------|-------------|
| Drupal CMS | Native Drupal module integrations for Acquia Cloud, Content Hub, and Site Studio. |
| GitHub Actions | GitHub Actions workflows for Acquia Cloud deployment automation using Acquia CLI. |
| Next.js | Headless Drupal with Next.js using Acquia CMS headless starter kit. |
| Acquia DAM | Digital Asset Management integration via Widen Collective for media management in Drupal. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Acquia Cloud API Full](openapi/acquia-cloud-openapi-full.yml)
- [Acquia Cloud - Account](openapi/acquia-cloud-account.yml)
- [Acquia Cloud - Agreements](openapi/acquia-cloud-agreements.yml)
- [Acquia Cloud - Application Performance Monitoring](openapi/acquia-cloud-application-performance-monitoring-services.yml)
- [Acquia Cloud - Applications](openapi/acquia-cloud-applications.yml)
- [Acquia Cloud - Cloud IDE](openapi/acquia-cloud-cloud-ide.yml)
- [Acquia Cloud - Codebases](openapi/acquia-cloud-codebases.yml)
- [Acquia Cloud - Distributions](openapi/acquia-cloud-distributions.yml)
- [Acquia Cloud - Email](openapi/acquia-cloud-email.yml)
- [Acquia Cloud - Environments](openapi/acquia-cloud-environments.yml)
- [Acquia Cloud - Identity Providers](openapi/acquia-cloud-identity-providers.yml)
- [Acquia Cloud - Invite](openapi/acquia-cloud-invite.yml)
- [Acquia Cloud - Messages](openapi/acquia-cloud-messages.yml)
- [Acquia Cloud - Notifications](openapi/acquia-cloud-notifications.yml)
- [Acquia Cloud - Options](openapi/acquia-cloud-options.yml)
- [Acquia Cloud - Organizations](openapi/acquia-cloud-organizations.yml)
- [Acquia Cloud - Private Networks](openapi/acquia-cloud-private-networks.yml)
- [Acquia Cloud - Subscriptions](openapi/acquia-cloud-subscriptions.yml)
- [Acquia Cloud - Teams and Permissions](openapi/acquia-cloud-teams-and-permissions.yml)

### JSON Schema

- [Application Schema](json-schema/acquia-cloud-application-schema.json)
- [Environment Schema](json-schema/acquia-cloud-environment-schema.json)
- [Organization Schema](json-schema/acquia-cloud-organization-schema.json)
- [User Schema](json-schema/acquia-cloud-user-schema.json)
- [Subscription Schema](json-schema/acquia-cloud-subscription-schema.json)
- [Team Schema](json-schema/acquia-cloud-team-schema.json)
- [SSH Key Schema](json-schema/acquia-cloud-ssh-key-schema.json)
- [Notification Schema](json-schema/acquia-cloud-notification-schema.json)

### JSON Structure

- [Application Structure](json-structure/acquia-cloud-application-structure.json)
- [Environment Structure](json-structure/acquia-cloud-environment-structure.json)
- [Organization Structure](json-structure/acquia-cloud-organization-structure.json)

### JSON-LD

- [Acquia Context](json-ld/acquia-context.jsonld)

### Examples

- [Application Example](examples/acquia-cloud-application-example.json)
- [Environment Example](examples/acquia-cloud-environment-example.json)
- [User Example](examples/acquia-cloud-user-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Acquia Cloud Applications](capabilities/shared/acquia-cloud-applications.yaml) — 5 operations for application and environment management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Drupal Application Management](capabilities/drupal-application-management.yaml) | Acquia Cloud | 6 | Drupal Developer, DevOps Engineer, Platform Administrator |

## Vocabulary

- [Acquia Vocabulary](vocabulary/acquia-vocabulary.yaml) — Unified taxonomy mapping 8 resources, 8 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Acquia Spectral Rules](rules/acquia-spectral-rules.yml) — 30+ rules across 13 categories enforcing Acquia Cloud API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
