# Ataraxy Developers community projects

A collection of twelve focused tools, exercises, and guides. All are public and
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
