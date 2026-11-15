# Dawid Boissé

Senior Java/Kotlin & Cloud Engineer • Payments • Ad Tech • GCP • AWS

- [e-mail](mailto:dawid.boisse@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/dawid-boisse/)
- [GitHub](https://github.com/cookieMr)

## Summary

Senior backend engineer with 15 years in software, 9+ of them working with Java (test automation, then development) and now Kotlin. Delivered production payment and ad-tech services on **GCP** and **AWS** for 4+ years, in distributed teams. GCP Associate Cloud Engineer and GitHub Actions certified.

## Core skills

|               |                                                                                   |
| ------------- | --------------------------------------------------------------------------------- |
| **Languages** | Java 8–25, Kotlin 2, TypeScript, Python                                           |
| **Backend**   | Spring 5/6/7 (Boot, Web, Security, Data JPA, AOP), Hibernate, REST, GraphQL, gRPC |
| **AWS**       | Lambda, ECS/ECR, API Gateway, SQS, SES, S3, CloudFormation                        |
| **GCP**       | Cloud Run, Cloud Functions, Pub/Sub, Secret Manager                               |
| **Data**      | Kafka, PostgreSQL (Aurora, Cloud SQL, AlloyDB), DynamoDB, Memcached               |
| **Infra**     | Terraform, Kubernetes, Docker                                                     |
| **Quality**   | JUnit 5, TestNG, Jest, WireMock, Allure                                           |
| **Tooling**   | Git & GitHub (Actions), Gradle, Maven, OpenTelemetry, Grafana & Datadog, Jira     |

## Experience

### Senior Software Engineer — Commerce Media Tech Sp. z o.o.

_May 2026 – Present_

- Develop and own 6–8 **Kotlin** microservices (Spring Boot, Ktor, Kafka) for an ad platform that handles ad clicks and bidding between advertisers and publishers: thousands req/day and hundreds of advertisers and publishers.
- Responsible for technical design and **AWS** architecture (ECS/ECR, S3, Aurora PostgreSQL), provisioned with **Terraform**; migrated legacy services to the new ECS-based platform.
- Improved CI/CD on **GitHub Actions**: cut build-and-deploy time by ~30% with the Gradle build cache and parallel jobs, shared via reusable workflows across all services.
- Cut the volume of emails sent to users by filtering notifications by their notification preferences, reusing existing Kafka events instead of adding new ones.

### Senior Software Engineer — GPC Global Technology Center Sp. z o.o.

_Jul 2023 – Apr 2026_

- Built and maintained Java 17–25 / Spring 6 REST microservices on **GCP** (Cloud Run, Cloud Run Jobs, Cloud Functions) processing **millions of dollars a day** in internal payments between client shops.
- Implemented **idempotency** around a third-party REST API that did not support it, so retries could not trigger duplicate payment calls.
- Owned features from design to production support in a team of 6–8, including diagnosing and fixing live issues.
- Raised test coverage by introducing **end-to-end** test suites for the payment flows I owned.
- Cut database query latency by ~20% (Cloud SQL, AlloyDB) and REST response times by ~10% by monitoring GCP metrics and tuning the slowest paths.

### Software Engineer — WorldRemit Poland Sp. z o.o.

_Aug 2022 – Jun 2023_

- Developed new **GraphQL** queries and endpoints (Netflix DGS) across 5–6 microservices serving mobile and desktop clients worldwide: millions of req/day and tens of thousands of active users.
- Orchestrated calls from the GraphQL layer to other teams' backend services via gRPC and to legacy services via REST, within the existing architecture.
- Fixed a caching issue on three service instances by replacing local caches with a shared **Memcached**, and reduced latency of selected endpoints by **10–15%**.
- Built **Grafana** dashboards, monitors and alerts for endpoint usage, focused on the authentication and money-transfer request endpoints.

### QA Engineer → Software Engineer — Grid Dynamics Poland Sp. z o.o.

_Aug 2017 – Jul 2022_

**2021–2022** — Software Engineer: shopping cart for a luxury retailer; team of 5–10 across Poland, Ukraine and the USA

- Developed and maintained a **serverless AWS** cart module (Lambda, DynamoDB, API Gateway, SQS) in TypeScript and Java 8/11, handling hundreds of orders and tens of thousands of req/day, with Black Friday peaks.
- Cut cart latency by **90%** (3 s → 300 ms) through caching and parallel downstream calls.
- Removed Lambda cold-start delays with **provisioned concurrency**.

**2020–2021** — Software Engineer: document-management modules for a wealth-management platform

- Built features that track which documents need signing, which are signed, and which are outdated and need re-signing.
- Created reusable modules that reduced code duplication, improved test coverage and simplified manual testing.

**2017–2020** — QA Engineer: client onboarding platform

- Built and maintained **5,000 end-to-end tests** that caught 5–10 bugs a week.
- Cut the suite's run time from **1 h down to 20 min** and integrated it into CI (Jenkins).

### Senior Software Developer — Ericsson Sp. z o.o.

_Sep 2011 – Jul 2017_

- Automated build, testing, code-quality checks and CI/CD for the _Base Station Controller_ product with Python scripts, replacing many manual steps, helping the team adopt **Jenkins**, and cutting build-and-deploy time from **days to hours**.
- Developed and tested features and subscriber-data handling for the _Home Location Register_ telecom product in an Agile team, using a proprietary language and in-house toolchain.

## Education

**M.Sc., Applied Computer Science** — 2006–2011  
AGH University of Science and Technology, Kraków

## Certifications & languages

- [**Google Cloud Associate Cloud Engineer**](https://www.credly.com/badges/bdb2e192-6920-4344-8feb-bace577d3460) (valid to May 2029)
- [**GitHub Actions**](https://www.credly.com/badges/2dac690c-2ac9-4ae0-beb7-c0295a0ddf8f) (valid to Nov 2027)
- Earlier: [AWS Certified Solutions Architect — Associate](https://www.credly.com/badges/4a8e3b6f-a2db-4212-afca-924af257ec32) (expired Sep 2026); ISTQB Foundation Level
- **Languages:** English (fluent), Polish (native)
