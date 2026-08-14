# GitHub Copilot Skills 完整封裝與稽核報告

來源：`github/awesome-copilot`；固定 commit：`782200e3a4f7c17248974ac4a63284c868bc290f`。

| 指標 | 數量 |
|---|---:|
| 技能總數 | 423 |
| 通過基本 frontmatter | 423 |
| 含可執行腳本的技能 | 29 |
| 明確預先允許 shell/bash 的技能 | 3 |

每項技能均保留官方原始目錄內容，並另外建立同名 `.skill` 壓縮封裝。稽核只標記可能需要人工複核的字串，不會修改官方技能內容。

## 技能索引

| 名稱 | 檔案數 | 腳本數 | Frontmatter | Shell 預核准 | SHA-256 |
|---|---:|---:|---|---|---|
| `acquire-codebase-knowledge` | 11 | 1 | 通過 | 否 | `94a1da1b609e31d3…` |
| `acreadiness-assess` | 2 | 0 | 通過 | 否 | `c1a8c93253d79bf7…` |
| `acreadiness-generate-instructions` | 1 | 0 | 通過 | 否 | `8a3887176a8a1afd…` |
| `acreadiness-policy` | 1 | 0 | 通過 | 否 | `bffac2eebecddd17…` |
| `ad-campaign-analyzer` | 1 | 0 | 通過 | 否 | `f68442debc84551a…` |
| `add-educational-comments` | 1 | 0 | 通過 | 否 | `65f6defd9f7da4af…` |
| `adobe-illustrator-scripting` | 5 | 0 | 通過 | 否 | `e7688805811c03b1…` |
| `agent-governance` | 1 | 0 | 通過 | 否 | `a91eb8ef638422fa…` |
| `agent-owasp-compliance` | 1 | 0 | 通過 | 否 | `3c461f890564aa52…` |
| `agent-skill-stack` | 11 | 5 | 通過 | 否 | `340c2f399ce7f8f7…` |
| `agent-supply-chain` | 1 | 0 | 通過 | 否 | `af309696b57bb67c…` |
| `agentic-eval` | 1 | 0 | 通過 | 否 | `40771d7d389c1542…` |
| `ai-prompt-engineering-safety-review` | 1 | 0 | 通過 | 否 | `81bf64d383cb7a6c…` |
| `ai-ready` | 1 | 0 | 通過 | 否 | `18b3b83b888d5b77…` |
| `ai-team-orchestration` | 5 | 0 | 通過 | 否 | `7072efd512ae4587…` |
| `anti-ui-slop` | 1 | 0 | 通過 | 否 | `c3cb98fb90778dee…` |
| `appinsights-instrumentation` | 8 | 1 | 通過 | 否 | `f4b4360b7b92859a…` |
| `apple-appstore-reviewer` | 1 | 0 | 通過 | 否 | `848a1946f838e1b3…` |
| `arch-linux-triage` | 1 | 0 | 通過 | 否 | `c9858a61f9e06cee…` |
| `architecture-blueprint-generator` | 1 | 0 | 通過 | 否 | `9b20f13d1d96ba1c…` |
| `arduino-azure-iot-edge-integration` | 3 | 0 | 通過 | 否 | `64809a8d020fb05e…` |
| `arize-ai-provider-integration` | 3 | 0 | 通過 | 否 | `cafea597cbdeb50f…` |
| `arize-annotation` | 3 | 0 | 通過 | 否 | `ed9c959c8b55557d…` |
| `arize-dataset` | 3 | 0 | 通過 | 否 | `6e254dc1950c5204…` |
| `arize-evaluator` | 3 | 0 | 通過 | 否 | `3cde9317c54725d6…` |
| `arize-experiment` | 3 | 0 | 通過 | 否 | `416f52a03d2ce188…` |
| `arize-instrumentation` | 2 | 0 | 通過 | 否 | `9fc6fe394f4ea3b3…` |
| `arize-link` | 2 | 0 | 通過 | 否 | `0471b36681aad894…` |
| `arize-prompt-optimization` | 3 | 0 | 通過 | 否 | `6a6e2a1d24efce8a…` |
| `arize-trace` | 3 | 0 | 通過 | 否 | `6698227c22016efd…` |
| `aspire` | 10 | 0 | 通過 | 否 | `edef54822bd9152a…` |
| `aspnet-minimal-api-openapi` | 1 | 0 | 通過 | 否 | `2c4b990eba7b246b…` |
| `audit-integrity` | 8 | 0 | 通過 | 否 | `f2d6d6d4056ccf27…` |
| `automate-this` | 1 | 0 | 通過 | 否 | `9d1d575cfc2e8088…` |
| `autoresearch` | 1 | 0 | 通過 | 否 | `8bfae087ef27eb37…` |
| `aws-cdk-python-setup` | 1 | 0 | 通過 | 否 | `6aa92139f8058346…` |
| `aws-cloudwatch-investigation` | 1 | 0 | 通過 | 否 | `4e7be1e0d2a90503…` |
| `aws-cost-optimize` | 1 | 0 | 通過 | 否 | `a4034e859ce1f297…` |
| `aws-resource-health-diagnose` | 1 | 0 | 通過 | 否 | `6f689419a66b03f8…` |
| `aws-resource-query` | 1 | 0 | 通過 | 否 | `7e01b067764fe6de…` |
| `aws-well-architected-review` | 1 | 0 | 通過 | 否 | `b3415325d66dc0bf…` |
| `az-cost-optimize` | 1 | 0 | 通過 | 否 | `4bad09d0db105898…` |
| `azure-architecture-autopilot` | 18 | 3 | 通過 | 否 | `a4887d1d8849e1ee…` |
| `azure-container-registry-cli` | 5 | 0 | 通過 | 否 | `fcade086d866dbad…` |
| `azure-deployment-preflight` | 4 | 0 | 通過 | 否 | `b11e45a9efa28f47…` |
| `azure-developer-cli` | 6 | 0 | 通過 | 否 | `cfc5b6c853dca470…` |
| `azure-devops-cli` | 9 | 0 | 通過 | 否 | `b961cf722af56f25…` |
| `azure-pricing` | 5 | 0 | 通過 | 否 | `61a34c6a6cc4afe0…` |
| `azure-resource-health-diagnose` | 1 | 0 | 通過 | 否 | `b58a96f0f25e6e03…` |
| `azure-resource-visualizer` | 3 | 0 | 通過 | 否 | `c018cd757ecf745b…` |
| `azure-role-selector` | 2 | 0 | 通過 | 否 | `5ecf0325ccde3e3a…` |
| `azure-smart-city-iot-solution-builder` | 2 | 0 | 通過 | 否 | `58bd630d520f7925…` |
| `azure-static-web-apps` | 1 | 0 | 通過 | 否 | `d8aa020f4c266800…` |
| `azure-well-architected-review` | 1 | 0 | 通過 | 否 | `05bf13a08ae968d0…` |
| `batch-files` | 10 | 0 | 通過 | 否 | `26f16d5b2bbc64de…` |
| `bench-read` | 1 | 0 | 通過 | 否 | `10c02f2d228c1698…` |
| `bigquery-pipeline-audit` | 1 | 0 | 通過 | 否 | `42f544298ade22c4…` |
| `boost-prompt` | 1 | 0 | 通過 | 否 | `2621a44fbd9fc263…` |
| `brag-sheet` | 1 | 0 | 通過 | 否 | `235eebe934fdf634…` |
| `breakdown-epic-arch` | 1 | 0 | 通過 | 否 | `76217938e959a2a3…` |
| `breakdown-epic-pm` | 1 | 0 | 通過 | 否 | `4417e67abc0e2103…` |
| `breakdown-feature-implementation` | 1 | 0 | 通過 | 否 | `882f8ade84f599e3…` |
| `breakdown-feature-prd` | 1 | 0 | 通過 | 否 | `e0a851ff26f6ddc2…` |
| `breakdown-plan` | 1 | 0 | 通過 | 否 | `24abce941a7c952a…` |
| `breakdown-test` | 1 | 0 | 通過 | 否 | `aec76bd6b3246889…` |
| `bug-receipt` | 5 | 0 | 通過 | 否 | `fbda2096c57791ee…` |
| `bug-reproduction-brief` | 1 | 0 | 通過 | 否 | `d0b06abce04f9a0a…` |
| `build-evidence-map` | 5 | 0 | 通過 | 否 | `6a0165e96acac1dd…` |
| `centos-linux-triage` | 1 | 0 | 通過 | 否 | `cc32685413a75070…` |
| `chrome-devtools` | 1 | 0 | 通過 | 否 | `85d9c4ef94e00ddf…` |
| `cli-mastery` | 11 | 0 | 通過 | 否 | `48671fb184846481…` |
| `cloud-design-patterns` | 10 | 0 | 通過 | 否 | `99a94b073eb8551f…` |
| `code-exemplars-blueprint-generator` | 1 | 0 | 通過 | 否 | `1a4e9008100148a1…` |
| `code-tour` | 5 | 2 | 通過 | 否 | `8c925edb7128db05…` |
| `codebase-memory-mcp` | 1 | 0 | 通過 | 否 | `503d7ec0448902b6…` |
| `codeql` | 7 | 0 | 通過 | 否 | `e30d50fc7a2591c7…` |
| `comment-code-generate-a-tutorial` | 1 | 0 | 通過 | 否 | `8fad68f9f99c8eb4…` |
| `commit-message-storyteller` | 2 | 0 | 通過 | 否 | `12d806f64f59f5df…` |
| `competitor-ad-intelligence` | 1 | 0 | 通過 | 否 | `0262922726285868…` |
| `containerize-aspnet-framework` | 1 | 0 | 通過 | 否 | `e6608a11e7c5ce16…` |
| `containerize-aspnetcore` | 1 | 0 | 通過 | 否 | `23f73cb98109f2a5…` |
| `content-management-systems` | 2 | 0 | 通過 | 否 | `5f44650142f163c1…` |
| `context-map` | 1 | 0 | 通過 | 否 | `cca0523289057f0f…` |
| `conventional-branch` | 1 | 0 | 通過 | 否 | `62d556675f48fd45…` |
| `conventional-commit` | 1 | 0 | 通過 | 否 | `f29c9486cede6c7b…` |
| `convert-excel-to-md` | 4 | 1 | 通過 | 否 | `f71787157833541d…` |
| `convert-pdf-to-md` | 4 | 1 | 通過 | 否 | `fa65c2c6fb9b2ee8…` |
| `convert-plaintext-to-md` | 1 | 0 | 通過 | 否 | `934c017d41118a44…` |
| `convert-word-to-md` | 4 | 1 | 通過 | 否 | `f681a293519dc2a3…` |
| `copilot-cli-quickstart` | 1 | 0 | 通過 | 否 | `720e848c508c9fcc…` |
| `copilot-instructions-blueprint-generator` | 1 | 0 | 通過 | 否 | `45fd25e507349b05…` |
| `copilot-pr-autopilot` | 24 | 7 | 通過 | 否 | `abc5d7a83090b9be…` |
| `copilot-sdk` | 1 | 0 | 通過 | 否 | `16beed1bc9cddb25…` |
| `copilot-spaces` | 1 | 0 | 通過 | 否 | `8040e190fca0c4c5…` |
| `copilot-usage-metrics` | 5 | 4 | 通過 | 否 | `eef941d09ce84ae1…` |
| `cosmosdb-datamodeling` | 1 | 0 | 通過 | 否 | `b588fe7b9cf925ee…` |
| `create-agentsmd` | 1 | 0 | 通過 | 否 | `bfbdbb76b17cca97…` |
| `create-architectural-decision-record` | 1 | 0 | 通過 | 否 | `5c99e32293271aef…` |
| `create-github-action-workflow-specification` | 1 | 0 | 通過 | 否 | `527e6c77d921d58a…` |
| `create-github-issue-feature-from-specification` | 1 | 0 | 通過 | 否 | `e4d8019e1a7e43b4…` |
| `create-github-issues-feature-from-implementation-plan` | 1 | 0 | 通過 | 否 | `ff0083bd824eaa94…` |
| `create-github-issues-for-unmet-specification-requirements` | 1 | 0 | 通過 | 否 | `f44956e909348a20…` |
| `create-implementation-plan` | 1 | 0 | 通過 | 否 | `5c282fded01e40a7…` |
| `create-llms` | 1 | 0 | 通過 | 否 | `2eea327b7f6ad67d…` |
| `create-readme` | 1 | 0 | 通過 | 否 | `d0ece1b2164ce137…` |
| `create-specification` | 1 | 0 | 通過 | 否 | `9796c1d33858522e…` |
| `create-spring-boot-java-project` | 1 | 0 | 通過 | 否 | `f295d4ddc256642e…` |
| `create-spring-boot-kotlin-project` | 1 | 0 | 通過 | 否 | `3700dedac4c989d6…` |
| `create-technical-spike` | 1 | 0 | 通過 | 否 | `e711706b4aebacac…` |
| `create-tldr-page` | 1 | 0 | 通過 | 否 | `9d929bc6ed3e9f90…` |
| `creating-oracle-to-postgres-master-migration-plan` | 1 | 0 | 通過 | 否 | `7998313b9bfd779b…` |
| `creating-oracle-to-postgres-migration-bug-report` | 2 | 0 | 通過 | 否 | `4df0834a9cee4a21…` |
| `creating-oracle-to-postgres-migration-integration-tests` | 1 | 0 | 通過 | 否 | `fb863d5918442d6d…` |
| `csharp-async` | 1 | 0 | 通過 | 否 | `e889958419757528…` |
| `csharp-docs` | 1 | 0 | 通過 | 否 | `93da3063bb770f13…` |
| `csharp-mstest` | 1 | 0 | 通過 | 否 | `f8417ce1101a3ea9…` |
| `csharp-nunit` | 1 | 0 | 通過 | 否 | `2026047ba0a3b1f3…` |
| `csharp-tunit` | 1 | 0 | 通過 | 否 | `634bf822bdbd01c5…` |
| `csharp-xunit` | 1 | 0 | 通過 | 否 | `3c224e79f92ec027…` |
| `d365-solution-blueprint` | 3 | 0 | 通過 | 否 | `968f1582d44e7e31…` |
| `daily-focus-board` | 7 | 1 | 通過 | 否 | `63ed0493cd89351c…` |
| `daily-prep` | 1 | 0 | 通過 | 否 | `205915474441d698…` |
| `data-breach-blast-radius` | 7 | 0 | 通過 | 否 | `b0c31f0e3b1675de…` |
| `datanalysis-credit-risk` | 4 | 3 | 通過 | 否 | `cd5c6929cd087356…` |
| `dataverse-python-advanced-patterns` | 1 | 0 | 通過 | 否 | `dd4f65b62c3b702c…` |
| `dataverse-python-production-code` | 1 | 0 | 通過 | 否 | `7299422fdb42dced…` |
| `dataverse-python-quickstart` | 1 | 0 | 通過 | 否 | `624493386b6fec1d…` |
| `dataverse-python-usecase-builder` | 1 | 0 | 通過 | 否 | `f2350c6a1f6c297e…` |
| `debian-linux-triage` | 1 | 0 | 通過 | 否 | `88092e8dbcdbe6d3…` |
| `declarative-agents` | 1 | 0 | 通過 | 否 | `cbfcbb1f6916629d…` |
| `dependabot` | 4 | 0 | 通過 | 否 | `fae18b0bdde8dfbb…` |
| `desk-journal` | 1 | 0 | 通過 | 否 | `e3cadeea21300c25…` |
| `desk-open` | 1 | 0 | 通過 | 否 | `50c7d91bc5c4bc06…` |
| `devops-rollout-plan` | 1 | 0 | 通過 | 否 | `9c71bc5839febec1…` |
| `diagnose` | 1 | 0 | 通過 | 否 | `0bf9eac36d6a323b…` |
| `doc-and-modernize` | 3 | 0 | 通過 | 否 | `ada6c58e04e58dcf…` |
| `documentation-writer` | 1 | 0 | 通過 | 否 | `ee53d65b163cd7eb…` |
| `dotnet-best-practices` | 1 | 0 | 通過 | 否 | `9ef94db7f06c167d…` |
| `dotnet-design-pattern-review` | 1 | 0 | 通過 | 否 | `0b2b93ae1950e075…` |
| `dotnet-mcp-builder` | 14 | 0 | 通過 | 否 | `b8117cfe2045f402…` |
| `dotnet-timezone` | 3 | 0 | 通過 | 否 | `814f12020ca4c990…` |
| `dotnet-upgrade` | 1 | 0 | 通過 | 否 | `2cea79257527663b…` |
| `doublecheck` | 2 | 0 | 通過 | 否 | `14e5b23c10e90f81…` |
| `draw-io-diagram-generator` | 13 | 2 | 通過 | 否 | `1da717c88f800bb9…` |
| `drawio` | 3 | 0 | 通過 | 否 | `4c77e3941e561b97…` |
| `editorconfig` | 1 | 0 | 通過 | 否 | `19ce7c1a970666aa…` |
| `ef-core` | 1 | 0 | 通過 | 否 | `23f0a7c7e8c05033…` |
| `efcore-d2-db-diagram` | 6 | 0 | 通過 | 否 | `a005bdcbcfdb87b0…` |
| `em-dash` | 1 | 0 | 通過 | 否 | `c9de78fafa93e3a3…` |
| `email-drafter` | 1 | 0 | 通過 | 否 | `723dbf7b93c9ce95…` |
| `entra-agent-user` | 1 | 0 | 通過 | 否 | `e2a7744aa594d4e2…` |
| `eval-driven-dev` | 19 | 2 | 通過 | 否 | `0c1e32c05bc982e2…` |
| `exam-ready` | 1 | 0 | 通過 | 否 | `16aa13b7cd04bfed…` |
| `excalidraw-diagram-generator` | 16 | 3 | 通過 | 否 | `2a54a2bcc7449a01…` |
| `eyeball` | 2 | 1 | 通過 | 否 | `aa4c5c27420de620…` |
| `fabric-lakehouse` | 3 | 0 | 通過 | 否 | `6cacb6e3e314ad21…` |
| `fedora-linux-triage` | 1 | 0 | 通過 | 否 | `9f66d011d7eeead8…` |
| `finalize-agent-prompt` | 1 | 0 | 通過 | 否 | `a72bea0359d7f692…` |
| `finnish-humanizer` | 2 | 0 | 通過 | 否 | `1278a44a7b59b4b6…` |
| `first-ask` | 1 | 0 | 通過 | 否 | `5131fd3d73856342…` |
| `flowstudio-power-automate-build` | 7 | 0 | 通過 | 否 | `0499de938c4363a7…` |
| `flowstudio-power-automate-debug` | 3 | 0 | 通過 | 否 | `4dda121b4fd21c04…` |
| `flowstudio-power-automate-governance` | 1 | 0 | 通過 | 否 | `a20e415d1b47848d…` |
| `flowstudio-power-automate-mcp` | 5 | 0 | 通過 | 否 | `8f24ed6432eabcd0…` |
| `flowstudio-power-automate-monitoring` | 1 | 0 | 通過 | 否 | `b2538f6f422d22e3…` |
| `fluentui-blazor` | 5 | 0 | 通過 | 否 | `df33f6260612e66c…` |
| `folder-structure-blueprint-generator` | 1 | 0 | 通過 | 否 | `418d532c42d07149…` |
| `foundry-agent-sync` | 1 | 0 | 通過 | 否 | `546e7161500a94ca…` |
| `foundry-hosted-agent-copilotkit` | 7 | 0 | 通過 | 否 | `bd282e8a425b3d5b…` |
| `freecad-scripts` | 6 | 0 | 通過 | 否 | `bdeea83b417f2690…` |
| `from-the-other-side-anitta` | 1 | 0 | 通過 | 否 | `ff2517147341c9b4…` |
| `from-the-other-side-quinn` | 1 | 0 | 通過 | 否 | `10f8db43dac15e99…` |
| `from-the-other-side-vega` | 1 | 0 | 通過 | 否 | `083009d5f084f6db…` |
| `from-the-other-side-wiggins` | 1 | 0 | 通過 | 否 | `2d23f0682ce08e09…` |
| `game-engine` | 15 | 0 | 通過 | 否 | `72d38d5568aa8cc6…` |
| `gdpr-compliant` | 3 | 0 | 通過 | 否 | `9c88af335bc125c5…` |
| `gen-specs-as-issues` | 1 | 0 | 通過 | 否 | `7c33068d277612fa…` |
| `generate-custom-instructions-from-codebase` | 1 | 0 | 通過 | 否 | `f24a3997ee9034af…` |
| `generate-image` | 1 | 0 | 通過 | 否 | `f44895a266dab7b2…` |
| `geofeed-tuner` | 8 | 0 | 通過 | 否 | `d5e8ceef67516e41…` |
| `gh-attach` | 1 | 0 | 通過 | 否 | `9e6eb6ddbd36b416…` |
| `git-commit` | 1 | 0 | 通過 | 是 | `2607fc60629b82b2…` |
| `git-flow-branch-creator` | 1 | 0 | 通過 | 否 | `8add10a7fce31ef9…` |
| `github-actions-efficiency` | 5 | 0 | 通過 | 否 | `cb1a6b7a2d06465b…` |
| `github-actions-hardening` | 6 | 0 | 通過 | 否 | `d826005e7e1f7792…` |
| `github-actions-runtime-upgrade-conventions` | 1 | 0 | 通過 | 否 | `a2086c47b046d101…` |
| `github-codespaces-efficiency` | 3 | 0 | 通過 | 否 | `0a9b4539a39ae998…` |
| `github-copilot-starter` | 1 | 0 | 通過 | 否 | `7b29145c2d3255c3…` |
| `github-issues` | 10 | 0 | 通過 | 否 | `82a5c82edde734f4…` |
| `github-release` | 3 | 0 | 通過 | 否 | `89dd98ca83f681dd…` |
| `gitmoji` | 2 | 0 | 通過 | 否 | `f2dc8d3bb07fff4b…` |
| `go-mcp-server-generator` | 1 | 0 | 通過 | 否 | `96615e5275583ea9…` |
| `gsap-framer-scroll-animation` | 3 | 0 | 通過 | 否 | `2fba45d529987cdf…` |
| `gtm-0-to-1-launch` | 1 | 0 | 通過 | 否 | `ef73238bfc0595dc…` |
| `gtm-ai-gtm` | 1 | 0 | 通過 | 否 | `179d38abc1184661…` |
| `gtm-board-and-investor-communication` | 1 | 0 | 通過 | 否 | `57aa8c8172663efa…` |
| `gtm-developer-ecosystem` | 1 | 0 | 通過 | 否 | `7819e397036a1d73…` |
| `gtm-enterprise-account-planning` | 1 | 0 | 通過 | 否 | `06e4c111361ddaf8…` |
| `gtm-enterprise-onboarding` | 1 | 0 | 通過 | 否 | `0ce0c2753bbc9722…` |
| `gtm-operating-cadence` | 1 | 0 | 通過 | 否 | `5144c2dd67358b50…` |
| `gtm-partnership-architecture` | 1 | 0 | 通過 | 否 | `51ae01c42c88b12c…` |
| `gtm-positioning-strategy` | 1 | 0 | 通過 | 否 | `ab8c31ebdb6abb78…` |
| `gtm-product-led-growth` | 1 | 0 | 通過 | 否 | `3b4c43f619bc1c29…` |
| `gtm-technical-product-pricing` | 1 | 0 | 通過 | 否 | `d5d8428507f3f2ab…` |
| `harness-engineering` | 1 | 0 | 通過 | 否 | `a442c82ec3f8cb2d…` |
| `image-annotations` | 1 | 0 | 通過 | 否 | `72b07e580bf2f80d…` |
| `image-manipulation-image-magick` | 1 | 0 | 通過 | 否 | `f4f81a1054a423c5…` |
| `impediment-prioritization` | 2 | 0 | 通過 | 否 | `9b916616ce85690e…` |
| `import-infrastructure-as-code` | 1 | 0 | 通過 | 否 | `374b851dcf36c923…` |
| `incident-postmortem` | 1 | 0 | 通過 | 否 | `007d7bb94f77b0e9…` |
| `integrate-context-matic` | 1 | 0 | 通過 | 否 | `12cb5f0c22eb3afe…` |
| `issue-fields-migration` | 4 | 0 | 通過 | 否 | `ab597b7f46488706…` |
| `java-add-graalvm-native-image-support` | 1 | 0 | 通過 | 否 | `81dbd0ee073c906d…` |
| `java-docs` | 1 | 0 | 通過 | 否 | `76cf49efcd6e99d9…` |
| `java-helidon` | 1 | 0 | 通過 | 否 | `0b51be097e5b5fea…` |
| `java-junit` | 1 | 0 | 通過 | 否 | `fbf3cb0d47ffb44b…` |
| `java-mcp-server-generator` | 1 | 0 | 通過 | 否 | `845cd573740bbee0…` |
| `java-refactoring-extract-method` | 1 | 0 | 通過 | 否 | `8a467a2fe1f1d8c1…` |
| `java-refactoring-remove-parameter` | 1 | 0 | 通過 | 否 | `96f080496b55308f…` |
| `java-springboot` | 1 | 0 | 通過 | 否 | `f1b9c6b1277178fc…` |
| `javascript-typescript-jest` | 1 | 0 | 通過 | 否 | `0073d19ab0275eb6…` |
| `javax-to-jakarta-migration` | 1 | 0 | 通過 | 否 | `00012770ad983334…` |
| `kotlin-mcp-server-generator` | 1 | 0 | 通過 | 否 | `f1d6d04bd8302df9…` |
| `kotlin-springboot` | 1 | 0 | 通過 | 否 | `beaa34d307bfcce5…` |
| `landing-page-conversion-audit` | 1 | 0 | 通過 | 否 | `55925d3c6953ea31…` |
| `latchshot-page-capture` | 2 | 0 | 通過 | 否 | `d4544f4154167359…` |
| `legacy-circuit-mockups` | 21 | 0 | 通過 | 否 | `d47730d99627a2ad…` |
| `linkedin-post-formatter` | 2 | 0 | 通過 | 否 | `7deb516f53bc0921…` |
| `lsp-setup` | 2 | 0 | 通過 | 否 | `081a8a321adb82aa…` |
| `make-repo-contribution` | 3 | 0 | 通過 | 是 | `fb32b7ff09809454…` |
| `markdown-to-html` | 16 | 0 | 通過 | 否 | `23f0161bebfc9e3b…` |
| `markstream-install` | 2 | 0 | 通過 | 否 | `9f1eb38cefae79ed…` |
| `mcp-cli` | 1 | 0 | 通過 | 否 | `8133a09f06ac79d6…` |
| `mcp-copilot-studio-server-generator` | 1 | 0 | 通過 | 否 | `290b35da40b5a648…` |
| `mcp-create-adaptive-cards` | 1 | 0 | 通過 | 否 | `9b01d7e179ce010b…` |
| `mcp-create-declarative-agent` | 1 | 0 | 通過 | 否 | `e85004817b09658e…` |
| `mcp-deploy-manage-agents` | 1 | 0 | 通過 | 否 | `54e29de79d6047e3…` |
| `mcp-implementation-security-review` | 1 | 0 | 通過 | 否 | `b830bb1e079f2a34…` |
| `mcp-release-qa` | 1 | 0 | 通過 | 否 | `0be021c85ba69215…` |
| `mcp-security-audit` | 1 | 0 | 通過 | 否 | `033f6989c7a06e20…` |
| `md-to-docx` | 3 | 0 | 通過 | 否 | `9bc9373431fd16e6…` |
| `meeting-minutes` | 1 | 0 | 通過 | 否 | `d36e1cf7d58d1ea2…` |
| `memory-merger` | 1 | 0 | 通過 | 否 | `6d64cdfdbf2309c7…` |
| `mentoring-juniors` | 1 | 0 | 通過 | 否 | `ea3d12e594aea60a…` |
| `microsoft-agent-framework` | 3 | 0 | 通過 | 否 | `a7468c87acb4a9c8…` |
| `microsoft-code-reference` | 1 | 0 | 通過 | 否 | `2a86c1b1a876f777…` |
| `microsoft-docs` | 1 | 0 | 通過 | 否 | `e49127ff2162330a…` |
| `microsoft-skill-creator` | 2 | 0 | 通過 | 否 | `5ae8a80bec48aa90…` |
| `migrating-oracle-to-postgres-data-access-code` | 1 | 0 | 通過 | 否 | `318270c9c8cc250a…` |
| `migrating-oracle-to-postgres-stored-procedures` | 1 | 0 | 通過 | 否 | `56b0b20a035c3ba2…` |
| `minecraft-plugin-development` | 9 | 0 | 通過 | 否 | `bd19e92042e2fa9d…` |
| `mini-context-graph` | 15 | 10 | 通過 | 否 | `76c31d28049049c3…` |
| `mkdocs-translations` | 1 | 0 | 通過 | 否 | `782aa96093d10b12…` |
| `msgraph-sdk` | 4 | 0 | 通過 | 否 | `46abbfdc01f84812…` |
| `msstore-cli` | 1 | 0 | 通過 | 否 | `abaef9913fe8c0d0…` |
| `multi-stage-dockerfile` | 1 | 0 | 通過 | 否 | `698bf93a84dae18f…` |
| `mvvm-toolkit` | 6 | 0 | 通過 | 否 | `eef5c9359e6c2a08…` |
| `mvvm-toolkit-di` | 2 | 0 | 通過 | 否 | `4634500590015fe9…` |
| `mvvm-toolkit-messenger` | 2 | 0 | 通過 | 否 | `1e20b17a298adebe…` |
| `namecheap` | 3 | 1 | 通過 | 否 | `de24c97908cc8abd…` |
| `nano-banana-pro-openrouter` | 3 | 1 | 通過 | 否 | `7dc56ddabae20c52…` |
| `napkin` | 7 | 0 | 通過 | 否 | `f3159d521bbcb649…` |
| `next-intl-add-language` | 1 | 0 | 通過 | 否 | `6b30075c5f43a449…` |
| `noob-mode` | 3 | 0 | 通過 | 否 | `a216076927d4dd5d…` |
| `nuget-manager` | 1 | 0 | 通過 | 否 | `9081279ef0313a18…` |
| `onboard-context-matic` | 1 | 0 | 通過 | 否 | `ef32055c42e70a40…` |
| `oo-component-documentation` | 4 | 0 | 通過 | 否 | `e73eb40982936dd7…` |
| `openapi-to-application-code` | 1 | 0 | 通過 | 否 | `d98883f9f1f65b65…` |
| `optimize-simplicite-logs` | 3 | 2 | 通過 | 否 | `fe44199c1d52d6a3…` |
| `pdftk-server` | 6 | 0 | 通過 | 否 | `a550ce06418c31de…` |
| `penpot-uiux-design` | 5 | 0 | 通過 | 否 | `4f1e31c72780e296…` |
| `performance-review-writer` | 1 | 0 | 通過 | 否 | `41aa964d32bff755…` |
| `pester-migration` | 4 | 0 | 通過 | 否 | `2d7c0ef3a8727ba9…` |
| `pester-should-migration` | 2 | 0 | 通過 | 否 | `56990214b04b60d7…` |
| `phoenix-cli` | 3 | 0 | 通過 | 否 | `59cc10df53fe4144…` |
| `phoenix-evals` | 35 | 0 | 通過 | 否 | `079b0fb78404fa16…` |
| `phoenix-tracing` | 32 | 0 | 通過 | 否 | `0384d195b3f3853b…` |
| `php-mcp-server-generator` | 1 | 0 | 通過 | 否 | `f83ee3d7862186b4…` |
| `pinecone-rag` | 1 | 0 | 通過 | 否 | `5db881e5a6b47e6a…` |
| `planning-oracle-to-postgres-migration-integration-testing` | 1 | 0 | 通過 | 否 | `00fb60907c69314a…` |
| `plantuml-ascii` | 1 | 0 | 通過 | 是 | `2fb2b41487ea6559…` |
| `playwright-automation-fill-in-form` | 1 | 0 | 通過 | 否 | `05c39652cc1ef6a3…` |
| `playwright-explore-website` | 1 | 0 | 通過 | 否 | `ac361696198c2db2…` |
| `playwright-generate-test` | 1 | 0 | 通過 | 否 | `8f963da3e25f705f…` |
| `postgresql-code-review` | 1 | 0 | 通過 | 否 | `1167ec9449aa866e…` |
| `postgresql-optimization` | 1 | 0 | 通過 | 否 | `8022448de70ba9a4…` |
| `power-apps-code-app-scaffold` | 1 | 0 | 通過 | 否 | `6d09e31150a18531…` |
| `power-bi-dax-optimization` | 1 | 0 | 通過 | 否 | `e98206e9864acfbf…` |
| `power-bi-model-design-review` | 1 | 0 | 通過 | 否 | `0e1f4a853086b048…` |
| `power-bi-performance-troubleshooting` | 1 | 0 | 通過 | 否 | `93b5d254c846d138…` |
| `power-bi-report-design-consultation` | 1 | 0 | 通過 | 否 | `12dacbd64cd67369…` |
| `power-platform-architect` | 1 | 0 | 通過 | 否 | `536111d4874719e4…` |
| `power-platform-mcp-connector-suite` | 1 | 0 | 通過 | 否 | `da3f7078803c9e4f…` |
| `powerbi-modeling` | 6 | 0 | 通過 | 否 | `e22cc1880ea00f22…` |
| `pr-dashboard` | 4 | 0 | 通過 | 否 | `fedb7559c93ed6a4…` |
| `pr-screenshots` | 1 | 0 | 通過 | 否 | `ff7ffe37e28f3a44…` |
| `prd` | 1 | 0 | 通過 | 否 | `1f3e1f005fc40fda…` |
| `premium-frontend-ui` | 1 | 0 | 通過 | 否 | `e7f3d02a0233beaf…` |
| `project-workflow-analysis-blueprint-generator` | 1 | 0 | 通過 | 否 | `3d55c341daf416e1…` |
| `prompt-optimizer` | 1 | 0 | 通過 | 否 | `089759ae0d5a7701…` |
| `publish-to-pages` | 4 | 3 | 通過 | 否 | `455e16677960733d…` |
| `pytest-coverage` | 1 | 0 | 通過 | 否 | `06481f4bbc6d80a5…` |
| `python-azure-iot-edge-modules` | 3 | 0 | 通過 | 否 | `9dad8426d49009a2…` |
| `python-mcp-server-generator` | 1 | 0 | 通過 | 否 | `2b598920b5fdc807…` |
| `python-pypi-package-builder` | 11 | 1 | 通過 | 否 | `8715e6246d607208…` |
| `qdrant-clients-sdk` | 1 | 0 | 通過 | 否 | `141f4f633e3b60d9…` |
| `qdrant-deployment-options` | 1 | 0 | 通過 | 否 | `7e10de46a33e9422…` |
| `qdrant-model-migration` | 1 | 0 | 通過 | 否 | `9354dcdd3742ecbc…` |
| `qdrant-monitoring` | 3 | 0 | 通過 | 否 | `17f1c6ea6c5d5b00…` |
| `debugging` | 1 | 0 | 通過 | 否 | `456996c034f783e1…` |
| `setup` | 1 | 0 | 通過 | 否 | `9635bb6858d0d977…` |
| `qdrant-performance-optimization` | 4 | 0 | 通過 | 否 | `e3f72afa7f0f663d…` |
| `indexing-performance-optimization` | 1 | 0 | 通過 | 否 | `1516ad0ab806bf92…` |
| `memory-usage-optimization` | 1 | 0 | 通過 | 否 | `dda972659149dd18…` |
| `search-speed-optimization` | 1 | 0 | 通過 | 否 | `3507104d22abfc0c…` |
| `qdrant-scaling` | 9 | 0 | 通過 | 否 | `4b7ff46f80abf23b…` |
| `minimize-latency` | 1 | 0 | 通過 | 否 | `75afc4897a6fda22…` |
| `scaling-data-volume` | 5 | 0 | 通過 | 否 | `4f8391d277b07236…` |
| `horizontal-scaling` | 1 | 0 | 通過 | 否 | `833be1967b8d430f…` |
| `sliding-time-window` | 1 | 0 | 通過 | 否 | `7346d141b2f8e3d4…` |
| `tenant-scaling` | 1 | 0 | 通過 | 否 | `b39422bf1fd1ea93…` |
| `vertical-scaling` | 1 | 0 | 通過 | 否 | `1b33d0342c0cc877…` |
| `scaling-qps` | 1 | 0 | 通過 | 否 | `74acc4db9159ef45…` |
| `scaling-query-volume` | 1 | 0 | 通過 | 否 | `83c9d6d3dc7d5229…` |
| `qdrant-search-quality` | 3 | 0 | 通過 | 否 | `5527fde219461ef6…` |
| `diagnosis` | 1 | 0 | 通過 | 否 | `7f5a15ea831c9899…` |
| `search-strategies` | 1 | 0 | 通過 | 否 | `54ffb44b9c2424c0…` |
| `qdrant-version-upgrade` | 1 | 0 | 通過 | 否 | `fb7d84a8ddc0df9b…` |
| `quality-playbook` | 31 | 1 | 通過 | 否 | `0bdda24bce989770…` |
| `quasi-coder` | 1 | 0 | 通過 | 否 | `954dfd6b818d8b88…` |
| `react-audit-grep-patterns` | 5 | 0 | 通過 | 否 | `c3c0747eaeef14fa…` |
| `react-container-presentation-component` | 3 | 0 | 通過 | 否 | `488f03ea2d7d8596…` |
| `react18-batching-patterns` | 3 | 0 | 通過 | 否 | `1bf957086f4cefc7…` |
| `react18-dep-compatibility` | 3 | 0 | 通過 | 否 | `38afb0accdbaa088…` |
| `react18-enzyme-to-rtl` | 3 | 0 | 通過 | 否 | `e6fbd7c2de3e8ffa…` |
| `react18-legacy-context` | 4 | 0 | 通過 | 否 | `f052cf0b6a478a8e…` |
| `react18-lifecycle-patterns` | 4 | 0 | 通過 | 否 | `0b881b23f4c3b712…` |
| `react18-string-refs` | 2 | 0 | 通過 | 否 | `c26431b00816ae28…` |
| `react19-concurrent-patterns` | 4 | 0 | 通過 | 否 | `68bdb70e3d6328e4…` |
| `react19-source-patterns` | 2 | 0 | 通過 | 否 | `99a66743a4d7e829…` |
| `react19-test-patterns` | 1 | 0 | 通過 | 否 | `2544f319ef76174d…` |
| `readme-blueprint-generator` | 1 | 0 | 通過 | 否 | `e2c7dabf2e455794…` |
| `refactor` | 1 | 0 | 通過 | 否 | `87789a786b96f99b…` |
| `refactor-method-complexity-reduce` | 1 | 0 | 通過 | 否 | `a09a18f7b370e105…` |
| `refactor-plan` | 1 | 0 | 通過 | 否 | `26f32d34d48e9a40…` |
| `remember` | 1 | 0 | 通過 | 否 | `fdbc1d3eca3219bf…` |
| `remember-interactive-programming` | 1 | 0 | 通過 | 否 | `cdc356396df6b494…` |
| `repo-story-time` | 1 | 0 | 通過 | 否 | `8f85047285d0e911…` |
| `resemble-detect` | 3 | 0 | 通過 | 否 | `9f1e1ba6b11feb19…` |
| `review-and-refactor` | 1 | 0 | 通過 | 否 | `9236d06a1500089d…` |
| `reviewing-oracle-to-postgres-migration` | 16 | 0 | 通過 | 否 | `9dcf20189e8f9bb4…` |
| `rhino3d-scripts` | 5 | 0 | 通過 | 否 | `2fda98d502fc6f94…` |
| `roundup` | 1 | 0 | 通過 | 否 | `95d187f8b2922dfa…` |
| `roundup-setup` | 2 | 0 | 通過 | 否 | `3dce319b4dc216a6…` |
| `ruby-mcp-server-generator` | 1 | 0 | 通過 | 否 | `db811a087b7b1fa1…` |
| `ruff-recursive-fix` | 1 | 0 | 通過 | 否 | `a6f4b355dd277d24…` |
| `rust-mcp-server-generator` | 1 | 0 | 通過 | 否 | `420ae9213c67ac82…` |
| `salesforce-apex-quality` | 1 | 0 | 通過 | 否 | `cfd904f9077e9716…` |
| `salesforce-component-standards` | 1 | 0 | 通過 | 否 | `7a1cf40c098d927b…` |
| `salesforce-flow-design` | 1 | 0 | 通過 | 否 | `d8123acaa4f0f028…` |
| `sandbox-npm-install` | 2 | 1 | 通過 | 否 | `b50935e19ba9a7dc…` |
| `scaffolding-oracle-to-postgres-migration-test-project` | 1 | 0 | 通過 | 否 | `85f7027bf84288a9…` |
| `scoutqa-test` | 1 | 0 | 通過 | 否 | `e9155cb506ef7c59…` |
| `screen-recording` | 1 | 0 | 通過 | 否 | `d0574cf904de9243…` |
| `secret-scanning` | 4 | 0 | 通過 | 否 | `20384724e006def6…` |
| `security-review` | 6 | 0 | 通過 | 否 | `a0fc25587c016178…` |
| `semantic-kernel` | 3 | 0 | 通過 | 否 | `31fb0f54078cf5b4…` |
| `server-side-conversion-tracking` | 1 | 0 | 通過 | 否 | `7e7e012d88e4af05…` |
| `setup-my-iq` | 8 | 0 | 通過 | 否 | `30da196c54ed0a5b…` |
| `shopify-review-triage` | 1 | 0 | 通過 | 否 | `5ae994507aaefeb1…` |
| `shuffle-json-data` | 1 | 0 | 通過 | 否 | `9035306ade3aed0a…` |
| `signal-write` | 1 | 0 | 通過 | 否 | `f24e94755f8707ac…` |
| `slang-shader-engineer` | 4 | 0 | 通過 | 否 | `eb0b7d3632cc3e01…` |
| `snowflake-semanticview` | 1 | 0 | 通過 | 否 | `42d1bf4bd7a1edd9…` |
| `sponsor-finder` | 1 | 0 | 通過 | 否 | `155923073dbbfd9b…` |
| `spring-boot-testing` | 15 | 0 | 通過 | 否 | `eaad2dd0c8cc72d2…` |
| `sql-code-review` | 1 | 0 | 通過 | 否 | `7dd337a327138123…` |
| `sql-optimization` | 1 | 0 | 通過 | 否 | `47c930907f25d674…` |
| `sql-server-table-reconciliation` | 2 | 1 | 通過 | 否 | `a5ed8872caaf6575…` |
| `ssma-console` | 1 | 0 | 通過 | 否 | `559f7a8c2be01580…` |
| `steno-mode` | 1 | 0 | 通過 | 否 | `3c55c1345411e5ee…` |
| `structured-autonomy-generate` | 1 | 0 | 通過 | 否 | `bd623b72048f59aa…` |
| `structured-autonomy-implement` | 1 | 0 | 通過 | 否 | `f985115da51ff25a…` |
| `structured-autonomy-plan` | 1 | 0 | 通過 | 否 | `a23272e52745d64f…` |
| `suggest-awesome-github-copilot-agents` | 1 | 0 | 通過 | 否 | `974e629421e71810…` |
| `suggest-awesome-github-copilot-instructions` | 1 | 0 | 通過 | 否 | `d2545b97b786f573…` |
| `suggest-awesome-github-copilot-skills` | 1 | 0 | 通過 | 否 | `326ab63e60c60b28…` |
| `swift-mcp-server-generator` | 1 | 0 | 通過 | 否 | `3fd2caf5c3da6b0f…` |
| `system-commandline-cli` | 1 | 0 | 通過 | 否 | `e8b4417caefda94a…` |
| `technical-job-search` | 1 | 0 | 通過 | 否 | `004561bd2215b671…` |
| `technology-stack-blueprint-generator` | 1 | 0 | 通過 | 否 | `3819bfa893ce2aa7…` |
| `terraform-azurerm-set-diff-analyzer` | 6 | 1 | 通過 | 否 | `91fa4e814e4c5ec9…` |
| `threat-model-analyst` | 17 | 0 | 通過 | 否 | `6ee0c81d165bd517…` |
| `tiny-stepping` | 1 | 0 | 通過 | 否 | `03b8048ef1f610ff…` |
| `tldr-prompt` | 1 | 0 | 通過 | 否 | `3f5e0aec3cf4d16b…` |
| `tm7-threat-model` | 2 | 0 | 通過 | 否 | `2899cab94c50f557…` |
| `transloadit-media-processing` | 1 | 0 | 通過 | 否 | `f9b7f9988e6c9044…` |
| `typescript-mcp-server-generator` | 1 | 0 | 通過 | 否 | `389dd5b2f6bf325e…` |
| `typespec-api-operations` | 1 | 0 | 通過 | 否 | `55f60154f5280414…` |
| `typespec-create-agent` | 1 | 0 | 通過 | 否 | `2cf564e4ce7004a3…` |
| `typespec-create-api-plugin` | 1 | 0 | 通過 | 否 | `4f117e47c8da8be5…` |
| `ui-screenshots` | 1 | 0 | 通過 | 否 | `a69d97ff390d75e4…` |
| `unit-test-vue-pinia` | 2 | 0 | 通過 | 否 | `a474c899c691cfe4…` |
| `update-avm-modules-in-bicep` | 1 | 0 | 通過 | 否 | `8071b53c14b94932…` |
| `update-implementation-plan` | 1 | 0 | 通過 | 否 | `b2f2a6bf2544b416…` |
| `update-llms` | 1 | 0 | 通過 | 否 | `c54d9353f00ae1d3…` |
| `update-markdown-file-index` | 1 | 0 | 通過 | 否 | `c1a435b99ca6984c…` |
| `update-specification` | 1 | 0 | 通過 | 否 | `56ce126a1040962d…` |
| `vardoger-analyze` | 1 | 0 | 通過 | 否 | `7cd27bf876e5713f…` |
| `vcpkg` | 4 | 0 | 通過 | 否 | `f26a092177e642b5…` |
| `verify-agent-action` | 1 | 0 | 通過 | 否 | `6d695f80736cda67…` |
| `vscode-ext-commands` | 1 | 0 | 通過 | 否 | `26c40c1adb82b80a…` |
| `vscode-ext-localization` | 1 | 0 | 通過 | 否 | `d35790138865dae7…` |
| `web-design-reviewer` | 3 | 0 | 通過 | 否 | `7c1185d4ddfb42ec…` |
| `webapp-testing` | 2 | 1 | 通過 | 否 | `ef6fdb26c90b74f3…` |
| `webmcpify` | 12 | 5 | 通過 | 否 | `0bc1723ce1043b4e…` |
| `what-context-needed` | 1 | 0 | 通過 | 否 | `9a7c2542d4fc0e28…` |
| `winmd-api-search` | 9 | 2 | 通過 | 否 | `32162739f4b5e993…` |
| `winui3-migration-guide` | 1 | 0 | 通過 | 否 | `117001488fd02eb4…` |
| `workiq-copilot` | 1 | 0 | 通過 | 否 | `666b1ab2c3ffba95…` |
| `workshop-create` | 1 | 0 | 通過 | 否 | `4a4993b876ad650c…` |
| `write-coding-standards-from-file` | 1 | 0 | 通過 | 否 | `b87eddc73b6f759b…` |
| `x-twitter-scraper` | 1 | 0 | 通過 | 否 | `1a0c1ffed55fe1bd…` |

