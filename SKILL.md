---
name: commercial-due-diligence
description: "End-to-end workflow for conducting Commercial Due Diligence (CDD) research, writing comprehensive reports, and generating interactive HTML dashboards. Use for: deep company research, competitive analysis, market sizing, and producing strategy consultant-grade deliverables."
---

# Commercial Due Diligence (CDD) Workflow

This skill provides a structured, two-phase workflow for conducting deep Commercial Due Diligence on a target company and producing high-quality, interactive deliverables.

## Phase 1: CDD Research & Report Generation

Conduct comprehensive research on the target company across multiple dimensions.

1. **Company & Product Research**: Analyze the company's homepage, product offerings, founding team, and funding history.
2. **Market & Competitive Landscape**: Size the Total Addressable Market (TAM) and identify direct/indirect competitors.
3. **Customers, Business Model & Financials**: Understand the pricing strategy, revenue model, and notable customer wins.
4. **Team & Leadership**: Investigate the founders' backgrounds, advisory board, and key investors.

After gathering all necessary information, compile a comprehensive CDD report.
Read `/home/ubuntu/skills/commercial-due-diligence/references/cdd-report-structure.md` for the required report structure.

Convert the final Markdown report to PDF format using the `manus-md-to-pdf` utility.

## Phase 2: Interactive HTML Dashboard Generation

Transform the comprehensive CDD report into a polished, self-contained interactive HTML dashboard suitable for presentation to clients or investment committees.

1. Read `/home/ubuntu/skills/commercial-due-diligence/references/html-dashboard-prompt.md` to get the exact prompt specification for the dashboard.
2. Use the prompt to generate a single, self-contained HTML file containing all 6 tabs, interactive charts (using Chart.js via CDN), competitive positioning maps, and print-to-PDF functionality.
3. Ensure the design strictly follows the McKinsey/Bain aesthetic (Dark navy #0A2342 + white + gold accent) and includes confidence indicators (🟢 High / 🟡 Medium / 🔴 Low).
4. Preview the generated HTML file in the browser to verify that all tabs, charts, and interactive elements render correctly.

## Delivery

Deliver both the final PDF report and the interactive HTML dashboard to the user.
