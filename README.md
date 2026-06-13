# Simplifi by Quicken

Simplifi by Quicken is a personal finance management application that aggregates financial accounts from over 14,000 institutions, enabling users to track spending, manage budgets, monitor investments, set savings goals, and access projected cash flow analytics.

## Overview

- **Website:** https://www.quicken.com/personal-finance/quicken-simplifi/
- **Documentation:** https://support.simplifi.quicken.com/en/
- **Blog:** https://www.quicken.com/blog/search/simplifi
- **Community:** https://community.simplifimoney.com/
- **Pricing:** https://www.quicken.com/products/pricing-comparison-products/

## APIs.json

This repository contains an APIs.json 0.19 profile for Simplifi by Quicken.

- [apis.yml](apis.yml) - Main APIs.json profile
- [plans/plans.yml](plans/plans.yml) - Subscription pricing plans
- [rate-limits/rate-limits.yml](rate-limits/rate-limits.yml) - Platform rate limit details
- [finops/finops.yml](finops/finops.yml) - Financial operations summary

## Notes

Simplifi by Quicken does not expose a public developer API. The platform uses internal OAuth connections to financial institutions and purpose-built biller APIs as consumer-facing integrations. Community members have requested a public API, but as of 2026, none has been released.

Maintained by [Kin Lane](https://apievangelist.com) / [API Evangelist](https://apievangelist.com).
