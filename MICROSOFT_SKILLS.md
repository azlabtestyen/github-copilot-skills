# Microsoft 相關 GitHub Copilot Skills

本目錄只保留直接屬於 Microsoft 生態的技能：Azure、.NET/ASP.NET、PowerShell/Windows、Visual Studio/VS Code、Microsoft 365、GitHub Copilot/Actions，以及 Microsoft AI/Data 服務。

來源：`github/awesome-copilot`，固定 commit：`782200e3a4f7c17248974ac4a63284c868bc290f`。

共篩選 **183** 項技能；每項同時產生可讀目錄與 `.skill` 封裝。

## 分類統計

| 分類 | 技能數 |
|---|---:|
| azure-infrastructure | 53 |
| dotnet-aspnet | 41 |
| github-copilot-actions | 21 |
| microsoft-365 | 18 |
| microsoft-ai-data | 4 |
| powershell-windows | 31 |
| visual-studio-vscode | 15 |

## 技能清單

### azure-infrastructure

| 技能 | 其他匹配分類 | 說明 |
|---|---|---|
| `appinsights-instrumentation` | dotnet-aspnet | Instrument a webapp to send useful telemetry data to Azure App Insights' |
| `arduino-azure-iot-edge-integration` | — | Design and implement Arduino integration with Azure IoT Hub and IoT Edge, including secure provisioning, resilient telemetry, command handling, and production guardrails.' |
| `arize-ai-provider-integration` | microsoft-ai-data | Creates, reads, updates, and deletes Arize AI integrations that store LLM provider credentials used by evaluators and other Arize features. Supports any LLM provider (e.g. OpenAI, Anthropic, Azure OpenAI, AWS Bedrock, Vertex AI, Gemini, NVI |
| `aspire` | dotnet-aspnet, powershell-windows, visual-studio-vscode | Aspire skill covering the Aspire CLI, AppHost orchestration, service discovery, integrations, MCP server, VS Code extension, Dev Containers, GitHub Codespaces, templates, dashboard, and deployment. Use when the user asks to create, run, deb |
| `az-cost-optimize` | microsoft-ai-data | Analyze Azure resources used in the app (IaC files and/or resources in a target rg) and optimize costs - creating GitHub issues for identified optimizations.' |
| `azure-architecture-autopilot` | powershell-windows, microsoft-ai-data | > |
| `azure-container-registry-cli` | powershell-windows, microsoft-365 | Manage Azure Container Registry via the az acr CLI including registries, images, cloud builds, ACR Tasks, authentication, tokens, geo-replication, and networking. Use when working with ACR, az acr commands, pushing/importing/purging contain |
| `azure-deployment-preflight` | — | Performs comprehensive preflight validation of Bicep deployments to Azure, including template syntax validation, what-if analysis, and permission checks. Use this skill before any deployment to Azure to preview changes, identify potential i |
| `azure-developer-cli` | powershell-windows | Design, create, review, migrate, or troubleshoot Azure Developer CLI (azd) projects using current Microsoft guidance. Use for azd, azure.yaml, AZD templates, Bicep or Terraform under infra, AZD environments and secrets, hooks, deployment wo |
| `azure-devops-cli` | powershell-windows | Manage Azure DevOps resources via CLI including projects, repos, pipelines, builds, pull requests, work items, artifacts, and service endpoints. Use when working with Azure DevOps, az commands, devops automation, CI/CD, or when user mention |
| `azure-pricing` | microsoft-ai-data | Fetches real-time Azure retail pricing using the Azure Retail Prices API (prices.azure.com) and estimates Copilot Studio agent credit consumption. Use when the user asks about the cost of any Azure service, wants to compare SKU prices, need |
| `azure-resource-health-diagnose` | microsoft-ai-data | Analyze Azure resource health, diagnose issues from logs and telemetry, and create a remediation plan for identified problems.' |
| `azure-resource-visualizer` | dotnet-aspnet | Analyze Azure resource groups and generate detailed Mermaid architecture diagrams showing the relationships between individual resources. Use this skill when the user asks for a diagram of their Azure resources or help in understanding how  |
| `azure-role-selector` | — | When user is asking for guidance for which role to assign to an identity given desired permissions, this agent helps them understand the role that will meet the requirements with least privilege access and how to apply that role. |
| `azure-smart-city-iot-solution-builder` | powershell-windows, microsoft-ai-data | Design and plan end-to-end Azure IoT and Smart City solutions: requirements, architecture, security, operations, cost, and a phased delivery plan with concrete implementation artifacts.' |
| `azure-static-web-apps` | github-copilot-actions | Helps create, configure, and deploy Azure Static Web Apps using the SWA CLI. Use when deploying static sites to Azure, setting up SWA local development, configuring staticwebapp.config.json, adding Azure Functions APIs to SWA, or setting up |
| `azure-well-architected-review` | github-copilot-actions, microsoft-ai-data | Perform an Azure Well-Architected Framework review of the current workload IaC and architecture, generating findings and GitHub issues for improvements.' |
| `cloud-design-patterns` | — | Cloud design patterns for distributed systems architecture covering 42 industry-standard patterns across reliability, performance, messaging, security, and deployment categories. Use when designing, reviewing, or implementing distributed sy |
| `containerize-aspnetcore` | dotnet-aspnet | Containerize an ASP.NET Core project by creating Dockerfile and .dockerfile files customized for the project.' |
| `cosmosdb-datamodeling` | microsoft-ai-data | Step-by-step guide for capturing key application requirements for NoSQL use-case and produce Azure Cosmos DB Data NoSQL Model design using best practices and common patterns, artifacts_produced: "cosmosdb_requirements.md" file and "cosmosdb |
| `create-readme` | — | Create a README.md file for the project' |
| `create-technical-spike` | visual-studio-vscode | Create time-boxed technical spike documents for researching and resolving critical development decisions before implementation.' |
| `data-breach-blast-radius` | dotnet-aspnet | Pre-breach impact analysis: inventories sensitive data (PII, PHI, PCI-DSS, credentials), traces data flows, scores exposure vectors, and produces a regulatory blast radius report with fine ranges sourced verbatim from GDPR Art. 83, CCPA § 1 |
| `dataverse-python-usecase-builder` | — | Generate complete solutions for specific Dataverse SDK use cases with architecture recommendations' |
| `dotnet-timezone` | dotnet-aspnet, powershell-windows | .NET timezone handling guidance for C# applications. Use when working with TimeZoneInfo, DateTimeOffset, NodaTime, UTC conversion, daylight saving time, scheduling across timezones, cross-platform Windows/IANA timezone IDs, or when a .NET u |
| `dotnet-upgrade` | dotnet-aspnet | Ready-to-use prompts for comprehensive .NET framework upgrade analysis and execution' |
| `entra-agent-user` | powershell-windows, microsoft-365 | Create Agent Users in Microsoft Entra ID from Agent Identities, enabling AI agents to act as digital workers with user identity capabilities in Microsoft 365 and Azure environments.' |
| `fabric-lakehouse` | microsoft-365, microsoft-ai-data | Use this skill to get context about Fabric Lakehouse and its features for software systems and AI-powered functions. It offers descriptions of Lakehouse data components, organization with schemas and shortcuts, access control, and code exam |
| `foundry-agent-sync` | powershell-windows | Create and synchronize prompt-based AI agents directly within Azure AI Foundry via REST API, from a local JSON manifest. Unlike scaffolding skills that only generate local code, this skill registers agents in the Foundry service itself — ma |
| `foundry-hosted-agent-copilotkit` | dotnet-aspnet | Ongoing development guidance for agentic web apps that pair a CopilotKit frontend with Microsoft Agent Framework agents on Azure AI Foundry hosted agents over the AG-UI protocol - add and gate agent tools, wire human-in-the-loop approvals,  |
| `import-infrastructure-as-code` | — | Import existing Azure resources into Terraform using Azure CLI discovery and Azure Verified Modules (AVM). Use when asked to reverse-engineer live Azure infrastructure, generate Infrastructure as Code from existing subscriptions/resource gr |
| `mcp-copilot-studio-server-generator` | — | Generate a complete MCP server implementation optimized for Copilot Studio integration with proper schema constraints and streamable HTTP support' |
| `microsoft-agent-framework` | dotnet-aspnet, microsoft-ai-data | Create, update, refactor, explain, or review Microsoft Agent Framework solutions using shared guidance plus language-specific references for .NET and Python.' |
| `microsoft-code-reference` | dotnet-aspnet, powershell-windows | Look up Microsoft API references, find working code samples, and verify SDK code is correct. Use when working with Azure SDKs, .NET libraries, or Microsoft APIs—to find the right method, check parameters, get working examples, or troublesho |
| `microsoft-docs` | dotnet-aspnet, powershell-windows, visual-studio-vscode, github-copilot-actions, microsoft-ai-data | Query official Microsoft documentation to find concepts, tutorials, and code examples across Azure, .NET, Agent Framework, Aspire, VS Code, GitHub, and more. Uses Microsoft Learn MCP as the default, with Context7 and Aspire MCP for content  |
| `microsoft-skill-creator` | dotnet-aspnet, powershell-windows, visual-studio-vscode, microsoft-ai-data | Create agent skills for Microsoft technologies using Learn MCP tools. Use when users want to create a skill that teaches agents about any Microsoft technology, library, framework, or service (Azure, .NET, M365, VS Code, Bicep, etc.). Invest |
| `msgraph-sdk` | dotnet-aspnet, microsoft-365 | Integrate Microsoft Graph SDK into any project — .NET, TypeScript/JavaScript, or Python. Covers auth patterns (client credentials, OBO, managed identity), SDK setup, calling Graph APIs, batching, delta queries, change notifications, throttl |
| `msstore-cli` | dotnet-aspnet, powershell-windows, github-copilot-actions | Microsoft Store Developer CLI (msstore) for publishing Windows applications to the Microsoft Store. Use when asked to configure Store credentials, list Store apps, check submission status, publish submissions, manage package flights, set up |
| `power-apps-code-app-scaffold` | visual-studio-vscode, microsoft-365, microsoft-ai-data | Scaffold a complete Power Apps Code App project with PAC CLI setup, SDK integration, and connector configuration' |
| `power-platform-mcp-connector-suite` | — | Generate complete Power Platform custom connector with MCP integration for Copilot Studio - includes schema generation, troubleshooting, and validation' |
| `pr-screenshots` | dotnet-aspnet, powershell-windows | Embed before/after screenshots and annotated images in pull request descriptions. Covers PR description patterns, image upload for Azure DevOps and GitHub, and sizing best practices.' |
| `python-azure-iot-edge-modules` | — | Build and operate Python Azure IoT Edge modules with robust messaging, deployment manifests, observability, and production readiness checks.' |
| `security-review` | — | AI-powered codebase security scanner that reasons about code like a security researcher — tracing data flows, understanding component interactions, and catching vulnerabilities that pattern-matching tools miss. Use this skill when asked to  |
| `semantic-kernel` | dotnet-aspnet, microsoft-ai-data | Create, update, refactor, explain, or review Semantic Kernel solutions using shared guidance plus language-specific references for .NET and Python.' |
| `sql-server-table-reconciliation` | dotnet-aspnet, powershell-windows, microsoft-365, microsoft-ai-data | Use when: comparing SQL Server tables across instances, data migration validation, ETL verification, row mismatch detection, schema drift, reconciliation report, production vs staging comparison. Uses mssql-python driver with Apache Arrow f |
| `ssma-console` | microsoft-ai-data | Use when: SSMA console operations — create project, generate assessment report, convert schema, migrate data, Oracle to SQL Server migration, schema conversion, data migration" |
| `suggest-awesome-github-copilot-agents` | dotnet-aspnet, github-copilot-actions | Suggest relevant GitHub Copilot Custom Agents files from the awesome-copilot repository based on current repository context and chat history, avoiding duplicates with existing custom agents in this repository, and identifying outdated agent |
| `suggest-awesome-github-copilot-instructions` | dotnet-aspnet, github-copilot-actions | Suggest relevant GitHub Copilot instruction files from the awesome-copilot repository based on current repository context and chat history, avoiding duplicates with existing instructions in this repository, and identifying outdated instruct |
| `suggest-awesome-github-copilot-skills` | dotnet-aspnet, github-copilot-actions | Suggest relevant GitHub Copilot skills from the awesome-copilot repository based on current repository context and chat history, avoiding duplicates with existing skills in this repository, and identifying outdated skills that need updates. |
| `terraform-azurerm-set-diff-analyzer` | — | Analyze Terraform plan JSON output for AzureRM Provider to distinguish between false-positive diffs (order-only changes in Set-type attributes) and actual resource changes. Use when reviewing terraform plan output for Azure resources like A |
| `transloadit-media-processing` | visual-studio-vscode, github-copilot-actions | Process media files (video, audio, images, documents) using Transloadit. Use when asked to encode video to HLS/MP4, generate thumbnails, resize or watermark images, extract audio, concatenate clips, add subtitles, OCR documents, or run any  |
| `update-avm-modules-in-bicep` | — | Update Azure Verified Modules (AVM) to latest versions in Bicep files.' |
| `vcpkg` | dotnet-aspnet, powershell-windows, visual-studio-vscode, github-copilot-actions | Guide for setting up vcpkg in C++ projects, managing dependency versions, and cross-compiling. Covers manifest initialization, CMake and Visual Studio integration, classic-to-manifest migration, version pinning, baselines, overrides, triple |

### dotnet-aspnet

| 技能 | 其他匹配分類 | 說明 |
|---|---|---|
| `architecture-blueprint-generator` | — | Comprehensive project architecture blueprint generator that analyzes codebases to create detailed architectural documentation. Automatically detects technology stacks and architectural patterns, generates visual diagrams, documents implemen |
| `aspnet-minimal-api-openapi` | — | Create ASP.NET Minimal API endpoints with proper OpenAPI documentation' |
| `autoresearch` | — | Autonomous iterative experimentation loop for any programming task. Guides the user through defining goals, measurable metrics, and scope constraints, then runs an autonomous loop of code changes, testing, measuring, and keeping/discarding  |
| `code-exemplars-blueprint-generator` | — | Technology-agnostic prompt generator that creates customizable AI prompts for scanning codebases and identifying high-quality code exemplars. Supports multiple programming languages (.NET, Java, JavaScript, TypeScript, React, Angular, Pytho |
| `containerize-aspnet-framework` | powershell-windows, visual-studio-vscode | Containerize an ASP.NET .NET Framework project by creating Dockerfile and .dockerfile files customized for the project.' |
| `copilot-instructions-blueprint-generator` | github-copilot-actions | Technology-agnostic blueprint generator for creating comprehensive copilot-instructions.md files that guide GitHub Copilot to produce code consistent with project standards, architecture patterns, and exact technology versions by analyzing  |
| `copilot-sdk` | github-copilot-actions | Build agentic applications with GitHub Copilot SDK. Use when embedding AI agents in apps, creating custom tools, implementing streaming responses, managing sessions, connecting to MCP servers, or creating custom agents. Triggers on Copilot  |
| `create-specification` | github-copilot-actions | Create a new specification file for the solution, optimized for Generative AI consumption.' |
| `creating-oracle-to-postgres-master-migration-plan` | — | Discovers all projects in a .NET solution, classifies each for Oracle-to-PostgreSQL migration eligibility, and produces a persistent master migration plan. Use when starting a multi-project Oracle-to-PostgreSQL migration, creating a migrati |
| `creating-oracle-to-postgres-migration-integration-tests` | — | Creates integration test cases targeting Oracle for .NET data access artifacts. Tests capture Oracle expected behavior as the authoritative baseline; they are written once and later ported to PostgreSQL by migrating the test project in Phas |
| `csharp-mstest` | — | Get best practices for MSTest 3.x/4.x unit testing, including modern assertion APIs and data-driven tests' |
| `csharp-nunit` | — | Get best practices for NUnit unit testing, including data-driven tests' |
| `csharp-tunit` | — | Get best practices for TUnit unit testing, including data-driven tests' |
| `csharp-xunit` | — | Get best practices for XUnit unit testing, including data-driven tests' |
| `dependabot` | github-copilot-actions | >- |
| `dotnet-best-practices` | microsoft-ai-data | Ensure .NET/C# code meets best practices for the solution/project.' |
| `dotnet-design-pattern-review` | microsoft-ai-data | Review the C#/.NET code for design pattern implementation and suggest improvements.' |
| `dotnet-mcp-builder` | — | Build Model Context Protocol (MCP) servers in C#/.NET against the current ModelContextProtocol 2.x NuGet packages. Helps with cases the model gets wrong without guidance — stale versions (0.x preview or 1.x-era defaults), the v2 stateless-b |
| `ef-core` | — | Get best practices for Entity Framework Core' |
| `efcore-d2-db-diagram` | — | Generate D2 database diagrams from Entity Framework Core models. USE FOR: EF Core database diagram, Entity Framework Core ERD, DbContext diagram, C# entity relationship diagram, PostgreSQL schema visualization, generate .d2 file from EF Cor |
| `fluentui-blazor` | — | > |
| `folder-structure-blueprint-generator` | — | Comprehensive technology-agnostic prompt for analyzing and documenting project folder structures. Auto-detects project types (.NET, Java, React, Angular, Python, Node.js, Flutter), generates detailed blueprints with visualization options, n |
| `github-actions-runtime-upgrade-conventions` | github-copilot-actions | Upgrade GitHub Actions to supported runtimes by selecting safe action versions, preserving workflow behavior, and validating post-upgrade execution.' |
| `javax-to-jakarta-migration` | — | Migrate Java code from javax.* to jakarta.* namespace. Use when upgrading to Tomcat 11, Jakarta EE 10, or when javax imports are detected in the codebase." |
| `migrating-oracle-to-postgres-data-access-code` | — | Migrates .NET/C# data access code from Oracle to PostgreSQL (Npgsql). Replaces Oracle NuGet packages, rewrites OracleConnection/OracleCommand/OracleDataReader usage, fixes DbType mappings, updates stored procedure invocation patterns, and a |
| `mvvm-toolkit` | — | CommunityToolkit.Mvvm (the MVVM Toolkit) core: source generators ([ObservableProperty], [RelayCommand], [NotifyPropertyChangedFor], [NotifyCanExecuteChangedFor], [NotifyDataErrorInfo]), base classes (ObservableObject / ObservableValidator / |
| `mvvm-toolkit-di` | powershell-windows | Wire CommunityToolkit.Mvvm ViewModels into Microsoft.Extensions.DependencyInjection. Covers the .NET Generic Host composition root, constructor injection, service lifetimes (Singleton / Transient / Scoped), IMessenger registration, resolvin |
| `mvvm-toolkit-messenger` | — | CommunityToolkit.Mvvm Messenger pub/sub for decoupled communication between ViewModels (or any objects). Covers WeakReferenceMessenger vs StrongReferenceMessenger, IRecipient<TMessage>, RequestMessage<T> / AsyncRequestMessage<T> / Collectio |
| `namecheap` | powershell-windows | Manage DNS records for domains registered with Namecheap via their API. List domains, view/add/update/remove DNS host entries (A, AAAA, CNAME, MX, TXT, etc.), and guide users through API setup including public IP detection and credential co |
| `nuget-manager` | powershell-windows | Manage NuGet packages in .NET projects/solutions. Use this skill when adding, removing, or updating NuGet package versions. It enforces using `dotnet` CLI for package management and provides strict procedures for direct file edits only when |
| `oo-component-documentation` | — | Create or update standardized object-oriented component documentation using a shared template plus mode-specific guidance for new and existing docs.' |
| `planning-oracle-to-postgres-migration-integration-testing` | — | Creates an integration testing plan for .NET data access artifacts during Oracle-to-PostgreSQL database migrations. Analyzes a single project to identify repositories, DAOs, and service layers that interact with the database, then produces  |
| `project-workflow-analysis-blueprint-generator` | — | Comprehensive technology-agnostic prompt generator for documenting end-to-end application workflows. Automatically detects project architecture patterns, technology stacks, and data flow patterns to generate detailed implementation blueprin |
| `qdrant-clients-sdk` | — | Qdrant provides client SDKs for various programming languages, allowing easy integration with Qdrant deployments." |
| `rhino3d-scripts` | — | Authoring and debugging scripts for Rhinoceros 3D (Rhino 8 and later). Use when asked to write RhinoScript (VBScript / .rvb / .vbs), RhinoPython, or RhinoCommon-based scripts; automate Rhino modeling tasks; build command macros; manipulate  |
| `scaffolding-oracle-to-postgres-migration-test-project` | — | Scaffolds an xUnit integration test project targeting Oracle in .NET solutions. Creates the test project, transaction-rollback base class, and seed data manager. Use only during Phase 3, before writing Oracle baseline integration tests. Do  |
| `sponsor-finder` | — | Find which of a GitHub repository's dependencies are sponsorable via GitHub Sponsors. Uses deps.dev API for dependency resolution across npm, PyPI, Cargo, Go, RubyGems, Maven, and NuGet. Checks npm funding metadata, FUNDING.yml files, and w |
| `system-commandline-cli` | — | Use this skill when adding, modifying, or reviewing CLI commands in a .NET project built with System.CommandLine. Triggers include: creating a new CLI command, adding options or arguments, wiring command handlers, registering subcommands, b |
| `technology-stack-blueprint-generator` | — | Comprehensive technology stack blueprint generator that analyzes codebases to create detailed architectural documentation. Automatically detects technology stacks, programming languages, and implementation patterns across multiple platforms |
| `update-specification` | github-copilot-actions | Update an existing specification file for the solution, optimized for Generative AI consumption based on new requirements or updates to any existing code.' |
| `winmd-api-search` | powershell-windows | Find and explore Windows desktop APIs. Use when building features that need platform capabilities — camera, file access, notifications, UI controls, AI/ML, sensors, networking, etc. Discovers the right API for a task and retrieves full type |

### github-copilot-actions

| 技能 | 其他匹配分類 | 說明 |
|---|---|---|
| `anti-ui-slop` | — | Stop Codex, GitHub Copilot, Claude Code, and Cursor from shipping generic UI. Use UIZZE’s public catalogue of 800,000+ real web and iOS screens to extract product-specific design decisions and enforce a hard finish gate for web and iOS inte |
| `cli-mastery` | — | Interactive training for the GitHub Copilot CLI. Guided lessons, quizzes, scenario challenges, and a full reference covering slash commands, shortcuts, modes, agents, skills, MCP, and configuration. Say "cliexpert" to start.' |
| `codeql` | — | Comprehensive guide for setting up and configuring CodeQL code scanning via GitHub Actions workflows and the CodeQL CLI. This skill should be used when users need help with code scanning configuration, CodeQL workflow files, CodeQL CLI comm |
| `copilot-cli-quickstart` | — | > |
| `copilot-usage-metrics` | — | Retrieve and display GitHub Copilot usage metrics for organizations and enterprises using the GitHub CLI and REST API. |
| `create-github-action-workflow-specification` | — | Create a formal specification for an existing GitHub Actions CI/CD workflow, optimized for AI consumption and workflow maintenance.' |
| `daily-focus-board` | — | Spin up a personal, motivating daily focus board that renders in a browser canvas and that the user drives by talking to their AI partner. Tasks track status (to-do → in progress → done) with timestamped progress notes and roll up into a "t |
| `generate-custom-instructions-from-codebase` | — | Migration and code evolution instructions generator for GitHub Copilot. Analyzes differences between two project versions (branches, commits, or releases) to create precise instructions allowing Copilot to maintain consistency during techno |
| `github-actions-efficiency` | — | Audit GitHub Actions workflow efficiency and recommend fixes to reduce CI minutes and costs.' |
| `github-actions-hardening` | — | Security hardening reviewer for GitHub Actions workflow files (.github/workflows/*.yml). Reasons about the Actions threat model that pattern matchers and general code linters miss — untrusted-input script injection, privileged triggers runn |
| `github-copilot-starter` | — | Set up complete GitHub Copilot configuration for a new project based on technology stack' |
| `gsap-framer-scroll-animation` | — | >- |
| `harness-engineering` | — | Adopt repository-level harness engineering for coding agents. Use when a user wants to prevent repeated AI coding-agent mistakes by turning failures into durable instructions, drift checks, regression tests, failure memory, and adoption rep |
| `mentoring-juniors` | — | Socratic mentoring for junior developers and AI newcomers. Guides through questions, never answers. Triggers: "help me understand", "explain this code", "I''m stuck", "Im stuck", "I''m confused", "Im confused", "I don''t understand", "I don |
| `mkdocs-translations` | — | Generate a language translation for a mkdocs documentation stack.' |
| `premium-frontend-ui` | — | A comprehensive guide for GitHub Copilot to craft immersive, high-performance web experiences with advanced motion, typography, and architectural craftsmanship.' |
| `publish-to-pages` | — | Publish presentations and web content to GitHub Pages. Converts PPTX, PDF, HTML, or Google Slides to a live GitHub Pages URL. Handles repo creation, file conversion, Pages enablement, and returns the live URL. Use when the user wants to pub |
| `python-pypi-package-builder` | — | End-to-end skill for building, testing, linting, versioning, and publishing a production-grade Python library to PyPI. Covers all four build backends (setuptools+setuptools_scm, hatchling, flit, poetry), PEP 440 versioning, semantic version |
| `tldr-prompt` | — | Create tldr summaries for GitHub Copilot files (prompts, agents, instructions, collections), MCP servers, or documentation from URLs and queries.' |
| `vardoger-analyze` | — | Use when the user asks to personalize the GitHub Copilot CLI assistant, adapt Copilot to their style, use vardoger, or analyze their Copilot CLI conversation history. Reads the local session directory at `~/.copilot/session-state/`, extract |
| `x-twitter-scraper` | — | Build GitHub Copilot workflows with Xquik X API SDKs, REST endpoints, hosted Apify Actor runs, MCP tools, TweetClaw OpenClaw plugin installs, signed webhooks, tweet search, user lookup, follower exports, media actions, and agent automation. |

### microsoft-365

| 技能 | 其他匹配分類 | 說明 |
|---|---|---|
| `email-drafter` | — | Draft and review professional emails that match your personal writing style. Analyzes your sent emails for tone, greeting, structure, and sign-off patterns via WorkIQ, then generates context-aware drafts for any recipient. USE FOR: draft em |
| `flowstudio-power-automate-build` | — | >- |
| `flowstudio-power-automate-debug` | — | >- |
| `flowstudio-power-automate-governance` | — | >- |
| `flowstudio-power-automate-mcp` | — | >- |
| `flowstudio-power-automate-monitoring` | — | >- |
| `mcp-create-adaptive-cards` | — | Skill converted from mcp-create-adaptive-cards.prompt.md' |
| `mcp-deploy-manage-agents` | — | Skill converted from mcp-deploy-manage-agents.prompt.md' |
| `power-bi-dax-optimization` | — | Comprehensive Power BI DAX formula optimization prompt for improving performance, readability, and maintainability of DAX calculations.' |
| `power-bi-model-design-review` | — | Comprehensive Power BI data model design review prompt for evaluating model architecture, relationships, and optimization opportunities.' |
| `power-bi-performance-troubleshooting` | microsoft-ai-data | Systematic Power BI performance troubleshooting prompt for identifying, diagnosing, and resolving performance issues in Power BI models, reports, and queries.' |
| `power-bi-report-design-consultation` | — | Power BI report visualization design prompt for creating effective, user-friendly, and accessible reports with optimal chart selection and layout design.' |
| `powerbi-modeling` | microsoft-ai-data | Power BI semantic modeling assistant for building optimized data models. Use when working with Power BI semantic models, creating measures, designing star schemas, configuring relationships, implementing RLS, or optimizing model performance |
| `setup-my-iq` | — | \| |
| `typespec-api-operations` | — | Add GET, POST, PATCH, and DELETE operations to a TypeSpec API plugin with proper routing, parameters, and adaptive cards' |
| `typespec-create-agent` | — | Generate a complete TypeSpec declarative agent with instructions, capabilities, and conversation starters for Microsoft 365 Copilot' |
| `typespec-create-api-plugin` | — | Generate a TypeSpec API plugin with REST operations, authentication, and Adaptive Cards for Microsoft 365 Copilot' |
| `workiq-copilot` | — | Guides the Copilot CLI on how to use the WorkIQ CLI/MCP server to query Microsoft 365 Copilot data (emails, meetings, docs, Teams, people) for live context, summaries, and recommendations.' |

### microsoft-ai-data

| 技能 | 其他匹配分類 | 說明 |
|---|---|---|
| `legacy-circuit-mockups` | — | Generate breadboard circuit mockups and visual diagrams using HTML5 Canvas drawing techniques. Use when asked to create circuit layouts, visualize electronic component placements, draw breadboard diagrams, mockup 6502 builds, generate retro |
| `minecraft-plugin-development` | — | Use this skill when building or modifying Minecraft server plugins for Paper, Spigot, or Bukkit, including plugin.yml setup, commands, listeners, schedulers, player state, team or arena systems, persistent progression, economy or profile da |
| `sql-code-review` | — | Universal SQL code review assistant that performs comprehensive security, maintainability, and code quality analysis across all SQL databases (MySQL, PostgreSQL, SQL Server, Oracle). Focuses on SQL injection prevention, access control, code |
| `sql-optimization` | — | Universal SQL performance optimization assistant for comprehensive query tuning, indexing strategies, and database performance analysis across all SQL databases (MySQL, PostgreSQL, SQL Server, Oracle). Provides execution plan analysis, pagi |

### powershell-windows

| 技能 | 其他匹配分類 | 說明 |
|---|---|---|
| `acquire-codebase-knowledge` | — | Use this skill when the user explicitly asks to map, document, or onboard into an existing codebase. Trigger for prompts like "map this codebase", "document this architecture", "onboard me to this repo", or "create codebase docs". Do not tr |
| `adobe-illustrator-scripting` | — | Write, debug, and optimize Adobe Illustrator automation scripts using ExtendScript (JavaScript/JSX). Use when creating or modifying scripts that manipulate documents, layers, paths, text frames, colors, symbols, artboards, or any Illustrato |
| `arize-link` | — | Generates deep links to the Arize UI for traces, spans, sessions, datasets, labeling queues, evaluators, and annotation configs. Produces clickable URLs for sharing Arize resources with team members. Use when the user wants to link to or op |
| `aws-cdk-python-setup` | — | Setup and initialization guide for developing AWS CDK (Cloud Development Kit) applications in Python. This skill enables users to configure environment prerequisites, create new CDK projects, manage dependencies, and deploy to AWS. |
| `batch-files` | — | Expert-level Windows batch file (.bat/.cmd) skill for writing, debugging, and maintaining CMD scripts. Use when asked to "create a batch file", "write a .bat script", "automate a Windows task", "CMD scripting", "batch automation", "schedule |
| `brag-sheet` | github-copilot-actions | > |
| `convert-excel-to-md` | — | Converts Excel (.xlsx) workbooks into Markdown so their contents can be accurately analyzed, summarized, searched, or extracted from. Use this skill whenever the user shares, references, or asks about a .xlsx file — even if they don''t say  |
| `convert-pdf-to-md` | — | Converts PDF (.pdf) documents into Markdown so their contents can be accurately analyzed, summarized, searched, or extracted from. Use this skill whenever the user shares, references, or asks about a .pdf file — even if they don''t say "con |
| `convert-word-to-md` | — | Converts Word (.docx) documents into Markdown so their contents can be accurately analyzed, summarized, searched, or extracted from. Use this skill whenever the user shares, references, or asks about a .docx file — even if they don''t say " |
| `copilot-pr-autopilot` | — | Copilot left 14 review comments on your PR — half are nits. Hours of fix → reply → resolve → re-request, and each round lands MORE comments. This skill runs loop engineering: auto-triggers Copilot Code Review via GraphQL (no @copilot mentio |
| `create-implementation-plan` | — | Create a new implementation plan file for new features, refactoring existing code or upgrading packages, design, architecture or infrastructure.' |
| `daily-prep` | microsoft-365 | Prepare for tomorrow''s meetings and tasks. Pulls calendar from Outlook via WorkIQ, cross-references open tasks and workspace context, classifies meetings, detects conflicts and day-fit issues, finds learning and deep-work slots, and genera |
| `drawio` | — | Generate draw.io diagrams as .drawio files and export to PNG/SVG/PDF with embedded XML |
| `editorconfig` | — | Generates a comprehensive and best-practice-oriented .editorconfig file based on project analysis and user preferences.' |
| `eyeball` | — | Document analysis with inline source screenshots. When you ask Copilot to analyze a document, Eyeball generates a Word doc where every factual claim includes a highlighted screenshot from the source material so you can verify it with your o |
| `github-release` | github-copilot-actions | > |
| `image-annotations` | — | Annotate screenshots, diagrams, and images with callout rectangles, arrows, labels, and color-coded highlights using PIL. Includes rules for animated GIF annotations with timing and pacing.' |
| `image-manipulation-image-magick` | — | Process and manipulate images using ImageMagick. Supports resizing, format conversion, batch processing, and retrieving image metadata. Use when working with images, creating thumbnails, resizing wallpapers, or performing batch image operat |
| `incident-postmortem` | — | Use when an outage, production incident, or significant service degradation has occurred and the team needs to write a structured blameless post-mortem. Triggers on phrases like "write a post-mortem", "incident review", "what went wrong", " |
| `lsp-setup` | github-copilot-actions | Enable code intelligence (go-to-definition, find-references, hover, type info) for any programming language by installing and configuring an LSP server for Copilot CLI. Detects the OS, installs the right server, and generates the JSON confi |
| `md-to-docx` | — | Convert Markdown files to professionally formatted Word (.docx) documents with embedded PNG images — pure JavaScript, no external tools required |
| `nano-banana-pro-openrouter` | — | Generate or edit images via OpenRouter with the Gemini 3 Pro Image model. Use for prompt-only image generation, image edits, and multi-image compositing; supports 1K/2K/4K output.' |
| `napkin` | — | Visual whiteboard collaboration for Copilot CLI. Creates an interactive whiteboard that opens in your browser — draw, sketch, add sticky notes, then share everything back with Copilot. Copilot sees your drawings and text, and responds with  |
| `optimize-simplicite-logs` | — | capability to parse Simplicité logs from a raw `.txt` file, filter fields to reduce noise, and output the result as structured JSON. |
| `pdftk-server` | — | Skill for using the command-line tool pdftk (PDFtk Server) for working with PDF files. Use when asked to merge PDFs, split PDFs, rotate pages, encrypt or decrypt PDFs, fill PDF forms, apply watermarks, stamp overlays, extract metadata, burs |
| `pester-migration` | — | Pester migration skill for upgrading PowerShell Pester test suites across major versions — v3→v4, v4→v5, and v5→v6. Covers the Discovery/Run two-phase model, moving setup into BeforeAll, $PSScriptRoot vs $MyInvocation, mock changes (Assert- |
| `pester-should-migration` | — | Experimental (preview) Pester skill for migrating classic Should -Be (v5) assertion syntax to the new Should-* (v6) assertions (note the hyphen, no space), e.g. `Should -Be` -> `Should-Be`, `Should -Not -Be` -> `Should-NotBe`. Tracks Pester |
| `server-side-conversion-tracking` | — | Set up server-side conversion tracking so purchases are reported accurately to Facebook, TikTok, Google and Bing despite iOS restrictions, ad blockers and cookie loss. Use when conversions are under-reported, when platform-reported purchase |
| `structured-autonomy-plan` | — | Structured Autonomy Planning Prompt' |
| `ui-screenshots` | visual-studio-vscode | Capture screenshots of web apps during development using Playwright and PIL. Supports full-page captures, interactive states, and an iterate-on-crop workflow that avoids slow re-screenshots.' |
| `winui3-migration-guide` | — | UWP-to-WinUI 3 migration reference. Maps legacy UWP APIs to correct Windows App SDK equivalents with before/after code snippets. Covers namespace changes, threading (CoreDispatcher to DispatcherQueue), windowing (CoreWindow to AppWindow), d |

### visual-studio-vscode

| 技能 | 其他匹配分類 | 說明 |
|---|---|---|
| `acreadiness-generate-instructions` | — | Generate tailored AI agent instruction files via AgentRC instructions command. Produces .github/copilot-instructions.md (default, recommended for Copilot in VS Code) plus optional per-area .instructions.md files with applyTo globs for monor |
| `ai-team-orchestration` | — | Bootstrap and run a lightweight multi-agent development team. Use when starting or adopting a project, planning work, coordinating implementation and optional QA, brainstorming with distinct perspectives, or preserving context across sessio |
| `boost-prompt` | — | Interactive prompt refinement workflow: interrogates scope, deliverables, constraints; copies final markdown to clipboard; never writes code. Requires the Joyride extension.' |
| `code-tour` | — | > |
| `convert-plaintext-to-md` | — | Convert a text-based document to markdown following instructions from prompt, or if a documented option is passed, follow the instructions for that option.' |
| `declarative-agents` | microsoft-365 | Complete development kit for Microsoft 365 Copilot declarative agents with three comprehensive workflows (basic, advanced, validation), TypeSpec support, and Microsoft 365 Agents Toolkit integration' |
| `draw-io-diagram-generator` | — | Use when creating, editing, or generating draw.io diagram files (.drawio, .drawio.svg, .drawio.png). Covers mxGraph XML authoring, shape libraries, style strings, flowcharts, system architecture, sequence diagrams, ER diagrams, UML class di |
| `mcp-create-declarative-agent` | microsoft-365 | Skill converted from mcp-create-declarative-agent.prompt.md' |
| `mcp-implementation-security-review` | — | \| |
| `memory-merger` | — | Merges mature lessons from a domain memory file into its instruction file. Syntax: `/memory-merger >domain [scope]` where scope is `global` (default), `user`, `workspace`, or `ws`.' |
| `penpot-uiux-design` | — | Comprehensive guide for creating professional UI/UX designs in Penpot using MCP tools. Use this skill when: (1) Creating new UI/UX designs for web, mobile, or desktop applications, (2) Building design systems with components and tokens, (3) |
| `power-platform-architect` | microsoft-365 | Use this skill when the user needs to transform business requirements, use case descriptions, or meeting transcripts into a technical Power Platform solution architecture, including component selection and Mermaid.js diagrams. |
| `remember` | — | Transforms lessons learned into domain-organized memory instructions (global or workspace). Syntax: `/remember [>domain [scope]] lesson clue` where scope is `global` (default), `user`, `workspace`, or `ws`.' |
| `vscode-ext-commands` | — | Guidelines for contributing commands in VS Code extensions. Indicates naming convention, visibility, localization and other relevant attributes, following VS Code extension development guidelines, libraries and good practices' |
| `vscode-ext-localization` | — | Guidelines for proper localization of VS Code extensions, following VS Code extension development guidelines, libraries and good practices' |

## 目錄結構

- `packages/<分類>/<技能>/`：技能原始目錄。
- `archives/<分類>/<技能>.skill`：可攜式封裝。
- `microsoft-skills-index.json`：機器可讀索引。

## 篩選原則

只有技能名稱、frontmatter 描述或主要內容明確提及 Microsoft 產品、平台、工具或 Microsoft 維護的 GitHub Copilot/Actions 生態，才會納入；泛用 Docker、AWS、GCP、Linux、通用 SEO 或一般程式設計技能不納入。
