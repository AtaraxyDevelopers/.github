# Ataraxy Developers community projects

A collection of 32 focused projects: 20 business workspaces and 12 developer tools, exercises, and guides. All are public and
MIT licensed. Use them in your own projects, adapt the examples, and contribute
improvements through repository issues and pull requests.

## Choose a starting point

- **New to practical JavaScript:** Developer Guides in English and Urdu, then the Bug Lab.
- **Building applications:** Setup Doctor, Backend Recipes, API Failure Playground, and the Webhook Lab.
- **Improving quality:** Accessible UI Recipes and Edge-Case Test Data.
- **Shipping and maintaining:** Release Workflows, Upgrade Cookbook, Deployment Recipes, and the Handbook.

| Repository | Purpose |
| --- | --- |
| [Developer Setup Doctor](https://github.com/AtaraxyDevelopers/dev-setup-doctor) | Diagnose project setup problems with actionable, secret-safe checks. |
| [Real-World Bug Lab](https://github.com/AtaraxyDevelopers/real-world-bug-lab) | Ten runnable debugging exercises with regression tests, hints, and solutions. |
| [Tested Backend Recipes](https://github.com/AtaraxyDevelopers/tested-backend-recipes) | Small tested backend recipes for pagination, retries, uploads, jobs, and idempotency. |
| [API Failure Playground](https://github.com/AtaraxyDevelopers/api-failure-playground) | A local HTTP API for exercising slow, failed, expired, and rate-limited responses. |
| [Accessible UI Recipes](https://github.com/AtaraxyDevelopers/accessible-ui-recipes) | Five framework-free UI patterns with keyboard and automated accessibility tests. |
| [Webhook Testing Lab](https://github.com/AtaraxyDevelopers/webhook-testing-lab) | A local signed webhook receiver and sender with replay and duplicate handling. |
| [Edge-Case Test Data](https://github.com/AtaraxyDevelopers/edge-case-test-data) | Deterministic synthetic fixtures for Unicode, dates, missing values, and boundary cases. |
| [Reusable Release Workflows](https://github.com/AtaraxyDevelopers/reusable-release-workflows) | Reusable GitHub Actions workflows with a working Node.js package and release validation. |
| [Framework Upgrade Cookbook](https://github.com/AtaraxyDevelopers/framework-upgrade-cookbook) | Executable Express 4 to 5 migration examples with shared HTTP contract tests. |
| [Small-App Deployment Recipes](https://github.com/AtaraxyDevelopers/small-app-deployment-recipes) | A runnable persistent Node.js app with backup, restore, container, and rollback exercises. |
| [Open Engineering Handbook](https://github.com/AtaraxyDevelopers/open-engineering-handbook) | Adaptable engineering practices, fictional worked examples, and a safe template generator. |
| [Developer Guides: English and Urdu](https://github.com/AtaraxyDevelopers/developer-guides-en-ur) | Ten bilingual practical lessons with runnable JavaScript examples and tests. |

## Business workspaces

| Project | What you can use |
| :--- | :--- |
| [Lead Response Desk](https://github.com/AtaraxyDevelopers/lead-response-desk) | Give every incoming inquiry an owner and a timely first response. |
| [Lead Qualification Engine](https://github.com/AtaraxyDevelopers/lead-qualification-engine) | Prioritize leads with explainable, adjustable qualification scores. |
| [Sales Pipeline Board](https://github.com/AtaraxyDevelopers/sales-pipeline-board) | Track deal stages, next actions, and stalled opportunities in one workspace. |
| [Quote to Sale](https://github.com/AtaraxyDevelopers/quote-to-sale) | Prepare clear quotations and export customer-ready HTML documents. |
| [Proposal Follow-Up Planner](https://github.com/AtaraxyDevelopers/proposal-followup-planner) | Keep proposal follow-ups timely, specific, and respectful. |
| [Booking Conversion Kit](https://github.com/AtaraxyDevelopers/booking-conversion-kit) | Qualify consultation requests and manage conflict-free appointment slots. |
| [Customer ROI Calculator](https://github.com/AtaraxyDevelopers/customer-roi-calculator) | Explain the potential savings and payback of a proposed solution. |
| [Referral Revenue Tracker](https://github.com/AtaraxyDevelopers/referral-revenue-tracker) | Connect referral codes with verified sales and outstanding partner rewards. |
| [Lost Deal Revival](https://github.com/AtaraxyDevelopers/lost-deal-revival) | Revisit lost opportunities when there is a relevant reason to reconnect. |
| [Checkout Recovery Kit](https://github.com/AtaraxyDevelopers/checkout-recovery-kit) | Prioritize abandoned checkouts and track confirmed recovered orders. |
| [Invoice Collection Desk](https://github.com/AtaraxyDevelopers/invoice-collection-desk) | See overdue balances and prepare accurate payment reminder drafts. |
| [Renewal Retention Manager](https://github.com/AtaraxyDevelopers/renewal-retention-manager) | Prepare for renewals and track customer health before contracts expire. |
| [Upsell Opportunity Finder](https://github.com/AtaraxyDevelopers/upsell-opportunity-finder) | Find relevant upgrades using transparent customer fit rules. |
| [Sales Funnel Analyzer](https://github.com/AtaraxyDevelopers/sales-funnel-analyzer) | Find the largest conversion losses across comparable sales cohorts. |
| [Campaign Profit Tracker](https://github.com/AtaraxyDevelopers/campaign-profit-tracker) | Compare campaign revenue with advertising and fulfillment costs. |
| [Profit-Safe Pricing Calculator](https://github.com/AtaraxyDevelopers/profit-safe-pricing) | Check price floors and discount headroom before making an offer. |
| [Customer Profitability Analyzer](https://github.com/AtaraxyDevelopers/customer-profitability-analyzer) | Understand which customer relationships support sustainable delivery. |
| [Subscription Spend Auditor](https://github.com/AtaraxyDevelopers/subscription-spend-auditor) | Review unused seats and upcoming renewals before more money is committed. |
| [Inventory Reorder Planner](https://github.com/AtaraxyDevelopers/inventory-reorder-planner) | Plan replenishment from observed demand, supplier lead times, and available stock. |
| [Project Scope & Margin Guard](https://github.com/AtaraxyDevelopers/project-margin-guard) | Spot scope creep and estimate the cost to finish before a project loses its margin. |

Install Node.js 22 or 24, run `npm ci`, `npm test`, `npm run example`, then `npm start`.
Open the exact 127.0.0.1 address printed by the app. The README includes a screenshot,
expected example results, field definitions, backup/restore instructions and optional
integration examples where available. Each app saves data on your own computer.

All 20 business projects include Chromium workflow tests and automated accessibility
checks. They use one currency per workspace and transparent, configurable assumptions.
Review outputs before using them for business decisions. Public multi-user hosting and
automated email, payment or store connections need additional integration work.

## Download and run

Open a repository and choose **Code → Download ZIP**, or clone it with Git. Install
Node.js 22 or 24, open a terminal in the repository folder, and run:

```sh
npm ci
npm test
```

The README then gives a demo command or a local server address. Most projects have
no runtime dependencies. The UI browser tests additionally need Chromium installed
through Playwright; the deployment container exercise requires Docker. Both also
provide local examples that do not require those optional tools. No paid account or
API subscription is required. Packages are distributed through GitHub releases;
these names are not currently published to the npm registry.

## Verification and scope

Every repository has CI for Node.js 22 and 24 on Linux, Windows, and macOS. The UI
project adds keyboard and automated accessibility checks in Chromium. The deployment
project adds a Linux container test for persistence across upgrade and image rollback.
Open each repository's Actions tab to see the results for its exact commit.

These are focused first releases with explicit contracts and limitations. Teaching
examples are labeled, synthetic data is used throughout, and production deployment
requirements are documented where relevant. The handbook's worked examples are
fictional and its policies are suggestions to adapt. Automated accessibility tests
do not replace manual assistive-technology testing.

## Support and contributions

Use the repository's issue templates for reproducible bugs and concrete feature
requests. Read CONTRIBUTING.md before a substantial change. Maintenance is best
effort; no response deadline is promised. For security concerns, follow
[SECURITY.md](SECURITY.md) and avoid posting sensitive details publicly.
