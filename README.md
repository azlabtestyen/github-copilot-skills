# GitHub Copilot Skills 完整封裝

本 repository 保存從官方 [github/awesome-copilot](https://github.com/github/awesome-copilot) 固定版本匯出的完整 Agent Skills 集合。

## 內容

- `packages/<skill-name>/`：逐項可讀的原始技能目錄。
- `archives/<skill-name>.skill`：逐項可攜式 `.skill` 封裝。
- `AUDIT.md`：技能數量、結構、腳本與安全標記報告。
- `audit.json`：機器可讀的完整索引與 SHA-256。

## 安全注意事項

技能可能包含腳本、網路操作或要求命令權限。請在使用前閱讀對應的 `SKILL.md`，不要對未審查的技能預先允許 shell/bash。
