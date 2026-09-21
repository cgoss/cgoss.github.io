# Colin Goss — Systems Analyst & Solution Architect

Source for my landing page at **[cgoss.github.io](https://cgoss.github.io)**.

---

## About

20+ years turning business requirements into working systems across healthcare, government, utilities
and financial services. I've held the **Systems Analyst** title at Alberta Health Services, the
Y.M.C.A., Alberta SPCA and Dasilva Group, and worked as a consultant or contractor at six more
organizations.

The work has been consistent throughout: sit down with the people who do the job, find out what they
actually need rather than what the change request says, model the data, document the system, and make
sure what gets built solves the real problem.

What makes that combination less common than it sounds is that I never stopped building. Twenty years
of C#/.NET and seventeen on SQL Server means a solution design arrives with an estimate behind it that
reflects what building it actually takes.

## What I do

- **Systems analysis** — requirements elicitation, business process analysis, gap and feasibility
  analysis, technical specifications, UAT support
- **Solution architecture** — domain-driven and data-model-first design, ERD and UML modelling, CQRS,
  integration design
- **.NET engineering** — C#, ASP.NET Core and MVC, Web API, Entity Framework, WPF, microservices with
  async service-to-service calls
- **Data and reporting** — SQL Server relational schema design, query and index optimization, data
  warehouse design, SSRS/SSIS/SSAS
- **Delivery** — CI/CD pipelines, Azure DevOps and Boards, Agile/Kanban, ITIL deployment validation
- **AI-assisted development** — daily hands-on Claude Code, plus a RAG pipeline in Python on
  PostgreSQL/pgvector

## A few things worth mentioning

**Setting a standard across teams I had no authority over.** At GE Intelligent Platforms, Proficy — a
mature enterprise WPF application of more than a million lines — needed internationalization. No
guidance existed for a codebase of that size and shape. I researched the approach from scratch,
authored the standard GE adopted, and built the tooling 100+ developers globally used to apply it.

**Finding the problem nobody was looking for.** At Alberta Health Services I traced a production
slowdown to reporting queries hitting the transactional database and separated the two, which fixed the
working day for everyone doing data entry. That didn't come out of a requirements workshop.

**Holding a position against the vendor.** At WorkSafeBC I found an Azure defect that deleted a
deployed artifact once it had been viewed, breaking our disaster-recovery design. Microsoft's
first-line answer was to rebuild and redeploy; I rejected it, because a rebuild on a different build
machine doesn't guarantee the same artifact. The defect was Azure-wide and was eventually fixed.

## Technology

| | |
|---|---|
| **Languages** | C#, SQL/T-SQL, JavaScript, Python, VB.NET, PowerShell |
| **Frameworks** | .NET / .NET Core, ASP.NET Core, MVC, Web API, Entity Framework, Dapper, Angular, React, Node.js, WPF |
| **Data** | SQL Server 6.5–2022, Oracle, PostgreSQL/pgvector, MongoDB, Elasticsearch, SSRS, SSIS, SSAS |
| **Cloud & delivery** | Azure (App Services, Functions, SQL), Azure DevOps, Octopus Deploy, TeamCity, Jenkins, GitLab CI/CD, AWS S3 |
| **Practice** | ERD and UML modelling, Jira and Confluence, Agile/Kanban, ITIL, OWASP, SonarQube, Claude Code |

## Work authorization

Canadian citizen and **TN-eligible under USMCA**. TN requires no petition, no filing fee, no cap and no
lottery — it's adjudicated at the border, and the only document a US employer provides is a letter of
intent to employ. **No sponsorship required.**

## This repository

A single static page — `index.html` with inline CSS, no build step and no dependencies. Deployed by
GitHub Pages.

```
index.html              the page
ColinGossCartoon.jpg    profile image
favicon.svg / .ico      icons
apple-touch-icon.png    iOS home screen icon
```

## Connect

- **LinkedIn** — [linkedin.com/in/colin-goss](https://linkedin.com/in/colin-goss)
- **GitHub** — [github.com/cgoss](https://github.com/cgoss)
- **Medium** — [@colin.goss](https://medium.com/@colin.goss) *(just getting started — first pieces going up shortly)*
- **Email** — colin.goss@gmail.com
