# -<style>
    /* 1. 基礎重設與背景設定 */
    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
        font-family: 'Helvetica Neue', Arial, sans-serif;
    }

    body {
        /* 漸層背景，可自由更換顏色 */
        background: linear-gradient(135deg, #0f172a 0%, #1e1b4b 100%);
        color: #ffffff;
        display: flex;
        justify-content: center;
        align-items: flex-start;
        min-height: 100vh;
        padding: 40px 20px;
    }

    /* 2. 主容器佈局 */
    .container {
        width: 100%;
        max-width: 580px;
        text-align: center;
    }

    /* 3. 個人資訊區塊 */
    .profile {
        margin-bottom: 32px;
    }

    .avatar {
        width: 96px;
        height: 96px;
        border-radius: 50%;
        object-fit: cover;
        border: 3px solid rgba(255, 255, 255, 0.2);
        margin-bottom: 16px;
        box-shadow: 0 8px 24px rgba(0, 0, 0, 0.2);
    }

    .name {
        font-size: 1.25rem;
        font-weight: 700;
        margin-bottom: 8px;
        letter-spacing: 0.5px;
    }

    .bio {
        font-size: 0.9rem;
        color: #94a3b8;
        line-height: 1.5;
        max-width: 80%;
        margin: 0 auto;
    }

    /* 4. 連結列表區塊 */
    .links-wrapper {
        display: flex;
        flex-direction: column;
        gap: 16px; /* 按鈕之間的間距 */
        margin-bottom: 40px;
    }

    /* 5. 核心按鈕樣式 */
    .link-card {
        display: flex;
        align-items: center;
        justify-content: center;
        position: relative;
        padding: 16px 24px;
        background: rgba(255, 255, 255, 0.08);
        border: 1px solid rgba(255, 255, 255, 0.1);
        border-radius: 12px;
        color: #ffffff;
        text-decoration: none;
        font-weight: 500;
        transition: all 0.25s ease;
        box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }

    /* 讓 Icon 靠左固定，文字維持居中 */
    .link-card i {
        position: absolute;
        left: 24px;
        font-size: 1.25rem;
    }

    /* 滑鼠懸停與點擊效果 */
    .link-card:hover {
        background: rgba(255, 255, 255, 0.16);
        transform: translateY(-2px);
        border-color: rgba(255, 255, 255, 0.25);
        box-shadow: 0 6px 20px rgba(0, 0, 0, 0.15);
    }

    .link-card:active {
        transform: translateY(0);
    }

    /* 6. 頁尾標籤 */
    footer {
        font-size: 0.8rem;
        color: #64748b;
    }

    footer a {
        color: #94a3b8;
        text-decoration: none;
    }
    
    footer a:hover {
        text-decoration: underline;
    }
</style>
