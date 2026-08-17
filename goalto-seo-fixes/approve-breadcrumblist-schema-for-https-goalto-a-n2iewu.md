# Structured data (schema) fix — Approve BreadcrumbList schema for https://goalto.ai/team/lead-response

Recommended by GoAlto. Review and apply this change to your site.

- **Change type:** Structured data (schema)

## Current

```json
{
  "schema": null
}
```

## Proposed

```json
{
  "@type": "BreadcrumbList",
  "@context": "https://schema.org",
  "itemListElement": [
    {
      "item": "https://goalto.ai/team",
      "name": "team",
      "@type": "ListItem",
      "position": 1
    },
    {
      "item": "https://goalto.ai/team/lead-response",
      "name": "lead response",
      "@type": "ListItem",
      "position": 2
    }
  ]
}
```

---
_This file documents an approved SEO change. Applying it to your source is up to you or your developer._
