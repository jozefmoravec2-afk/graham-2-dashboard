GRAHAM DASHBOARD SAFETY v1.0
Stable snapshot: 2026-10-11
Source of truth: dashboard_source.html
Public runtime: index.html loader + dashboard_b64/part1.txt ... part6.txt

MANDATORY UPDATE PROTOCOL
1. Fetch all six live chunks and reconstruct the complete HTML.
2. Never edit or deploy from a partial/chunk-mixed document.
3. Save/update dashboard_source.html only from a fully validated document.
4. Validate BEFORE deployment.
5. Generate all six chunks from exactly the same validated source.
6. Deploy all six chunks as one logical release.
7. Fetch all six chunks again and reconstruct the deployed HTML.
8. Validate AFTER deployment and compare with source.
9. If any write is interrupted, DO NOT continue editing the mixed live state. Restore from dashboard_source.html / stable backup first.
10. Root index.html login/noindex loader is independent and must not be overwritten by dashboard HTML.

INTEGRITY CHECKS
- complete <html> ... </html>
- Current Strategy / Graham 2.0 present
- Earnings Quality module present
- 12 ticker mini-reports present: VGWD SPYD MSFT ADI SAN AIT O ELE WM AGS NDA V
- exactly 12 Graham 2.0 score labels
- Achievement System v2 present
- Interaktívny checklist present
- Dividendy present
- Vklady present
- Mesačný denník portfólia present
- Slovník skratiek a pojmov present
- no unexpected loss of major sections
- post-deploy reconstructed HTML must equal dashboard_source.html

CURRENT STABLE VALIDATION
html open/close: PASS
strategy: PASS
earnings quality: PASS
12 tickers: PASS
12 score labels: PASS
achievements: PASS
checklist: PASS
dividends: PASS
deposits: PASS
monthly journal: PASS
glossary: PASS

RULE: A failed validation means NO DEPLOY.
