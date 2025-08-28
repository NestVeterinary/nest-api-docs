# Nest API — Docs & Issue Tracker

> **Version:** 1.2 · **OpenAPI:** 3.1 · **Base URL:** `https://nestvet.com/api/1.1/wf` · **Auth:** Bearer token

This repository is a **temporary** home for the Nest API specification and a single place for partners to report API issues. Until our full developer portal is live:

- Read the API spec in `openapi.yaml` (or `openapi.json`).
- File bugs using **GitHub Issues** (a short, structured template is provided).

> ⚠️ **Security & privacy:** Do **not** paste secrets, access tokens, or PII into issues. Mask or remove sensitive data in requests/responses.

---

## What’s here

- `openapi.yaml` (or `openapi.json`): the authoritative NestVet API definition (OpenAPI 3.1, version **1.2**).

## Quickstart

### View / import the spec
You can import the OpenAPI file into your preferred tool:
- **Postman**: *Import → File* and select `openapi.yaml`.
- **Insomnia**: *Create → Import From File* and select `openapi.yaml`.
- **Swagger Editor**: open the editor and paste the YAML.

## Reporting a bug

1. Click **New issue** → choose **Bug report**.
2. Fill out the required fields
3. Include helpful IDs when relevant (e.g., Stripe `payment_intent` / `payout`, `invoice_pims_id`, `pet_id`, `clinic`).
4. Submit one issue per distinct problem.

> If you receive a non‑200 response or data looks inconsistent with this spec, please include the **exact** HTTP status, sanitized response body, and approximate **UTC** timestamp.
