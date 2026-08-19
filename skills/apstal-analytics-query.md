# Analytics Query

## Description
Query Apstal analytics data through the semantic API endpoint.

## Endpoint
POST https://apstal.com/api/ai/semantic

## Authentication
Requires Supabase JWT bearer token in Authorization header.

## Usage
Send a natural language query about website analytics:

```json
{
  "messages": [{"role": "user", "content": "How many visitors did I have last week?"}],
  "projectId": "your-project-id"
}
```

The API uses Cube Core semantic layer to translate natural language into structured analytics queries against ClickHouse.

## Capabilities
- Visitor counts and trends
- Traffic sources analysis
- Bot detection statistics
- Behavioral metrics
- Performance monitoring (Web Vitals)
- Device intelligence
- Custom event tracking
