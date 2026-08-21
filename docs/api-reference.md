# API Reference

The Nimbus Analytics API lets you send events, query analytics data, and manage your workspace programmatically.

## Authentication

All API requests must include your API token in the `Authorization` header:

```
Authorization: Bearer YOUR_API_TOKEN
```

## Core endpoints

- `POST /v1/events` – Send one or more events to Nimbus Analytics.
- `GET /v1/funnels` – Query funnel conversion data.
- `GET /v1/retention` – Query retention analysis results.

## Example

```bash
curl -X POST https://api.nimbusanalytics.example/v1/events \
  -H "Authorization: Bearer YOUR_API_TOKEN" \
  -H "Content-Type: application/json" \
  -d '{"event": "signup_completed", "user_id": "42"}'
```

All responses are returned as JSON. See the full endpoint documentation for request and response schemas.
