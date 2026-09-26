# Contributing to Incenta

## Rules and data

Incentive rules change and can be jurisdiction-specific. Mark demonstration records as synthetic, cite an authoritative source for factual program changes, and include an effective date. Never commit client pro formas or personal data.

## Development

```bash
cd server && npm ci && npm run build
cd ../addin && npm ci && npm run build
```

Keep pull requests focused and explain how eligibility, tradeoff, or spreadsheet-writing behavior was verified. Changes that modify a workbook must preserve an auditable change summary and undo path.
