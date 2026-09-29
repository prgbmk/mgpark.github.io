# CLAUDE.md — mgpark.github.io

## Mission
Personal GitHub Pages site/repository. It also serves public update metadata used by ChatGPT_UsageApp.

## Integration dependency
`ChatGPT_UsageApp` publishes/validates `chatgpt-usage/latest.json` here using a minimally scoped token. Do not change the manifest schema or path without coordinating with the Android app.

## Safety
- Never commit secrets or tokens.
- Preserve public manifest validity and freshness semantics.
- Changes affecting `chatgpt-usage/latest.json` should be tested against the consuming ChatGPT_UsageApp update logic.
