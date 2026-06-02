# Sahil Pavaskar

### Security Engineer | AppSec, Cloud Security, LLM Security, Web Security

I build security tooling and cloud systems that help engineering teams find risk earlier, fix it faster, and ship with confidence.

My work sits at the intersection of secure software engineering, application security, cloud identity, and AI-assisted code review. I have 2+ years of security engineering experience across threat modeling, security design reviews, SAST tuning, vulnerability discovery, IAM hardening, and Python/Go automation in AWS-heavy environments.

More recently I have been working on LLM security: indirect prompt injection, RAG poisoning, and measuring the gap between what a guardrail claims to stop and what it actually stops. The output is open-source tooling that reports attack success rate as a number, not a vibe.

<p>
  <a href="https://github.com/SahilPavaskar"><img src="https://img.shields.io/badge/GitHub-SahilPavaskar-181717?style=flat-square&logo=github" alt="GitHub" /></a>
  <a href="https://www.linkedin.com/in/sahil-pavaskar-325b851b0"><img src="https://img.shields.io/badge/LinkedIn-Sahil%20Pavaskar-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn" /></a>
  <a href="https://sahilpavaskar.github.io/portfolio/"><img src="https://img.shields.io/badge/Portfolio-Live-111827?style=flat-square&logo=vercel" alt="Portfolio" /></a>
  <a href="mailto:sahilpavaskar81@gmail.com"><img src="https://img.shields.io/badge/Email-sahilpavaskar81%40gmail.com-BB001B?style=flat-square&logo=gmail" alt="Email" /></a>
</p>

---

## What I Build

- **LLM and AI security tooling** - red-team harnesses for indirect prompt injection and RAG poisoning, retrieval-time defenses, ASR scoring, and cross-checks against tools like NVIDIA garak and promptfoo.
- **AI-assisted secure code review** - tooling that combines static analysis with LLM review to surface actionable security findings, CWE context, and remediation guidance inside developer workflows.
- **Cloud-native security automation** - AWS IAM, GuardDuty, Lambda, VPC, Terraform, and GitHub Actions pipelines for secure deployment, policy enforcement, and least-privilege operations.
- **Web and application security systems** - threat models, design reviews, auth testing, injection/SSRF analysis, dependency risk checks, and secure SDLC automation.
- **Identity and access security** - IAM policy review, OAuth 2.0/SAML/OIDC flows, SSO patterns, RBAC, secrets exposure checks, and cloud attack-path thinking.

---

## Featured Security Work

| Project | What it demonstrates | Stack |
| --- | --- | --- |
| [wormwood](https://github.com/SahilPavaskar/wormwood) | Red-team harness for indirect prompt injection and RAG poisoning. Runs a scenario-by-carrier attack matrix through a working RAG pipeline, scores each attempt with a deterministic regex judge, and reports ASR before and after a retrieval-time defense (40% to 7% on gpt-4o-mini). Findings cross-checked with NVIDIA garak and packaged as a portable promptfoo suite. Maps to OWASP LLM01, LLM08, and MITRE ATLAS AML.T0051. | Python, Chroma, OpenAI API, NVIDIA garak, promptfoo |
| [aws-guardduty-ir-lab](https://github.com/SahilPavaskar/aws-guardduty-ir-lab) | Hands-on AWS security lab where GuardDuty findings trigger EventBridge, Lambda response logic, SNS alerting, and optional EC2 containment with least-privilege IAM. | AWS GuardDuty, EventBridge, Lambda, SNS, EC2, IAM, Terraform, Python |
| [cloud-identity-attack-path-analyzer](https://github.com/SahilPavaskar/cloud-identity-attack-path-analyzer) | In-progress security project focused on modeling cloud identity relationships, risky permissions, and privilege paths before they become exploitable. | Python, AWS IAM, graph analysis |
| [Task-API-AWS](https://github.com/SahilPavaskar/Task-API-AWS) | Serverless backend showing AWS application engineering fundamentals: API Gateway routes, Lambda handlers, DynamoDB persistence, and SAM/CloudFormation deployment. | Python, AWS SAM, API Gateway, Lambda, DynamoDB |
| [portfolio](https://sahilpavaskar.github.io/portfolio/) | Professional portfolio site for security engineering work, projects, certifications, and technical background. | React, Vite, TypeScript, Tailwind CSS |

---

## Security Stack

| Domain | Tools and technologies |
| --- | --- |
| AppSec and Web Security | Threat modeling, security design reviews, Burp Suite, SAST/DAST, Semgrep, Bandit, secure code review, vulnerability research |
| Cloud Security | AWS IAM, GuardDuty, Lambda, VPC, CloudWatch, SNS, Terraform, Docker, Kubernetes, GitHub Actions |
| LLM and AI Security | Indirect prompt injection, RAG poisoning, retrieval-time guardrails, ASR scoring, NVIDIA garak, promptfoo, OWASP LLM Top 10, MITRE ATLAS, OpenAI and Gemini APIs, Chroma |
| AI for Security Automation | LLM-assisted review workflows, Python security tooling, GitHub Actions CI/CD, finding triage automation |
| Software Engineering | Python, Go, Java, C/C++, TypeScript, JavaScript, Bash, FastAPI, Node.js, REST APIs |
| Protocols and Identity | OAuth 2.0, SAML, OIDC, TLS/SSL, DNS, HTTP/S, RBAC, least privilege |

---

## Credentials

- MS in Computer Science, California State University East Bay - Expected May 2026
- AWS Certified Solutions Architect - Associate - April 2026
- CompTIA Security+ - February 2025
- OSCP+ - Expected June 2026

---

## Current Focus

I am currently focused on LLM security alongside ongoing work in secure cloud architecture and AppSec automation. On the LLM side that means measuring how often a poisoned document can hijack a retrieval-augmented chatbot, how much a real defense moves the number, and which carrier ends up surviving the filter. On the cloud and AppSec side the goal is the same: catch real vulnerabilities without flooding engineers with noise.
