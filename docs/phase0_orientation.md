# 📌 Phase 0: Orientation

This document summarizes my personal orientation phase as I begin transitioning into the data analytics field. 
It’s not meant as a tutorial, but as a reflection and reference of what I’ve learned, understood, and clarified for myself.

---

## 🎯 Purpose of This Phase

This orientation phase sets the foundation for everything that follows in my transition into data analytics.  
It helped me build a clear mental map of the field by focusing on:

* Understanding what data analysts *actually* do in the real world
* Exploring how different data-related roles compare (e.g. BI, functional, junior, engineering, science)
* Surfacing common misconceptions about analyst roles and expectations
* Mapping out the core tools used across the field and their purposes
* Understanding the typical workflow of a data analyst from start to finish
* Learning what “good” outputs look like (dashboards, KPIs, reports)
* A glossary of essential terms for future reference

---

## 👤 Analyst Roles & Responsibilities

### 🧪 Data Analyst
> A Data Analyst is the engine of daily data work — turning messy numbers into useful answers.  
> They’re the bridge between raw data and everyday business questions, but not the architect of systems, strategies, or predictive models.

“Data Analyst” is sometimes used as a broad label for anyone working with data, but in practice, it's also a well-defined job title with specific expectations, tools, and business value. 
It sits at the heart of many analytics teams — highly practical and execution-focused.

A Data Analyst is the most hands-on role when it comes to turning raw data into insights that directly support business decisions. Their core responsibility is to **explore, clean, and interpret** data to answer specific questions. 
They typically work with existing datasets (from Excel, SQL databases, BI tools, etc.) and deliver reports, charts, and summaries that help others understand what’s going on — and why.

#### What They *Are*:
- Focused on **descriptive and diagnostic** analysis (what happened, why did it happen)
- Fluent in tools like **Excel**, **SQL**, **Power BI/Tableau**, and optionally **Python/pandas**
- Tasked with turning raw data into **clear, actionable business answers**
- Often working alongside marketing, finance, ops, or product teams

#### What They *Are Not*:
- Not responsible for building data pipelines — that’s the **Data Engineer’s** role
- Not defining business processes — that’s for **Business** or **Functional Analysts**
- Not focused on statistical modeling or ML — that’s for **Data Scientists** or **Quants**
- Not the owners of complex dashboard infrastructure — that usually falls to **BI Analysts**

#### In summary:
- Cleans, explores, and analyzes raw data  
- Answers business questions using trends, metrics, and comparisons  
- Creates dashboards, reports, and KPIs to communicate findings clearly

#### Tools They Use:
Excel, SQL, Power BI or Tableau, and optionally Python (pandas, Jupyter)

### 📊 Business Analyst
> A Business Analyst connects people, processes, and data.  
> They help organizations define what they need, why they need it, and how success should be measured — often long before any data is touched.

Unlike data analysts who primarily focus on data exploration and reporting, Business Analysts operate **upstream**: identifying business problems, gathering stakeholder requirements, and translating those into project goals, specifications, or process changes. 
They often work between technical teams (engineers, analysts, developers) and non-technical departments (marketing, operations, HR).

Business Analysts may work with data, but it’s usually not their core task. Their strength lies in understanding how systems, processes, and goals connect — and ensuring that what gets built or analyzed actually solves the right problem.

#### What They *Are*:
- Focused on **requirement gathering**, **process understanding**, and **goal alignment**
- Skilled at communicating with **stakeholders**, **end users**, and **technical teams**
- Often involved early in projects — helping **frame the questions**, not just answer them
- Fluent in business models, documentation, and frameworks like SWOT, flowcharts, UML

#### What They *Are Not*:
- Not responsible for exploring datasets — that’s the **Data Analyst’s** job
- Not designing dashboards or running SQL — that’s typically the realm of **BI Analysts** or **Data Analysts**
- Not creating models or writing production code — they don’t operate as **engineers** or **scientists**
- Not tied to a single tool — their power is in communication and clarity, not code

#### In summary:
- Gathers and clarifies business needs  
- Translates those needs into functional specifications or data questions  
- Supports project scoping, prioritization, and outcome definition

