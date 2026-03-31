# DeClaw: Secure Your Personal AI Assistants
### By DeClaw

**Stop PII leaks. Deflect Direct or Indirect Prompt Injections. 100% Local Processing.**

DeClaw is an **Endpoint DLP** (Data Loss Prevention) and **AI Security** layer for macOS that sits between your personal AI agents and Internet. It runs entirely on your device, ensuring your sensitive data (SSN, credit cards, API keys) never leaves your machine unmasked.

---

## 🔒 Why DeClaw?

### 1. Local-First Architecture
Unlike cloud security proxies, DeClaw is a native macOS binary.
- **No Servers:** We do not see, store, or process your prompts.
- **Zero Latency:** Millisecond scanning happens in RAM on your Mac.
- **Privacy:** Your data stays yours.

### 2. Intelligent PII Redaction
DeClaw automatically detects and masks sensitive entities *before* they are sent to an LLM.
- **Supported:** US SSN, Credit Cards, API Keys (AWS, OpenAI, etc.), Email Addresses, Phone Numbers.
- **How it works:** `My SSN is 123-45-6789` → `My SSN is [SSN_REDACTED]`. The LLM never sees the real value.

### 3. Prompt Injection Defense
Blocks malicious "Indirect Injections" hidden in websites or documents that try to hijack your AI agent.
- **Pre-Execution Scanning:** analyzing inputs for manipulative patterns.
- **Skill Protection:** Prevents unauthorized tool use (e.g., file system access, email sending).

---

## 📥 Installation

**Requirements:**
- macOS 12.0 (Monterey) or later.
- Apple Silicon (M1/M2/M3) recommended.

**Steps:**
1.  Get your Free License Key from [website](https://declaw.ai/#pricing)
1.  **Download** the latest `.dmg` from the [Releases](https://github.com/declaw-ai/declaw-desktop/releases) page.
2.  Open the DMG and drag **DeClaw.app** to your **Applications** folder.
3.  Launch DeClaw from Applications. Activate Declaw by giving your license key.
4.  Follow the onboarding steps to install the local CA certificate (required for HTTPS inspection).

---

## 🛡️ Privacy & Trust

DeClaw is built by the team at **DeClaw**.

- **No Data Collection:** We do not collect your prompts, file contents, or screen data.
- **Crash Reports:** Opt-in only. Traces to help us fix bugs.
- **Usage Stats:** We collect minimal, pseudonymous counters (e.g., "5 threats blocked today") linked to a random installation ID to verify the software's effectiveness.

View our full [Privacy Policy](https://declaw.ai/privacy) and [Terms of Service](https://declaw.ai/terms).

---

## 🐛 Support & Feedback

Found a bug? Have a feature request?
Please open an [Issue](https://github.com/declaw-ai/declaw-desktop/issues) in this repository.

---

*Disclaimer: DeClaw is security software provided "as is". While we strive for perfection, no software is flawless. Always review critical outputs.*

Copyright © 2026 DeClaw. All rights reserved.
