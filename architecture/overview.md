# Advisoira — Conceptual Product Architecture

This is a product-level map based on the founder's description, **not** a verified production architecture or data-flow specification.

## Client and public experiences
- Advisoira website and public financial tools.
- Mobile experience for investment-goal progress and monthly behaviour logging.
- Client Snapshot workflow for collecting financial information.

## Application and integration layer
The founder has identified Supabase, APIs and Resend as supporting technology. Exact service boundaries, authentication design, database schema and deployment topology are intentionally not disclosed.

## Financial intelligence capabilities
- ETF premium/discount analysis.
- Mutual fund holdings overlap.
- Sector exposure and portfolio concentration.
- Client financial profiling and planning inputs.
- Historical investment research and valuation analysis.
- Operational portfolio-data auditing.

Production workflows should account for data provenance, freshness, missing records, access controls, privacy, calculation validation and human review of consequential financial outputs.

This does not assert that all products share one database, backend service or deployment pipeline.