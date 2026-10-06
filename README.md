<!-- =========================================================
     HERO
========================================================= -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=58A6FF&height=240&section=header&text=Beracah&fontSize=72&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=Software%20Engineering%20%7C%20Data%20%7C%20Automation%20%7C%20Intelligent%20Systems&descAlignY=58&descSize=15" width="100%" alt="Beracah hero banner" />

<br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&multiline=false&width=720&height=40&lines=Building+practical+systems;Software+%C2%B7+Data+%C2%B7+Automation+%C2%B7+AI;From+problem+%E2%86%92+design+%E2%86%92+ship;Controlled+intelligent+workflows" alt="Typing animation" />

<br>

<p>
  <em>
    Bachelor of Information Technology student building practical systems
    that turn problems into software, data, automation, and intelligent workflows.
  </em>
</p>

<br>

<p>
  <img src="https://img.shields.io/badge/Software_Engineering-161B22?style=for-the-badge&logo=visualstudio&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/Data-161B22?style=for-the-badge&logo=pandas&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/Automation-161B22?style=for-the-badge&logo=docker&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/Intelligent_Systems-161B22?style=for-the-badge&logo=openai&logoColor=58A6FF" />
</p>

<br>

<a href="#featured-projects">
  <img src="https://img.shields.io/badge/Projects-View_Work-238636?style=for-the-badge&logo=github&logoColor=white" />
</a>
&nbsp;
<a href="#technology">
  <img src="https://img.shields.io/badge/Stack-Explore-1F6FEB?style=for-the-badge&logo=stackoverflow&logoColor=white" />
</a>

<br><br>

<a href="https://github.com/MabasaBee603163">
  <img src="https://img.shields.io/badge/GitHub-MabasaBee603163-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
&nbsp;
<a href="https://www.linkedin.com/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="mailto:603163@student.belgiumcampus.ac.za">
  <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

</div>

<br>

---

<!-- =========================================================
     WHAT I BUILD
========================================================= -->

<h2 id="what-i-build">What I Build</h2>

<table>
<tr>
<td width="25%" align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="36" height="36" alt="Software" />
<br><strong>Software</strong><br>
APIs, auth, architecture
</td>
<td width="25%" align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="36" height="36" alt="Data" />
<br><strong>Data</strong><br>
Pipelines, analytics, ML
</td>
<td width="25%" align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="36" height="36" alt="Automation" />
<br><strong>Automation</strong><br>
Workflows and orchestration
</td>
<td width="25%" align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="36" height="36" alt="Intelligent Systems" />
<br><strong>Intelligent Systems</strong><br>
MCP, agents, controlled tools
</td>
</tr>
</table>

<details>
<summary><strong>How my work connects</strong></summary>

<br>

Across my projects: <strong>understand → design → automate → keep it safe and measurable.</strong>

```mermaid
flowchart LR
    A[Problem] --> B[Software]
    A --> C[Data]
    A --> D[Automation]
    A --> E[Intelligent Systems]
    B --> F[Practical Systems]
    C --> F
    D --> F
    E --> F
    F --> G[Govern · Secure · Transform · Predict]

    style A fill:#161B22,stroke:#58A6FF,color:#fff
    style F fill:#161B22,stroke:#3FB950,color:#fff
```

<br>

</details>

---

<!-- =========================================================
     FEATURED PROJECTS
========================================================= -->

<h2 id="featured-projects">Featured Projects</h2>

### CloudGuard

<strong>Cloud Governance · Automation · Intelligent Systems</strong>

A local-first cloud governance platform built around
<strong>detection, controlled remediation, human approval and auditability.</strong>

<p>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
&nbsp;
<a href="https://github.com/MabasaBee603163/CloudGuard">
<img src="https://img.shields.io/badge/VIEW_PROJECT-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
</p>

<details>
<summary><strong>Details</strong></summary>

<br>

<strong>Highlights:</strong> policy detection · remediation workflows · MCP-style tools · human approval gates · audit trails · AI auditor

```mermaid
flowchart LR
    A[Cloud Resources] --> B[Detect]
    B --> C[Evaluate Risk]
    C --> D{Approval Gate}
    D -->|Approved| E[Remediate]
    D -->|Rejected| F[Log]
    E --> G[Audit]
    F --> G
    G --> H[AI Auditor]
```

