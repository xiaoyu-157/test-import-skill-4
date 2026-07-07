## Description: <br>
Helps agents learn from corrections, self-reflection, and repeated workflow patterns by maintaining local memory and guidance files. <br>

This skill is ready for commercial/non-commercial use. <br>

## Publisher: <br>
[xiaoyu-157](https://clawhub.ai/user/xiaoyu-157) <br>

### License/Terms of Use: <br>
MIT-0 <br>


## Use Case: <br>
Developers and agent users can use this skill to preserve corrections, preferences, and reusable execution lessons across sessions while keeping memory organized by global, domain, and project scope. <br>

### Deployment Geography for Use: <br>
Global <br>

## Known Risks and Mitigations: <br>
Risk: Local cross-session memory can retain sensitive corrections, preferences, or workflow details if users store them by mistake. <br>
Mitigation: Review ~/self-improving/ periodically, avoid storing secrets or sensitive personal data, and use the documented show, export, and forget controls to inspect or clear memory. <br>
Risk: Setup guidance can change local workspace steering files such as AGENTS.md, SOUL.md, and HEARTBEAT.md. <br>
Mitigation: Review proposed file changes before relying on them, preserve existing workspace guidance, and require explicit user consent before installing the optional Proactivity companion skill. <br>
Risk: Incorrect or stale lessons could cause an agent to apply outdated preferences or overgeneralize a narrow correction. <br>
Mitigation: Keep new lessons tentative until repeated or confirmed, isolate project-specific rules from global memory, cite memory sources when applying them, and support deletion when the user asks to forget. <br>


## Reference(s): <br>
- [ClawHub skill page](https://clawhub.ai/xiaoyu-157/self-improving-1-2-16-1) <br>
- [Skill homepage](https://clawic.com/skills/self-improving) <br>


## Skill Output: <br>
**Output Type(s):** [text, markdown, shell commands, configuration, guidance] <br>
**Output Format:** [Markdown guidance with shell commands and configuration snippets] <br>
**Output Parameters:** [1D] <br>
**Other Properties Related to Output:** [May create or update local Markdown memory files under ~/self-improving/ when activated by an agent; no extra binaries are required.] <br>

## Skill Version(s): <br>
1.0.0 (source: ClawHub release metadata; artifact frontmatter version 1.2.16) <br>

## Ethical Considerations: <br>
Users should evaluate whether this skill is appropriate for their environment, review any generated or modified files before relying on them, and apply their organization's safety, security, and compliance requirements before deployment. <br>
