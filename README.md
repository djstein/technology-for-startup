# Technology for Startup

List of Technology to Run a Startup

## Backend

- HTTP API
  - Django https://www.djangoproject.com
  - Graphene https://docs.graphene-python.org/projects/django/en/latest/
- Database Interface
  - Django ORM https://docs.djangoproject.com/en/3.2/topics/db/queries/
- Background Workers
  - Celery https://docs.celeryproject.org/en/stable/getting-started/introduction.html
- Task Scheduling
  - Celery Beat https://github.com/celery/django-celery-beat
- Messaging
  - RabbitMQ https://www.rabbitmq.com
- Websocket Communication
  - Django Channels https://channels.readthedocs.io/en/stable/
- Session Management
  - Django Sessions https://docs.djangoproject.com/en/3.2/topics/http/sessions/
- Interaction Analytics
  - ???
- Logging
  - Django Logging https://docs.djangoproject.com/en/3.2/topics/logging/
- SMTP Server
  - SendGrid https://sendgrid.com

## Frontend

- Content Renderer / Node Differ
  - React https://reactjs.org
- Single Native and Web Codebase
  - React Native + React Native Web
- Generated Typed Backend SDK
  - GraphQL Code Generator https://www.graphql-code-generator.com
- Global State Management
  - React Query https://react-query.tanstack.com
- Server Side Rendering
  - NextJS http://nextjs.org
- Static Asset Caching
  - Vercel CDN
  - Minio https://min.io
- Image Optimization
  - NextJS Image Component https://nextjs.org/docs/api-reference/next/image
- Styles
  - Styled Components https://styled-components.com
- UI Components
  - Hand Build Library
  - Tailwind https://tailwindcss.com
- Web Workers
  - https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Using_web_workers
- Service Worker / Offline Cache
  - https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API
  - with NextJS https://github.com/hanford/next-offline
- Cookie Management
  - JS Cookie https://github.com/js-cookie/js-cookie
- Interaction Analytics
  - Vercel Analytics https://vercel.com/analytics
  - Segment
- Logging
  - ???

## Data Storage

- Relational Database
  - PostgreSQL https://www.postgresql.org
- Relational Database Connection Pooler
  - PgBouncer https://www.pgbouncer.org
- Database Admin Interface
  - Postico https://eggerapps.at/postico/
- Non Relational Database
  - MongoDB https://www.mongodb.com
- In Memory Caching
  - Redis https://redis.io
- Blob File Storage
  - Minio https://min.io

## Networking

- DNS
  - CoreDNS https://kubernetes.io/docs/tasks/access-application-cluster/configure-dns-cluster/
- Load Balancer
  - https://kubernetes.io/docs/concepts/services-networking/
- Static IP Assignment
  - In Cluster Static IP Assignment via ??? (this exists)
- Ingress
  - Traefik https://doc.traefik.io/traefik/providers/kubernetes-ingress/
- SSL
  - Kubernetes Example https://kubernetes.io/docs/tasks/tls/managing-tls-in-a-cluster/

## Authentication and Authorization

- Social Media Authentication
  - ??? OAuth?
- On Prem Authentication
  - hand Rolled?
- Groups
  - ??? OAuth? LDAP?
- Permission
  - ??? OAuth? LDAP?
- No Password Auth
  - Email / SMS Verification? OAuth?
- Token Generation
  - Hand Rolled
- Token Rotation
  - Hand Rolled

## Payments

- Payment Processing
  - Stripe Payments https://stripe.com/payments
  - Stripe Connect https://stripe.com/connect
- Subscriptions
  - Stripe Billing https://stripe.com/billing
- Analytics
  - Stripe Sigma https://stripe.com/sigma
- Fraud
  - Stripe Radar https://stripe.com/radar

## Deployment

- Release Creation
  - GitHub Releases Beta https://github.blog/2021-10-04-beta-github-releases-improving-release-experience/
- Containerization Orchestration
  - Kubernetes https://kubernetes.io
- Image Registry
  - GitHub Packages https://github.com/features/packages
- Package Registry
  - GitHub Packages https://github.com/features/packages

## Integration

- Ephemeral Scheduler
  - Teckton https://tekton.dev
  - GitHub Actions https://github.com/features/actions
- Ephemeral Workers
  - Teckton https://tekton.dev
  - GitHub Actions https://github.com/features/actions
- Frontend Integration Test Runner
  - Selenium Workers https://www.selenium.dev
  - React Testing Library https://testing-library.com/docs/react-testing-library/intro/

## Triage

- Aggregated Log
  - DataDog https://www.datadoghq.com
- Distributed Tracing
  - DataDog + OpenTrace https://www.datadoghq.com/knowledge-center/distributed-tracing/
- Aggregated Error Tracking
  - DataDog Error Tracking https://www.datadoghq.com/blog/error-tracking/
- Realtime Metrics
  - DataDog + Prometheus https://www.datadoghq.com

## Customer Messaging

- Messaging Tracking
  - Custom Database table?
- Text Messaging
  - Twilio https://www.twilio.com
- Email Marketing
  - MailChimp https://mailchimp.com
  - SendGrid https://sendgrid.com
- Social Media Integration
  - Hand Rolled for Twitter / Instagram?

## Design Tools

- Vectors Editing
  - Figma https://www.figma.com
- 3D Modeling:
  - Blender https://www.blender.org
- Asset Creation
  - Adobe Illustrator https://www.adobe.com/products/illustrator.html
- Image Editing
  - Adobe LightRoom https://www.adobe.com/products/photoshop-lightroom.html

## Workflow Tools

- Employee Messaging
  - Slack https://slack.com
- Task Management
  - GitHub Projects Beta https://github.com/features/issues/
- Ticketing
  - GitHub Issues https://github.com/features/issues/
  - Zendesk https://www.zendesk.com
- Expense Reporting
  - Expensify https://www.expensify.com
- Double In/Out Accounting
  - https://stripe.com/atlas/guides/bookkeeping-and-accounting
