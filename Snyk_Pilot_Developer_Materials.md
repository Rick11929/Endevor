# Snyk Code + IaC Pilot Testing – Developer Materials
# Snyk Code + IaC 试点测试 – 开发者材料

---

## 1. Developer Task Checklist（开发者任务清单）
**可以直接发给 40 位开发者使用**

### English Version

**Snyk Code + IaC Pilot – Your Task Checklist**

Please complete the following tasks during the pilot period.  
Estimated time: 1–2 hours in total (spread over the pilot weeks).

#### Mandatory Tasks

| # | Task | Status | Notes |
|---|------|--------|-------|
| 1 | Install Snyk CLI on your machine (macOS / Windows / Linux) | ☐ | |
| 2 | Authenticate successfully (`snyk auth`) | ☐ | |
| 3 | Install Snyk plugin in your main IDE (VS Code / IntelliJ / other) | ☐ | |
| 4 | Run at least **one** `snyk code test` on a real project | ☐ | |
| 5 | Run at least **one** `snyk iac test` (if you have Terraform / K8s / CloudFormation files) | ☐ | |
| 6 | Use the IDE plugin for real-time scanning while coding (at least 30–60 min) | ☐ | |
| 7 | Try at least one Fix / Agent Fix suggestion (if available) | ☐ | |
| 8 | Submit the **Mid-term Feedback** form (end of Week 2) | ☐ | |
| 9 | Submit the **Final Questionnaire** (end of Week 4) | ☐ | |

#### Optional but Highly Encouraged
- Compare the same project results with Checkmarx
- Test on more than one language / project
- Share interesting findings in the Teams/Slack channel

**Support Channel**: [Your Teams/Slack channel name]  
**Office Hours**: Every [Day] [Time]

---

### 中文版

**Snyk Code + IaC 试点测试 – 开发者任务清单**

请在试点期间完成以下任务。  
预计总时间：1–2 小时（可分散在几周内完成）。

#### 必须完成的任务

| # | 任务 | 状态 | 备注 |
|---|------|------|------|
| 1 | 在本地安装 Snyk CLI（macOS / Windows / Linux） | ☐ | |
| 2 | 成功完成认证（`snyk auth`） | ☐ | |
| 3 | 在主要 IDE 中安装 Snyk 插件（VS Code / IntelliJ / 其他） | ☐ | |
| 4 | 对真实项目至少执行一次 `snyk code test` | ☐ | |
| 5 | 至少执行一次 `snyk iac test`（如果有 Terraform / K8s / CloudFormation 文件） | ☐ | |
| 6 | 在编码过程中使用 IDE 插件进行实时扫描（累计至少 30–60 分钟） | ☐ | |
| 7 | 尝试至少一次修复建议（Fix / Agent Fix，如有） | ☐ | |
| 8 | 提交**中期反馈**表格（第 2 周末） | ☐ | |
| 9 | 提交**最终问卷**（第 4 周末） | ☐ | |

#### 可选但强烈建议
- 对比同一项目在 Checkmarx 与 Snyk 的扫描结果
- 测试多个语言 / 项目
- 在 Teams/Slack 频道分享有趣的发现

**支持频道**：[你的 Teams/Slack 频道名称]  
**Office Hour**：每周 [星期几] [时间]

---

## 2. Detailed Questionnaire（详细问卷问题清单）

### A. Mid-term Feedback (Week 2) – 中期反馈（第2周）

**English**

1. Have you successfully installed and authenticated the Snyk CLI?  
   - Yes / No / Had issues (please describe)

2. Have you successfully installed the IDE plugin?  
   - Yes / No / Had issues (please describe)

3. How easy was the installation process overall? (1 = Very difficult, 10 = Very easy)

4. Did you encounter any network / authentication problems due to the company intranet?  
   - Yes / No / Comments

5. Any immediate blockers or questions?

**中文**

1. 你是否已成功安装并完成 Snyk CLI 认证？  
   - 是 / 否 / 遇到问题（请描述）

2. 你是否已成功安装 IDE 插件？  
   - 是 / 否 / 遇到问题（请描述）

3. 整体安装过程的容易程度？（1 = 非常困难，10 = 非常容易）

4. 是否因公司内网限制遇到网络或认证问题？  
   - 是 / 否 / 补充说明

5. 目前有任何阻碍或问题吗？

---

### B. Final Questionnaire (Week 4) – 最终问卷（第4周）

**English Version**

**Section 1: Basic Information**
1. Your name / team / primary programming language(s)
2. How many real projects did you scan with Snyk Code?
3. Did you test Snyk IaC? (Yes / No)

**Section 2: Installation & Setup (1–10 scale)**
4. Ease of installing CLI
5. Ease of installing IDE plugin
6. Ease of authentication

**Section 3: Scanning Experience**
7. Perceived scan speed compared to Checkmarx (Much slower / Slightly slower / Similar / Slightly faster / Much faster)
8. How useful were the findings overall? (1 = Not useful, 10 = Very useful)
9. What percentage of findings do you consider real / actionable? (approx. %)
10. What percentage of findings do you consider noise / false positives? (approx. %)
11. Did the IDE real-time scanning interfere with your normal coding flow? (1 = No interference, 10 = Severe interference)