```mermaid
stateDiagram-v2
    [*] --> Detected
    Detected --> Evaluating
    Evaluating --> PendingApproval
    PendingApproval --> Approved: approve
    PendingApproval --> Rejected: reject
    Approved --> Remediating
    Remediating --> Audited: success
    Remediating --> Failed: error
    Failed --> PendingApproval: retry
    Rejected --> Audited
    Audited --> [*]
```

<br>

</details>

---

### BankOps AI MCP Server

<strong>Secure Operations · RBAC · Automation</strong>

AI-assisted banking ops prototype with
<strong>permissions, controlled tool access and auditability.</strong>

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/MCP-181717?style=flat-square&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/RBAC-161B22?style=flat-square&logo=auth0&logoColor=white" />
&nbsp;
<a href="https://github.com/MabasaBee603163/BankOps-AI-MCP-Server">
<img src="https://img.shields.io/badge/VIEW_PROJECT-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
</p>

<details>
<summary><strong>Details</strong></summary>

<br>

<strong>Highlights:</strong> RBAC · controlled tools · authz · workflow orchestration · audit logging

```mermaid
sequenceDiagram
    actor User
    participant Auth as Auth and RBAC
    participant Agent as AI Agent
    participant MCP as MCP Tool Server
    participant Ops as Banking Ops
    participant Audit as Audit Log

    User->>Auth: Authenticate
    Auth->>Agent: Role and permissions
    Agent->>MCP: Request tool action
    MCP->>Auth: Check boundary
    alt Allowed
        MCP->>Ops: Execute tool
        Ops-->>MCP: Result
        MCP->>Audit: Log event
        MCP-->>Agent: Response
    else Denied
        MCP->>Audit: Log denial
        MCP-->>Agent: Error
    end
```

```mermaid
erDiagram
    USER ||--o{ ROLE_ASSIGNMENT : has
    ROLE ||--o{ ROLE_ASSIGNMENT : grants
    ROLE ||--o{ PERMISSION : includes
    USER ||--o{ TOOL_REQUEST : initiates
    TOOL ||--o{ TOOL_REQUEST : targeted_by
    PERMISSION ||--o{ TOOL : authorizes
    TOOL_REQUEST ||--|| AUDIT_EVENT : produces
```

<br>

</details>

---

### Distributed ETL Orchestrator

<strong>Data Engineering · ETL · Cloud</strong>

Distributed pipeline for automated ingestion, profiling, transformation and loading.

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
&nbsp;
<a href="https://github.com/MabasaBee603163/Distributed-ETL-Orchestrator">
<img src="https://img.shields.io/badge/VIEW_PROJECT-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
</p>

<details>
<summary><strong>Details</strong></summary>

<br>

<strong>Highlights:</strong> CSV profiling · SQL DDL · API ingest · orchestration · Postgres/Supabase · Docker · AWS ECS/Fargate

```mermaid
flowchart TB
    S1[CSV] --> I[Ingest]
    S2[APIs] --> I
    I --> P[Profile]
    P --> T[Transform]
    T --> L[Load]
    L --> DB[(PostgreSQL)]
```

<br>

</details>

---

### Academic Risk Prediction

<strong>Machine Learning · Analytics · Decision Support</strong>

ML project using student data to identify academic risk patterns and support earlier intervention.

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
&nbsp;
<a href="https://github.com/MabasaBee603163/bc-student-academic-risk-prediction">
<img src="https://img.shields.io/badge/VIEW_PROJECT-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
</p>

<details>
<summary><strong>Details</strong></summary>

<br>

<strong>Highlights:</strong> data prep · EDA · feature engineering · classification · evaluation · reproducible experiments

```mermaid
flowchart LR
    A[Raw Data] --> B[Prepare]
    B --> C[EDA]
    C --> D[Features]
    D --> E[Train]
    E --> F[Evaluate]
    F --> G[Predict Risk]
```

<br>

</details>

---

<!-- =========================================================
     TECHNOLOGY
========================================================= -->

<div align="center">

<h2 id="technology">Technologies and Tools</h2>

### Languages

<img src="https://skillicons.dev/icons?i=python,cs,java,js,ts,html,css,mysql" />

### Development

