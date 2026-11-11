# Gerson Castillo

**Digital Finance Transformation** · finance leadership, systems, data and AI

Seventeen years in finance, building the tools my teams needed along the way. I work where the finance function meets its systems: from the business problem to the specification, the build with IT, user acceptance and adoption. When code is the fastest way to get it right, I write it.

## Projects

### Azhum · financial-intelligence platform

**[Azhum](https://azhum.com)** is a platform I designed, built and run in production on Microsoft Azure (EU). The code is private; the reporting demo is public, no sign-up, at **[azhum.com](https://azhum.com)**.

- **What it does:** a cost and profitability accounting engine opens the P&L by customer, business line, cost centre or project and keeps every figure traceable to its journal entry. A reporting layer sits on top. **Lumen**, an LLM agent layer, investigates causes and proposes actions with the evidence attached.
- **How it is built:** a .NET solution in three layers and nine projects, with a code module and a database per client. Data moves from raw to core to a star-schema mart that is read only through views.
- **Data flow:** ingestion with Azure Functions in Python; engines in C# for the cube, accruals, financial statements and KPIs.
- **Lumen:** a four-route router and an analyst agent with 23 governed tools. Every figure it returns is labelled as asserted, cross-checked, reference or prediction, with human approval in the loop.

### MSc thesis · valuing unlisted companies with machine learning

An application that values unlisted companies and writes the valuation report: a CatBoost model for the revenue multiple, neural networks (Keras) for the cost of capital, SHAP for explainability, and an LLM that drafts the narrative under guardrails. Built by a team of six as microservices (FastAPI, Flask, React and TypeScript, Docker). I led the project, designed the methodology and the architecture, and wrote half of the backend. The code is private.

### Earlier work

- In-house finance systems for an FMCG distributor (.NET, SQL, Power BI): treasury integrated with SAP Business One and an e-commerce platform for around 40,000 retail customers.
- A .NET and SQL Server application that prepares client accounting data before it is loaded into a consolidation platform.

## Digital Finance Transformation: what I do

- **Process and operating model:** record to report, procure to pay, order to cash.
- **Management and cost accounting:** P&L by customer, business line, route or asset, reconciled to the statutory close.
- **Finance systems:** functional specification, ERP integration, portals, release governance with IT, UAT and adoption.
- **Close, consolidation and reporting:** IFRS and Spanish GAAP, IFRS 16.
- **AI agents with governance:** tool use, traceable evidence and human approval.

## Technologies

| Area | What I use |
|---|---|
| Languages | C#, Python, SQL |
| Application | .NET 8, Blazor Server, Entity Framework Core, REST APIs |
| Data and BI | SQL Server, Azure SQL, data modelling, Power BI, Power Query |
| Cloud | Microsoft Azure: App Service, Azure Functions, Entra ID, Key Vault, Blob Storage, Application Insights |
| AI | LLM agents with tool use, Claude (Anthropic SDK), Microsoft Agent Framework, Microsoft.Extensions.AI, prompt and workflow design |
| Machine learning | CatBoost, Keras, SHAP (MSc thesis) |
| Finance systems | Dynamics 365 Business Central, SAP Business One, Oracle APEX, Lucanet and AMANA, consolidation (EPM) software |
| Also used | FastAPI, Flask, React and TypeScript, Docker (MSc thesis) |
| Tooling | Git, GitHub Actions, Visual Studio, VS Code, AI-assisted development |

## Background

Head of finance, with IT reporting in; Deputy CFO of a Spanish transport and logistics group; implementation lead for a financial-consolidation SaaS across Iberia and Latin America. Degree in Public Accounting, Law degree, MSc in Big Data, Data Science & AI (Universidad Complutense de Madrid).

## Public here

Coursework and experiments from the MSc: financial-market prediction with CNNs, RNNs and embeddings, news sentiment with FinBERT, and classic machine learning. My production work lives in private repositories.

---

[gersoncastillo.com](https://gersoncastillo.com) · [LinkedIn](https://www.linkedin.com/in/gersoncastillolorenzo) · [azhum.com](https://azhum.com)
