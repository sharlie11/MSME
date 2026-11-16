# Merchant Master
### Making Credit Readiness Easier for Small Businesses

## About

Getting a business loan is not always easy, especially for small shop owners and micro-businesses. Many of them run their businesses successfully but don't have properly organised financial records. Sales details may be in notebooks, purchase bills may be stored separately, and most transactions may happen through UPI.

When they approach a bank for a loan, arranging all this information and understanding the required documents becomes difficult.

We came up with Merchant Master to address this problem.

Merchant Master is a platform that helps small business owners organise their business records, understand their financial position and find suitable government schemes and credit opportunities. The idea is to make the process less confusing, especially for business owners who may not have much knowledge of financial documentation.

## What are we planning to build?

The platform will allow business owners to create a basic business profile and upload their financial documents. Using AI-based document processing, the system will extract useful details from invoices and bills and organise them.

Based on the available information, it will generate financial summaries so that business owners can get a clearer picture of their sales, purchases and expenses.

We also plan to include a scheme discovery feature that helps users find government schemes based on their business details. Another important part is credit readiness, where the platform checks available information against published lender requirements and shows what documents are still needed.

Our aim is not just to show information but to help users understand what they need to do next.

## Main Features

- Business profile creation and onboarding.
- Uploading invoices, purchase bills and other financial documents.
- Extracting and organising financial information using OCR.
- Generating sales, purchase and expense summaries.
- Finding relevant government schemes.
- Checking documents against available credit requirements.
- Preparing application checklists and tracking progress.

## How AI is Used

We are planning to use a multi-agent AI architecture for this project.

Instead of handling every task through one AI model, we divide the work between specialised agents.

- **Business Understanding Agent:** Understands the business and its requirements.
- **Document Intelligence Agent:** Extracts information from uploaded documents.
- **Financial Analysis Agent:** Prepares financial summaries using the extracted data.
- **Scheme Discovery Agent:** Finds government schemes and checks their published conditions.
- **Credit Readiness Agent:** Identifies missing information and documents.
- **Verification Agent:** Checks calculations and information before presenting the results.

A central Orchestrator Agent manages these tasks and coordinates the agents based on what the user needs.

## Technologies We Plan to Use

| Area | Technology |
|---|---|
| Frontend | React, TypeScript, Tailwind CSS |
| Backend | Python, FastAPI |
| AI Agent Workflow | LangGraph |
| LLM | Gemini / Ollama |
| Document Processing | PaddleOCR |
| Data Analysis | Pandas |
| Database | PostgreSQL |
| Vector Search | pgvector |
| Authentication | Supabase |

## Development Approach

We plan to develop the platform in stages, starting with business registration, document upload and financial data extraction. Once these basic features are working, we will integrate the financial analysis and scheme discovery modules, followed by the credit readiness and multi-agent workflow.

We also want to make sure that the information shown to users is understandable and supported by reliable sources.

## What We Hope to Achieve

Through Merchant Master, we want to reduce the difficulty small business owners face when preparing financial information for formal credit. We hope the platform will help them understand their business records better, become aware of available government support and prepare their applications with more confidence.

## Future Plans

In the future, we would like to add regional language support, improve document recognition for different invoice formats and explore secure integrations with financial data sources.

## Useful References

- [myScheme – Government Schemes](https://www.myscheme.gov.in/)
- [Udyam Registration](https://www.udyamregistration.gov.in/)
- [MUDRA](https://www.mudra.org.in/)
- [Reserve Bank of India](https://www.rbi.org.in/)

---

*Merchant Master is a hackathon project focused on making financial preparation simpler and more accessible for micro and small businesses.*