#### Tools They Use:
Documentation platforms (Confluence, Notion), flowcharting tools (Lucidchart, Draw.io), spreadsheets, sometimes basic SQL or BI tools

### 🧠 BI Analyst (Business Intelligence Analyst)
> A BI Analyst transforms raw data into structured, repeatable, visual reporting — building the dashboards, metrics, and reporting systems that organizations rely on to track performance and make decisions.

While a Data Analyst answers *ad hoc questions*, a **BI Analyst** focuses on building **ongoing, scalable reporting systems**. 
Their job is to define KPIs, model data for reporting, and build or maintain dashboards that provide visibility across departments.
They are often the ones making sure that dashboards are **reliable**, **automated**, and **tailored to decision-makers**, not just technically accurate. 
They sit closer to the business than engineers, but deeper in tooling than business analysts. *(See 'Difference from Business Analyst' below)*

#### What They *Are*:
- Experts in **dashboarding**, **reporting tools**, and **KPI logic**
- Often responsible for maintaining **data models** or **semantic layers** within tools like Power BI, Looker, or Tableau
- Serve as the **bridge between raw data and executive-ready visual output**
- Frequently collaborate with both analysts and business stakeholders

#### What They *Are Not*:
- Not involved in raw requirement gathering — that’s more for a **Business Analyst**
- Not usually exploring messy datasets or running one-off queries — that’s the **Data Analyst’s** domain
- Not building the data pipelines underneath dashboards — that’s handled by **Data Engineers**
- Not doing advanced stats, forecasting, or ML — they’re not **Data Scientists**

#### Difference from Business Analyst:
A **Business Analyst** focuses on *what* needs to be built and *why*, based on stakeholder needs and process mapping.  
A **BI Analyst** focuses on *how* performance is measured and *what to report on*, by creating scalable metrics and visuals.
In essence, BI analysts are focused on understanding what has happened and why, while business analysts are focused on improving how things are done.

- Business Analyst: “We need to track customer retention because it’s hurting our revenue.”  
- BI Analyst: “Here’s a dashboard that shows customer retention by cohort and churn triggers.”

#### In summary:
- Designs and owns dashboards, reports, and KPIs  
- Translates data into ongoing performance tracking tools  
- Makes data accessible, timely, and meaningful to non-technical users

#### Tools They Use:
Power BI, Tableau, Looker, Google Data Studio, SQL, Excel, DAX, LookML, possibly some Python for integration

### 🛠 Junior Analyst / Reporting Assistant
*! This isn’t a distinct domain, but an early-career version of the analyst track.*

> A Junior Analyst supports the data team by handling routine tasks — cleaning data, running basic queries, refreshing reports — while learning the tools and workflows of full-fledged analysts.

This role is often an **entry point** into the analytics field. 
Junior Analysts may not yet be solving complex problems, but they are essential in helping the team stay productive by handling day-to-day maintenance, simple data pulls, or preparing datasets for others to use.
They often shadow more senior analysts, assisting in tasks while building their technical and analytical confidence. Over time, this role is meant to evolve into a full Analyst position.

#### What They *Are*:
- Early-career analysts supporting a data team
- Tasked with **repetitive but important work** (data prep, formatting, refreshing reports)
- Often learning through **mentorship and hands-on practice**
- Useful across many domains — marketing, ops, finance, HR, etc.

#### What They *Are Not*:
- Not expected to lead analysis or build dashboards from scratch (yet)
- Not responsible for gathering business requirements or defining KPIs
- Not deeply involved in modeling, engineering, or stakeholder communication
- Not specialists — their role is often general and reactive

#### In summary:
- Assists more experienced analysts with foundational tasks  
- Provides support across data cleaning, formatting, reporting  
- Learns by doing — with potential to grow into more autonomous work

#### Tools They Use:
Excel, SQL (basic), Power BI or Tableau (as end users or light editors), shared dashboards, task management tools (e.g. Jira, Trello)

### 🧼 Data Steward / Data Quality Analyst
> A Data Steward ensures that data is accurate, consistent, well-documented, and trustworthy — acting as the guardian of data integrity across systems and teams.

