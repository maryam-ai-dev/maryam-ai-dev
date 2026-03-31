<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=32&duration=3000&pause=1000&color=C9608A&center=true&vCenter=true&width=500&height=70&lines=hi%2C+i'm+maryam+%F0%9F%91%8B;AI+engineer+%2B+builder.)](https://git.io/typing-svg)

**AI-focused software engineer** building at the intersection of NLP, identity, and real-world applications.

📍 London, UK &nbsp;·&nbsp; 🎓 Greenwich CS → KCL MSc AI, Sept 2026 &nbsp;·&nbsp; 💼 Open to AI / fullstack roles

</div>

---

### 🚀 Featured Projects

**🧠 Traced — AI Medical Learning Simulator**
AI-powered clinical reasoning system using RAG over biomedical literature. Hybrid retrieval (BM25 + dense embeddings), structured case extraction with Pydantic, and a rule-based disease progression simulation engine that models symptom evolution over time.

`rag` `bm25` `pydantic` `fastapi` `python`

---

**✍️ AI Writing Style Preservation** *(FYP dissertation)*
End-to-end system for preserving individual voice in AI-assisted text generation. Extracts a 47-feature stylometric vector across 7 tiers (character, surface, lexical, syntactic, psycholinguistic, character n-gram, function word bigram) and maintains a persistent per-user StyleVector updated via Exponential Moving Average. Context-aware prompt construction separates voice patterns from register - informal markers are gated behind a formality classifier using sentence fragment ratio and question mark density as discriminators. Evaluated using scale-normalised cosine similarity to prevent Yule's K domination.

`spacy` `sbert` `gpt-4o-mini` `spring-boot` `java` `postgresql` `flutter`

---

**🌍 Revert - Community Platform for Muslim Reverts**
Full-stack social platform built specifically for Muslim reverts to find community, share their journey, and connect with people who understand the experience. Backend uses FastAPI with async PostgreSQL via SQLAlchemy, JWT auth with refresh token rotation, and a journey-based compatibility scoring system for buddy matching — reusing a scoring pipeline originally built for personality-based matching in Galaxie, adapted to track spiritual milestones and shared revert experiences rather than Big Five traits. Flutter frontend with feed, DM, and onboarding flows.

`flutter` `fastapi` `postgresql` `sqlalchemy` `jwt` `dart`

---

**🔒 Galaxie - Identity-First Social Platform** *(private)*
An identity-first social platform built around the belief that you are the centre. The core is a stylometric voice fingerprinting engine: a 47-feature NLP pipeline extracts a per-user StyleVector from natural writing across chat, notebook, and post surfaces. Profiles are updated continuously using EMA without storing raw text, keeping the system GDPR-compliant by design. World-space matching uses a cosine similarity layer over StyleVectors stored in pgvector to surface users with complementary linguistic identities rather than shared interests. The reaction system is polymorphic - a single infrastructure handles reactions across messages, posts, and journal entries via a target-type discriminator column. DM infrastructure uses cursor-based pagination over an append-only message log. Backend is Domain-Driven Design with a pure Java domain layer, Spring Boot application layer, and infrastructure adapters behind port interfaces so the generation model and NLP service are swappable without touching business logic.

`nlp` `stylometry` `ema` `pgvector` `flutter` `spring-boot` `fastapi` `postgresql` `ddd`

---

### 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=c9608a)
![Java](https://img.shields.io/badge/Java-0d1117?style=for-the-badge&logo=openjdk&logoColor=c9608a)
![Dart](https://img.shields.io/badge/Dart-0d1117?style=for-the-badge&logo=dart&logoColor=c9608a)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=for-the-badge&logo=typescript&logoColor=c9608a)
![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=for-the-badge&logo=fastapi&logoColor=c9608a)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-0d1117?style=for-the-badge&logo=springboot&logoColor=c9608a)
![Flutter](https://img.shields.io/badge/Flutter-0d1117?style=for-the-badge&logo=flutter&logoColor=c9608a)
![Next.js](https://img.shields.io/badge/Next.js-0d1117?style=for-the-badge&logo=nextdotjs&logoColor=c9608a)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=c9608a)
![pgvector](https://img.shields.io/badge/pgvector-0d1117?style=for-the-badge&logo=postgresql&logoColor=c9608a)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=c9608a)
![Firebase](https://img.shields.io/badge/Firebase_Auth-0d1117?style=for-the-badge&logo=firebase&logoColor=c9608a)
![Cloudflare](https://img.shields.io/badge/Cloudflare_R2-0d1117?style=for-the-badge&logo=cloudflare&logoColor=c9608a)

---

### 📫 Contact

[maryam18yousuf@gmail.com](mailto:maryam18yousuf@gmail.com) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/maryam-yousuf)
