<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>陈设计 | 品牌公关设计师作品集</title>
    <link rel="stylesheet" href="style.css">
    <!-- 引入 GSAP 及其 ScrollTrigger 插件 -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>
</head>
<body>

    <!-- 固定导航栏 -->
    <header class="navbar">
        <div class="logo">CHEN.DESIGN</div>
        <nav>
            <ul class="nav-links">
                <li><a href="#home">首页</a></li>
                <li><a href="#works">作品展示</a></li>
                <li><a href="#experience">经验背景</a></li>
                <li><a href="#contact">联系方式</a></li>
            </ul>
        </nav>
        <!-- 移动端汉堡菜单图标 -->
        <div class="menu-toggle" id="mobile-menu">
            <span></span>
            <span></span>
            <span></span>
        </div>
    </header>

    <main>
        <!-- 首屏 Hero 区 -->
        <section id="home" class="hero">
            <div class="hero-content">
                <h1 class="gsap-reveal">塑造品牌，<br>传递核心价值。</h1>
                <p class="gsap-reveal">我是独立品牌公关设计师。专注于品牌视觉升级、公关活动物料设计及全案视觉统筹。用极简的视觉语言，讲述深刻的品牌故事。</p>
                <a href="#works" class="btn gsap-reveal">查看作品</a>
            </div>
        </section>

        <!-- 作品展示区 -->
        <section id="works" class="works section-padding">
            <div class="container">
                <h2 class="section-title">精选作品 <span>Selected Works</span></h2>
                <div class="works-grid">
                    <!-- 作品卡片 1 -->
                    <a href="detail.html" class="work-card">
                        <div class="img-wrapper">
                            <!-- 使用 loading="lazy" 实现图片懒加载 -->
                            <img src="https://images.unsplash.com/photo-1600132806370-bf17e65e942f?auto=format&fit=crop&w=800&q=80" alt="TechNova 品牌升级" loading="lazy">
                        </div>
                        <div class="work-info">
                            <h3>TechNova 品牌视觉升级</h3>
                            <p>科技 / 品牌重塑 / VI系统</p>
                        </div>
                    </a>
                    <!-- 作品卡片 2 -->
                    <a href="detail.html" class="work-card">
                        <div class="img-wrapper">
                            <img src="https://images.unsplash.com/photo-1541462608143-67571c6738dd?auto=format&fit=crop&w=800&q=80" alt="Lumina 新品发布会" loading="lazy">
                        </div>
                        <div class="work-info">
                            <h3>Lumina 2023 新品发布会</h3>
                            <p>公关活动 / 空间视觉 / 物料设计</p>
                        </div>
                    </a>
                    <!-- 作品卡片 3 -->
                    <a href="detail.html" class="work-card">
                        <div class="img-wrapper">
                            <img src="https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?auto=format&fit=crop&w=800&q=80" alt="Aura 美妆年度公关礼盒" loading="lazy">
                        </div>
                        <div class="work-info">
                            <h3>Aura 美妆年度公关礼盒</h3>
                            <p>包装设计 / 创意概念</p>
                        </div>
                    </a>
                    <!-- 作品卡片 4 -->
                    <a href="detail.html" class="work-card">
                        <div class="img-wrapper">
                            <img src="https://images.unsplash.com/photo-1497366216548-37526070297c?auto=format&fit=crop&w=800&q=80" alt="Oasis 商业空间导视" loading="lazy">
                        </div>
                        <div class="work-info">
                            <h3>Oasis 商业空间导视系统</h3>
                            <p>环境图形 / 导视系统</p>
                        </div>
                    </a>
                </div>
            </div>
        </section>

        <!-- 经验背景区 (时间线) -->
        <section id="experience" class="experience section-padding">
            <div class="container">
                <h2 class="section-title">经验背景 <span>Background</span></h2>
                <div class="timeline">
                    <!-- 工作经历 1 -->
                    <div class="timeline-item">
                        <div class="timeline-dot"></div>
                        <div class="timeline-content">
                            <span class="date">2021 - 至今</span>
                            <h3>高级品牌设计师</h3>
                            <h4>Ogilvy 奥美公关</h4>
                            <p>主导多个世界500强企业的品牌公关战役视觉统筹，负责从创意概念到最终物料落地，带领3人设计小队提升创意交付质量。</p>
                        </div>
                    </div>
                    <!-- 工作经历 2 -->
                    <div class="timeline-item">
                        <div class="timeline-dot"></div>
                        <div class="timeline-content">
                            <span class="date">2018 - 2021</span>
                            <h3>视觉设计师</h3>
                            <h4>独立设计工作室</h4>
                            <p>专注于初创品牌的VI系统搭建与日常公关活动物料支持，积累了跨行业的品牌视觉管理经验。</p>
                        </div>
                    </div>
                    <!-- 教育经历 -->
                    <div class="timeline-item">
                        <div class="timeline-dot"></div>
                        <div class="timeline-content">
                            <span class="date">2014 - 2018</span>
                            <h3>视觉传达设计 本科</h3>
                            <h4>中国美术学院</h4>
                            <p>主修品牌设计、字体排印与新媒体艺术，多次获得国家级设计竞赛奖项。</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- 页脚/联系方式 -->
    <footer id="contact" class="footer">
        <div class="container">
            <h2 class="section-title">开启合作 <span>Get in touch</span></h2>
            <div class="contact-info">
                <p>准备好让您的品牌脱颖而出吗？<br>随时期待与您的交流。</p>
                <a href="mailto:hello@chendesign.com" class="email-link">hello@chendesign.com</a>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2023 Chen Design. All Rights Reserved.</p>
                <div class="socials">
                    <a href="#">Behance</a>
                    <a href="#">Zcool</a>
                    <a href="#">LinkedIn</a>
                </div>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