This role isn’t about answering business questions or visualizing data — it’s about **ensuring the data is reliable enough** for others to do so. 
Data Stewards define what data means, monitor for quality issues, track lineage, and ensure compliance with data governance standards. 
They often act as the bridge between business teams (who need clear definitions) and technical teams (who manage the infrastructure).

While sometimes considered non-technical, this role requires deep attention to detail, excellent documentation habits, and strong communication skills.

#### What They *Are*:
- Focused on **data correctness, consistency, and documentation**
- Responsible for defining **business terms, KPIs, and field-level metadata**
- Proactive in **flagging issues**, monitoring anomalies, or maintaining data dictionaries
- Often embedded within analytics, operations, or governance teams

#### What They *Are Not*:
- Not conducting exploratory analysis or answering data questions — that’s for **Data Analysts**
- Not building dashboards — that’s for **BI Analysts**
- Not engineering data flows or pipelines — handled by **Data Engineers**
- Not gathering business needs or running workshops — more typical of **Business Analysts**

#### In summary:
- Maintains and enforces standards around data definitions and quality  
- Enables analysts and business users to work with consistent, reliable datasets  
- Operates across teams to promote trust in shared data sources

#### Tools They Use:
SQL, data catalog tools (e.g. Alation, Collibra, Atlan), Excel, issue trackers (Jira), internal documentation tools (Confluence, Notion), metadata managers, sometimes profiling tools or basic dashboards

### ⚙️ Functional Analyst
> A Functional Analyst ensures that business processes and software systems align — translating what users need into how systems should behave.

This role sits between business and IT. Functional Analysts focus on **understanding workflows, documenting system requirements, and validating implementations**. 
They often work on software projects (e.g. ERP, CRM, internal tools) where business logic needs to be correctly embedded into system features and integrations.

Unlike Business Analysts who focus more on goals and strategy, Functional Analysts deal with **how those goals are executed in tools and systems**, especially in tech-heavy environments.

#### What They *Are*:
- Experts in mapping **business processes to system behaviors**
- Focused on **validating**, **specifying**, and sometimes **testing** technical solutions
- Skilled in writing user stories, use cases, and flow diagrams
- Often work closely with **developers, architects, and QA teams**

#### What They *Are Not*:
- Not performing data analysis — they don’t pull data or build dashboards
- Not responsible for KPIs or reporting — that’s for **BI or Data Analysts**
- Not focused on infrastructure — not a **Data Engineer**
- Not typically leading stakeholder strategy — that’s more for **Business Analysts**

#### In summary:
- Bridges the gap between business requirements and system implementation  
- Translates functional needs into structured specs and flows  
- Ensures that tools and platforms reflect real-world business logic

#### Tools They Use:
Flowchart tools (Lucidchart, Draw.io), documentation systems (Confluence, Notion), task boards (Jira), business requirement templates, sometimes SQL or lightweight scripting to validate data behavior

### 🏗 Data Engineer
! *Not an analyst per se, but knowing what they do helps you work with them*

> A Data Engineer builds the pipelines, systems, and infrastructure that make clean, structured data available for analysts, dashboards, and applications.

While analysts focus on using data, **Data Engineers focus on moving and shaping it**. 
They design workflows that extract data from sources (like APIs, apps, or logs), transform it into usable formats, and load it into data warehouses or databases — a process known as **ETL (Extract, Transform, Load)** or **ELT**.

Data Engineers are highly technical. They often write production-grade code, maintain cloud-based infrastructure, and optimize systems for scale and reliability. 
Their work is mostly invisible to business users, but critical to everyone downstream.

#### What They *Are*:
- Builders of **data pipelines**, **ingestion systems**, and **data warehouses**
- Experts in managing **large datasets**, **scheduling**, and **transformation logic**
- Collaborators with analysts, BI developers, and data scientists to ensure usable data access
- Fluent in **cloud tools**, **SQL**, and **programming languages like Python or Scala**

#### What They *Are Not*:
- Not responsible for reporting, dashboards, or answering business questions — that’s for **Analysts**
- Not gathering stakeholder needs or writing process docs — that’s for **Business or Functional Analysts**
- Not focused on ML or statistical modeling — that’s the role of a **Data Scientist**
- Not always end-user-facing — often work “behind the scenes” to maintain infrastructure

