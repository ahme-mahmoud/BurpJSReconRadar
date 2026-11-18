# Contributing

Thanks for your interest in improving BurpJSReconRadar.

## Before making changes

1. Fork the repository.
2. Create a focused branch for your change.
3. Review the existing implementation and keep changes scoped to one issue.
4. Avoid including real API keys, tokens, cookies, session identifiers, or other sensitive data in code, screenshots, logs, or test fixtures.

## Making a change

- Prefer small, clearly named commits.
- Preserve compatibility with the Burp Suite and Jython/Python runtime targeted by the project.
- Keep passive scanning behavior non-intrusive; do not add active requests or testing against third-party systems without authorization.
- Update the README when user-facing behavior or configuration changes.

## Validation

Before opening a pull request:

- Review the diff for accidental secrets and unrelated changes.
- Test the extension in a local Burp Suite environment where possible.
- Include the exact environment and validation steps in the pull request.
- Clearly disclose any validation that could not be performed.

## Pull requests

A pull request should explain:

- What changed and why.
- How the change was tested.
- Any compatibility considerations or known limitations.

Keep discussions constructive and be open to maintainer feedback.
