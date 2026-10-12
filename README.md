> **Fictional demo repository.** This repository belongs to the [Agentic Blocks demo](https://govness-demo.vercel.app/blocks/civil-registry-lookup-mcp). The institution, people and work described here are invented for demonstration; it is not a real government project and contains no working code.

# Civil registry lookup MCP server

MCP server that verifies birth and business registration numbers against the national registries.

## Overview

Read-only verification: the server answers yes, no or not found for a registration number, never returning personal data beyond what the caller already holds.

## Tools

- `verify_birth_registration`
- `verify_business_registration`
- `registry_status`

## Interfaces

Protocol: `mcp`. Languages: en.

## Maintainers

Directorate of Digital Public Services. Licence: MIT.
