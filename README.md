# O-Fit Common Questions

Remote FAQ content for O-Fit iOS and Flutter apps.

## Data file

- `common-questions.json` — canonical FAQ payload

## Update flow

1. Edit `common-questions.json`
2. Commit and push to `main`
3. Apps fetch the latest JSON from:

```
https://raw.githubusercontent.com/talk812/O-Fit-CommonQuestions/main/common-questions.json
```

## JSON schema

```json
{
  "version": 1,
  "lastUpdated": "2026-07-17",
  "faqs": [
    {
      "category": "請假",
      "question": "...",
      "answer": "...",
      "tags": ["..."],
      "keywords": ["..."],
      "priority": "high"
    }
  ]
}
```
