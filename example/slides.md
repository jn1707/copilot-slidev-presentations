---
theme: default
class: text-left
transition: fade-out
---

# GitHub Copilot CLI

Your terminal's new sidekick

**Date:** February 15, 2026

**Public Preview**

<style>
h1 {
  font-weight: 900;
  color: #7B3FF2;
}
</style>

---
transition: fade-out
---

# What is GitHub Copilot CLI?

<v-clicks>

- AI-powered coding assistant for your terminal
- Reads, writes, and runs code where you work
- Agent-powered with GitHub-native context
- Part of Copilot Pro, Pro+, Business, and Enterprise

</v-clicks>

<style>
h1 {
  font-weight: 900;
  color: #7B3FF2;
}
</style>

---
transition: fade-out
---

# Key Advantages

<div style="display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 1.5rem; margin-top: 3rem;">
  <div style="background: linear-gradient(135deg, #f5f3ff 0%, #ede9fe 100%); border: 2px solid #7B3FF2; border-radius: 12px; padding: 1.5rem; box-shadow: 0 4px 16px rgba(123,63,242,0.12);">
    <h3 style="color: #7B3FF2; margin-bottom: 1rem;">Less Setup</h3>
    <p style="font-size: 0.9em;">Included with your Copilot subscription—no extra costs or complex configuration</p>
  </div>
  <div style="background: linear-gradient(135deg, #eff6ff 0%, #dbeafe 100%); border: 2px solid #1F6FEB; border-radius: 12px; padding: 1.5rem; box-shadow: 0 4px 16px rgba(31,111,235,0.12);">
    <h3 style="color: #1F6FEB; margin-bottom: 1rem;">GitHub Native</h3>
    <p style="font-size: 0.9em;">Direct access to your repositories, issues, and pull requests from terminal</p>
  </div>
  <div style="background: linear-gradient(135deg, #f0f9ff 0%, #e0f2fe 100%); border: 2px solid #58A6FF; border-radius: 12px; padding: 1.5rem; box-shadow: 0 4px 16px rgba(88,166,255,0.12);">
    <h3 style="color: #58A6FF; margin-bottom: 1rem;">Full Control</h3>
    <p style="font-size: 0.9em;">Explicit approvals for every action—complete transparency and security</p>
  </div>
</div>

<style>
h1 {
  font-weight: 900;
  color: #7B3FF2;
}
</style>

---
transition: fade-out
---

# What Can Copilot CLI Do?

<v-clicks>

- **Explore projects** – Understand codebase structure instantly
- **Install dependencies** – Setup new projects in seconds
- **Edit files** – Make changes with conversational commands
- **Run commands** – Execute build, test, and deploy tasks
- **Debug issues** – Iterate fast without leaving terminal
- **Access GitHub context** – Link issues and PRs directly

</v-clicks>

<style>
h1 {
  font-weight: 900;
  color: #7B3FF2;
}
</style>

---
layout: two-cols
transition: fade-out
---

# Use Cases

**Legacy Codebases**
- Navigate unfamiliar code
- Understand dependencies
- Explain architecture

**Cross-Platform Setup**
- Configure dev environments
- Install toolchains
- Resolve compatibility

::right::

**Multi-Step Tasks**
- Refactor across files
- Build complex features
- Automate workflows

**Rapid Prototyping**
- Generate boilerplate
- Test ideas quickly
- Iterate locally

<style>
h1 {
  font-weight: 900;
  color: #7B3FF2;
}
</style>

---
transition: fade-out
---

# Extending with MCP Servers

<!-- Model Context Protocol integration -->
<div class="mt-4">

**MCP (Model Context Protocol)** lets you extend Copilot CLI's capabilities:

