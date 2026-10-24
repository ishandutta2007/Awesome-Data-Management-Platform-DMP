# Awesome-Data-Management-Platform-DMP

# Awesome-Data-Management-Platform-DMP

# Top Data Management Platform (DMP)
**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Audience Data Management, Identity Resolution, Segmentation, Activation & Privacy-Compliant Data Platforms*

**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Management Platforms (DMPs)** and closely related Customer Data Platforms (CDPs). These tools collect, unify, segment, and activate audience and customer data for advertising, personalization, and marketing use cases.

**Examples** include Adobe Audience Manager, Lotame, Neustar, Eyeota, LiveRamp, Permutive, Salesforce Audience Studio, Oracle BlueKai, Nielsen DMP, and Carbon DMP (the category leaders).

**Open-source emphasis**: Pure traditional DMPs are predominantly commercial due to scale, identity graphs, and compliance requirements. However, a growing set of open-source **Customer Data Platforms (CDPs)** and related tools — **Apache Unomi**, **Tracardi**, **Jitsu**, **RudderStack** (core), **PostHog**, and others — provide transparent, self-hostable alternatives for audience data collection, profiling, segmentation, and activation. This section is heavily expanded around these practical open options.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Adobe Audience Manager](https://business.adobe.com/products/audience-manager/adobe-audience-manager.html)**  
  Enterprise DMP for collecting, organizing, and activating audience data across Adobe Experience Cloud and external advertising platforms.

- **[Lotame](https://www.lotame.com/)**  
  Audience data platform offering DMP capabilities, data collaboration, and enrichment for brands, publishers, and agencies.

- **[Neustar (TransUnion)](https://www.home.neustar/)**  
  Identity and marketing intelligence platform with strong data management, audience segmentation, and activation features.

- **[Eyeota](https://www.eyeota.com/)**  
  Global data marketplace and audience platform focused on data-driven targeting and audience insights.

- **[LiveRamp](https://liveramp.com/)**  
  Leading identity resolution and data connectivity platform that enables safe data collaboration and activation across ecosystems.

- **[Permutive](https://permutive.com/)**  
  Publisher-focused data platform combining DMP-like capabilities, data clean rooms, and first-party audience activation.

- **[Salesforce Audience Studio](https://www.salesforce.com/products/marketing-cloud/data-management/)**  
  Salesforce’s audience management and activation solution integrated with Marketing Cloud and Data Cloud.

- **[Oracle BlueKai](https://www.oracle.com/cx/advertising/data-management-platform/)**  
  Classic enterprise DMP for managing first-, second-, and third-party data and activating audiences across channels.

- **[Nielsen DMP / Marketing Cloud](https://www.nielsen.com/)**  
  Audience measurement and data management capabilities leveraged for media planning and activation.

- **[Carbon DMP](https://www.carbon.com/)** (and similar specialized DMPs)  
  Niche or regional data management platforms focused on specific markets or vertical audience data needs.

## Open-Source GitHub Projects
- **[Apache Unomi](https://github.com/apache/unomi)**  
  Official Apache open-source Customer Data Platform. Provides profile management, segmentation, privacy controls, real-time personalization, and a plugin architecture. One of the purest open-source DMP/CDP alternatives.

- **[Tracardi](https://github.com/Tracardi/tracardi)**  
  API-first, composable open-source CDP designed for collecting customer journey data, building profiles, segmentation, and automated engagement. Self-hostable and privacy-oriented.

- **[Jitsu](https://github.com/jitsucom/jitsu)**  
  Open-source (MIT) event collection and CDP-style pipeline. Strong warehouse-first approach for collecting, transforming, and activating customer data.

- **[RudderStack](https://github.com/rudderlabs/rudder-server)**  
  Popular customer data platform with open-source core components for event streaming, identity resolution, and data activation (note: some parts use source-available licensing).

- **[PostHog](https://github.com/PostHog/posthog)**  
  Open-source product analytics platform with strong CDP-like capabilities including event collection, person profiles, feature flags, experiments, and data pipelines.

- **[Multiwoven](https://github.com/Multiwoven/multiwoven)**  
  Open-source reverse ETL and lightweight CDP tooling that helps turn a data warehouse into an activation and audience platform.

- **[Pimcore](https://github.com/pimcore/pimcore)**  
  Open-core platform that includes Customer Data Platform (CDP) features alongside PIM, MDM, DAM, and digital experience management.

- **[Snowplow](https://github.com/snowplow/snowplow)**  
  Open-source behavioral data pipeline focused on high-quality event collection and modeling — frequently used as a foundation for custom audience and CDP systems.

- **[LEO CDP Framework](https://github.com/trieu/leo-cdp-framework)**  
  Open-source AI-first Customer Data Platform framework for building self-hosted, customizable CDP infrastructure with machine learning capabilities.

- **[Open-source Identity & Consent Tools](https://github.com/)** (supporting ecosystem)  
  Projects such as consent management platforms, identity resolution libraries, and privacy tools that complement open CDP stacks for compliant audience data handling.

### Additional Strong Open-Source Options
- Core open CDP engines: **Apache Unomi**, **Tracardi**.
- Event collection & pipelines: **Jitsu**, **Snowplow**, **RudderStack** (core).
- Broader product + data platforms: **PostHog**, **Pimcore**.
- Warehouse-native activation: **Multiwoven** and reverse-ETL style tools.
- Accepting that commercial DMPs (Adobe Audience Manager, Lotame, LiveRamp, Oracle BlueKai, Permutive, Salesforce) still dominate in large-scale identity graphs, third-party data marketplaces, advanced clean rooms, and enterprise-grade activation networks.

**Frameworks for building custom systems**:  
Start with **Apache Unomi** or **Tracardi** for core profile and segmentation capabilities → layer **Jitsu** or **Snowplow** for high-quality event collection → use a warehouse + reverse ETL (or Multiwoven) for activation → add consent and privacy tooling. Suitable for organizations that prioritize data ownership, transparency, and the ability to customize audience logic without vendor lock-in.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Data Management Platforms handle sensitive audience and personal data. Strict compliance with privacy regulations (GDPR, CCPA, etc.), consent management, and data governance is essential. Open-source alternatives give greater control and transparency but require significant engineering and legal oversight. This list is not legal, privacy, or security advice.

---
**Made for marketing technologists, data engineers, privacy-conscious teams, and open-source advocates.**

Let's keep audience data platforms more transparent, controllable, and open where practical.
