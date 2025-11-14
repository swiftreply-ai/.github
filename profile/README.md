<!-- Banner / Logo (Optional) -->
<!--
<div align="center" width="100%">
  <img src="https://github.com/swiftreply-ai/.github/blob/a0bc865e866c7ee4d7629952cf7e780843ed3788/logo_banner.png" />
</div>
-->


<h1 align="center">🔥 SwiftReply AI</h1>

<p align="center">
  <strong>AI-powered, context-aware reply generation for email, chat, customer support & workflow automation.</strong>
</p>

<p align="center">
  <a href="https://github.com/swiftreply-ai/swiftreply-ai-sdk">SDK</a> •
  <a href="https://github.com/swiftreply-ai/swiftreply-ai-docs">Docs</a> •
  <a href="https://github.com/swiftreply-ai/swiftreply-ai-examples">Examples</a> •
  <a href="https://github.com/swiftreply-ai/swiftreply-ai-website">Website</a> •
  <a href="https://github.com/swiftreply-ai/swiftreply-ai-showcase">Showcase</a>
</p>

<p align="center">
  <a href="https://github.com/swiftreply-ai"><img src="https://img.shields.io/badge/org-SwiftReply%20AI-black?style=for-the-badge&logo=github"></a>
  <a href="https://www.linkedin.com/in/tapasmahanta"><img src="https://img.shields.io/badge/Founder-Tapas%20Mahanta-blue?style=for-the-badge&logo=linkedin"></a>
</p>

---

## ⚡ What is SwiftReply AI?

SwiftReply AI helps individuals and businesses craft intelligent, personalized, and highly contextual replies across multiple communication channels.

### Built for:
- ✉️ **Emails**  
- 💬 **Messaging & chat**  
- 🎧 **Customer support agents**  
- 🧾 **Team communication**  
- 🔄 **Automated workflows**  

Its core engine is optimized for:
- ⚡ Speed  
- 🎯 Accuracy  
- 🧠 Context awareness  
- 🧩 Easy developer integration  

---

## 🌐 Public Repositories

A clean separation between **public developer tools** and **internal infrastructure**.

### 🟦 Developer-Facing Repos (Public)

| Repository | Description |
|-----------|-------------|
| 🔌 **[swiftreply-ai-sdk](https://github.com/swiftreply-ai/swiftreply-ai-sdk)** | Official TypeScript SDK for SwiftReply AI |
| 📘 **[swiftreply-ai-docs](https://github.com/swiftreply-ai/swiftreply-ai-docs)** | API docs, guides, onboarding & architecture |
| 🧪 **[swiftreply-ai-examples](https://github.com/swiftreply-ai/swiftreply-ai-examples)** | Ready-to-run demos & integrations |
| 🌐 **[swiftreply-ai-website](https://github.com/swiftreply-ai/swiftreply-ai-website)** | Public marketing & landing website |
| 🖼️ **[swiftreply-ai-showcase](https://github.com/swiftreply-ai/swiftreply-ai-showcase)** | Product screenshots, demo videos, workflows |
| 🛠 **[swiftreply-ai-cli](https://github.com/swiftreply-ai/swiftreply-ai-cli)** | CLI for interacting with SwiftReply AI |

---

## 🔒 Internal Repositories (Private)

| Repository | Description |
|-----------|-------------|
| ⚙️ **swiftreply-ai-core** | Core backend engine, API gateway, orchestration |
| 🧬 **swiftreply-ai-models** | Training pipelines, inference & evaluation |
| ☁️ **swiftreply-ai-infra** | IaC, Kubernetes, CI/CD, secrets, monitoring |
| 🖥 **swiftreply-ai-ui** | Internal admin dashboard & platform UI |

---

## 🧪 Quick Demo (SDK)

```ts
import SwiftReply from "@swiftreply-ai/sdk";

const client = new SwiftReply({
  apiKey: process.env.SR_API_KEY,
});

const reply = await client.reply({
  prompt: "Follow up politely about the pending document.",
});

console.log(reply.output);
```
## 🔗 More examples:
[https://github.com/swiftreply-ai/swiftreply-ai-examples](https://github.com/swiftreply-ai/swiftreply-ai-examples)

## 🎥 Product Showcase:
Screenshots, demo video, API samples, workflows & architecture:

[➡️ https://github.com/swiftreply-ai/swiftreply-ai-showcase](https://github.com/swiftreply-ai/swiftreply-ai-showcase)

## 🛣️ Roadmap Highlights

- 🧠 Context Memory Engine
- 🔌 Gmail / Outlook Integrations
- 🤝 Customer Support Integrations (Zendesk, Intercom, Freshdesk)
- 🛠 Workflow Builder (UI)
- 📈 Usage Analytics
- 🛡️ Enterprise Suite (SAML, RBAC, Audit Logs)

Full roadmap will be made public soon.

## 🤝 Contributing

We welcome contributions to:

- SDK
- Docs
- Examples
- CLI

Open PRs are reviewed quickly and we maintain high-quality engineering standards.


## 👤 Maintainer & Founder
### 👨‍💻 Tapas Mahanta
Founder & Lead Engineer
