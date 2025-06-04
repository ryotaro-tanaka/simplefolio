```md
✅ 優先度高 – すぐに取り組むべきこと
1. GitHubのREADME拡充（技術力・成果の言語化）
  * 「どんな課題をどう解決したか」「設計上の工夫点」など、技術的ハイライトを具体的に追加
  * 英語圏の採用担当者がパッと見て「これは実務に近い」と思える表現へ
2. 英語レジュメのアップデート
  * JobHuntXの開発経験を主軸に職歴・スキルを整理
  * 英語で成果を伝える文言（STAR法など）を活用
3. 技術説明資料 or ポートフォリオスライド作成（英語）
  * JobHuntXの「目的・技術選定・アーキテクチャ・課題解決・成果」をまとめる
  * 面接・ビザ申請時の技術資料にも流用可能
```

# このポートフォリオスライドの目的（端的な説明）

このスライドの目的は、Ryotaro TanakaさんがオーストラリアでWebアプリケーション開発職に応募する際に、自身の技術力・実績・就労意欲を簡潔かつ視覚的に伝えることです。
JobHuntXという実プロジェクトを軸に、「課題解決力・技術選定・設計力・開発実行力」をアピールし、履歴書だけでは伝わりにくいスキルと成果をより魅力的に表現するための補足資料です。

# スライド構成と内容の説明

## 📘 1. Title Slide
**Ryotaro Tanaka**  
Web Application Developer  
Seeking opportunities in Australia (PR pathway welcomed)  
🌐 https://jobhuntx.onrender.com  
💻 https://github.com/ryotaro-tanaka  
📧 ryotaro_tanaka@outlook.com  

---

## 💡 2. About Me
- 6+ years experience in web application development
- Skilled in ASP.NET Core (C#), React, TypeScript
- Currently on a Working Holiday Visa (valid until Mar 2026)
- Seeking long-term opportunities toward PR (e.g., subclass 190, 491)
- Open to relocation anywhere in Australia

---

## Current Project: JobHuntX

### Overview
A job aggregation web application built to showcase production-ready full-stack skills.  
🔧 Tech Stack: ASP.NET Core, React, TypeScript, Docker  
🎯 Goal: Demonstrate ability to build scalable, testable, and maintainable systems  

👉 [See Live](https://jobhuntx.onrender.com) | [Source Code](https://github.com/ryotaro-tanaka/jobhuntx)

---

### Why I built JobHuntX
- I wanted to solve my own problem and build a tool tailored for real use  
- At the same time, I used this opportunity to demonstrate my development skills  

---

### System Architecture
- Backend: ASP.NET Core Web API (C#)  
- Frontend: React + TypeScript  
- Data Sources: RSS, Public APIs, Web scraping  
📈 [View Architecture Diagram](assets/diagram-backend.png)

---

### Key Features
- Unified handler pattern for job sources (abstract handler + concrete handlers)  
- Caching optimization using IMemoryCache  
- Centralized error handling and logging  
- Type-safe frontend API with NSwag  
- Automated testing for frontend and backend  
- CI support using GitHub Actions  
- CD support using Docker and Render  
- Unified development environment using Docker  

---

### Results & Learnings
- The current features are still insufficient for fully solving my own challenge of "job hunting to obtain PR in Australia"  
- Architectural planning during the design phase led to improved performance and maintainability  
- I was able to showcase my full-stack development skills  
