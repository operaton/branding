# What is Operaton?

- The free Open Source BPM Engine for everyone
- State-of-the-art with its own vision for the future
- Fork of Camunda 7 CE

---

# Our vision

Operaton shall be a austainable BPM solution for the next decade.

- Completely free Open Source (not only open core)
- Community ownership via a legal foundation
- No vendor lock-in, no licence fees, no restrictions
- All components will be Open Source
- Seamless migration from Camunda 7 CE to Operaton
- Completely renew the code base including the webapps
- Provide a welcoming environment for contributors
- Enable professional services by third parties

---

# Who are we?

## Core Contributors
- Karsten Thoms (itemis AG)
  - Main contributor
- Julian Haupt (backoffice.plus)
  - Social Media manager
  - Backports
- Paul Hempel (Lambdaschmiede GmbH)
  - New web applications
  - operaton.org Website

---

# Who are we?

## Initiators

- Tim Zöller (Lambdaschmiede GmbH)
  - Former Camunda trainer
- Andreas Zill (n3rdy by natur3 UG (haftungsbeschränkt))
  - Documentation
  - Legal
- Andreas Klein (DemandFlow GmbH)
  - Documentation
  - Legal

---

# Who are we?
## Frequent Contributors

- Arne Deutsch (itemis AG): JUnit 5 migration
- Wolfgang Schmoller (itemis AG): JavaEE -> JakartaEE migration
- Javad Malaquti (itemis AG): Docker, Helm Charts

---

# History

## October 2024
- Creation of the fork
- Re-Branding of Camunda 7 CE
- Release 1.0.0-beta-1

---
# History

## December 2024
- Release 1.0.0-beta-2
- Raise minimal Java version to 17
- Set up build infrastructure
- First automated release with JReleaser
- Enable static code and coverage analysis with SonarQube

---
# History

## January 2025
- Release 1.0.0-beta-3
- First release of "Operaton" distribution (formerly known as "Camunda Run")
- Enablement of integration tests for all distributions
- First release with Docker and Helm Charts
- Massive reduction of Sonar findings

---
# History

## May 2025
- Release 1.0.0-beta-4
- First release with full JakartaEE 10 migration
- Drop  JavaEE support

---

# Roadmap

## Q2/2025
- Publish revised documentation
- Founding of the Operaton e.V. non-profit organization
- Release of new web apps beta (replacement for tasklist, cockpit and admin)

## Q3/2025
- Release of new web apps beta (replacement for tasklist, cockpit and admin)
- Prepare semi-automatic migration path to Operaton

## October 2025
- End of life Camunda 7.24 CE
- Release 1.0 based on 7.24 CE
- Publish distributions via various packagers like Homebrew, Winget

---

# Roadmap - 2026 and beyond

- Release version 1.1 – No breaking changes
- Further improvements based on our users needs
- Remove deprecated code

---

# Early Adopters

- Ritense
- OpenBPM
- Sucurema
- Bundesministerium für Arbeit und Soziales
- (others that don't want to get publicly named)

---

# Code Base Renewal

- Raise Java to language level 17
- Drop support for legacy JavaEE containers
- Raise dependencies to latest and secure versions
- Migrate tests to JUnit 5 & AssertJ
- Resolve security & static code analysis findings

---

# Activity

- 750 commits
- 21 contributors
- Changed files: 18.903 (8.454 unique)
- Changed lines:
- +152.513
- -180.351
- => - 27.838
- 3.800 workflow executions
- 0 API breakages

---

# Code Cleanup

- Initial code base had 16k Sonar issues
- 12k issues resolved
- ~50% resolved with help of OpenRewrite

---

# JUnit 5 migration

- 25k automated test cases in JUnit 4
- Created a new extension library for JUnit 5

![JUnit 5 migration status](assets/junit5-migration-progress.png "JUnit 5 Migration Status")

---

# Outlook

- Documentation
- Distributions