<img src="https://skillicons.dev/icons?i=react,nodejs,express,fastapi,git,github,postman,vite" />

### Databases

<img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite" />

### Cloud and DevOps

<img src="https://skillicons.dev/icons?i=aws,azure,docker,githubactions,linux" />

### Data and ML

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="48" alt="Python" />
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" height="48" alt="Pandas" />
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="48" alt="NumPy" />
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/scikitlearn/scikitlearn-original.svg" height="48" alt="Scikit-learn" />
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" height="48" alt="PyTorch" />
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" height="48" alt="TensorFlow" />

</div>

---

<!-- =========================================================
     ENGINEERING APPROACH
========================================================= -->

<h2 id="engineering-approach">Engineering Approach</h2>

<p>
I don't start with a framework. I start with the problem, then design a system that can be
<strong>built, secured, automated and improved</strong> over time.
</p>

<br>

<div align="center">

```mermaid
flowchart LR
    A["01<br/>PROBLEM"] --> B["02<br/>ANALYSE"]
    B --> C["03<br/>DESIGN"]
    C --> D["04<br/>BUILD"]
    D --> E["05<br/>SECURE"]
    E --> F["06<br/>AUTOMATE"]
    F --> G["07<br/>MEASURE"]
    G --> H["08<br/>IMPROVE"]
    H -.-> B

    style A fill:#161B22,stroke:#F78166,color:#fff
    style D fill:#161B22,stroke:#58A6FF,color:#fff
    style E fill:#161B22,stroke:#E3B341,color:#fff
    style F fill:#161B22,stroke:#3FB950,color:#fff
    style H fill:#161B22,stroke:#D2A8FF,color:#fff
```

</div>

<br>

<table>
<tr>
<td width="25%" valign="top">

<strong>01 · Problem</strong>
<br>
What are we solving, and for whom?

</td>
<td width="25%" valign="top">

<strong>02 · Analyse</strong>
<br>
Where should responsibility live? What can fail?

</td>
<td width="25%" valign="top">

<strong>03 · Design</strong>
<br>
Data flow, boundaries, roles, and interfaces.

</td>
<td width="25%" valign="top">

<strong>04 · Build</strong>
<br>
Ship a working slice, not a perfect abstraction.

</td>
</tr>
<tr>
<td width="25%" valign="top">

<strong>05 · Secure</strong>
<br>
Auth, RBAC, and audit trails by default.

</td>
<td width="25%" valign="top">

<strong>06 · Automate</strong>
<br>
Turn repeatable work into workflows.

</td>
<td width="25%" valign="top">

<strong>07 · Measure</strong>
<br>
Logs, metrics, and outcomes that prove value.

</td>
<td width="25%" valign="top">

<strong>08 · Improve</strong>
<br>
Feed results back into the next iteration.

</td>
</tr>
</table>

<br>

<details>
<summary><strong>How this shows up in my systems</strong></summary>

<br>

<table>
<tr>
<td width="33%" valign="top">

<strong>Security</strong>
<br><br>
Permissions and auditability are part of the design, not a later patch.
<br><br>
<code>Authenticate → Authorize → Execute → Audit</code>

</td>
<td width="33%" valign="top">

<strong>Data</strong>
<br><br>
I care about the full path from raw input to a usable decision.
<br><br>
<code>Collect → Clean → Transform → Act</code>

</td>
<td width="34%" valign="top">

<strong>Intelligent systems</strong>
<br><br>
Agents only act through controlled tools with clear boundaries.
<br><br>
<code>Agent → Policy → Tool → State → Log</code>

</td>
</tr>
</table>

<br>

</details>

---

<!-- =========================================================
     PROFILE FOOTER
========================================================= -->

<div align="center">

### Build things. Understand the system. Improve it.

<br>

<a href="https://github.com/MabasaBee603163">
<img src="https://img.shields.io/badge/GitHub-MabasaBee603163-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
&nbsp;
<a href="https://www.linkedin.com/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="mailto:603163@student.belgiumcampus.ac.za">
<img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<br><br>

<sub>
Bachelor of Information Technology · Software Engineering · Data · Automation · Intelligent Systems
</sub>

<br><br>

### Building · Securing · Shipping

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=58A6FF&height=140&section=footer&animation=twinkling" width="100%" alt="footer banner" />
