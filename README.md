# Data Automation Portfolio

Data analysis and workflow automation projects built around real problems in nonprofit, human services, finance, and business operations.

## About Me

I'm a data and automation practitioner with about seven years in monitoring and evaluation, case management, and workforce development across nonprofit and public sector settings. That background shapes how I approach data: I start with the program question, then build the pipeline, analysis, or automation that answers it.

**Education**
- Master of Science in Rural Development Studies
- Post Graduate Program in AI Agents for Business Applications, McCombs School of Business, The University of Texas at Austin in Collaboration with Great Learning

**Tools:** SQL, Excel (Power Query, XLOOKUP, dashboards), Power BI, Python (pandas), n8n, OpenAI, Vector databases (Pinecone), Supabase

## Projects

| Project | What it does | Tools | Status |
|---|---|---|---|
| [ShopNest Ticket Intelligence](./shopnest-ticket-intelligence) | Analyzes and categorizes customer support tickets with an automated workflow | n8n, AI agents | Completed |
| [Driving Investment Performance through Grounded Synthesis](./investment-grounded-synthesis) | RAG research assistant that answers broker questions across 500 news articles, 500 price records, and a 126-page 10-Q filing (1,528 indexed chunks), citing sources and declining to answer when evidence is missing. An LLM judge scores every answer on relevance, groundedness, completeness, and citation quality; tuning retrieval depth raised the top test case from 3.0 to 4.5 out of 5 | n8n, OpenAI, Pinecone, RAG | Completed |
| [Last-Mile Delivery Exception System](./last-mile-delivery-exceptions) | Multi-agent system that filters noisy delivery logs, decides resolutions, writes tier-appropriate customer messages, and escalates cases to a supervisor. Scored 100% on all five evaluation metrics after one fix, up from 80% on the first run | n8n, OpenAI, RAG, Python, SQLite | Completed |
| Program Reporting Automation | Simplifies meal count and reimbursement reporting using sample data | Excel, Power Query | Planned |
| Program Outcomes Dashboard | Tracks service utilization and outcome indicators for a human services program | SQL, Power BI | Planned |
| [HavenTally](https://github.com/Diddy-Syl/HavenTally) | Household budget tracking web app with a seven-table database for accounts, transactions, bills, and debts | React, Vite, Supabase | In progress |

Each project folder includes its own README covering the problem, approach, results, and how to run it.

## How This Repo Is Organized

```
Data-Automation-Portfolio/
├── README.md
├── shopnest-ticket-intelligence/
├── investment-grounded-synthesis/
├── last-mile-delivery-exceptions/
└── ...
```

Each project folder contains its workflow files (n8n JSON exports), sample data, and a project README.

## A Note on Data

All datasets in this repo are synthetic, course-provided, or anonymized. No real client, employer, or personal data is included, and no API keys or credentials are stored here.

## Contact

- GitHub: [Diddy-Syl](https://github.com/Diddy-Syl)
- LinkedIn: [Diddy-Syl George](https://www.linkedin.com/in/diddy-syl-george)
