<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jiping Bai - 白吉平 | 个人学术主页</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary: #2563eb;
            --dark: #111827;
            --light: #f9fafb;
            --gray: #6b7280;
            --border: #e5e7eb;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Microsoft YaHei", sans-serif;
            background-color: var(--light);
            color: var(--dark);
            line-height: 1.7;
        }

        /* 导航栏 */
        nav {
            background: white;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        .nav-container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 1rem 1.5rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            font-size: 1.25rem;
            font-weight: 700;
            color: var(--primary);
        }
        .nav-links a {
            margin-left: 1.5rem;
            text-decoration: none;
            color: var(--dark);
            font-weight: 500;
        }
        .nav-links a:hover {
            color: var(--primary);
        }

        /* 主体 */
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 3rem 1.5rem;
        }

        /* 个人信息 */
        .hero {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            align-items: center;
            margin-bottom: 4rem;
        }
        .hero-info {
            flex: 1;
            min-width: 300px;
        }
        .hero-name {
            font-size: 2.2rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
        }
        .hero-title {
            font-size: 1.1rem;
            color: var(--gray);
            margin-bottom: 1rem;
        }
        .tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-top: 1rem;
        }
        .tag {
            background: #eff6ff;
            color: var(--primary);
            padding: 0.25rem 0.75rem;
            border-radius: 999px;
            font-size: 0.9rem;
        }

        /* 区块样式 */
        section {
            margin-bottom: 3.5rem;
        }
        .section-title {
            font-size: 1.4rem;
            font-weight: 600;
            margin-bottom: 1.25rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid var(--border);
            color: var(--primary);
        }
        .item {
            margin-bottom: 1.25rem;
        }
        .item h4 {
            font-weight: 600;
            font-size: 1.05rem;
        }
        .item p {
            color: var(--gray);
        }

        /* 联系方式图标 */
        .contact-links {
            display: flex;
            gap: 1rem;
            margin-top: 1rem;
        }
        .contact-links a {
            color: var(--primary);
            font-size: 1.25rem;
        }

        /* 响应式 */
        @media (max-width: 768px) {
            .hero-name {
                font-size: 1.8rem;
            }
        }
    </style>
</head>

<body>

<!-- 导航栏 -->
<nav>
    <div class="nav-container">
        <div class="logo">Jiping Bai</div>
        <div class="nav-links">
            <a href="#about">关于我</a>
            <a href="#education">教育</a>
            <a href="#research">研究方向</a>
            <a href="#publications">论文</a>
            <a href="#projects">项目</a>
            <a href="#awards">奖项</a>
            <a href="#contact">联系</a>
        </div>
    </div>
</nav>

<!-- 主体内容 -->
<div class="container">

    <!-- 个人简介 -->
    <div class="hero">
        <div class="hero-info">
            <h1 class="hero-name">Jiping Bai / 白吉平</h1>
            <p class="hero-title">哈尔滨工业大学 计算机技术 | 硕士研究生</p>
            <p>中国海洋大学 保密技术 | 本科</p>
            <div class="tags">
                <span class="tag">可信人工智能</span>
                <span class="tag">模型安全防御</span>
                <span class="tag">不确定性评估</span>
                <span class="tag">ESFJ</span>
            </div>
            <div class="contact-links">
                <a href="mailto:25s130329@stu.hit.edu.cn"><i class="fas fa-envelope"></i></a>
                <a href="https://orcid.org/0009-0008-7412-8433" target="_blank"><i class="fab fa-orcid"></i></a>
                <a href="https://jipingbai.github.io" target="_blank"><i class="fas fa-globe"></i></a>
            </div>
        </div>
    </div>

    <!-- 关于我 -->
    <section id="about">
        <h2 class="section-title">关于我</h2>
        <div class="item">
            <p>• 2024 IEEE SMC 会议审稿人</p>
            <p>• 抖音 / 小红书：随定 Suiding</p>
        </div>
    </section>

    <!-- 教育经历 -->
    <section id="education">
        <h2 class="section-title">教育经历</h2>
        <div class="item">
            <h4>哈尔滨工业大学 | 计算机技术 | 硕士</h4>
        </div>
        <div class="item">
            <h4>中国海洋大学 | 保密技术 | 本科</h4>
        </div>
    </section>

    <!-- 研究方向 -->
    <section id="research">
        <h2 class="section-title">研究方向 / 技能</h2>
        <p><strong>核心领域：</strong>可信人工智能、模型安全防御、不确定性评估</p>
    </section>

    <!-- 学术论文 -->
    <section id="publications">
        <h2 class="section-title">学术论文</h2>
        <div class="item">
            <h4>CE: Knowledge Tracking Model Uncertainty Assessment Method under Trusted Artificial Intelligence</h4>
            <p>IEEE SMC 2024</p>
            <p>结合聚类算法与蒙特卡罗方法，实现知识追踪模型不确定性量化评估</p>
        </div>
    </section>

    <!-- 项目经验 -->
    <section id="projects">
        <h2 class="section-title">项目与专利</h2>

        <div class="item">
            <h4>迭代选举的复杂性分析 | SRDP 大学生创新项目</h4>
            <p>研究迭代选举在控制操作下的计算复杂性，构建数学模型与优化算法，结题评级：良好</p>
        </div>

        <div class="item">
            <h4>Towards the Deep Blue | 2024 美国大学生数学建模竞赛 A 题</h4>
            <p>元胞自动机 + Lotka-Volterra 模型模拟生态系统动态变化</p>
        </div>

        <div class="item">
            <h4>基于博弈论与密码学的机器学习数据遗忘方法 | 国家发明专利（第一发明人）</h4>
            <p>机器遗忘学习、纳什均衡、SISA、密码学保护</p>
        </div>

        <div class="item">
            <h4>呼吸暂停综合征检测方法 | 国家发明专利（第四发明人）</h4>
            <p>TMNet 神经网络、LSTM、域适应、生理信号监测</p>
        </div>
    </section>

    <!-- 荣誉奖项 -->
    <section id="awards">
        <h2 class="section-title">荣誉与奖项</h2>
        <div class="item">
            <p>• 哈尔滨工业大学硕士第一学年一等奖学金</p>
            <p>• 2024 中国海洋大学优秀学生、优秀共青团干部</p>
            <p>• 2023 ISCC 全国大学生信息安全竞赛 国家二等奖</p>
            <p>• 校二等奖学金、社会实践奖学金、金城科技创新一等奖学金</p>
        </div>
    </section>

    <!-- 联系方式 -->
    <section id="contact">
        <h2 class="section-title">联系方式</h2>
        <p>邮箱：25s130329@stu.hit.edu.cn</p>
        <p>ORCID：0009-0008-7412-8433</p>
        <p>学术主页：https://jipingbai.github.io</p>
        <p>抖音 / 小红书：随定 Suiding</p>
    </section>

</div>

</body>
</html>
