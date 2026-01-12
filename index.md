---
layout: page
title: 📚 程式課程學習中心
---

<style>
    /* 全域字體優化 */
    :root {
        --text-primary: #1d1d1f;
        --text-secondary: #86868b;
        --accent: #0071e3;
        --card-bg: #ffffff;
        --border-light: #f5f5f7;
    }

    .main-container {
        font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        max-width: 900px;
        margin: 0 auto;
        color: var(--text-primary);
    }

    .header-area {
        text-align: left;
        padding: 60px 0 40px 0;
    }

    .header-area h1 {
        font-size: 2.5rem;
        font-weight: 700;
        letter-spacing: -0.02em;
        border: none;
        margin-bottom: 10px;
    }

    .header-area p {
        color: var(--text-secondary);
        font-size: 1.2rem;
    }

    /* 卡片區域排版 */
    .card-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
        gap: 20px;
        margin-bottom: 60px;
    }

    .course-card {
        background: var(--card-bg);
        border: 1px solid #ebebeb;
        border-radius: 18px;
        padding: 32px;
        text-decoration: none !important;
        transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    .course-card:hover {
        border-color: transparent;
        box-shadow: 0 20px 40px rgba(0,0,0,0.06);
        transform: translateY(-4px);
    }

    .course-card h2 {
        font-size: 1.4rem;
        font-weight: 600;
        margin: 0 0 12px 0;
        color: var(--text-primary);
        display: flex;
        align-items: center;
        gap: 10px;
    }

    .course-card p {
        font-size: 0.95rem;
        line-height: 1.5;
        color: var(--text-secondary);
        margin-bottom: 24px;
    }

    .learn-more {
        font-size: 0.95rem;
        font-weight: 500;
        color: var(--accent);
        display: flex;
        align-items: center;
    }

    .learn-more::after {
        content: " 〉";
        font-size: 0.8rem;
        margin-left: 5px;
        transition: transform 0.2s;
    }

    .course-card:hover .learn-more::after {
        transform: translateX(3px);
    }

    /* 更新日誌 - 輕量化設計 */
    .log-section {
        border-top: 1px solid var(--border-light);
        padding-top: 40px;
    }

    .log-section h3 {
        font-size: 1.1rem;
        font-weight: 600;
        margin-bottom: 20px;
    }

    .log-item {
        display: flex;
        gap: 20px;
        margin-bottom: 12px;
        font-size: 0.9rem;
    }

    .log-date {
        color: var(--text-secondary);
        font-family: monospace;
        min-width: 85px;
    }
</style>

<div class="main-container">
    <header class="header-area">
        <h1>程式課程學習中心</h1>
        <p>探索科學計算與人工智慧的實務應用</p>
    </header>

<div class="card-grid">
        <a href="./matlab/ch01" class="course-card">
            <div>
                <h2><span>📊</span> MATLAB</h2>
                <p>掌握矩陣運算核心，解決複雜的科學計算與數據可視化難題。</p>
            </div>
            <div class="learn-more">開始學習</div>
        </a>

<a href="./ai/ch01" class="course-card">
            <div>
                <h2><span>🤖</span> AI 課程</h2>
                <p>從基礎統計到深度學習，一步步建構屬於你的神經網路模型。</p>
            </div>
            <div class="learn-more">開始學習</div>
        </a>

<a href="./more/ch01" class="course-card">
            <div>
                <h2><span>🚀</span> 多元選修</h2>
                <p>跨領域結合 AI 機器人實作，將程式碼轉化為現實世界的動力。</p>
            </div>
            <div class="learn-more">開始學習</div>
        </a>
    </div>

<section class="log-section">
        <h3>最新更新紀錄</h3>
        <div class="log-item">
            <span class="log-date">2026.01.12</span>
            <span class="log-content">視覺介面全面翻新，優化閱讀體驗。</span>
        </div>
        <div class="log-item">
            <span class="log-date">2025.12.28</span>
            <span class="log-content">新增 AI 課程：神經網路架構解析。</span>
        </div>
    </section>
</div>
