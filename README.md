# 🛡️ AI Red Teaming & LLM Security Roadmap

This repository is a structured, community-driven roadmap for transitioning from traditional AppSec to **AI/LLM Red Teaming**. It follows the foundational principles of `roadmap.sh` and integrates industry-standard frameworks.

## 🚀 The Path to Mastery

### 🟦 Level 1: Foundational Knowledge

*Before you can break it, you must understand how it's built.*

* [ ] **AI/ML Fundamentals**
* [Learn Prompting (Fundamental Course)](https://learnprompting.org)
* [ ] Supervised vs. Unsupervised vs. Reinforcement Learning
* [ ] Neural Networks & Transformer Architectures (BERT, GPT)
* [ ] Generative Models & LLMs


* [ ] **Cybersecurity Principles (AI Context)**
* [ ] The CIA Triad in non-deterministic systems
* [ ] AI Threat Modeling & Risk Management
* [ ] Vulnerability Assessment vs. Red Teaming



---

### 🟨 Level 2: Prompt Hacking & Model Vulnerabilities

*The core of LLM-specific exploitation.*

* [ ] **Prompt Hacking Techniques**
* [ ] **Direct Prompt Injection:** Overriding system instructions
* [ ] **Indirect Prompt Injection:** Attacking via RAG or web search results
* [ ] **Jailbreaking:** Persona adoption, encoding bypasses, and safety filter evasion


* [ ] **Model-Level Attacks**
* [ ] **Data Poisoning:** Manipulating training/fine-tuning datasets
* [ ] **Model Extraction:** Stealing weights or logic via API
* [ ] **Privacy Attacks:** Model Inversion & Membership Inference



---

### 🟧 Level 3: System & Infrastructure Security

*AI does not live in a vacuum; it lives in your stack.*

* [ ] **Code & Infrastructure**
* [ ] **Insecure Deserialization** in model pickles
* [ ] **Remote Code Execution (RCE)** via sandboxed environments
* [ ] **API Protection:** AuthN/AuthZ for AI gateways


* [ ] **Agentic AI Security**
* [ ] Goal Hijacking in autonomous agents
* [ ] Tool Misuse & Privilege Escalation



---

### 🟥 Level 4: Practical Experience & Methodology

*Hands-on application and professional standards.*

* [ ] **Testing Methodologies**
* [ ] Black Box, White Box, and Grey Box testing for AI
* [ ] Automated vs. Manual Red Teaming


* [ ] **The Toolbelt**
* [ ] **Testing Platforms:** [Garak](https://github.com/leondz/garak), [PyRIT](https://www.google.com/search?q=https://github.com/Azure/pyrit)
* [ ] **Benchmark Datasets:** [Hugging Face Leaderboards]()


* [ ] **Hands-on Labs**
* [ ] [HackAPrompt CTF]()
* [ ] [TensorTrust]() (Interactive Prompt Injection Lab)



---

### 🟩 Level 5: Professional Development & Defense

*Hardening systems and staying ahead of the curve.*

* [ ] **Defense Strategies**
* [ ] Adversarial Training & Robust Model Design
* [ ] Continuous Monitoring & Output Filtering


* [ ] **Industry Standards**
* [ ] [OWASP Top 10 for LLMs]()
* [ ] [MITRE ATLAS Framework]()


* [ ] **Credentials & Community**
* [ ] **Conferences:** DEF CON AI Village
* [ ] **Courses:** SANS AI Security tracks



---

## 🛠️ Contribution

This roadmap is always evolving. If you find a new vulnerability class or a better tool, please open a PR!

---

### Why this works as a "Source of Truth":

1. **Iterative Learning:** The checkboxes give users a psychological sense of progress.
2. **Verified Resources:** By linking to established entities like **OWASP**, **MITRE**, and **Learn Prompting**, you gain immediate credibility.
3. **Modern Scope:** It includes **Agentic AI Security**, which is the most sought-after skill in 2026.
