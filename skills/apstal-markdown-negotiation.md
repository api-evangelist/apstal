# Markdown Negotiation

## Description
Apstal supports content negotiation for AI agents. When a request includes `Accept: text/markdown`, the server returns a markdown representation of the page content instead of HTML.

## Usage
Send requests with the `Accept: text/markdown` header:

```
GET /blog/some-article HTTP/1.1
Accept: text/markdown
```

The response will be `Content-Type: text/markdown` with the page content as clean markdown.

## Supported Paths
- `/blog/*` — Blog articles (returned as original markdown)
- `/docs/*` — Documentation pages
- `/` — Homepage summary

## Implementation
The middleware checks the `Accept` header and routes to markdown rendering for supported paths. HTML remains the default for browser requests.
