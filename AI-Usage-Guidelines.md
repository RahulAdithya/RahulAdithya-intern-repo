# AI Usage Guidelines & Reflection
**Author:** Rahul Adithya

## 🔍 Research & Learn

### 1. AI Tools for My Role
As an intern focusing on cybersecurity and development, typical tools include:
* **Large Language Models (LLMs):** Like Gemini or ChatGPT for explaining complex security concepts or summarizing documentation.
* **Coding Assistants:** Like GitHub Copilot for boilerplate code generation and debugging assistance.
* **Security Scanners:** AI-driven tools that identify vulnerabilities in source code.

### 2. Benefits & Risks in a Professional Setting
* **Benefits:** Significant productivity boosts, faster troubleshooting of error logs, and the ability to quickly synthesize vast amounts of research.
* **Risks:** Generation of "hallucinations" (confident but false information), potential for introducing insecure code patterns, and the risk of leaking sensitive internal data to public models.

### 3. What NEVER to enter into AI Tools
* **Confidential Source Code:** Proprietary logic or internal Focus Bear codebases.
* **Authentication Details:** API keys, passwords, or `.env` file contents.
* **Personal Identifiable Information (PII):** User emails, names, or private internal discussions.
* **Internal Credentials:** GitHub tokens or server access details.

### 4. Fact-Checking & Validation
* **Cross-Reference:** Always verify technical advice against official documentation (e.g., GitHub Docs or Apple Developer docs).
* **Manual Testing:** Never commit AI-generated code without running it in a local, isolated environment first.
* **Logic Review:** Critically read through AI explanations to ensure the logic aligns with established cybersecurity principles.

---

## 📝 Reflection

### When to use AI vs. Own Skills
I use AI as a "thought partner" for brainstorming, structuring documents, or explaining unfamiliar error messages. However, I rely on my own skills for final decision-making, security audits, and writing core logic where precision and security are paramount.

### Avoiding Over-Reliance
I avoid over-reliance by attempting to solve a problem manually first. I use AI to help me understand *why* a solution works rather than just asking for the solution itself. This ensures I am still building my own expertise as a cybersecurity student.

### Ensuring Data Privacy
I will treat AI prompts as public forums. I will strip all specific identifiers—such as company names, specific IP addresses, or internal repo names—before asking for assistance with a general technical problem.

---

## 🛠️ Task Completion

* **Improved Task:** I used AI to help structure the comparative research for the `competitive_landscape.md` assignment.
* **Critical Review:** While the AI provided a good structure, I had to manually edit the content to ensure it accurately reflected the specific "Grizzly vs. Cuddly" modes and recent 2025/2026 updates of the Focus Bear app.
* **New Best Practice:** **"Anonymize before you prompt."** I will never paste a real error log containing internal paths or tokens into an AI; I will replace them with generic placeholders (e.g., `[INTERNAL_PATH]`) first.
