---
title: "ブログ自動投稿エージェントを作った話：Claude API＋Supabase＋GitHub Actionsで実現した仕組み"
emoji: "📝"
type: "tech"
topics: ["claudeapi", "supabase", "githubactions", "python", "nextjs"]
published: true
---

Next.js製ブログの記事作成〜公開を全自動化するエージェントシステムの設計と実装を公開。テーマキューはSupabase（PostgreSQL）で管理し、GitHub Actionsで毎朝定期実行、Claude APIで2000〜4000字のMarkdown記事を生成、GitHub Contents APIで直接コミットしてVercelが自動デプロイする仕組み。インフラコストはほぼゼロで、「書く」行為を「テーマを登録する」だけに置き換えた。

---
元記事: https://chiapuru.com/blog/auto-post-agent