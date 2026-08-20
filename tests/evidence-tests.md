# Evidence Testing Guidelines

Tests the evidence parsing, validation, and classification layer.

## Tests Cases
1. **Empty / Null Metadata**: Provide raw scraped website text with no dates or URLs. Ensure validation fails.
2. **Unsupported Source**: Provide source type `anonymous_blog_comment`. Ensure classification defaults to Tier 4 / low-confidence.
