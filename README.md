[Cron Parser](https://apify.com/lazymac/cron-parser?fpr=data)

# Cron Parser

Explain, validate, and generate cron expressions. Preview next run times and browse common cron patterns.

## Input

- `action` (string): Action — `explain`, `validate`, `next`, `generate`, `common`
- `expression` (string): Cron expression to parse
- `count` (integer): Number of next runs to display
- `from` (string): Start date for next run calculation
- `generateOptions` (object): Options for generating a cron expression

## Output

Returns human-readable explanation, validation result, next run times, generated expression, or list of common patterns.