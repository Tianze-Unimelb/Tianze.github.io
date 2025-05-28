---
layout: page0
---

# About Me

<img src="https://zhangtianze.com/MeJhiPli.png" class="floatpic" width="360" height="480">

Here is **Tianze Zhang (张天泽)**.

I’m an undergraduate student majoring in CS at the University of Melbourne. Previously, I served as a research assistant at the Xinjiang Key Laboratory of Signal Detection and Processing, advised by [Prof. Gang Shi](https://it.xju.edu.cn/info/1144/2113.htm), and I still keep in close contact with the lab. I also spent a great summer research project at the University of Hong Kong with [Prof. Heming Cui](https://www.cs.hku.hk/people/academic-staff/heming).

If you are interested in any aspect of me, I would love to chat and collaborate, please email me at - *zhangtianze.unimelb[at]gmail.com*

---

<!--## Academic Background

 - **July 2025 - Future:** The University of Melbourne (BSc, CS)
 - **Jan 2023 - June 2025:** Xinjiang Key Laboratory of Signal Detection and Processing(Research assistant)
 - **Sep 2022 - June 2024:** Xinjiang University (BSc, CS)(Transfer to UniMelb)
 - **July 2023 - Aug 2023:** The University of Hongkong(Summer research)

---
-->

<!--## Academic Milestones-->

<!-- Mar 2024：Very honored to receive the **Offer of Bachelor of Science** from **The University of Melbourne**. -->
<!-- July 2023：Very excited to join a **Summer reasearch** project at **The University of Hong Kong**.-->
<!-- Jan 2023：Very honored to join the **Xinjiang Key Laboratory of Signal Detection and Processing**.-->

<!--## Recommendation

- Recommendation Letter from [Prof. Gang Shi](https://it.xju.edu.cn/info/1144/2113.htm) , Xinjiang University
- Recommendation Letter from [Prof. Heming Cui](https://www.cs.hku.hk/people/academic-staff/heming) , The University of Hongkong.

---
-->

## Research Interests

 - Natural Language Processing
 - Applied Machine Learning
 - Computer Vision
 - Computational Law
 - Quantitative Analysis

My current research focuses on practical problems faced by artificial intelligence in complex legal scenarios. My interests are **Machine Learning** and its applications in **Law**, **Finance**, and **Medicine**. In short, advanced technologies such as artificial intelligence have a positive impact on everyone's life. I hope to devote my talents to this meaningful cause and bring benefits to society.

---

## News and Updates

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        :root {
            --ac-primary: #2c3e50;
            --ac-secondary: #3498db;
            --ac-text-light: #ecf0f1;
            --ac-bg: #fff;
            --ac-gray-light: #f8f9fa;
            --ac-gray: #6c757d;
            --ac-shadow: 0 10px 30px rgba(0,0,0,0.1);
            --ac-shadow-hover: 0 15px 40px rgba(0,0,0,0.15);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
            background: linear-gradient(135deg, #f5f7fa 0%, #e9ecef 100%);
            color: #333;
            overflow-x: hidden;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        /* 主容器 */
        .academic-showcase {
            width: 90%;
            max-width: 900px;
            margin: 40px auto;
        }

        .section-title {
            text-align: center;
            font-size: 36px;
            font-weight: 300;
            margin-bottom: 50px;
            color: var(--ac-primary);
            position: relative;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: -15px;
            left: 50%;
            transform: translateX(-50%);
            width: 60px;
            height: 3px;
            background: var(--ac-secondary);
            border-radius: 2px;
        }

        /* 内容容器 */
        .carousel-container {
            position: relative;
            height: auto;
            border-radius: 16px;
            overflow: hidden;
            box-shadow: var(--ac-shadow);
            background: var(--ac-bg);
            display: flex;
        }

        /* 左侧成就展示区 */
        .content-panel {
            flex: 1;
            position: relative;
            background: var(--ac-bg);
            overflow: hidden;
        }

        .achievement-wrapper {
            position: relative;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .achievement-card {
            position: absolute;
            width: 90%;
            max-width: 600px;
            padding: 50px;
            opacity: 0;
            transform: translateY(30px) scale(0.95);
            transition: all 0.6s cubic-bezier(0.4, 0, 0.2, 1);
            pointer-events: none;
        }

        .achievement-card.active {
            opacity: 1;
            transform: translateY(0) scale(1);
            pointer-events: all;
        }

        .achievement-card.prev {
            transform: translateY(-30px) scale(0.95);
        }

        .achievement-card.next {
            transform: translateY(30px) scale(0.95);
        }

        .achievement-date {
            color: var(--ac-secondary);
            font-size: 14px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 12px;
            display: inline-block;
            position: relative;
            padding-left: 25px;
        }

        .achievement-date::before {
            content: '';
            position: absolute;
            left: 0;
            top: 50%;
            transform: translateY(-50%);
            width: 15px;
            height: 2px;
            background: var(--ac-secondary);
        }

        .achievement-title {
            font-size: 28px;
            font-weight: 700;
            margin-bottom: 20px;
            color: var(--ac-primary);
            line-height: 1.3;
        }

        .achievement-description {
            font-size: 16px;
            line-height: 1.8;
            color: #5a6c7d;
            margin-bottom: 25px;
        }

        .achievement-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .tag {
            display: inline-block;
            padding: 6px 16px;
            background: rgba(52, 152, 219, 0.1);
            color: var(--ac-secondary);
            border-radius: 20px;
            font-size: 13px;
            font-weight: 500;
            border: 1px solid rgba(52, 152, 219, 0.2);
            transition: all 0.3s ease;
        }

        .tag:hover {
            background: var(--ac-secondary);
            color: white;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(52, 152, 219, 0.3);
        }

        /* 右侧时间轴面板 */
        .timeline-panel {
            width: 320px;
            background: var(--ac-primary);
            position: relative;
            display: flex;
            align-items: center;
            overflow: hidden;
        }

        .timeline-wrapper {
            width: 100%;
            height: 70%;
            position: relative;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 40px;
        }

        .timeline-container {
            position: relative;
            width: 100%;
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            gap: 30px;
            transition: transform 0.6s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .timeline-item {
            position: absolute;
            width: 100%;
            padding-left: 35px;
            cursor: pointer;
            opacity: 0;
            transform: scale(0.8) translateY(0);
            transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
            pointer-events: none;
        }

        /* 居中显示的三个位置 */
        .timeline-item.position-prev {
            transform: translateY(-80px) scale(0.85);
            opacity: 0.4;
            pointer-events: all;
        }

        .timeline-item.position-current {
            transform: translateY(0) scale(1);
            opacity: 1;
            pointer-events: all;
        }

        .timeline-item.position-next {
            transform: translateY(80px) scale(0.85);
            opacity: 0.4;
            pointer-events: all;
        }

        .timeline-item::before {
            content: '';
            position: absolute;
            left: 0;
            top: 8px;
            width: 12px;
            height: 12px;
            background: rgba(255, 255, 255, 0.3);
            border-radius: 50%;
            border: 2px solid rgba(255, 255, 255, 0.5);
            transition: all 0.5s ease;
        }

        .timeline-item.position-current::before {
            width: 18px;
            height: 18px;
            background: var(--ac-secondary);
            border-color: var(--ac-bg);
            box-shadow: 0 0 0 4px rgba(52, 152, 219, 0.3);
            top: 5px;
        }

        .timeline-date {
            color: var(--ac-text-light);
            font-weight: 600;
            margin-bottom: 5px;
            font-size: 14px;
            transition: all 0.5s ease;
        }

        .timeline-item.position-current .timeline-date {
            font-size: 18px;
        }

        .timeline-title {
            color: rgba(255, 255, 255, 0.7);
            font-size: 13px;
            line-height: 1.4;
            transition: all 0.5s ease;
        }

        .timeline-item.position-current .timeline-title {
            color: rgba(255, 255, 255, 0.9);
            font-size: 14px;
        }

        /* 连接线 */
        .timeline-line {
            position: absolute;
            left: 45px;
            top: 50%;
            transform: translateY(-50%);
            width: 2px;
            height: 160px;
            background: linear-gradient(to bottom,
            transparent 0%,
            rgba(255,255,255,0.2) 30%,
            rgba(52,152,219,0.5) 50%,
            rgba(255,255,255,0.2) 70%,
            transparent 100%);
            pointer-events: none;
        }

        /* 导航控制 */
        .nav-controls {
            position: absolute;
            bottom: 40px;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            align-items: center;
            gap: 30px;
            z-index: 10;
        }

        .nav-button {
            width: 45px;
            height: 45px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.95);
            border: none;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
            font-size: 18px;
            color: var(--ac-gray);
        }

        .nav-button:hover:not(:disabled) {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.15);
            background: white;
            color: var(--ac-secondary);
        }

        .nav-button:disabled {
            opacity: 0.3;
            cursor: not-allowed;
        }

        .progress-counter {
            font-size: 14px;
            color: var(--ac-gray);
            font-weight: 500;
            background: white;
            padding: 8px 20px;
            border-radius: 20px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
        }

        .current-number {
            color: var(--ac-secondary);
            font-weight: 700;
            font-size: 16px;
        }

        /* 边缘渐变效果 */
        .timeline-panel::before,
        .timeline-panel::after {
            content: '';
            position: absolute;
            left: 0;
            right: 0;
            height: 80px;
            pointer-events: none;
            z-index: 1;
        }

        .timeline-panel::before {
            top: 0;
            background: linear-gradient(to bottom, var(--ac-primary) 0%, transparent 100%);
        }

        .timeline-panel::after {
            bottom: 0;
            background: linear-gradient(to top, var(--ac-primary) 0%, transparent 100%);
        }

        /* 响应式设计 */
        @media (max-width: 768px) {
            .academic-showcase {
                width: 95%;
            }

            .carousel-container {
                height: auto;
                flex-direction: column;
            }

            .content-panel {
                min-height: 400px;
            }

            .achievement-card {
                padding: 30px;
            }

            .achievement-title {
                font-size: 24px;
            }

            .timeline-panel {
                width: 100%;
                height: 180px;
            }

            .timeline-wrapper {
                flex-direction: row;
                height: 100%;
                padding: 20px;
            }

            .timeline-container {
                flex-direction: row;
            }

            .timeline-item.position-prev {
                transform: translateX(-120px) scale(0.85);
            }

            .timeline-item.position-current {
                transform: translateX(0) scale(1);
            }

            .timeline-item.position-next {
                transform: translateX(120px) scale(0.85);
            }

            .timeline-line {
                display: none;
            }

            .nav-controls {
                bottom: 20px;
            }
        }

        /* 加载动画 */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .academic-showcase {
            animation: fadeInUp 0.8s ease-out;
        }
    </style>
</head>
<body>
<div class="academic-showcase">

    <div class="carousel-container">
        <!-- 左侧内容面板 -->
        <div class="content-panel">
            <div class="achievement-wrapper">
                <div class="achievement-card active" data-index="0">
                    <div class="achievement-date">2025-03</div>
                    <h3 class="achievement-title">Paper Acceptance</h3>
                    <p class="achievement-description">
                        Our Work--SWR-BIDeN: An Improved BIDeN Model for Severe Weather Removal in Image Processing was accepted by IJCNN2025
                    </p>
                    <div class="achievement-tags">
                        <span class="tag">CCF-C</span>
                        <span class="tag">AI</span>
                        <span class="tag">IJCNN2025</span>
                    </div>
                </div>

                <div class="achievement-card" data-index="1">
                    <div class="achievement-date">2025-04</div>
                    <h3 class="achievement-title">Paper Acceptance</h3>
                    <p class="achievement-description">
                        Our Work--LightDrone-YOLO: A Novel Lightweight and Efficient Object Detection Network for Unmanned Aerial Vehicles was accepted by ICIC2025
                    </p>
                    <div class="achievement-tags">
                        <span class="tag">CCF-C</span>
                        <span class="tag">AI</span>
                        <span class="tag">ICIC2025</span>
                    </div>
                </div>

                <div class="achievement-card" data-index="2">
                    <div class="achievement-date">2025-04</div>
                    <h3 class="achievement-title">Paper Acceptance</h3>
                    <p class="achievement-description">
                        Our Work--Lightweight Remote Sensing Image Change Detection Based on Global Feature Fusion was accepted by ICIC2025
                    </p>
                    <div class="achievement-tags">
                        <span class="tag">CCF-C</span>
                        <span class="tag">AI</span>
                        <span class="tag">ICIC2025</span>
                    </div>
                </div>

                <div class="achievement-card" data-index="3">
                    <div class="achievement-date">2025-04</div>
                    <h3 class="achievement-title">Paper Acceptance</h3>
                    <p class="achievement-description">
                        Our Work--GlintNet: A Lightweight Global-Local Integration Network with Spatial-Channel Mixed Attention for ReID was accepted by ICIC2025
                    </p>
                    <div class="achievement-tags">
                        <span class="tag">CCF-C</span>
                        <span class="tag">AI</span>
                        <span class="tag">ICIC2025</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- 右侧时间轴面板 -->
        <div class="timeline-panel">
            <div class="timeline-line"></div>
            <div class="timeline-wrapper">
                <div class="timeline-container" id="timelineContainer">
                    <!-- 时间轴项目将通过JavaScript动态生成 -->
                </div>
            </div>
        </div>
    </div>

    <!-- 导航控制 -->
    <div class="nav-controls">
        <button class="nav-button" id="prevBtn">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5">
                <path d="M15 18l-6-6 6-6"/>
            </svg>
        </button>
        <div class="progress-counter">
            <span class="current-number" id="currentNum">1</span> / <span id="totalNum">6</span>
        </div>
        <button class="nav-button" id="nextBtn">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5">
                <path d="M9 18l6-6-6-6"/>
            </svg>
        </button>
    </div>
</div>

<script>
    // 时间轴数据
    const timelineData = [
        { date: '2025-03', title: 'Our work was accepted by IJCNN2025' },
        { date: '2025-04', title: 'Our work was accepted by ICIC2025' },
        { date: '2025-04', title: 'Our work was accepted by ICIC2025' },
        { date: '2025-04', title: 'Our work was accepted by ICIC2025' },

    ];

    // 初始化变量
    let currentIndex = 0;
    const achievementCards = document.querySelectorAll('.achievement-card');
    const timelineContainer = document.getElementById('timelineContainer');
    const prevBtn = document.getElementById('prevBtn');
    const nextBtn = document.getElementById('nextBtn');
    const currentNum = document.getElementById('currentNum');
    const totalNum = document.getElementById('totalNum');
    const totalItems = achievementCards.length;

    // 设置总数
    totalNum.textContent = totalItems;

    // 创建时间轴项目
    function createTimelineItems() {
        timelineData.forEach((item, index) => {
            const timelineItem = document.createElement('div');
            timelineItem.className = 'timeline-item';
            timelineItem.setAttribute('data-index', index);

            timelineItem.innerHTML = `
                    <div class="timeline-date">${item.date}</div>
                    <div class="timeline-title">${item.title}</div>
                `;

            timelineItem.addEventListener('click', () => {
                goToIndex(index);
            });

            timelineContainer.appendChild(timelineItem);
        });
    }

    // 更新时间轴位置
    function updateTimelinePositions() {
        const items = timelineContainer.querySelectorAll('.timeline-item');

        items.forEach((item, index) => {
            item.classList.remove('position-prev', 'position-current', 'position-next');

            if (index === currentIndex - 1 && index >= 0) {
                item.classList.add('position-prev');
            } else if (index === currentIndex) {
                item.classList.add('position-current');
            } else if (index === currentIndex + 1 && index < totalItems) {
                item.classList.add('position-next');
            }
        });
    }

    // 更新显示状态
    function updateDisplay(index) {
        // 更新成就卡片
        achievementCards.forEach((card, i) => {
            card.classList.remove('active', 'prev', 'next');
            if (i === index) {
                card.classList.add('active');
            } else if (i < index) {
                card.classList.add('prev');
            } else {
                card.classList.add('next');
            }
        });

        // 更新时间轴
        updateTimelinePositions();

        // 更新进度数字
        currentNum.textContent = index + 1;

        // 更新按钮状态
        prevBtn.disabled = index === 0;
        nextBtn.disabled = index === totalItems - 1;
    }

    // 切换到指定索引
    function goToIndex(index) {
        if (index >= 0 && index < totalItems) {
            currentIndex = index;
            updateDisplay(currentIndex);
        }
    }

    // 上一个
    function goPrev() {
        if (currentIndex > 0) {
            goToIndex(currentIndex - 1);
        }
    }

    // 下一个
    function goNext() {
        if (currentIndex < totalItems - 1) {
            goToIndex(currentIndex + 1);
        }
    }

    // 事件监听器
    prevBtn.addEventListener('click', goPrev);
    nextBtn.addEventListener('click', goNext);

    // 键盘控制
    document.addEventListener('keydown', (e) => {
        if (e.key === 'ArrowLeft' || e.key === 'ArrowUp') {
            e.preventDefault();
            goPrev();
        } else if (e.key === 'ArrowRight' || e.key === 'ArrowDown') {
            e.preventDefault();
            goNext();
        } else if (e.key >= '1' && e.key <= '9') {
            const num = parseInt(e.key) - 1;
            if (num < totalItems) {
                goToIndex(num);
            }
        }
    });

    // 鼠标滚轮控制
    let isScrolling = false;
    const carouselContainer = document.querySelector('.carousel-container');

    carouselContainer.addEventListener('wheel', (e) => {
        e.preventDefault();
        if (!isScrolling) {
            isScrolling = true;
            if (e.deltaY > 0) {
                goNext();
            } else {
                goPrev();
            }
            setTimeout(() => {
                isScrolling = false;
            }, 600);
        }
    });

    // 触摸滑动支持
    let touchStartX = 0;
    let touchStartY = 0;
    let touchEndX = 0;
    let touchEndY = 0;

    carouselContainer.addEventListener('touchstart', (e) => {
        touchStartX = e.touches[0].clientX;
        touchStartY = e.touches[0].clientY;
    });

    carouselContainer.addEventListener('touchmove', (e) => {
        touchEndX = e.touches[0].clientX;
        touchEndY = e.touches[0].clientY;
    });

    carouselContainer.addEventListener('touchend', () => {
        const diffX = touchStartX - touchEndX;
        const diffY = touchStartY - touchEndY;
        const threshold = 50;

        if (Math.abs(diffX) > Math.abs(diffY)) {
            // 水平滑动
            if (diffX > threshold) {
                goNext();
            } else if (diffX < -threshold) {
                goPrev();
            }
        } else {
            // 垂直滑动
            if (diffY > threshold) {
                goNext();
            } else if (diffY < -threshold) {
                goPrev();
            }
        }
    });

    // 自动高度调整
    function adjustTimelineHeight() {
        const isMobile = window.innerWidth <= 768;
        if (!isMobile) {
            const activeCard = document.querySelector('.achievement-card.active');
            if (activeCard) {
                const cardHeight = activeCard.offsetHeight;
                const container = document.querySelector('.carousel-container');
                container.style.height = Math.max(500, cardHeight + 100) + 'px';
            }
        }
    }

    // 窗口大小改变时调整
    window.addEventListener('resize', () => {
        adjustTimelineHeight();
        updateTimelinePositions();
    });

    // 添加平滑过渡
    function smoothTransition() {
        const items = timelineContainer.querySelectorAll('.timeline-item');
        items.forEach((item) => {
            item.style.transition = 'all 0.5s cubic-bezier(0.4, 0, 0.2, 1)';
        });
    }

    // 初始化
    createTimelineItems();
    updateDisplay(0);
    smoothTransition();
    adjustTimelineHeight();

    // 预加载动画
    window.addEventListener('load', () => {
        setTimeout(() => {
            document.querySelector('.academic-showcase').style.opacity = '1';
        }, 100);
    });

    // 添加悬停效果
    achievementCards.forEach(card => {
        card.addEventListener('mouseenter', () => {
            if (card.classList.contains('active')) {
                card.style.transform = 'translateY(0) scale(1.02)';
            }
        });

        card.addEventListener('mouseleave', () => {
            if (card.classList.contains('active')) {
                card.style.transform = 'translateY(0) scale(1)';
            }
        });
    });

    // 页面可见性改变时的处理
    document.addEventListener('visibilitychange', () => {
        if (!document.hidden) {
            smoothTransition();
        }
    });
</script>
</body>
</html>
