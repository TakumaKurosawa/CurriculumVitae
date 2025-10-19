---
title: English
layout: page
toc: true
---

## Profile

- Name: Takuma Kurosawa
- Job: Backend Engineer
- Company: [CyberAgent, Inc.](https://www.cyberagent.co.jp/en/)
- Links
  - X(Twitter): [x.com/TakumaKurosawa](https://x.com/TakumaKurosawa)
  - Qiita: [qiita.com/TakumaKurosawa](https://qiita.com/TakumaKurosawa)
  - GitHub: [github.com/TakumaKurosawa](https://github.com/TakumaKurosawa)
  - TechTrain: [techbowl.co.jp/techtrain/mentors/78](https://techbowl.co.jp/techtrain/mentors/78)

### Strengths

- Translating business requirements into system design
- End-to-end development from requirement definition to implementation
- Breaking down complex problems
- Team development infrastructure design
- Development efficiency improvement and automation
- Backend and infrastructure development

### Professional Summary

I have experience in all phases from product launch to operation. I excel at design and development that maximizes outcomes while prioritizing business impact. I'm particularly interested in building systems and infrastructure to achieve higher productivity as a team.

### Skills

| Technology/Skill        | Category               | Experience |
| ----------------------- | ---------------------- | ---------- |
| Go                      | Languages              | 5 years    |
| AWS                     | Cloud & Infrastructure | 5 years    |
| Docker                  | Cloud & Infrastructure | 5 years    |
| Terraform               | Cloud & Infrastructure | 5 years    |
| DynamoDB                | Database               | 5 years    |
| GitHub Actions          | Tools                  | 5 years    |
| Python                  | Languages              | 3 years    |
| MySQL                   | Database               | 3 years    |
| PostgreSQL              | Database               | 3 years    |
| Redis                   | Database               | 3 years    |
| LangChain / LangGraph   | Framework & Library    | 3 years    |
| gRPC (Protocol Buffers) | Communication Protocol | 3 years    |
| PipeCD                  | Tools                  | 3 years    |
| Datadog                 | Tools                  | 3 years    |
| Typescript              | Languages              | 2 years    |
| Nuxt.js (Vue.js)        | Framework & Library    | 2 years    |
| PHP                     | Languages              | 1 year     |
| CosmosDB (mongoDB)      | Database               | 1 year     |
| Azure                   | Cloud & Infrastructure | 1 year     |

### Experience

| Skill/Experience                        | Experience |
| --------------------------------------- | ---------- |
| DevOps                                  | 3 years    |
| Scrum development                       | 3 years    |
| Tech Lead                               | 2 years    |
| Engineering Manager                     | 2 years    |
| Waterfall development                   | 2 years    |
| AI-native development environment setup | 2 years    |
| LLMOps                                  | 2 years    |
| PdM (Product Manager)                   | 1 year     |

## Work Experience

### June 2025 - Present: DX Project for a Major Retail Company - AI Business Unit

| Item          | Details                                                                                                                                           |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Project Scale | Large-scale users (4M WAU, 8M MAU)<br>Team: PM × 6, Backend × 4, Frontend × 3, Native × 4, Designer × 2<br>Co-development with 4 external vendors |
| Role          | Backend Engineer                                                                                                                                  |
| Technologies  | Go, Docker, MySQL, gRPC, Envoy, Terraform, AWS, Datadog, k6                                                                                       |

#### Responsibilities

Rejoined the application revamp project for a major drugstore chain.  
In the growth phase of a product that has grown into a large-scale service with 4 million WAU and 8 million MAU, working as a backend engineer responsible for design and development.

#### Skills and Knowledge Gained

- Experience in growth development of large-scale services
- Experience in continuous product development
- Experience in safely scaling services
  - Design and implementation of test strategies
  - Gradual rollout using feature flags

### May 2025 - August 2025: AI Development Project for Patent Analysis at a Major Chemical Company - Galirage, Inc.

| Item          | Details                                                                        |
| ------------- | ------------------------------------------------------------------------------ |
| Project Scale | PM × 1, Engineer × 4                                                           |
| Role          | Generative AI Engineer                                                         |
| Technologies  | Python (Streamlit, LangChain, LangGraph), LangSmith, Azure, PostgreSQL, Docker |

#### Responsibilities

Participated as a generative AI engineer.  
Implemented an AI agent that analyzes patent documents using RAG.  
Joined the product development phase after PoC completion and contributed to translating client needs into product specifications.

#### Skills and Knowledge Gained

- Experience in hearing client needs and translating them into product specifications
- Building RAG systems in highly specialized domains such as patent documents
- AI agent design and implementation experience

### January 2025 - May 2025: Development of [Raggle](https://raggle.jp/) and Competition Hosting - Galirage, Inc.

| Item          | Details                                                                  |
| ------------- | ------------------------------------------------------------------------ |
| Project Scale | ~150 participants per competition<br>Team: CS × 1, PdM and Tech Lead × 1 |
| Role          | PdM and Tech Lead                                                        |
| Technologies  | Python (Streamlit, LangChain), LangSmith, Firebase, GCP, Docker, Rollbar |

#### Responsibilities

Took over the role of PdM and tech lead, responsible for development to improve product quality.  
Hosted competitions to compete on RAG answer accuracy.

【Competition Hosting】

- Created RAG problems
- Built scoring (evaluation) infrastructure for answer accuracy
- User analysis

#### Skills and Knowledge Gained

- Experience creating product vision and development roadmap as a PdM
- Design and development of RAG competition platform
- Experience building evaluation infrastructure
- Practicing cycles of user analysis and product improvement

### February 2024 - June 2025: [Cyber AI Scheduler](https://www.cyberagent.co.jp/news/detail/id=30869) - AI Operations Unit

| Item          | Details                                                                                                                        |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Project Scale | PM × 1, Engineer × 4, Data Scientist × 1<br>Deployed company-wide at CyberAgent Inc. (~11,000 employees)                       |
| Role          | Engineering Manager and Tech Lead                                                                                              |
| Technologies  | Go, Python (LangChain, LangGraph), LangSmith, Docker, PostgreSQL, gRPC, Envoy, Terraform, AWS, Azure (OpenAI), Datadog, PipeCD |

#### Responsibilities

Designed and developed the winning idea of the [contests to generate ideas for the use of generative AI.](https://www.cyberagent.co.jp/way/list/detail/id=29503), receiving the top prize.  
Participated in the project as the manager of engineering team and tech lead.  
Responsible for designing and developing an application that uses generative AI to facilitate schedule adjustments through natural language.  
Conducted evaluations and proofs of concept (PoC) for new technologies, including generative AI.

_Note: An internal contest held by CyberAgent Inc.  
Approximately 2,200 ideas were submitted for using generative AI within the company._

#### Development Topics

**Technology Selection and Initial Architecture:**  
Led the overall architecture and technology selection for the development project, considering team members' tech stacks and application characteristics. The introduction of GitHub Codespaces and trunk-based development was particularly well-received by the team.

**Production Infrastructure Setup:**  
Built AWS infrastructure (ECS, DynamoDB, VPC, ALB, S3, SQS, etc.) using Terraform. To prevent knowledge silos, also built CI/CD pipeline using GitHub Actions and PipeCD.

**Generative AI Technology Evaluation and PoC:**  
Researched and compared LLMs and related libraries to design and implement applications using generative AI. Made the decision to integrate generative AI based on Azure OpenAI Service + Python + LangChain, considering team members' tech stacks.

**User Dictionary Feature Implementation:**  
Implemented a user dictionary feature for the AI to identify schedule participants. Realized this by combining OpenSearch for full-text search and DynamoDB for user dictionary data storage. Also implemented a mechanism to periodically synchronize with daily updated user information sources using EventBridge and ECS.

**Requirement Definition and KPI Design:**  
Since this was a project where engineers also led the specifications and requirement definition, worked on user story design and UI mock creation in the initial phase. Proposed a structure to release in small increments per phase and clarify KPIs for each phase, which resulted in earlier feedback and significant benefits.

**Presented at CyberAgent Developer Conference 2024:**  
Shared development processes and technical initiatives externally.  
Reference: [LLM Evaluation Infrastructure for Generative AI Application Development](https://developers.cyberagent.co.jp/blog/archives/50580/)

**LLMOps Infrastructure Proposal and Implementation:**  
It was difficult to establish KPIs with business stakeholders using vague metrics like "poor response accuracy." Built an evaluation infrastructure using techniques such as LLM as a judge to measure "response accuracy" as a common understanding with business stakeholders, and visualized it with LangSmith. As a result, this became a good opportunity for business stakeholders to understand the AI agent mechanisms from the ground up.

#### Skills and Knowledge Gained

- Experience in evaluating and adopting new technologies such as generative AI
- Experience in making business decisions through PoCs
- Design and development of applications using generative AI
- Skills necessary for building generative AI applications using Azure OpenAI Service, LangChain / LangGraph, and Langsmith

### April 2023 - Present: New Development Base Establishment - Hanoi Devcenter

#### Responsibilities

Established a new department with the mission of boosting the company's development competitiveness by hiring talented local engineers in Vietnam.  
Utilized experience in recruitment and training from the time of joining the company to build an engineering organization that contributes to the company from scratch.

#### Skills and Knowledge Gained

- Engineering organization management
- Culture promotion
- Recruitment strategy design
- Experience living abroad

### April 2023 - January 2024: DX Project for a Major Retail Company - AI Business Unit

| Item          | Details                                                             |
| ------------- | ------------------------------------------------------------------- |
| Project Scale | PM × 10, Frontend × 5, Backend × 5, Native × 4, Designer × 2        |
| Role          | Backend Engineer                                                    |
| Technologies  | Go, Docker, MySQL, gRPC, Envoy, Terraform, AWS, Datadog, k6, PipeCD |

#### Responsibilities

Participated in the launch phase of an application revamp project for a major drugstore chain.  
Collaborated with four SIer companies, in addition to the client company, to develop the application.  
Worked as a backend engineer from the product launch to the completion of the production release.  
Conducted load testing and built observability foundations in addition to feature development before the production release.

#### Development Topics

**Coupon Feature Design and Implementation:**  
Realized a system capable of registering and distributing multiple types of coupons, including user acquisition, targeting, and all-user types. Given that the service was expected to handle over 600 RPS, conducted load testing and performance tuning. Achieved high-performance design by using different DB types according to data characteristics, such as master data (coupon data) and user data (usage history). Also implemented concurrent processing using Goroutines on the application logic side, achieving significant performance improvements.

**Observability Infrastructure Design and Implementation:**  
Given the large-scale traffic expected for the service, it was necessary to strengthen the operational system for production release. Led the design and construction of monitoring systems essential for service operations. Educated team members, including business stakeholders, on what observability is and why it's necessary, and clarified what needs to be built to enhance observability. Specifically, completed visualization of business metrics and system metrics through Datadog dashboards, error alert notification infrastructure, health monitoring through Synthetics tests, and on-call tool selection. **As a result, the client company highly appreciated the post-release monitoring system, leading to double the maintenance budget.**

#### Skills and Knowledge Gained

- Scrum development
- Challenges of collaboration with other companies
- Preparation for production releases in services expected to have large-scale user access
  - Design and implementation of load testing strategies
  - Observability infrastructure setup

### April 2021 - March 2023: Remotenashi - AI Business Unit

| Item          | Details                                                                          |
| ------------- | -------------------------------------------------------------------------------- |
| Project Scale | PM/Sales × 7, Designer × 1, Engineer × 10                                        |
| Role          | Full-stack Engineer                                                              |
| Technologies  | Go, Docker, MySQL, Terraform, AWS, Typescript, Nuxt.js (Vue.js), Vite, Bucketeer |

#### Responsibilities

Engaged in the development of a product proposed in [an internal new business proposal contest](https://x.com/CyberAgent_PR/status/1324539728813715456) that was commercialized.  
Participated as an engineer in the development and operation of an [online customer service tool to achieve the DX of hospitality](https://www.cyberagent.co.jp/news/detail/id=28275).  
As a full-stack engineer, responsible for end-to-end processes from requirements and design definition to implementation.  
Conducted technical verification and replacement to new technologies (Vue3+Vite) with the introduction of Nuxt.js v3 beta.

#### Development Topics

**Nuxt3 Beta Verification and Migration from Nuxt2 to Vue3:**  
Led technical verification when Nuxt3 beta was released. After evaluation, decided to migrate to Vue3 (Vite) instead, reasoning that SSR was not necessary for our use case and disagreement with the main contributor's direction. Completed the full migration from Nuxt2 to Vue3 independently.

**Product Proposal Feature:**  
After understanding the current business workflow, proposed and released a new feature to realize more effective online experiences. Worked with a designer and business member as a team of three, completing everything from UI image creation in Figma to client proposals, requirement definition, implementation, and release. Implemented using WebSocket and Pinia to realize an experience where products proposed by customer service staff are displayed in real-time on customers' screens and can be purchased.

**Client Domain Understanding and Feature Proposals as Solutions:**  
Based on hearing results brought back by business members, conducted requirement definition and UI/UX design to understand client business, extract issues, and lead to feature proposals. For approved features, handled everything from basic design to implementation and release. Rather than just building what was requested, worked closely with business members and designers across disciplines to consider clients' latent needs and issues and connect them to feature proposals.

#### Skills and Knowledge Gained

- Experience in generating and refining business ideas
- Experience in launching products from the business idea phase
- Development experience as a full-stack engineer
- Experience in technical verification and selection
- Design thinking for reflecting UI/UX in the product

## Output

### Past Presentation Materials

- [Recap: Migrating 80 BILLION RECORDS From MySQL to Bigtable](https://speakerdeck.com/takumakurosawa/recap-migrating-80-billion-records-from-mysql-to-bigtable)
- [Figma → Vue コード自動生成サービスを技術検証してみた](https://speakerdeck.com/takumakurosawa/figma-vue-kodozi-dong-sheng-cheng-sabisuwoji-shu-jian-zheng-sitemita)
- [VueUse のすすめ](https://speakerdeck.com/takumakurosawa/vue-dot-js-v-tokyo-meetup-16)
- [僕が Go の設計に対して不思議に思うこと](https://speakerdeck.com/takumakurosawa/pu-gagonoshe-ji-nidui-sitebu-si-yi-nisi-ukoto)

### Blog posts

- [GitHub 実践ハンズオン](https://qiita.com/TakumaKurosawa/items/79a75026327d8deb9c04)
- [【Go 言語で学ぶ】抽象化](https://qiita.com/TakumaKurosawa/items/4e26f77bd62fb734cf55)
- [【AWS ハンズオン】Nuxt + Golang 構成の Web アプリを AWS へデプロイしよう！](https://qiita.com/TakumaKurosawa/items/e67315583009257cd1ea)
- [Google Go Style Guide を読んでみよう！ - Style Decisions 編](https://qiita.com/TakumaKurosawa/items/fbb1418111604837d8ac)
