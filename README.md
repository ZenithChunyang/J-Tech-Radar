# J-Tech Radar: Bridge the Gap between CN/EN and JP IT Stack 🇯🇵💻

[English] | [日本語] | [中文]

## 🚀 Overview
**J-Tech Radar** is an open-source tool designed for developers aiming to work in the Japanese IT industry. It focuses on the linguistic nuances of the Japanese tech ecosystem, specifically targeting the conversion of English/Chinese technical concepts into **Katakana-based IT terminology** and **Keigo-based development workflows**.

This project helps bridge the gap between global technical standards and local Japanese implementation practices.

## 🛠 Tech Stack
- **Core:** Java 17+ / Spring Boot 3.4
- **Persistence:** MySQL 8.0 / Redis (for terminology caching)
- **AI/LLM:** Spring AI + DeepSeek-V3 (Simulating Japanese Code Review)
- **Architecture:** Domain-Driven Design (Simplified)

## 🔥 Core Modules (Hardcore Features)
- **Technical Katakana Engine:** Mapping global terms (e.g., *Microservices*) to JP localized terms (*マイクロサービス*) with contextual code snippets.
- **Agentic Code Reviewer:** A simulated "Japanese Senior Engineer" bot that reviews your PRs using standard Japanese development etiquette and technical honorifics.
- **Development Lifecycle Glossary:** Focuses on terms used in **Requirement Definition (要件定義)**, **Design (設計)**, and **Testing (テスト)** phases in Japan.

## 📂 Database Schema (Snapshot)
The system tracks technical terms across three dimensions:
- `global_term`: Standard English/Industry term.
- `jp_katakana`: How Japanese developers say/write it.
- `jp_business_context`: Usage in Japanese development meetings.

## 📈 Roadmap
- [x] Initial Spring Boot 3 Scaffolding
- [ ] Integration with JP Tech News Aggregator (Qiita/Zenn API)
- [ ] AI-powered Business Email Generator for Dev Teams

---
**Vision:** Empowering global engineers to seamlessly integrate into Japan's Digital Transformation (DX) wave.
**Author:** [ZenithChunyang] | **University:** [Beijing Information and Science Technology University]