Unlike *BI Analysts*, they don’t work in front-end tools; unlike *Data Scientists*, their goal isn’t modeling — it’s availability and reliability.

#### In summary:
- Designs and maintains the data architecture that analytics depends on  
- Moves data from sources to usable storage through automated, scalable pipelines  
- Makes analytics possible by ensuring clean, accessible, timely data

#### Tools They Use:
Python, SQL, Airflow, dbt, Spark, Kafka, cloud platforms (AWS, GCP, Azure), data warehouses (Snowflake, BigQuery, Redshift), Docker, Git, APIs, command-line tools

### 🔬 Data Scientist
! *Often confused with data analysts by outsiders, useful to know what sets it apart*

> A Data Scientist builds models and algorithms that help predict future outcomes, uncover deep patterns, or automate decision-making using statistical and machine learning techniques.

Where Data Analysts look at **what happened**, Data Scientists focus on **what will happen** or **why it matters statistically**. 
They work with large, sometimes unstructured datasets and apply mathematical models to forecast trends, cluster behaviors, or classify data points. 
Their goal is to generate insight at scale — often using code-heavy tools and research-like methods such as through experiment design or A/B testing.

This is one of the most technical roles in the data space, often requiring strong backgrounds in statistics, math, and programming. 
However, in many teams, they also collaborate with analysts to ensure their models are used in real decision-making.

#### What They *Are*:
- Experts in **statistics**, **machine learning**, and **experimental design**
- Builders of models for **prediction**, **classification**, **clustering**, or **recommendation**
- Skilled in **data wrangling**, **feature engineering**, and **model validation**
- Comfortable working with **large datasets** and **high-dimensional problems**

#### What They *Are Not*:
- Not responsible for maintaining data pipelines — that’s the **Data Engineer’s** role
- Not focused on building dashboards or recurring reports — handled by **BI Analysts**
- Not gathering business requirements or system specs — that’s for **Business/Functional Analysts**
- Not necessarily plugged into operational data workflows unless the company is mature enough to deploy models

#### In summary:
- Uses advanced math and programming to generate predictions or classify data  
- Builds models that inform strategy, automation, or product features  
- Often bridges research, experimentation, and scalable data solutions

#### Tools They Use:
Python (NumPy, pandas, scikit-learn, TensorFlow, PyTorch), Jupyter Notebooks, SQL, R, Git, cloud notebooks (Google Colab, SageMaker), data visualization tools (Matplotlib, seaborn, Plotly), Docker, cloud environments (GCP, AWS, Azure)

---

## 📌 Field-Specific Analyst Roles
There are many analyst job titles that apply core data analysis skills within specific industries or domains. 
These roles often overlap with general analyst functions but are shaped by the business context.

Legend:
🧪 Data Analyst
📊 Business Analyst
🧠 BI Analyst
🛠 Junior Analyst *(Can be applied to any and all field-specific roles)*
🧼 Data Steward / Quality *(May be embedded in any industry, ensuring integrity of the data feeding any and all roles)*
⚙️ Functional Analyst *(Overlaps where business logic meets tools — useful framing in complex orgs)*
🏗 Data Engineer *(Not directly represented in most field-specific titles, but support them behind the scenes (with the exception of Quant))*
🔬 Data Scientist *(Not directly represented in most field-specific titles, but support them behind the scenes (with the exception of Quant))*

