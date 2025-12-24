# 🎯 Agent Skills

Agent Skills are self-contained folders with instructions and bundled resources that enhance AI capabilities for specialized tasks. Based on the [Agent Skills specification](https://agentskills.io/specification), each skill contains a `SKILL.md` file with detailed instructions that agents load on-demand.

Skills differ from other primitives by supporting bundled assets (scripts, code samples, reference data) that agents can utilize when performing specialized tasks.
### How to Use Agent Skills

**What's Included:**
- Each skill is a folder containing a `SKILL.md` instruction file
- Skills may include helper scripts, code templates, or reference data
- Skills follow the Agent Skills specification for maximum compatibility

**When to Use:**
- Skills are ideal for complex, repeatable workflows that benefit from bundled resources
- Use skills when you need code templates, helper utilities, or reference data alongside instructions
- Skills provide progressive disclosure - loaded only when needed for specific tasks

**Usage:**
- Browse the skills table below to find relevant capabilities
- Copy the skill folder to your local skills directory
- Reference skills in your prompts or let the agent discover them automatically

| Name | Description | Bundled Assets |
| ---- | ----------- | -------------- |
| [ios-open-source-app-study](../skills/ios-open-source-app-study/SKILL.md) | A step-by-step Copilot kit (agents/prompts/instructions/docs) to deeply understand an open-source iOS app codebase (Swift/SwiftUI/Xcode), including a foqos case study workflow. | `templates/.github/agents/ios-feature-replication-coach.agent.md`<br />`templates/.github/agents/ios-project-onboarding.agent.md`<br />`templates/.github/docs/foqos-walkthrough.md`<br />`templates/.github/docs/ios-study-workflow.md`<br />`templates/.github/instructions/ios-pr-review-checklist.instructions.md`<br />`templates/.github/instructions/ios-project-study.instructions.md`<br />`templates/.github/prompts/ios-dependency-audit.prompt.md`<br />`templates/.github/prompts/ios-feature-slice-learning-card.prompt.md`<br />`templates/.github/prompts/ios-file-by-file-notes.prompt.md`<br />`templates/.github/prompts/ios-module-map.prompt.md`<br />`templates/.github/prompts/ios-repo-triage.prompt.md`<br />`templates/.github/prompts/ios-similar-feature-implementation-guide.prompt.md`<br />`templates/.github/prompts/ios-targets-capabilities-map.prompt.md` |
| [webapp-testing](../skills/webapp-testing/SKILL.md) | Toolkit for interacting with and testing local web applications using Playwright. Supports verifying frontend functionality, debugging UI behavior, capturing browser screenshots, and viewing browser logs. | `test-helper.js` |
