# 📝 PoCForge — Bug Bounty PoC Builder (MIT)

Build formatted, submittable Proof-of-Concept reports for **authorized**
bug-bounty targets. UI in EN/TR/AR. Static single file + README.

## Builder

14 vulnerability types (XSS ×3, SQLi ×3, SSRF, IDOR, Redirect, Traversal,
CMDi, CSRF, SSTI, XXE), each with curated test payloads, severity default,
fix guidance and OWASP references. Output: Markdown report with Summary,
Severity, numbered Steps to Reproduce, PoC in **cURL + Python + HTML**,
Impact, Remediation, References. Copy / download / local history
(save, reload, delete, export JSON).

Shell-safe code generation (quote escaping verified by tests).

## Money & contact

- `CONFIG.ads` footer slot (dev/cloud-tool ads).
- Donate: BTC + USDT-TRC20 + IBANs live.
- 📧 baranavisat@gmail.com · 📞 +90 531 326 37 22 · WhatsApp

## Run

```bash
cd pocforge
python3 -m http.server 8080
```

## License

MIT. Test authorized targets only.