**Section 4: Fix Suggestions**
12. Did you try any Fix / Agent Fix suggestions? (Yes / No)
13. If yes, how helpful were they? (1–10)
14. Would you trust and apply the suggested fixes in production code? (Yes / Maybe / No)

**Section 5: Comparison & Adoption**
15. Overall, how does the developer experience of Snyk (CLI + IDE) compare to your current Checkmarx usage?  
    (Much worse / Worse / Similar / Better / Much better)
16. Would you be willing to continue using Snyk CLI + IDE in your daily work after this pilot?  
    (Definitely not / Probably not / Neutral / Probably yes / Definitely yes)
17. What is the single biggest advantage you saw?
18. What is the single biggest drawback or concern?
19. Any other comments or suggestions?

**中文版**

**第一部分：基本信息**
1. 你的姓名 / 团队 / 主要编程语言
2. 你用 Snyk Code 扫描了几个真实项目？
3. 你是否测试了 Snyk IaC？（是 / 否）

**第二部分：安装与设置（1–10 分）**
4. CLI 安装容易程度
5. IDE 插件安装容易程度
6. 认证过程容易程度

**第三部分：扫描体验**
7. 与 Checkmarx 相比，扫描速度感觉如何？（慢很多 / 稍慢 / 差不多 / 稍快 / 快很多）
8. 整体发现结果的有用程度？（1 = 完全没用，10 = 非常有用）
9. 你认为大约多少比例的发现是真实 / 可行动的？（约 %）
10. 你认为大约多少比例的发现是噪音 / 误报？（约 %）
11. IDE 实时扫描对你正常编码流程的干扰程度？（1 = 几乎无干扰，10 = 严重干扰）

**第四部分：修复建议**
12. 你是否尝试过 Fix / Agent Fix 建议？（是 / 否）
13. 如果尝试过，有用程度？（1–10）
14. 你是否信任并愿意在生产代码中应用这些修复建议？（是 / 可能 / 否）

**第五部分：对比与采用意愿**
15. 整体而言，Snyk（CLI + IDE）的开发者体验与你目前使用的 Checkmarx 相比如何？  
    （差很多 / 较差 / 差不多 / 较好 / 好很多）
16. 试点结束后，你是否愿意在日常工作中继续使用 Snyk CLI + IDE？  
    （肯定不会 / 可能不会 / 中立 / 可能会 / 肯定会）
17. 你看到的最大优点是什么？
18. 最大的缺点或顾虑是什么？
19. 其他意见或建议？

---

## 3. Kick-off Meeting PPT Outline（启动会 PPT 大纲）

**建议总时长：45–60 分钟**

### Slide Structure

**Slide 1 – Title**  
Snyk Code + IaC Pilot Testing Kick-off  
公司内网 CLI + IDE 试点启动会  
Date | Presenter

**Slide 2 – Agenda**  
1. Why we are doing this pilot  
2. Scope & Limitations  
3. What we ask you to do  
4. Timeline  
5. Success Criteria  
6. Support & Next Steps  
7. Q&A

**Slide 3 – Why this Pilot**  
- Evaluate modern SAST experience focused on developer productivity  
- Focus on AI-era code security needs  
- Collect real feedback from 40 developers before larger decisions  
- Current limitation: No Broker → cannot do SCM integration yet

**Slide 4 – Scope**  
**In Scope**  
- Snyk Code (SAST)  
- Snyk IaC  
- CLI + IDE plugins only  

**Out of Scope (for now)**  
- SCM / PR checks  
- CI/CD full integration  
- Snyk Broker  
- Container scanning

**Slide 5 – What You Need to Do (Checklist Summary)**  
Show the 9 mandatory tasks clearly  
Emphasize: Total time investment is small (1–2 hours)

**Slide 6 – Timeline**  
Week 1: Kick-off + Installation  
Week 2–3: Active testing on real projects  
Week 4: Final questionnaire + deeper feedback  
Week 5: Analysis & report

**Slide 7 – Success Criteria (High Level)**  
- ≥70% participation completion  
- Good developer experience scores  
- Majority willingness to continue using  
- Clear evidence of value vs current tools

**Slide 8 – How We Will Support You**  
- Dedicated Teams/Slack channel  
- Weekly Office Hours  
- Champions for each tech stack  
- Installation guide + FAQ document

**Slide 9 – Important Notes**  
- Code will be analyzed in Snyk Cloud (confirm with compliance if needed)  
- Use real projects if possible, otherwise provided sample projects  
- Be honest in feedback – both positive and negative are valuable

**Slide 10 – Next Immediate Actions**  
1. Join the support channel today  
2. Install CLI + IDE plugin this week  
3. Complete first scan before end of Week 1  
4. Watch for mid-term survey link

**Slide 11 – Q&A**

**Slide 12 – Thank You / Contact**

---

**文件已准备好：**
- Excel 追踪模板：`Snyk_Pilot_Success_Criteria_Tracker.xlsx`
- 本 Markdown 文件包含完整的 Checklist + 问卷 + PPT 大纲
