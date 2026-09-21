# Xrotel Agents

### Codex was built for agents. Xrotel helps them work like a team.

Xrotel Agents is a ready-to-use multi-agent orchestration system for OpenAI Codex.

Instead of treating every development task as one long job for one agent, Xrotel gives Codex a structured team of specialised agents for exploration, implementation, validation, deeper reasoning and risk review.

You choose the orchestration profile.

Xrotel handles how the team works.

---

## 🔒 Before anything else: Xrotel does not modify Codex

Xrotel does **not** inject into, patch, replace or modify the Codex application.

It does not:

* patch the Codex client;
* inject code into Codex;
* intercept OpenAI traffic;
* proxy your OpenAI requests;
* modify your ChatGPT or Codex subscription;
* bypass usage controls;
* spoof another client;
* share or require your OpenAI credentials;
* install a background service between you and OpenAI.

Xrotel is a configuration and instruction package designed to work with Codex's existing project instructions and agent functionality.

**Your Codex installation remains Codex.**

### Works with Codex — not around it.

Xrotel is an independent third-party project and is not affiliated with, sponsored by or endorsed by OpenAI.

---

# 🤖 Meet the team

The important part isn't simply having more agents.

**It's knowing when to use them.**

Xrotel separates different kinds of development work across specialised roles.

### 🔎 Repository Explorer

Investigates unfamiliar projects, identifies relevant files and gathers context before unnecessary implementation begins.

### 🛠 Implementation Worker

Handles focused implementation once the problem and relevant scope are understood.

### 🧪 Test Runner

Validates implementations independently and reports whether the required checks actually pass.

### 🛡 Risk Reviewer

Looks for regressions, security implications, edge cases and architectural risks that implementation alone may miss.

### 🧠 Deep Solver

Handles bounded difficult engineering problems when deeper reasoning is genuinely warranted.

### 🏗 Lead Architect

Provides higher-level technical judgement for difficult planning, architectural decisions and complex implementation boundaries.

### 🎯 Intent Agents

Help preserve what the user actually asked for so that increasingly complicated development work does not drift away from the original goal.

### 📚 Evidence Curator

Helps gather and consolidate evidence when decisions need stronger technical grounding.

### 🚀 Frontier Architect

Reserved for especially difficult architectural reasoning where the selected orchestration profile calls for it.

---

# Four orchestration profiles

Xrotel lets each project use the profile appropriate for the work being performed.

## ⚡ Efficient

**Capability without unnecessary overhead.**

Designed for projects where you want coordinated agents while keeping the workflow deliberately lean.

Recommended starting primary family:

**Luna High**

---

## ⚖️ Balanced

**The everyday Xrotel profile.**

A balance of implementation capability, validation, delegation and reasoning for normal software-development work.

Recommended starting primary family:

**Luna Max**

---

## 🔥 Power

**For demanding engineering work.**

Power gives the primary stronger responsibility for technical direction while delegating substantial implementation work appropriately.

Recommended starting primary family:

**Sol Medium**

Reasoning level remains flexible within the supported Sol family.

---

## 🚀 Maximum

**For the difficult jobs.**

Maximum is designed for complex engineering work where stronger architecture, acceptance and deeper reasoning matter more than keeping the workflow minimal.

Recommended starting primary family:

**Astra Medium**

---

# 🔄 Switch profiles per project

You don't have to reinstall Xrotel every time you want a different workflow.

After the Universal Core has been installed, an individual project can be switched between:

**Efficient → Balanced → Power → Maximum**

The project's Xrotel profile changes without replacing your global agent files or modifying your source code.

Start a fresh Codex session after changing a project profile so its project instructions are loaded cleanly.

---

# ⬇️ Download Xrotel

Download the latest packages from:

**GitHub Releases → Latest Release**

For most users, the easiest option is the complete Xrotel package containing all available profiles.

Individual profile packages are also provided for users who prefer them.

---

# ❤️ Xrotel is free

Xrotel Orchestrator is currently available free of charge.

If it improves your Codex workflow, saves you time or helps you build better software, you can optionally support continued development.

### Support once

https://www.paypal.com/ncp/payment/X3YXRNX2WWSZ6

### Support Xrotel monthly — $3/month

https://www.paypal.com/webapps/billing/plans/subscribe?plan_id=P-1HU900860L732862RNKMIYKY

Financial support is completely optional and does not purchase additional licence rights.

Can't support financially?

⭐ Star the repository
🐛 Report an issue
💬 Share your experience
📣 Tell another developer about Xrotel

That helps too.

---

# 📦 Installation

After downloading your chosen Xrotel package:

1. Extract the ZIP.
2. Open `README-FIRST.md`.
3. Follow the installation instructions provided with the package.
4. Run the included Project Optimizer once for projects you want to make profile-switchable.
5. Select the appropriate primary model family in Codex.
6. Start a fresh Codex session.

No Xrotel server, account or external service is required to run the orchestration package.

---

# 🔐 Your code stays where it is

Xrotel does not require you to upload your repository to Xrotel.

It does not act as an API proxy and does not need access to your OpenAI credentials.

The configuration operates in the Codex environment where you install it.

---

# 📝 Licensing

Xrotel is free to use under the included Xrotel Personal / Internal Use License.

You may use and modify Xrotel for your own personal or commercial software-development work.

Redistribution, resale, mirroring or repackaging for unrelated third parties is not permitted.

See `LICENSE.md` for the complete terms.

---

# ⚠️ Compatibility

OpenAI may independently change Codex, available models, reasoning levels, configuration behaviour or agent capabilities.

Xrotel will continue to evolve alongside supported Codex workflows where practical.

---

# Xrotel Agents

**Build with a team, not just an agent.**
