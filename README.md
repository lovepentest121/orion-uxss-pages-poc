# Controlled Orion UXSS Victim Page

This repository hosts only the static victim page for a controlled Orion Browser security PoC.

GitHub Pages cannot serve the required dynamic response:

```text
HTTP/1.1 302 Found
Location: javascript:<marker-only proof script>
```

So this public Pages site is only the controlled victim side. The attacker redirect endpoint must be hosted on controlled dynamic infrastructure during authorized testing.

No real accounts, credentials, cookies, or third-party websites are used.

Marker:

```text
ORION-SAFE-MARKER-2026-06
```

Usage:

```text
https://lovepentest121.github.io/orion-uxss-pages-poc/?attacker=https%3A%2F%2Fyour-controlled-attacker-endpoint.example%2Freal-poc-attacker-redirect
```
