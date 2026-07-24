# WorldFirst (worldfirst)

WorldFirst is a United Kingdom-founded cross-border payments and money-movement company, headquartered in London and owned by Ant Group (Alipay) since 2019. It gives online sellers, marketplaces, and SMEs a multi-currency World Account to collect, hold, convert, and send money across borders, plus a World Card for multi-currency spending and supplier/marketplace payouts. Its home market is the United Kingdom; its book is global e-commerce and cross-border trade.

WorldFirst ships a genuine, API-native developer platform at [developers.worldfirst.com](https://developers.worldfirst.com/) built on Ant Group's Antom-style gateway. The interface is RESTful, JSON, and HTTPS-only, hosted per region (`open-sea` / `open-eu` / `open-na`.worldfirst.com) under `/amsin/api/v1/`. Requests are secured with RSA256/ECC224 digital signatures plus OAuth 2.0 access tokens, and asynchronous notifications (webhooks) return payment and trade-order results. No downloadable OpenAPI/Swagger is published — the gateway blocks anonymous spec fetches (`RefererCheckFailed`), so integration is gated behind partner onboarding and the console's iMock/iTest tooling.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/worldfirst/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/worldfirst/refs/heads/main/apis.yml)

## Tags

- Payments
- United Kingdom
- Cross-Border
- Money Transfer
- Foreign Exchange
- Payouts
- Payment Gateway
- E-commerce
- Multi-Currency
- Card Issuing

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### WorldFirst Enterprise Solution API

The World Account API covering customer onboarding, account and beneficiary management, statements, foreign exchange, transfer, payout, invoicing, and virtual-card credit for globally based partners and customers.

- **Human URL:** [Enterprise Solution API overview](https://developers.worldfirst.com.cn/docs/alipay-worldfirst/worldfirst_enterprise_solution/api_overview)
- **Base URL:** `https://open-sea.worldfirst.com/amsin/api/v1`

### WorldFirst Pay Solution API

Cashier Payment acceptance for overseas e-commerce merchants: create a payment order, let the customer pay, inquire about status, and receive an asynchronous payment notification.

- **Human URL:** [Pay Solution getting started](https://developers.worldfirst.com/docs/alipay-worldfirst/cashier_payment/getting_started)
- **Base URL:** `https://open-sea.worldfirst.com/amsin/api/v1`

### WorldFirst WorldTrade Solution API

Cross-border trade transactions — FX quote lookup (`inquiryQuotes`), trade-order submission (`createTradeOrder`), and a WorldFirst-initiated `notifyTradeOrderCloseResult` callback.

- **Human URL:** [WorldTrade Solution overview](https://developers.worldfirst.com/docs/alipay-worldfirst/worldtrade_solution/overview)
- **Base URL:** `https://open-sea.worldfirst.com/amsin/api/v1`

## Common Properties

- [Website](https://www.worldfirst.com/)
- [Developer Portal](https://developers.worldfirst.com/)
- [Documentation](https://developers.worldfirst.com/docs/alipay-worldfirst/overview/home)
- [API Reference](https://developers.worldfirst.com/docs/alipay-worldfirst/overview/apis)
- [Getting Started](https://developers.worldfirst.com/docs/alipay-worldfirst/cashier_payment/getting_started)
- [Pricing](https://www.worldfirst.com/uk/pricing/)
- [Blog](https://www.worldfirst.com/uk/blog/)
- [Terms of Service](https://www.worldfirst.com/uk/terms-and-conditions/)
- [Privacy Policy](https://www.worldfirst.com/uk/privacy-policy/)
- [LinkedIn](https://www.linkedin.com/company/world-first)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