Field-specific roles:
- ** 📊 Financial Analyst** – Budget forecasting, investment analysis, and financial planning
- ** 📊 Market Analyst** – Consumer behavior, trend forecasting, market segmentation
- ** 🧪 Product Analyst** – Feature usage tracking, product performance metrics, user journey analysis
- ** 🧪 📊 Operations Analyst** – Logistics optimization, efficiency analysis, internal performance tracking
- ** 🧪 📊 🧠 Risk Analyst** – Risk modeling, fraud detection, insurance metrics
- ** 🔬 🏗 Quantitative Analyst (Quant)** – Statistical modeling and algorithmic trading (often in finance)
- ** 🧪 Healthcare Analyst** – Patient outcome tracking, hospital operations, public health data analysis
- ** 🧪 Customer Insights Analyst** – Customer satisfaction, churn prediction, survey analysis
- ** 🧪 Retail Analyst** – Inventory optimization, POS data insights, store performance
- ** 🧪 E-commerce Analyst** – Funnel conversion tracking, sales forecasting, website analytics
- ** 🧪 HR Analyst / People Analyst** – Workforce metrics, retention, recruitment performance
- ** 🧠 Supply Chain Analyst** – Vendor metrics, shipping efficiency, inventory turnover
- ** 🧪 Manufacturing Analyst** – Process monitoring, defect tracking, throughput analysis
- ** 🧪 Telecom Analyst** – Call data records, network performance, usage patterns
- ** 🧠 Energy Analyst** – Grid data, fuel usage, forecasting consumption trends
- ** 🧪 Sports Analyst** – Performance metrics, scouting data, game statistics
- ** 🧪 Real Estate Analyst** – Property valuation, housing market trends, ROI analysis
- ** 🧠 Media Analyst** – Audience measurement, ad performance, content engagement
- ** 🧪 Environmental Data Analyst** – Climate data, pollution tracking, sustainability KPIs
- ** 🏗 Cybersecurity/Data Security Analyst** – Anomaly detection, intrusion data, access monitoring (slightly outside the pure data track, but fits on the edge of engineering)

These roles often require combinations of general data analysis tools (Excel, SQL, Python, dashboards) but tailor their KPIs, outputs, and methods to their field’s needs.

---

## ⚠️ Common Misconceptions About Data Roles

Examples (to be expanded on, maybe in relation to above roles):
“Data analysis is just about making dashboards” -> (explain further)
“All analysts write code” -> (explain further)
“You need a math degree” -> (explain further)

---

## 🛠️ Tools & Their Purposes

| Tool                            | Purpose                                                                  |
| ------------------------------- | ------------------------------------------------------------------------ |
| **Excel**                       | Fast exploration, cleaning, summary stats, basic charts                  |
| **SQL**                         | Querying structured data from databases                                  |
| **Python**                      | Automated cleaning, analysis, and visualization                          |
| **Power BI / Tableau**          | Dashboarding and KPI reporting                                           |
| **Jupyter Notebooks**           | Interactive Python workspace for analysis, testing, and visual output    |
| **Git/GitHub**                  | Version control and collaboration on scripts, notebooks, and projects    |
| **Google Sheets**               | Lightweight spreadsheet analysis and collaborative dashboards            |
| **Looker / Qlik**               | Alternative BI tools used in some industries                             |
| **Google BigQuery / Snowflake** | Cloud-based data warehouses for large-scale querying                     |
| **R**                           | Statistical analysis and modeling (less common in business-facing roles) |

---

## 📈 What Makes a Good Dashboard / Report?

* Shows trends or comparisons over time
* Has clear, focused KPIs that match business goals
* Easy to read at a glance
* Explains *why* something matters — not just what the number is

### Example KPIs:

* Sales revenue per region
* Churn rate over time
* Average customer acquisition cost

---

## 🔄 Typical Workflow of a Data Analyst

1. **Understand the question or business problem**
2. **Find and gather the data** (Excel, database, API, etc.)
3. **Clean and transform** the data
4. **Explore** it for patterns, issues, trends
5. **Analyze** — answer the question with evidence
6. **Visualize** — dashboards or charts
7. **Communicate** the story and recommendations

---

## 📚 Resources Used in This Phase

*(To be filled in as I go — courses, videos, examples)*

* [ ] Add links to any videos watched
* [ ] Note useful articles or PDFs
* [ ] Mention specific dashboards explored

- CareerFoundry's "Get started in Data Analytics" playlist: https://www.youtube.com/playlist?list=PL4GEkVtNYGlLYrpgpLLy8KlyX0xf31YKE

---

## 💬 Personal Notes & Takeaways

*(To be filled in during or after logging)*

* [ ] What did I already intuitively know?
* [ ] What surprised me?
* [ ] What tools or ideas seem most exciting?
* [ ] What am I still unsure about?

---

## Glossary of Key Terms

**KPI** — 
**Metric** — 
**Dimension** — 
**ETL** — 
**Dashboard** — 
**Data pipeline** — 
(*expand further with other useful terms*)


---

*This document will evolve slightly as I finalize Phase 0 and move into the fundamentals.*
