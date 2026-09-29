# mgpark.github.io Project Status

## As of
2026-09-29 KST

## Current state
Personal GitHub Pages repository. It is also a public metadata endpoint for ChatGPT_UsageApp.

## Integration
`ChatGPT_UsageApp` publishes `chatgpt-usage/latest.json` here. The Android app uses this metadata to detect releases.

## Current work state
No known standalone active development task. Treat changes to `chatgpt-usage/latest.json` as an integration change.

## Safety
Never commit secrets/tokens. Preserve JSON schema and freshness semantics. When changing the public update metadata contract, validate the consuming Android app as well.

## New session
Inspect current Pages/site structure and latest ChatGPT_UsageApp release workflow before changing update metadata.