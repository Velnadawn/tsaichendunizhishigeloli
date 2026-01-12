---
layout: page
title: 📚 程式課程學習中心
---

<style>
    :root {
        --matlab-color: #ed6c02;
        --ai-color: #0288d1;
        --more-color: #2e7d32;
        --bg-white: #ffffff;
        --text-main: #2c3e50;
        --text-sub: #7f8c8d;
    }

    .hero-section {
        text-align: center;
        padding: 40px 0;
        background: linear-gradient(to bottom, #f8f9fa, #ffffff);
        border-radius: 20px;
        margin-bottom: 30px;
    }

    .card-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        gap: 25px;
        padding: 10px;
    }

    .card {
        background: var(--bg-white);
        border: 1px solid #f0f0f0;
        border-radius: 16px;
        padding: 30px 24px;
        text-decoration: none !important;
        transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
        display: flex;
        flex-direction: column;
        align-items: center;
        box-shadow: 0 4px 6px rgba(0,0,0,0.02);
    }

    .card:hover {
        transform: translateY(-8px);
        box-shadow: 0 15px 30px rgba(0,0,0,0.08);
        border-color: #e0e0e0;
    }

    /* 圖示與標題樣式 */
    .card-icon {
        font-size: 3rem;
        margin-bottom: 15px;
    }

    .card h2 {
        margin: 10px 0;
        font-size: 1.5rem;
        font-weight: 700;
        color: var(--text-main);
    }

    .card p {
        font-size: 0.95rem;
        color: var(--text-sub);
        line-height: 1.6;
        text-align: center;
        margin-bottom: 20px;
        min-height: 3em;
    }

    /* 自定義按鈕 */
    .btn-start {
        width: 100%;
        padding: 10px;
        border-radius: 8px;
        font-weight: 600;
        text-align: center;
        transition: 0.2s;
    }

    /* 各別卡片的主題色 */
    .card-matlab .btn-start { border: 1.5px solid var(--matlab-color); color: var(--matlab-color) !important; }
    .card-matlab:hover .btn-start { background: var(--matlab-color); color: white !important; }

    .card-ai .btn-start { border: 1.5px solid var(--ai-color); color: var(--ai-color) !important; }
    .card-ai:hover .btn-start { background: var(--ai-color); color: white !important; }

    .card-more .btn-start { border: 1.5px solid var(--more-color); color: var(--more-color) !important; }
    .card-more:hover .btn-start { background: var(--more-color); color: white !important; }

    /* 更新日誌樣式 */
    .update-log {
        margin-top: 50px;
        padding: 20px;
        background-color: #fcfcfc;
        border-left: 4px solid #eee;
        border-radius: 4px;
    }
</style>

<div class="hero-section">
    <h1 style="border:none; margin-bottom:10px;">歡迎來到我的線上講義</h1>
    <p style="color:#7f8c8d; font-size:1.1rem;">專為 **MATLAB** 與 **AI** 學習者設計的免費資源平台</p>
</div>

<div class="card-container">
    <a href="./matlab/ch01" class="card card-matlab">
        <div class="card-icon">📊</div>
        <h2>MATLAB</h2>
        <p>矩陣運算、數據繪圖與<br>科學計算基礎課程</p>
        <span class="btn-start">開始學習</span>
    </a>

    <a href="./ai/ch01" class="card card-ai">
        <div class="card-icon">🤖</div>
        <h2>AI 課程</h2>
        <p>機器學習導論與<br>神經網路實作教學</p>
        <span class="btn-start">開始學習</span>
    </a>

    <a href="./more/ch01" class="card card-more">
        <div class="card-icon">🚀</div>
        <h2>多元選修</h2>
        <p>探索 AI 機器人與<br>更多跨領域應用</p>
        <span class="btn-start">開始學習</span>
    </a>
</div>

<div class="update-log">
    <h3 style="margin-top:0;">📢 最新更新</h3>
    <ul style="list-style: none; padding-left: 0; font-size: 0.95rem;">
        <li><code style="color:#e91e63;">2026-01-12</code> 🎨 升級全新現代感白底介面與 UI 優化</li>
        <li><code style="color:#e91e63;">2025-12-28</code> 🧠 新增 AI 課程第二章「神經網路」</li>
        <li><code style="color:#e91e63;">2025-12-28</code> 🔗 修正 MATLAB 側邊欄導覽連結</li>
    </ul>
</div>
