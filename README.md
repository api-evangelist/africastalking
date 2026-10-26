# Africa's Talking (africastalking)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Africa's Talking is a pan-African communications platform that exposes a unified set of REST APIs for SMS, USSD, Voice, Airtime, Mobile Data, and Payments. Developers authenticate with an apiKey and username and reach mobile subscribers across Kenya, Nigeria, Uganda, Tanzania, Rwanda, and other African markets through carrier integrations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/africastalking/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/africastalking/refs/heads/main/apis.yml)

## Tags

- Communications
- SMS
- USSD
- Voice
- Airtime
- Mobile Data
- Payments
- Africa

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Africa's Talking SMS API

Send single and bulk SMS, monetize content with premium SMS, manage premium subscriptions and checkout tokens, and fetch inbox messages via the messaging endpoint authenticated with apiKey and username headers.

- **Human URL:** [https://developers.africastalking.com/docs/sms/overview](https://developers.africastalking.com/docs/sms/overview)
- **Base URL:** `https://api.africastalking.com/version1`

#### Tags

- SMS
- Messaging
- Bulk SMS
- Premium SMS

#### Properties

- [Documentation](https://developers.africastalking.com/docs/sms/overview)
- [API Reference](https://developers.africastalking.com/docs/sms/sending/bulk)
- [OpenAPI](openapi/africastalking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/africastalking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/africastalking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Africa's Talking USSD API

Build interactive USSD menus driven by HTTP callbacks. Africa's Talking POSTs session state (sessionId, serviceCode, phoneNumber, text) to your callback URL and your response begins with CON to continue or END to terminate the session.

- **Human URL:** [https://developers.africastalking.com/docs/ussd/overview](https://developers.africastalking.com/docs/ussd/overview)
- **Base URL:** `https://api.africastalking.com/version1`

#### Tags

- USSD
- Menu
- Sessions

#### Properties

- [Documentation](https://developers.africastalking.com/docs/ussd/overview)
- [OpenAPI](openapi/africastalking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/africastalking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/africastalking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Africa's Talking Voice API

Make outbound calls, transfer and queue calls, and upload media files. Incoming and outgoing calls trigger HTTP callbacks to which you respond with Voice XML actions such as Say, Play, GetDigits, Dial, Record, and Enqueue.

- **Human URL:** [https://developers.africastalking.com/docs/voice/overview](https://developers.africastalking.com/docs/voice/overview)
- **Base URL:** `https://voice.africastalking.com`

#### Tags

- Voice
- Call
- IVR

#### Properties

- [Documentation](https://developers.africastalking.com/docs/voice/overview)
- [OpenAPI](openapi/africastalking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/africastalking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/africastalking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Africa's Talking Airtime API

Programmatically distribute mobile airtime to one or many recipients across supported African carriers, with per-recipient currency, amount, and retry control.

- **Human URL:** [https://developers.africastalking.com/docs/airtime/overview](https://developers.africastalking.com/docs/airtime/overview)
- **Base URL:** `https://api.africastalking.com/version1`

#### Tags

- Airtime
- Top Up
- Rewards

#### Properties

- [Documentation](https://developers.africastalking.com/docs/airtime/overview)
- [API Reference](https://developers.africastalking.com/docs/airtime/sending)
- [OpenAPI](openapi/africastalking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/africastalking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/africastalking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Africa's Talking Mobile Data API

Disburse mobile data bundles in bulk to subscribers, specifying quantity, unit (MB or GB), and validity (Day, Week, or Month) per recipient against a registered payment product.

- **Human URL:** [https://developers.africastalking.com/docs/data/overview](https://developers.africastalking.com/docs/data/overview)
- **Base URL:** `https://bundles.africastalking.com`

#### Tags

- Mobile Data
- Bundles
- Disbursement

#### Properties

- [Documentation](https://developers.africastalking.com/docs/data/overview)
- [API Reference](https://developers.africastalking.com/docs/data/sending)
- [OpenAPI](openapi/africastalking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/africastalking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/africastalking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Africa's Talking Payments API

Collect and disburse money over mobile money rails, including mobile C2B checkout, B2C disbursement to customers, and B2B business-to-business transfers, with per-country currency and metadata support.

- **Human URL:** [https://developers.africastalking.com/docs/payments/overview](https://developers.africastalking.com/docs/payments/overview)
- **Base URL:** `https://payments.africastalking.com`

#### Tags

- Payments
- Mobile Money
- B2C
- B2B
- Checkout

#### Properties

- [Documentation](https://developers.africastalking.com/docs/payments/overview)
- [API Reference](https://developers.africastalking.com/docs/payments/mobile_c2b/checkout)
- [OpenAPI](openapi/africastalking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/africastalking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/africastalking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/AfricasTalkingLtd)
- [LinkedIn](https://www.linkedin.com/company/africa-s-talking)
- [Website](https://africastalking.com)
- [Documentation](https://developers.africastalking.com)
- [Plans](plans/africastalking-plans-pricing.yml)
- [Rate Limits](rate-limits/africastalking-rate-limits.yml)
- [Fin Ops](finops/africastalking-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
