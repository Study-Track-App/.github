# Study-Track

Study productivity tools for students who want to plan better, track their work, and understand their progress.

[study-track.app](https://study-track.app) · [Documentation](https://github.com/Study-Track-App/Study-Track-Docs)

## About Study-Track

Study-Track is a higher-education study and productivity platform built around a simple idea: students should be able to see where their time goes and turn that information into better planning.

The product combines study-time tracking, weekly and daily planning, deadlines, analytics, calendar tooling, gamification, social features, and Premium functionality across web and mobile experiences.

## Repositories

| Repository | Purpose |
|---|---|
| [`flodlol/Study-Track`](https://github.com/flodlol/Study-Track) | Primary Study-Track application, backend, mobile app, and admin tooling |
| [`Study-Track-App/Study-Track-Docs`](https://github.com/Study-Track-App/Study-Track-Docs) | Canonical product, technical, business, legal, and operational documentation |
| [`Study-Track-App/Study-Track-API`](https://github.com/Study-Track-App/Study-Track-API) | Dedicated API work |
| [`Study-Track-App/Study-Track-Hardware`](https://github.com/Study-Track-App/Study-Track-Hardware) | Hardware and device-integration experiments |
| [`flodlol/Study-Track-Admin-Discord-Bot`](https://github.com/flodlol/Study-Track-Admin-Discord-Bot) | Analytics, reporting, charting, and growth-intelligence pipeline |

## Documentation

Cross-repository documentation is maintained in [`Study-Track-App/Study-Track-Docs`](https://github.com/Study-Track-App/Study-Track-Docs).

Useful entry points:

- [Repository map](https://github.com/Study-Track-App/Study-Track-Docs/blob/main/repositories/README.md)
- [Product overview](https://github.com/Study-Track-App/Study-Track-Docs/blob/main/product/overview.md)
- [Features](https://github.com/Study-Track-App/Study-Track-Docs/tree/main/features)
- [System architecture](https://github.com/Study-Track-App/Study-Track-Docs/blob/main/architecture/system-overview.md)
- [Infrastructure](https://github.com/Study-Track-App/Study-Track-Docs/tree/main/infrastructure)
- [Integrations](https://github.com/Study-Track-App/Study-Track-Docs/tree/main/integrations)
- [Analytics](https://github.com/Study-Track-App/Study-Track-Docs/tree/main/analytics)
- [Design](https://github.com/Study-Track-App/Study-Track-Docs/tree/main/design)
- [Engineering](https://github.com/Study-Track-App/Study-Track-Docs/tree/main/engineering)
- [Operations](https://github.com/Study-Track-App/Study-Track-Docs/tree/main/operations)

## Technology

Study-Track currently uses React and Vite for the primary web application, Firebase and Google Cloud for backend services and data, Netlify for web delivery, Stripe and RevenueCat for billing, Cloudinary for media, Resend for transactional email, and GA4 for product analytics.

The platform also includes native mobile work, internal admin tooling, automated reporting, and integrations with external calendar and productivity systems.

## Engineering principles

We keep repository-specific setup close to the code and shared product or architecture knowledge in the canonical documentation repository.

Documentation-worthy changes should update `Study-Track-Docs` in the same workstream so product behavior, architecture, infrastructure, analytics, business rules, and operational knowledge stay synchronized with implementation.

## Product

Study-Track is available at [study-track.app](https://study-track.app).
