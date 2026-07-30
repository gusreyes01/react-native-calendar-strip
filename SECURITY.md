# Security Policy

## Support status

This fork preserves the 2.0.3 library API and uses an end-of-life React Native
development toolchain for compatibility testing. Security fixes that preserve
the public API are accepted, but the legacy example application and toolchain
should not be treated as a supported modern mobile stack.

Consumers should keep their application runtime current, review the library's
small runtime dependency set, and avoid copying the example's historical
dependency versions into production applications.

## Reporting a vulnerability

Do not publish exploit details or sensitive data in a public issue. Use the
repository's **Security** tab to submit a private vulnerability report with the
affected version, impact, reproduction steps, and a suggested mitigation when
available. Maintainers will coordinate validation and disclosure through the
private advisory.
