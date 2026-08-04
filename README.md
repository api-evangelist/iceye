# ICEYE (iceye)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

ICEYE operates the world's largest constellation of small Synthetic Aperture Radar (SAR) satellites, delivering all-weather day-and-night imagery down to 25 cm resolution across multiple modes. The ICEYE API Platform at api.iceye.com exposes a Catalog API over an archive of 60,000+ SAR scenes and a Tasking API that lets customers schedule the constellation up to 14 days in advance without a feasibility study or human-in-the-loop. A companion Company API exposes account context. Beyond raw imagery, ICEYE publishes natural catastrophe products - Flood Insights, Wildfire Insights, and Hurricane Insights - used by insurance, government, banking, and utilities customers, and ships Gen 4 ISR, ISR Cell, Connect, and Federate sovereign mission systems for defense and intelligence.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/iceye/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/iceye/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- SAR
- Satellite Imagery
- Earth Observation
- Tasking
- Catalog
- Flood Monitoring
- Disaster Response
- Defense
- ISR
- Geospatial
- All-Weather

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### ICEYE Catalog API

Search, list, purchase, and retrieve products from ICEYE's archive of 60,000+ SAR scenes. Endpoints cover catalog item search, listing, purchase, and retrieval of purchased items for download.

- **Human URL:** [https://docs.iceye.com/constellation/api/1.0/](https://docs.iceye.com/constellation/api/1.0/)
- **Base URL:** `https://api.iceye.com`

#### Tags

- Catalog
- Search
- Archive
- SAR

#### Properties

- [Documentation](https://docs.iceye.com/constellation/api/1.0/)
- [Postman Collection](collections/iceye.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iceye.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ICEYE Tasking API

Direct tasking interface to the ICEYE SAR constellation. Create tasks up to 14 days in advance with no feasibility study, retrieve task status, list tasks, cancel tasks, fetch task scenes, and price tasks - built for machine-to-machine automation.

- **Human URL:** [https://docs.iceye.com/constellation/api/tasking/](https://docs.iceye.com/constellation/api/tasking/)
- **Base URL:** `https://api.iceye.com`

#### Tags

- Tasking
- SAR
- Constellation
- Automation

#### Properties

- [Documentation](https://docs.iceye.com/constellation/api/tasking/)
- [Postman Collection](collections/iceye.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iceye.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ICEYE Company API

Account and company context API providing identity, entitlement, and organizational metadata that frames Catalog and Tasking calls.

- **Human URL:** [https://docs.iceye.com/constellation/api/1.0/](https://docs.iceye.com/constellation/api/1.0/)
- **Base URL:** `https://api.iceye.com`

#### Tags

- Account
- Company
- Identity

#### Properties

- [Documentation](https://docs.iceye.com/constellation/api/1.0/)
- [Postman Collection](collections/iceye.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iceye.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ICEYE Platform

Web platform at platform.iceye.com for browsing catalog imagery, submitting tasking orders, monitoring task status, and downloading delivered SAR products through the same backend as the API Platform.

- **Human URL:** [https://platform.iceye.com/](https://platform.iceye.com/)
- **Base URL:** `https://platform.iceye.com/`

#### Tags

- Platform
- Web Console
- Tasking

#### Properties

- [Documentation](https://platform.iceye.com/docs/tasking)
- [Postman Collection](collections/iceye.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iceye.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.iceye.com/)
- [S A R Data](https://www.iceye.com/sar-data)
- [S A R Data A P I](https://www.iceye.com/sar-data/api)
- [Tasking](https://www.iceye.com/sar-data/tasking)
- [Documentation](https://docs.iceye.com/)
- [A P I Documentation](https://docs.iceye.com/constellation/api/1.0/)
- [Platform](https://platform.iceye.com/)
- [Product Documents](https://www.iceye.com/resources/product-documents)
- [Flood Insights](https://www.iceye.com/solutions/natural-catastrophe-insights/flood-insights)
- [Wildfire Insights](https://www.iceye.com/solutions/natural-catastrophe-insights/wildfire-insights)
- [Hurricane Insights](https://www.iceye.com/solutions/natural-catastrophe-insights/hurricane-insights)
- [Mission Systems](https://www.iceye.com/government-and-defense/mission-systems)
- [Newsroom](https://www.iceye.com/newsroom)
- [LinkedIn](https://www.linkedin.com/company/iceye-ltd/)
- [X (Twitter)](https://x.com/ICEYEfi)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
