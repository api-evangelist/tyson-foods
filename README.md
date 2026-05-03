# Tyson Foods

Tyson Foods is one of the world's largest food companies and a Fortune 100 company, producing chicken, beef, pork, and prepared foods. Tyson Foods provides B2B integration capabilities for trading partners including EDI (Electronic Data Interchange) and API integrations for supply chain management, order processing, and logistics operations.

**URL:** [https://www.tysonfoods.com](https://www.tysonfoods.com)

## Tags

B2B Integration, EDI, Food, Fortune 100, Supply Chain

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-03

## APIs

### Tyson Foods EDI Integration API

B2B EDI and REST API integration for Tyson Foods trading partners supporting order management and shipment tracking.

**Human URL:** [https://www.tysonfoods.com/business-solutions](https://www.tysonfoods.com/business-solutions)
**Base URL:** https://api.tysonfoods.com

**Tags:** EDI, Logistics, Order Management, Supply Chain

**Properties**
- [Documentation](https://www.tysonfoods.com/business-solutions)
- [OpenAPI](openapi/tyson-foods-edi-integration-api-openapi.yml)
- [Trading Partner Portal](https://www.tysonfoods.com/business-solutions/trading-partner)

## Common Properties

- [Website](https://www.tysonfoods.com)
- [Business Solutions](https://www.tysonfoods.com/business-solutions)
- [Investor Relations](https://ir.tysonfoods.com)
- [Sustainability](https://www.tysonfoods.com/sustainability)
- [Terms of Service](https://www.tysonfoods.com/legal/terms-and-conditions)
- [Privacy Policy](https://www.tysonfoods.com/legal/privacy-policy)

## Artifacts

### JSON Schemas

| Schema | Description |
|---|---|
| [Order](json-schema/tyson-foods-order-schema.json) | Purchase order |
| [Shipment](json-schema/tyson-foods-shipment-schema.json) | Shipment / Advance Ship Notice |

### JSON Structures

| Structure | Description |
|---|---|
| [Order](json-structure/tyson-foods-order-structure.json) | Order field documentation |

### JSON-LD Context

- [Tyson Foods Context](json-ld/tyson-foods-context.jsonld)

### Examples

| Example | Description |
|---|---|
| [Get Orders](examples/tyson-foods-get-orders-example.json) | Retrieve purchase orders |
| [Get Shipments](examples/tyson-foods-get-shipments-example.json) | Retrieve shipment tracking |

### Spectral Rules

- [Tyson Foods Rules](rules/tyson-foods-rules.yml) — Enforces API naming, security, and HTTPS conventions

### Naftiko Capabilities

**Shared API Definitions**
- [EDI Integration](capabilities/shared/edi-integration.yaml) — Tyson Foods EDI REST API

**Workflow Capabilities**
- [Supply Chain Integration](capabilities/supply-chain-integration.yaml) — Order management and shipment tracking (3 tools)

### Vocabulary

- [Tyson Foods Vocabulary](vocabulary/tyson-foods-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
