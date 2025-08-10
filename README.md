
⚠️ **Disclaimer**  
This repository contains demonstration code and synthetic data for AI Ethics PoCs.
It is not production-ready. Unauthorized commercial use is prohibited.

# AI Compliance Self-Assessment Tool

**Author:** Grimaldi Roberto | AI Ethics  
Self-assess AI projects against EU AI Act + FINMA and generate audit-ready reports.

## Setup
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Logical Steps
1. Intake project metadata (purpose, data, model type, impact).
2. Classify risk level; map required controls (EU AI Act + FINMA).
3. Generate evidence checklist and assign owners.
4. Compute readiness score; highlight gaps & deadlines.
5. Export PDF audit pack; version for traceability.
6. Schedule quarterly re-assessment.
7. Track model fleet coverage in dashboard.

## KPIs
- Business: Compliance cost ↓ ≥20%.
- Ethics: 100% risk classification coverage.
- Compliance: Zero critical findings in pre-audit.

## Files
- `app.py` — Streamlit app.
- `rules/*.yaml` — rule sets.
- `reports/compliance_report.pdf` — generated output.
- `assets/cover.png` — cover image placeholder.
