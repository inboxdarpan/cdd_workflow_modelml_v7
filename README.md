# Commercial Due Diligence (CDD) Skill

This project contains the **`commercial-due-diligence`** skill, an end-to-end workflow designed for autonomous AI agents to conduct deep Commercial Due Diligence (CDD) research, write comprehensive reports, and generate interactive HTML dashboards.

## Overview

The skill transforms a general-purpose AI agent into a specialized strategy consultant capable of executing a structured, two-phase workflow:

1. **Phase 1: CDD Research & Report Generation**
   - Conducts comprehensive research on a target company across multiple dimensions (Company & Product, Market & Competitive Landscape, Business Model & Financials, Team & Leadership).
   - Compiles findings into a structured, multi-section Markdown report.
   - Converts the final report into a professional PDF document.

2. **Phase 2: Interactive HTML Dashboard Generation**
   - Transforms the comprehensive CDD report into a polished, self-contained interactive HTML dashboard.
   - The dashboard is designed for presentation to clients or investment committees, featuring a McKinsey/Bain aesthetic, interactive charts (via Chart.js), competitive positioning maps, and print-to-PDF functionality.

## Skill Structure

The skill is organized into the following components:

- **`SKILL.md`**: The main workflow guide that instructs the AI agent on how to execute the two-phase CDD process.
- **`references/cdd-report-structure.md`**: A detailed template outlining the required sections and content for the comprehensive CDD report.
- **`references/html-dashboard-prompt.md`**: A precise, reusable prompt specification for generating the interactive HTML dashboard, ensuring consistent design, structure, and interactivity.

## Usage

This skill is intended to be used by an autonomous AI agent (like Manus). When a user requests a commercial due diligence report or an interactive CDD dashboard for a specific company, the agent will trigger this skill and follow the defined workflow.

### Example Triggers

- "Run a full commercial due diligence on [Company Name]."
- "Create an interactive HTML CDD dashboard for [Company Name]."
- "Research [Company Name] and its competitors, and provide a comprehensive CDD report."

## Output Deliverables

Upon successful execution, the skill produces two primary deliverables:

1. **Comprehensive CDD Report (PDF)**: A detailed, well-structured document covering all aspects of the target company and its market.
2. **Interactive HTML Dashboard (.html)**: A self-contained, presentation-ready dashboard with interactive elements, visualizations, and a professional design.

## Note on Skill Design

Skills are modular, self-contained packages that extend an AI agent's capabilities by providing specialized knowledge, workflows, and tools. They are designed to be read and executed by the agent, not directly by human users. This README serves as external documentation for human reference.
