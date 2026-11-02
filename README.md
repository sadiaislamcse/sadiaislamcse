# Sadia Islam

I build AI agents that take over repetitive business work: CRM updates, research, and social media posting. Based in Dhaka, Bangladesh.

[Portfolio](https://sadiaislamcse.github.io) | [Email](mailto:sadiaislam881278@gmail.com) | [LinkedIn](https://www.linkedin.com/in/sadiaislamcse) | [Published paper](https://doi.org/10.1016/j.jpi.2024.100398)

## About

I am an Associate Web Developer at Accord Tech Solutions, and most of my work there is AI: Python agents that use browsers, APIs and LLMs to finish tasks people used to do by hand. I like building tools that non-technical teammates can run on their own.

I have a B.Sc. in Computer Science and Engineering from Daffodil International University and a published paper on explainable machine learning.

## Projects

### Multi-Agent CRM Automation
A main agent that runs specialized sub-agents for item listing and time billing. It reads work from Excel and updates a design-industry CRM across several accounts.

- Each sub-agent has its own instructions and shared code modules.
- Built for a client, so details are kept general.

**Stack:** Python, Playwright, openpyxl

### Salesforce CRM Agent
Finds active customers, researches each contact and their LinkedIn profile, and writes the results back into Salesforce and the CRM.

- Reuses an existing signed-in browser session and behaves like a person to avoid bot blocks.
- Delivered with a client handover guide: a PDF and an HTML page with copy-ready commands.

**Stack:** Python, Playwright (CDP-attach), openpyxl, Salesforce API

### SD TitleFinder Agent
Finds job titles and LinkedIn URLs for 1,460 contacts at 529 accounts.

- Accepts a match only when confidence is high enough.
- Saves progress as it goes and picks up where it stopped after an interruption.

**Stack:** Python, Playwright, Excel write-back

### CampaignScout Agent
Adds Google rating, review count, SEO score and AEO score to a list of 2,253 contacts from 925 staffing companies.

- Multi-agent structure with checkpoint and resume, plus command-line options.

**Stack:** Python, Google Places API, PageSpeed Insights

### Social Media AI Agent (script version)
Writes captions with an LLM, generates images, and publishes Facebook posts on its own. A Telegram bot controls it.

- Packaged in Docker and deployed on Railway with automated workflows.

**Stack:** Python, Groq LLM, Stability AI, Facebook Graph API, Telegram Bot API, Docker, GitHub Actions, Railway

### Social Media Automation (Make.com version)
The same posting workflow rebuilt so non-technical staff can run it. Approved rows in a Google Sheet pull captions and media from Google Drive and post to Facebook and Instagram on schedule.

- One branch per platform, content-code logic in IML formulas, Telegram alerts for success and failure.
- Scenario edited through the Make.com API, with media downloaded once per run to cut data transfer.

**Stack:** Make.com, Google Sheets, Google Drive, Facebook and Instagram Graph APIs, Telegram

### Smaller tools
- Job board agent that finds companies mentioning specific software in their job postings.
- Email verification agent using the Debounce API.
- Product scraper with retry and timeout handling (Selenium).

## Research

**[A Precise Machine Learning Model: Detecting Cervical Cancer Using Feature Selection and Explainable AI](https://doi.org/10.1016/j.jpi.2024.100398)**, Journal of Pathology Informatics, September 2024.
I built a feature-selected model to classify cervical cancer risk and used SHAP to explain its predictions.

## How I build

- One master instruction file for the project and one per agent, with shared code modules.
- Progress is saved after every unit of work, so a crash never means starting over.
- Written for the person who will run it: clear commands, plain notifications, a handover guide.
- Claude Code is my main development environment.

## Skills

| Area | Tools |
|---|---|
| AI and ML | LLM applications, agentic AI, multi-agent systems, prompt engineering, machine learning, deep learning, NLP, SHAP |
| Libraries | TensorFlow, PyTorch, Keras, Scikit-learn, Hugging Face, Pandas, NumPy |
| Automation and data | Python, SQL, Playwright, Selenium, BeautifulSoup, openpyxl, ETL pipelines, Make.com |
| APIs | REST, Salesforce, Facebook and Instagram Graph, Telegram Bot, Google Sheets and Drive |
| Deployment | Docker, Git and GitHub, GitHub Actions, Railway, VPS over SSH |

## Contact

Open to AI engineer and AI automation roles. Write to [sadiaislam881278@gmail.com](mailto:sadiaislam881278@gmail.com).
