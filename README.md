The Multi-Agent Research Assistant is an AI-powered research automation system built in n8n that performs comprehensive company research using multiple specialized AI agents.
Instead of relying on a single AI model, the workflow distributes tasks across dedicated agents, each responsible for gathering specific types of information, and then combines the results into a structured research report.
The workflow accepts a company name as input and uses a supervisor agent to coordinate multiple research agents.
Each agent performs a specialized task:
Company Research Agent – Collects company overview, products, services, industry, and key information.
Website Research Agent – Scrapes and analyzes content from the company website.
Social Media Agent – Finds and analyzes LinkedIn and Instagram profiles.
Review Analysis Agent – Collects customer reviews and sentiment insights.
Web Search Agent – Uses Tavily Search to gather recent online information and news and outputs the results in the chat output.