## 可能需要人工複核的內容

共 52 項技能包含命令或網路操作相關字串；這些只是稽核標記，不代表惡意。安裝或使用時應遵循最小權限與人工確認原則。

### `agent-governance`

偵測項目：curl

### `aspire`

偵測項目：curl, sudo 

### `automate-this`

偵測項目：curl, rm -rf, wget

### `aws-cdk-python-setup`

偵測項目：aws configure

### `aws-cost-optimize`

偵測項目：aws configure

### `aws-resource-health-diagnose`

偵測項目：aws configure

### `aws-resource-query`

偵測項目：aws configure

### `azure-architecture-autopilot`

偵測項目：az login

### `azure-container-registry-cli`

偵測項目：az login, curl, sudo 

### `azure-deployment-preflight`

偵測項目：az login

### `azure-developer-cli`

偵測項目：az login

### `azure-devops-cli`

偵測項目：curl, sudo 

### `batch-files`

偵測項目：CURL, WGET, curl, wget

### `codeql`

偵測項目：sudo 

### `competitor-ad-intelligence`

偵測項目：curl

### `containerize-aspnet-framework`

偵測項目：curl

### `containerize-aspnetcore`

偵測項目：curl, rm -rf, wget

### `convert-excel-to-md`

偵測項目：sudo 

