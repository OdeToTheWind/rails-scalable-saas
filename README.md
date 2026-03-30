# rails-scalable-saas

[![Ruby](https://img.shields.io/badge/Ruby-3.3%2B-red.svg)](https://www.ruby-lang.org)
[![Rails](https://img.shields.io/badge/Rails-7.2%2B%20%7C%208.0+-CC0000.svg)](https://rubyonrails.org)
[![CI - Lint & Test](https://github.com/OdeToTheWind/rails-scalable-saas/actions/workflows/tests.yml/badge.svg)](https://github.com/OdeToTheWind/rails-scalable-saas/actions)
[![CI - RuboCop](https://github.com/OdeToTheWind/rails-scalable-saas/actions/workflows/lint.yml/badge.svg)](https://github.com/OdeToTheWind/rails-scalable-saas/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Progress](https://img.shields.io/badge/Progress-0%2F100%20demos-blue.svg)](https://github.com/OdeToTheWind/rails-scalable-saas/tree/main/docs/progress)

**100 progressive demos to master scalable SaaS development with Ruby on Rails.**

---

## Overview

**rails-scalable-saas** is a structured, production-grade learning and showcase repository containing **100 carefully designed demos**.

It follows a clear progression:

- **Beginner (01-25)**: Core Rails fundamentals and basic SaaS MVPs
- **Intermediate (26-50)**: Hotwire, background jobs, payments, caching, and multi-tenancy basics
- **Advanced (51-75)**: Full scaling patterns, Docker/Kamal, observability, complex architectures
- **Real-World (76-100)**: Complete end-to-end SaaS applications with production-ready implementations

Built to help you **learn deeply and outperform** by mastering modern Rails tooling, scalability patterns, and real-world SaaS engineering practices used by companies like Shopify and Basecamp.

## Why This Repository?

- Progressive difficulty that builds real expertise
- Emphasis on **scalability** (multi-tenancy, caching, jobs, horizontal scaling, monitoring)
- Reproducible structure with shared components, GitHub Actions, and documentation
- Focus on modern stack: Hotwire (Turbo + Stimulus), Solid Queue / Sidekiq, PostgreSQL, Docker, Kamal, Stripe, etc.
- Professional engineering practices: testing, linting, auditing, zero-downtime deploys
- Designed for developers who want to go beyond tutorials and build production-grade SaaS products

## Repository Structure

```bash
rails-scalable-saas/
├── .github/
│   └── workflows/          # CI: lint.yml & tests.yml
├── docs/
│   ├── progress/           # Detailed docs for each demo_01.md → demo_100.md
│   └── architecture/       # scaling_patterns.md, db_schema_design.md, etc.
├── demos/
│   ├── beginner/           # Demos 01-25
│   ├── intermediate/       # Demos 26-50
│   ├── advanced/           # Demos 51-75
│   └── real-world/         # Demos 76-100
├── scripts/
│   └── bootstrap_demo.sh   # Helper to create new demos
├── shared/                 # Reusable logic
│   ├── gems/               # Internal private gems
│   └── docker/             # Common Dockerfiles & Compose configs
├── package.json            # (Optional) Frontend asset workspaces
├── README.md
├── LICENSE
└── .gitignore
```

## Daily Progress

Track your 100-day deliberate practice journey. One demo per day.

| Day | Project / Topic                                      | Level          | Status     | Key Learnings / Deliverables |
|-----|------------------------------------------------------|----------------|------------|---------------------------------------------------------------------------------------------|
| 01  | Basic User Signup & Dashboard SaaS                   | Beginner       | ⏳ Planned | Rails setup, scaffolding, Devise authentication, simple dashboard |
| 02  | Todo List SaaS for Teams                             | Beginner       | ⏳ Planned | CRUD operations, User has_many Tasks associations |
| 03  | Simple Blog SaaS with Posts                          | Beginner       | ⏳ Planned | Action View, forms, validations |
| 04  | Invoice Generator MVP                                | Beginner       | ⏳ Planned | PDF generation with Prawn, Action Mailer |
| 05  | Project Tracker Basic                                | Beginner       | ⏳ Planned | Nested resources, basic authorization |
| 06  | Client CRM Starter                                   | Beginner       | ⏳ Planned | Search with Ransack, pagination with Pagy |
| 07  | Subscription Landing Page                            | Beginner       | ⏳ Planned | Static pages, Tailwind CSS integration |
| 08  | Feedback Form SaaS                                   | Beginner       | ⏳ Planned | File uploads with Active Storage |
| 09  | Simple Analytics Dashboard                           | Beginner       | ⏳ Planned | Basic charts with Chartkick |
| 10  | User Profile SaaS                                    | Beginner       | ⏳ Planned | Avatar uploads, user settings |
| 11  | Calendar Scheduler Basic                             | Beginner       | ⏳ Planned | Date handling and simple pickers |
| 12  | Team Invite System Starter                           | Beginner       | ⏳ Planned | Mailer previews, invitations |
| 13  | Expense Tracker MVP                                  | Beginner       | ⏳ Planned | Money gem for currency handling |
| 14  | Knowledge Base Articles                              | Beginner       | ⏳ Planned | Markdown rendering |
| 15  | Basic API for SaaS Clients                           | Beginner       | ⏳ Planned | JSON rendering, API controllers |
| 16  | Notification Center                                  | Beginner       | ⏳ Planned | Polymorphic notifications |
| 17  | File Sharing SaaS                                    | Beginner       | ⏳ Planned | Active Storage variants |
| 18  | Simple Forum SaaS                                    | Beginner       | ⏳ Planned | Threaded comments |
| 19  | Onboarding Checklist                                 | Beginner       | ⏳ Planned | Wizard forms with Wicked |
| 20  | Basic Billing Overview                               | Beginner       | ⏳ Planned | Static pricing tables |
| 21  | Task Board Kanban Lite                               | Beginner       | ⏳ Planned | Basic drag-and-drop with Stimulus |
| 22  | User Activity Log                                    | Beginner       | ⏳ Planned | Paper Trail auditing |
| 23  | Simple Search SaaS                                   | Beginner       | ⏳ Planned | Full-text search with pg_search |
| 24  | Dashboard Metrics Cards                              | Beginner       | ⏳ Planned | Counter caches |
| 25  | Multi-Page SaaS Landing                              | Beginner       | ⏳ Planned | Internationalization (I18n) basics |
| 26  | Real-time Todo SaaS                                  | Intermediate   | ⏳ Planned | Turbo Streams, Stimulus controllers |
| 27  | Invoice SaaS with Background PDF                     | Intermediate   | ⏳ Planned | Active Job + Solid Queue/Sidekiq, async processing |
| 28  | Subscription Management                              | Intermediate   | ⏳ Planned | Stripe Checkout & Webhooks |
| 29  | Project Management with Teams                        | Intermediate   | ⏳ Planned | Pundit authorization, role-based access |
| 30  | Client Portal with File Uploads                      | Intermediate   | ⏳ Planned | Active Storage direct uploads |
| 31  | Analytics with Caching                               | Intermediate   | ⏳ Planned | Rails caching strategies with Redis/Solid Cache |
| 32  | Email Campaign Builder                               | Intermediate   | ⏳ Planned | Action Mailer + bulk jobs |
| 33  | Calendar with Turbo                                  | Intermediate   | ⏳ Planned | Turbo Frames for partial updates |
| 34  | Multi-Step Onboarding                                | Intermediate   | ⏳ Planned | Hotwire-driven wizards |
| 35  | Expense Reports with Exports                         | Intermediate   | ⏳ Planned | Background CSV/Excel exports |
| 36  | Basic Multi-Tenancy (Row-level)                      | Intermediate   | ⏳ Planned | ActsAsTenant gem, query scoping |
| 37  | Notification System Real-time                        | Intermediate   | ⏳ Planned | Turbo Streams + Action Cable |
| 38  | Search with Autocomplete                             | Intermediate   | ⏳ Planned | Stimulus + Turbo autocomplete |
| 39  | Billing Dashboard                                    | Intermediate   | ⏳ Planned | Stripe Billing Portal integration |
| 40  | Team Collaboration Board                             | Intermediate   | ⏳ Planned | Optimistic UI with Turbo |
| 41  | API Rate Limiting                                    | Intermediate   | ⏳ Planned | Rack::Attack usage in SaaS APIs |
| 42  | Document Signing Flow                                | Intermediate   | ⏳ Planned | PDF processing with background jobs |
| 43  | User Impersonation                                   | Intermediate   | ⏳ Planned | Devise + admin impersonation |
| 44  | Caching Strategies                                   | Intermediate   | ⏳ Planned | Russian Doll caching & invalidation |
| 45  | Background Job Monitoring                            | Intermediate   | ⏳ Planned | Sidekiq Web / Mission Control |
| 46  | Feature Flags                                        | Intermediate   | ⏳ Planned | Flipper gem rollout strategies |
| 47  | Audit Logging Advanced                               | Intermediate   | ⏳ Planned | Paper Trail with custom callbacks |
| 48  | Multi-DB Setup Basics                                | Intermediate   | ⏳ Planned | Multiple databases & read replicas |
| 49  | Hotwire-powered Chat Lite                            | Intermediate   | ⏳ Planned | Turbo + Stimulus real-time chat |
| 50  | SaaS Metrics Tracking                                | Intermediate   | ⏳ Planned | Custom instrumentation |
| 51  | Full Multi-Tenant SaaS (Schema Isolation)            | Advanced       | ⏳ Planned | Database-per-tenant, job & cache scoping |
| 52  | Scalable Invoice SaaS                                | Advanced       | ⏳ Planned | Sidekiq batches, horizontal scaling with Puma |
| 53  | Real-time Collaboration Platform                     | Advanced       | ⏳ Planned | Action Cable + Turbo Streams at scale |
| 54  | Subscription SaaS with Usage-Based Billing           | Advanced       | ⏳ Planned | Stripe Metered billing & revenue analytics |
| 55  | Advanced Analytics Engine                            | Advanced       | ⏳ Planned | Materialized views in PostgreSQL |
| 56  | Enterprise Project Management                        | Advanced       | ⏳ Planned | Complex permissions with nested sets |
| 57  | AI-Assisted SaaS Features                            | Advanced       | ⏳ Planned | External AI API integration via jobs |
| 58  | High-Performance Search                              | Advanced       | ⏳ Planned | Elasticsearch / Meilisearch indexing |
| 59  | Dockerized Multi-Service SaaS                        | Advanced       | ⏳ Planned | Docker Compose + Kamal deployment |
| 60  | CI/CD Pipeline Full                                  | Advanced       | ⏳ Planned | GitHub Actions with parallel testing |
| 61  | Advanced Caching & Performance                       | Advanced       | ⏳ Planned | Solid Cache + query optimization |
| 62  | Background Job Patterns at Scale                     | Advanced       | ⏳ Planned | Nested workers, priority queues |
| 63  | Secure Multi-Tenant API                              | Advanced       | ⏳ Planned | OAuth + tenant scoping |
| 64  | Real-time Dashboards                                 | Advanced       | ⏳ Planned | Turbo + WebSockets with fallbacks |
| 65  | Audit & Compliance Logging                           | Advanced       | ⏳ Planned | Full audit trails & export jobs |
| 66  | Microservices Communication in Rails                 | Advanced       | ⏳ Planned | API-only engines + shared gems |
| 67  | Advanced Payments & Invoicing                        | Advanced       | ⏳ Planned | Stripe Connect for marketplaces |
| 68  | Scalable File Processing                             | Advanced       | ⏳ Planned | Active Storage + background variants |
| 69  | Feature-Rich Admin Panel                             | Advanced       | ⏳ Planned | Avo or custom advanced admin |
| 70  | Database Sharding Basics                             | Advanced       | ⏳ Planned | Multi-schema scaling patterns |
| 71  | Observability & Monitoring                           | Advanced       | ⏳ Planned | Sentry / Prometheus integration |
| 72  | Zero-Downtime Deployments                            | Advanced       | ⏳ Planned | Kamal Blue-Green deployment |
| 73  | Advanced Multi-Tenancy (Hybrid)                      | Advanced       | ⏳ Planned | Row + schema hybrid isolation |
| 74  | Performance Benchmarking                             | Advanced       | ⏳ Planned | RubyProf, rack-mini-profiler, YJIT |
| 75  | Full SaaS Boilerplate                                | Advanced       | ⏳ Planned | All tools combined |
| 76  | Complete Project Management SaaS                     | Real-World     | ⏳ Planned | Multi-tenancy + real-time + subscriptions + scaling |
| 77  | Invoicing & Billing Platform                         | Real-World     | ⏳ Planned | Payments, webhooks, analytics, Docker deploy |
| 78  | Client CRM SaaS                                      | Real-World     | ⏳ Planned | Teams, files, notifications, performance |
| 79  | Knowledge Base + Support SaaS                        | Real-World     | ⏳ Planned | Search, AI hints, CI/CD |
| 80  | Collaboration Workspace SaaS                         | Real-World     | ⏳ Planned | Chat, tasks, docs, horizontal scaling |
| 81  | Learning Management SaaS                             | Real-World     | ⏳ Planned | Video uploads, payments, progress tracking |
| 82  | Marketplace SaaS (Stripe Connect)                    | Real-World     | ⏳ Planned | Vendor onboarding, payouts, tenancy |
| 83  | Analytics & Reporting SaaS                           | Real-World     | ⏳ Planned | Data pipelines, caching, exports |
| 84  | Task Automation SaaS                                 | Real-World     | ⏳ Planned | Workflows, background jobs at scale |
| 85  | HR & Team Management SaaS                            | Real-World     | ⏳ Planned | Onboarding, compliance |
| 86  | E-commerce Backend SaaS                              | Real-World     | ⏳ Planned | Products, orders, inventory scaling |
| 87  | Real-time Communication SaaS                         | Real-World     | ⏳ Planned | Chat scaling with Action Cable |
| 88  | Document Management SaaS                             | Real-World     | ⏳ Planned | Signing, versioning, secure storage |
| 89  | Event & Booking SaaS                                 | Real-World     | ⏳ Planned | Calendars, payments, multi-tenant |
| 90  | Finance Tracker SaaS                                 | Real-World     | ⏳ Planned | Transactions, reports, bank sync |
| 91  | Content Creation SaaS                                | Real-World     | ⏳ Planned | Editor, exports, collaboration |
| 92  | Customer Support Portal SaaS                         | Real-World     | ⏳ Planned | Tickets, knowledge base, real-time |
| 93  | Inventory Management SaaS                            | Real-World     | ⏳ Planned | Multi-location, dashboards |
| 94  | Marketing Automation SaaS                            | Real-World     | ⏳ Planned | Campaigns, analytics, integrations |
| 95  | Healthcare Lite SaaS                                 | Real-World     | ⏳ Planned | Compliance, secure tenancy, audits |
| 96  | Freelancer Platform SaaS                             | Real-World     | ⏳ Planned | Proposals, contracts, payments |
| 97  | Scaled Monitoring SaaS                               | Real-World     | ⏳ Planned | Metrics, alerts, observability |
| 98  | AI-Enhanced Productivity SaaS                        | Real-World     | ⏳ Planned | Integrations, jobs, caching |
| 99  | Enterprise-Grade Boilerplate SaaS                    | Real-World     | ⏳ Planned | All advanced features + deployment |
| 100 | Capstone Scalable SaaS Clone (Basecamp-inspired)     | Real-World     | ⏳ Planned | Complete production-scale implementation with all tools |

---

## Backend Tech Stack & Deployment Strategy

**Core Stack**
- Ruby 3.3+
- Ruby on Rails 7.2+ / 8.0 (Hotwire-first)
- PostgreSQL (with pg_search, JSONB, materialized views)
- Redis (Solid Queue / Sidekiq, Solid Cache)
- Hotwire: Turbo + Stimulus + Tailwind CSS
- Authentication: Devise + Pundit
- Payments: Stripe (Checkout, Billing, Webhooks, Connect)
- Background Processing: Solid Queue (preferred) / Sidekiq
- Auditing: Paper Trail
- Feature Flags: Flipper
- Search: pg_search → Elasticsearch/Meilisearch (advanced)

**Deployment Strategy**
- Containerization: Docker + multi-stage builds (shared/docker/)
- Orchestration: Kamal (zero-downtime deploys, Blue-Green)
- CI/CD: GitHub Actions (lint.yml + tests.yml with parallel jobs)
- Scaling: Horizontal scaling with Puma + multiple workers
- Monitoring: Sentry, New Relic patterns, log aggregation
- Database: Primary + read replicas, multi-schema / row-level tenancy
- Zero-downtime migrations and rolling restarts

---

## Getting Started

### Prerequisites
- Ruby 3.3 or higher
- PostgreSQL 14+
- Redis 7+
- Node.js 20+ (for asset pipeline if needed)
- Docker & Docker Compose (recommended for advanced & real-world demos)

### Setup Steps

```bash
# 1. Clone the repository
git clone https://github.com/OdeToTheWind/rails-scalable-saas.git
cd rails-scalable-saas

# 2. Bootstrap any demo (example: Demo 01)
./scripts/bootstrap_demo.sh beginner/01_basic_user_signup

# 3. Follow the detailed guide for that demo
cat docs/progress/demo_01.md

# 4. Run the demo
cd demos/beginner/01_basic_user_signup
bundle install
rails db:setup
rails server
```
### Running Tests & Linting
```bash
# For any specific demo
cd demos/beginner/01_xxx
bundle exec rubocop
bundle exec rspec
```
## Demo 100 – The Capstone

**Demo 100: Enterprise-Grade Basecamp-Inspired SaaS**

A fully featured, multi-tenant, real-time collaboration platform that brings together **all 99 previous demos** into one production-ready application.

### Features Implemented

- **Multi-Tenancy**: Hybrid approach with both **schema isolation** and **row-level security**
- **Real-time Collaboration**: Turbo Streams + Action Cable for live updates across tasks, comments, and documents
- **Billing System**: Subscription + usage-based billing using Stripe (Checkout, Metered billing, Webhooks, and Billing Portal)
- **Background Job Pipelines**: Scalable job processing with Solid Queue / Sidekiq, batch jobs, priority queues, and retries
- **Advanced Search & File Handling**: Meilisearch/Elasticsearch integration + Active Storage with background variants and virus scanning
- **Analytics Dashboard**: Real-time metrics, materialized views, and export jobs
- **Deployment**: Fully Dockerized with Kamal for zero-downtime Blue-Green deployments
- **Observability & Security**: Full audit trails (Paper Trail), Sentry integration, rate limiting, and comprehensive logging

This capstone demo serves as the ultimate showcase of everything learned throughout the 100-demo journey — from basic Rails CRUD to enterprise-grade scalable SaaS architecture.

---

## Key Features Across the Repository

- Progressive difficulty with clear learning objectives for each level
- Shared reusable components in the `shared/` folder (gems and Docker configs)
- Consistent CI/CD pipelines for linting (RuboCop) and testing (RSpec)
- Detailed architecture and progress documentation in the `docs/` folder
- Strong focus on performance, security, and scalability starting from Day 1
- Real SaaS patterns implemented: multi-tenancy, billing, collaboration, analytics, and automation

---

## Contributing

This is a **personal 100-day learning challenge** repository.

However, issues, suggestions, feature requests, and thoughtful discussions are highly welcome.

If you would like to contribute:
1. Open an issue to discuss your idea
2. Fork the repository and create a feature branch
3. Ensure all tests pass and code follows RuboCop rules
4. Submit a Pull Request with clear description

Pull requests that improve documentation, fix bugs, or add new scaling patterns are especially appreciated.

---

## License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.