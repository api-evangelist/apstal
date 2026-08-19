# auth.md

Apstal supports agent authentication for accessing analytics APIs.

## Agent Audience
AI agents and automation tools that need to query website analytics data programmatically.

## Registration Methods

### API Key
1. Create an account at https://apstal.com/register
2. Navigate to Settings → API Keys in the dashboard
3. Generate a new API key with appropriate scopes
4. Use the key in the `Authorization: Bearer <key>` header for all API requests

### OAuth 2.0
Apstal uses Supabase Auth (GoTrue) as the identity provider:
- Authorization endpoint: https://apstal.com/api/auth/callback
- Token endpoint: https://apstal.com/api/auth/token
- Supported grants: authorization_code, refresh_token
- Scopes: read, write, admin

## Credential Use
- API keys grant access to analytics query endpoints (/api/analytics/*)
- OAuth tokens grant access to the full API surface
- All credentials should be kept secret and transmitted over HTTPS only

## Protected Resources
- Base URL: https://apstal.com/api
- Protected Resource Metadata: https://apstal.com/.well-known/oauth-protected-resource
- Authorization Server Metadata: https://apstal.com/.well-known/oauth-authorization-server

## Agent Skills
- Analytics Query: https://apstal.com/.well-known/agent-skills/analytics-query/SKILL.md
- Markdown Negotiation: https://apstal.com/.well-known/agent-skills/markdown-negotiation/SKILL.md
