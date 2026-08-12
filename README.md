# AI Contract Intelligence Platform

An autonomous multi-agent AI system for reviewing contracts, identifying risky clauses, checking compliance, and generating negotiation recommendations.

## Project Overview

The AI Contract Intelligence Platform automates commercial contract analysis using specialized AI agents.

The system can:
- Review contracts
- Extract and compare important clauses
- Detect legal and commercial risks
- Check compliance requirements
- Recommend negotiation changes
- Generate a structured final report

## Multi-Agent Architecture

The platform consists of five specialized agents:

1. **Contract Reviewer** – Extracts key provisions such as SLA, liability, termination, and privacy clauses.
2. **Clause Comparator** – Compares clauses against standard commercial terms.
3. **Risk Detector** – Identifies risks and assigns a normalized risk score.
4. **Compliance Checker** – Checks governing-law and jurisdiction-specific requirements.
5. **Negotiation Advisor** – Combines the findings and generates negotiation recommendations.

## Tech Stack

- Python 3.10+
- Google Colab
- Gemini API / SDK
- Pydantic
- Multi-agent architecture

## How to Run

1. Open the notebook:
   [Open in Google Colab](YOUR_COLAB_LINK)

2. Add your Gemini API key when prompted.

3. Run the notebook cells sequentially.

4. Provide the contract text for analysis.

5. The agents will process the contract and generate the final structured report.

## Example Output

The system identifies:
- High-risk clauses
- Compliance concerns
- Recommended redlines
- Negotiation strategy
- Final status such as `APPROVED` or `REQUIRES_REVISION`

## Repository Structure

```text
AI-Contract-Intelligence-Platform/
│
├── AI_Contract_Intelligence_Platform.ipynb
└── README.md