- Connect custom tools and APIs
- Add domain-specific context
- Integrate internal systems
- Browse the [GitHub MCP Registry](https://github.com/mcp)

</div>

```bash
# Example: Search GitHub issues from terminal
gh copilot "Find beginner-friendly issues in cli/cli"
```

<style>
h1 {
  font-weight: 900;
  color: #7B3FF2;
}
</style>

---
transition: fade-out
---

# Frequently Asked Questions

**Q: Who can access Copilot CLI?**  
A: Included with Copilot Pro, Pro+, Business, and Enterprise plans

**Q: What operating systems are supported?**  
A: macOS, Linux, and Windows (via WSL)

**Q: How much does it cost?**  
A: No additional cost—included in your Copilot subscription

**Q: What models does CLI use?**  
A: Currently Claude Sonnet 4+ and GPT-5 (premium models only)

<style>
h1 {
  font-weight: 900;
  color: #7B3FF2;
}
</style>

---
transition: fade-out
---

# CLI vs VS Code Extension

**Copilot CLI**
- Terminal-focused workflow
- Agent-powered task execution
- Better for console operations
- Premium models only
- Explicit approval for actions

**VS Code Extension**
- Editor-integrated experience
- Inline code suggestions
- More mature feature set
- Free + premium models available
- Code checkpoints and richer UI

<style>
h1 {
  font-weight: 900;
  color: #7B3FF2;
}
</style>

---
transition: fade-out
---

# Community Feedback

<!-- Key insights from user experiences -->
<div style="display: flex; flex-direction: column; gap: 1.2rem; margin-top: 2rem;">

<div style="background: linear-gradient(90deg, #f5f3ff 0%, #f8f9fa 100%); border: 2px solid #7B3FF2; border-radius: 12px; box-shadow: 0 4px 16px rgba(123,63,242,0.08); padding: 1.2rem;">
  <span style="font-size: 1.05em; font-weight: bold; color: #7B3FF2;">Better Console Handling</span>
  <div class="mt-1">"CLI is somewhat better at using console—extension tends to run tests in watch mode and timeout"</div>
</div>

<div style="background: linear-gradient(90deg, #f5f3ff 0%, #f8f9fa 100%); border: 2px solid #7B3FF2; border-radius: 12px; box-shadow: 0 4px 16px rgba(123,63,242,0.08); padding: 1.2rem;">
  <span style="font-size: 1.05em; font-weight: bold; color: #7B3FF2;">Complementary Tools</span>
  <div class="mt-1">"Default to CLI if it solves your problems, use extension when it fails"</div>
</div>

<div style="background: linear-gradient(90deg, #f5f3ff 0%, #f8f9fa 100%); border: 2px solid #7B3FF2; border-radius: 12px; box-shadow: 0 4px 16px rgba(123,63,242,0.08); padding: 1.2rem;">
  <span style="font-size: 1.05em; font-weight: bold; color: #7B3FF2;">Different Approaches</span>
  <div class="mt-1">"Different team, different system prompt leads to different characteristics"</div>
</div>

</div>

<style>
h1 {
  font-weight: 900;
  color: #7B3FF2;
}
</style>

---
transition: fade-out
---

# Getting Started

**Installation:**

```bash
# Install GitHub CLI first (if not already installed)
brew install gh

# Install Copilot CLI extension
gh extension install github/gh-copilot

# Start using it
gh copilot
```

**First Steps:**
1. Run `gh copilot` to start interactive mode
2. Ask questions about your codebase
3. Request changes with natural language
4. Review and approve each action

<style>
h1 {
  font-weight: 900;
  color: #7B3FF2;
}
</style>

---
layout: center
class: text-center
transition: fade-out
---

# Try GitHub Copilot CLI

Code faster, smarter, together.

<div class="mt-8">

[Install Now](https://github.com/github/copilot-cli) · [Documentation](https://docs.github.com/copilot/concepts/agents/about-copilot-cli) · [Pricing](https://github.com/features/copilot/plans)

</div>

<div class="mt-8 text-sm opacity-70">

Questions?

</div>

<style>
h1 {
  font-weight: 900;
  color: #7B3FF2;
}
</style>
