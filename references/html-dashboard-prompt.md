# HTML Dashboard Prompt Template

When generating the interactive HTML CDD dashboard, use the following exact prompt structure to ensure consistency and high quality.

```markdown
Using the full CDD report you just produced on [COMPANY NAME], Assemble a single interactive HTML dashboard that a strategy consultant could present to a client or investment committee.

The dashboard must include:

STRUCTURE:
- Header: "[COMPANY NAME] — Commercial Due Diligence" with today's date and a confidence rating badge
- Tabbed navigation with 6 tabs:
  1. Executive Summary
  2. Market Size & Growth
  3. Competitive Landscape (visual positioning map or comparison table)
  4. Business Model & Revenue Signals
  5. Strategic Priorities & Revenue Opportunities
  6. Key Risks

DESIGN REQUIREMENTS:
- Clean, professional — McKinsey/Bain aesthetic, not a startup landing page
- Dark navy + white + accent colour (#0A2342 as primary)
- Each tab has a "Key Takeaway" callout box at the top (1–2 sentences)
- Confidence indicators on data points (🟢 High / 🟡 Medium / 🔴 Low)
- All data cited inline with source references

INTERACTIVITY:
- Tab switching (no page reload)
- Collapsible sections for detailed data
- Hover tooltips on competitor comparison table
- A "Download / Print to PDF" button

Output a single self-contained HTML file. No external dependencies except CDN-hosted CSS/JS (Tailwind or Bootstrap OK).
```
