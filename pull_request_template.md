## 附录：Pull Request (PR) 提交模板
请在每次提交 PR 时，复制以下内容到描述中并如实勾选：


### 📝 PR 检查清单 (PR Checklist)

**1. 项目基础信息：**
- [ ] 本项目安全级别为： `[请填写: Level 1 / 2 / 3]`
- [ ] (仅限前端新建项目) 我已在 README.md 中说明了前端框架的选择原因 (不少于 50 字)。

**2. AI 辅助说明：**
- [ ] 本次代码主要使用了以下 AI 工具进行辅助编写：
  - [ ] Cursor Auto
  - [ ] Claude Sonnet
  - [ ] Gemini 3 Pro
  - [ ] 无，纯手工编写

**3. 安全与质量自查：**
- [ ] 代码已通过本地 ESLint / Prettier 格式化检查。
- [ ] GitHub Actions (CI/CD) 及 CodeQL 安全扫描已全部通过 (显示绿勾)。
- [ ] 我已检查过新增代码的异常处理 (Try/Catch) 及边界条件。
- [ ] (针对 Level 2/3) 核心逻辑变更已邀请相关同事或 Tech Lead 进行 Code Review。

**简要描述本次 PR 的主要改动：**
