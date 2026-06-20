# Africa's Talking (africastalking)

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
