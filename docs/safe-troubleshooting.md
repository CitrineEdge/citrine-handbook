# Safe Troubleshooting For On-Device Trading

A clear report is more useful than a full account dump. Record the behavior before
changing settings or reinstalling an app, which can remove useful local evidence.

## Useful Report Fields

```text
App version/build:
Android version and device model:
Mode and runtime state:
Approximate event time and timezone:
Screen or action:
Expected behavior:
Observed behavior:
Can it be repeated? If so, the smallest steps:
Any error text, with account identifiers removed:
```

Do not include API keys, private keys, seed phrases, access tokens, Google Play
purchase tokens, bank/tax records or full exchange order identifiers. Redact
account names, balances and notification content from public screenshots where
they are unnecessary. Review exports before sharing; a JSON file is not anonymous
merely because it does not resemble a photograph.

## Observe First

- Distinguish a display still loading from a confirmed zero, unavailable input
  or a paused runtime. Capture the exact status rather than paraphrasing it.
- Note whether a position was opened externally or by the app, and which device
  was managing it. Observation is monitoring, not an execution controller.
- Check Coinbase directly when the question concerns a real order or position.
  Do not repeatedly press an order action merely because a display is delayed.
- Note connectivity, device restart/background changes and the timing of any
  app update. These are diagnostic clues, not proof of a cause.
- Do not place trades simply to reproduce a UI issue. Start with Paper or a
  non-trading reproduction where possible.

## Where To Send It

Use [Citrine support](https://citrineedge.com/support/) for account-specific help.
The public documentation repository is for corrections to the handbook, not
private trading support. See [Security reporting](../SECURITY.md) for suspected
vulnerabilities. Never post credentials, even if asked by an unverified account.

[Back to handbook](../README.md)
