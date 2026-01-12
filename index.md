---
layout: page
title: 📚 程式課程學習中心
---

<style>
    /* 強制覆蓋主題背景 */
    body, .main-wrapper-dark {
        background-color: #050505 !important;
        color: #e0e0e0 !important;
    }

    .main-wrapper-dark {
        padding: 60px 20px;
        font-family: -apple-system, system-ui, sans-serif;
        min-height: 100vh;
    }

    .container-inner {
        max-width: 1000px;
        margin: 0 auto;
    }

    .header-area {
        text-align: center;
        margin-bottom: 60px;
    }

    .header-area h1 {
        font-size: 3rem;
        font-weight: 800;
        color: #ffffff !important;
        margin-bottom: 15px;
        border: none !important;
        letter-spacing: -1px;
    }

    .header-area p {
        color: #888;
        font-size: 1.2rem;
    }

    /* 卡片設計：深色磨砂質感 */
    .card-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 30px;
    }

    .dark-card {
        background: #111111;
        border: 1px solid #222;
        border-radius: 24px;
        padding: 40px;
        text-decoration: none !important;
        transition: all 0.3s ease;
        display: flex;
        flex-direction: column;
    }

    .dark-card:hover {
        background: #161616;
        border-color: #444;
        transform: translateY(-10px);
        box-shadow: 0 20px 40px rgba(0,0,0,0.6);
    }

    .dark-card h2 {
        font-size: 1.6rem;
        color: #ffffff !important;
        margin: 0 0 15px 0;
        border: none !important;
    }

    .dark-card p {
        color: #999;
        font-size: 1rem;
        line-height: 1.6;
        margin-bottom: 30px;
        flex-grow: 1;
    }

    /* 動作按鈕 */
    .go-btn {
        color: #ffffff !important;
        font-weight: 600;
        display: flex;
        align-items: center;
        gap: 8px;
    }

    .go-btn::after {
        content: '→';
        transition: transform 0.3s;
    }

    .dark-card:hover .go-btn::after {
        transform: translateX(8px);
    }

    /* 針對不同課程的發光效果 */
    .dark-card:hover h2 {
        text-shadow: 0 0 15px rgba(255,255,255,0.2);
    }

    /* 更新日誌 */
    .update-section {
        margin-top: 80px;
        padding-top: 40px;
        border-top: 1px solid #222;
    }

    .update-section h3 {
        color: #fff !important;
        font-size: 1.2rem;
        margin-bottom: 20px;
    }

    .update-item {
        margin-bottom: 12px;
        color: #666;
        font-size: 0.95rem;
    }

    .update-date {
        color: #444;
        margin-right: 15px;
        font-family: monospace;
    }
</style>

<div class="main-wrapper-dark">
    <div class="container-inner">
        <header class="header-area">
            <h1>程式課程學習中心</h1>
            <p>2026 年度 MATLAB 與 AI 核心技術講義</p>
        </header>

<div class="card-grid">
            <a href="./matlab/ch01" class="dark-card">
                <h2>📊 MATLAB</h2>
                <p>從矩陣運算到專業繪圖，建構科學計算的堅實基礎。</p>
                <div class="go-btn">Start Learning</div>
            </a>

<a href="./ai/ch01" class="dark-card">
                <h2>🤖 AI 課程</h2>
                <p>深度學習導論：從零開始實作你的第一個神經網路。</p>
                <div class="go-btn">Start Learning</div>
            </a>

<a href="./more/ch01" class="dark-card">
                <h2>🚀 多元選修</h2>
                <p>結合 AI 機器人與自動化控制，實踐跨領域的創新應用。</p>
                <div class="go-btn">Start Learning</div>
            </a>
        </div>

 <div class="update-section">
            <h3>最近更新</h3>
            <div class="update-item">
                <span class="update-date">2026.01.12</span>
                <span>介面切換至深色沉浸式版本。</span>
            </div>
            <div class="update-item">
                <span class="update-date">2025.12.28</span>
                <span>新增 AI 課程：Transformer 架構解析。</span>
            </div>
        </div>
    </div>
</div>
