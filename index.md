---
layout: page
title: 📚 程式課程學習中心
---

<style>
    /* 深色主題變數 */
    :root {
        --bg-dark: #0f172a;           /* 深藍黑背景 */
        --card-bg: #1e293b;           /* 卡片深色背景 */
        --text-primary: #f8fafc;      /* 近純白文字 */
        --text-secondary: #94a3b8;    /* 灰色文字 */
        --accent-matlab: #fb923c;     /* 橘色光暈 */
        --accent-ai: #38bdf8;         /* 藍色光暈 */
        --accent-more: #4ade80;       /* 綠色光暈 */
    }

    .main-wrapper {
        background-color: var(--bg-dark);
        color: var(--text-primary);
        padding: 40px 20px;
        border-radius: 24px;
        font-family: 'Inter', system-ui, -apple-system, sans-serif;
    }

    .header-section {
        text-align: center;
        margin-bottom: 50px;
    }

    .header-section h1 {
        font-size: 2.8rem;
        font-weight: 800;
        background: linear-gradient(to right, #fff, #94a3b8);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        border: none;
    }

    /* 卡片容器 */
    .course-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        gap: 25px;
    }

    /* 卡片基礎樣式 */
    .glass-card {
        background: var(--card-bg);
        border: 1px solid rgba(255, 255, 255, 0.1);
        border-radius: 20px;
        padding: 30px;
        text-decoration: none !important;
        transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        position: relative;
        overflow: hidden;
    }

    .glass-card:hover {
        transform: scale(1.02);
        border-color: rgba(255, 255, 255, 0.2);
        box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4);
    }

    /* 頂部裝飾條 */
    .glass-card::before {
        content: "";
        position: absolute;
        top: 0; left: 0; width: 100%; height: 4px;
    }

    .card-matlab::before { background: var(--accent-matlab); }
    .card-ai::before { background: var(--accent-ai); }
    .card-more::before { background: var(--accent-more); }

    .glass-card h2 {
        color: var(--text-primary);
        font-size: 1.5rem;
        margin-bottom: 15px;
        display: flex;
        align-items: center;
        gap: 12px;
    }

    .glass-card p {
        color: var(--text-secondary);
        font-size: 0.95rem;
        line-height: 1.6;
        margin-bottom: 25px;
    }

    /* 霓虹按鈕 */
    .action-label {
        font-weight: 600;
        font-size: 0.9rem;
        display: inline-flex;
        align-items: center;
        color: var(--text-primary);
    }

    .action-label svg {
        margin-left: 8px;
        transition: transform 0.3s;
    }

    .glass-card:hover .action-label svg {
        transform: translateX(5px);
    }

    /* 更新日誌 */
    .changelog {
        margin-top: 60px;
        padding: 25px;
        background: rgba(255, 255, 255, 0.03);
        border-radius: 15px;
    }

    .changelog h3 { color: var(--text-primary); border: none; margin-bottom: 15px; }
    .log-row {
        display: flex;
        margin-bottom: 10px;
        font-size: 0.9rem;
        border-bottom: 1px solid rgba(255,255,255,0.05);
        padding-bottom: 8px;
    }
    .date-tag { color: var(--accent-ai); font-family: monospace; width: 100px; }
</style>

<div class="main-wrapper">
    <div class="header-section">
        <h1>程式課程學習中心</h1>
        <p style="color: var(--text-secondary);">探索 MATLAB 運算力與 AI 的無限可能</p>
    </div>

<div class="course-grid">
        <a href="./matlab/ch01" class="glass-card card-matlab">
            <h2>📊 MATLAB</h2>
            <p>深入淺出演算法開發，掌握科學數據處理的業界標準工具。</p>
            <div class="action-label">
                進入課程 <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"></line><polyline points="12 5 19 12 12 19"></polyline></svg>
            </div>
        </a>

<a href="./ai/ch01" class="glass-card card-ai">
            <h2>🤖 AI 課程</h2>
            <p>探索機器學習與神經網路，從理論基礎到建構自動化 AI 模型。</p>
            <div class="action-label">
                進入課程 <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"></line><polyline points="12 5 19 12 12 19"></polyline></svg>
            </div>
        </a>

<a href="./more/ch01" class="glass-card card-more">
            <h2>🚀 多元選修</h2>
            <p>結合 AI 機器人實務，打破虛擬與現實的邊界，啟發無限創意。</p>
            <div class="action-label">
                進入課程 <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"></line><polyline points="12 5 19 12 12 19"></polyline></svg>
            </div>
        </a>
    </div>

<div class="changelog">
        <h3>📢 最近更新</h3>
        <div class="log-row">
            <span class="date-tag">2026.01.12</span>
            <span>切換至 Dark Mode 賽博風格介面。</span>
        </div>
        <div class="log-row">
            <span class="date-tag">2025.12.28</span>
            <span>新增 AI 課程：深度學習與卷積神經網路實作。</span>
        </div>
    </div>
</div>
