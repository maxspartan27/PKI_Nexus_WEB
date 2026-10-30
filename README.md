# PKI NEXUS 6.0 — Digital Trust Lab

Single-file offline-first Ukrainian educational website on public-key infrastructure, based on Lecture 15 (Class 32).

## Publish on GitHub Pages

1. Create a GitHub repository and upload `index.html` to the repository root.
2. Open Settings → Pages → Build and deployment → Deploy from a branch.
3. Select `main` and `/ (root)`; save.
4. Open your `https://username.github.io/repository/` URL.

## New in v6

- Secure File Lab: real local AES-256-GCM encrypt/decrypt of files up to 12 MiB; PBKDF2/SHA-256, 310000 iterations, random salt and IV. Custom `.pki6` container.
- Trust Atlas: educational, illustrative network diagram for hierarchy, mesh and bridge models; 6 verification cases. **Not a real certificate chain validator.**
- Defense Studio: 5-minute rehearsal, checklist, speaking notes, and locally exported printable HTML report.
- Earlier modules preserved: X.509 inspector, ECDSA, Crypto Vault, Magic Studio, visual themes, simulation of CA, decision tools, quizzes.

## Privacy and limits

All processing stays in your browser; the website does not contact any backend. Use a strong, unique passphrase, and test with copies. The site is an educational tool, not a real certificate authority, independent PKI validator, or a professional backup solution. Web Crypto requires a secure context such as HTTPS or an approved local origin. Sample image themes are embedded in the HTML and remain accessible offline. Avoid putting real secrets into classroom demos.

Author credit: Максим Ковалишин · 2026.