### `convert-pdf-to-md`

偵測項目：sudo 

### `convert-word-to-md`

偵測項目：sudo 

### `copilot-pr-autopilot`

偵測項目：gh auth, sudo 

### `copilot-spaces`

偵測項目：gh auth

### `create-spring-boot-java-project`

偵測項目：curl

### `create-spring-boot-kotlin-project`

偵測項目：curl

### `flowstudio-power-automate-mcp`

偵測項目：cURL

### `foundry-agent-sync`

偵測項目：az login

### `foundry-hosted-agent-copilotkit`

偵測項目：az login, curl

### `github-issues`

偵測項目：gh auth

### `github-release`

偵測項目：gh auth

### `image-manipulation-image-magick`

偵測項目：sudo 

### `import-infrastructure-as-code`

偵測項目：az login

### `legacy-circuit-mockups`

偵測項目：sudo 

### `markdown-to-html`

偵測項目：sudo 

### `mcp-implementation-security-review`

偵測項目：curl, eval(, rm -rf

### `mcp-security-audit`

偵測項目：curl

### `nano-banana-pro-openrouter`

偵測項目：curl

### `noob-mode`

偵測項目：curl, rm -rf

### `pdftk-server`

偵測項目：curl, sudo 

### `penpot-uiux-design`

偵測項目：curl, rm -rf

### `plantuml-ascii`

偵測項目：sudo , wget

### `pr-dashboard`

偵測項目：gh auth

### `publish-to-pages`

偵測項目：curl, gh auth, rm -rf

### `qdrant-clients-sdk`

偵測項目：curl

### `quality-playbook`

偵測項目：rm -rf

### `ruby-mcp-server-generator`

偵測項目：chmod +x

### `sandbox-npm-install`

偵測項目：rm -rf, sudo 

### `security-review`

偵測項目：eval(

### `suggest-awesome-github-copilot-agents`

偵測項目：curl

### `suggest-awesome-github-copilot-instructions`

偵測項目：curl

### `suggest-awesome-github-copilot-skills`

偵測項目：curl

### `vcpkg`

偵測項目：curl, rm -rf

### `x-twitter-scraper`

偵測項目：curl
