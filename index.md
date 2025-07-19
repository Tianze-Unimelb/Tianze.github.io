---
layout: page0
---

# About Me

<img src="https://zhangtianze.com/ZTZ .jpg" class="floatpic" width="360" height="480">

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
- Computer Vision
- Computational Law
- Quantitative Analysis

<!-- My current research focuses on practical problems faced by artificial intelligence in complex legal scenarios. My interests are **Artificial intelligence.** and its applications in **Law**, **Finance**, and **Medicine**. In short, advanced technologies such as artificial intelligence have a positive impact on everyone's life. I hope to devote my talents to this meaningful cause and bring benefits to society.
-->

---

## News and Updates
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* 完全封装的新闻模块样式 - 所有样式都限制在 .academic-news-module 内 */
        .academic-news-module {
            /* 重置所有子元素的默认样式 */
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            width: 100%;
            max-width: 1000px;
            margin: 0 auto;
            position: relative;
            background: transparent;
        }

        .academic-news-module *,
        .academic-news-module *::before,
        .academic-news-module *::after {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        .academic-news-module .news-wrapper {
            --ac-primary: #2c3e50;
            --ac-secondary: #3498db;
            --ac-text-light: #ecf0f1;
            --ac-bg: #fff;
            --ac-gray-light: #f8f9fa;
            --ac-gray: #6c757d;
            --ac-shadow: 0 10px 30px rgba(0,0,0,0.1);
            --ac-shadow-hover: 0 15px 40px rgba(0,0,0,0.15);

            color: #333;
            overflow: hidden;
            border-radius: 16px;
            background: rgba(255, 255, 255, 0.95);
            box-shadow: 0 12px 40px rgba(0, 0, 0, 0.1);
            position: relative;
            animation: fadeInUp 0.8s ease-out;
            height: 100%;
        }

        /* 内容容器 - 覆盖整个背景 */
        .academic-news-module .carousel-container {
            position: relative;
            height: 340px;
            border-radius: 14px;
            overflow: hidden;
            box-shadow: 0 8px 25px rgba(0,0,0,0.08);
            background: var(--ac-bg);
            display: flex;
            border: 1px solid rgba(0,0,0,0.05);
        }

        /* 左侧成就展示区 */
        .academic-news-module .content-panel {
            flex: 0 0 70%;
            position: relative;
            background: var(--ac-bg);
            overflow: hidden;
        }

        .academic-news-module .achievement-wrapper {
            position: relative;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 15px;
        }

        .academic-news-module .achievement-card {
            position: absolute;
            width: 100%;
            max-width: 700px;
            padding: 60px;
            opacity: 0;
            transform: translateY(30px) scale(0.95);
            transition: all 0.6s cubic-bezier(0.4, 0, 0.2, 1);
            pointer-events: none;
            margin: 0;
            background: white;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }

        .academic-news-module .achievement-card.active {
            opacity: 1;
            transform: translateY(0) scale(1);
            pointer-events: all;
            z-index: 2;
        }

        .academic-news-module .achievement-card.prev,
        .academic-news-module .achievement-card.next {
            z-index: 1;
        }

        .academic-news-module .achievement-card.prev {
            transform: translateY(-30px) scale(0.95);
        }

        .academic-news-module .achievement-card.next {
            transform: translateY(30px) scale(0.95);
        }

        .academic-news-module .achievement-date {
            color: var(--ac-secondary);
            font-size: 15px;  /* 原来16px，缩小到14px */
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin: 0 0 15px 0;
            display: inline-block;
            position: relative;
            padding-left: 24px;
        }

        .academic-news-module .achievement-date::before {
            content: '';
            position: absolute;
            left: 0;
            top: 50%;
            transform: translateY(-50%);
            width: 14px;
            height: 3px;
            background: var(--ac-secondary);
        }

        .academic-news-module .achievement-title {
            font-size: 22px;  /* 原来24px，缩小到20px */
            font-weight: 700;
            margin: 0 0 20px 0;
            color: var(--ac-primary);
            line-height: 1.3;
        }

        .academic-news-module .achievement-description {
            font-size: 15px;  /* 原来16px，缩小到14px */
            line-height: 1.7;
            color: #5a6c7d;
            margin: 0 0 25px 0;
        }

        .academic-news-module .achievement-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 0;
            padding: 0;
            list-style: none;
        }

        .academic-news-module .tag {
            display: inline-block;
            padding: 6px 15px;
            background: rgba(52, 152, 219, 0.1);
            color: var(--ac-secondary);
            border-radius: 20px;
            font-size: 12px;  /* 原来13px，缩小到12px */
            font-weight: 600;
            border: 1px solid rgba(52, 152, 219, 0.2);
            transition: all 0.3s ease;
            margin: 0;
        }

        .academic-news-module .tag:hover {
            background: var(--ac-secondary);
            color: white;
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(52, 152, 219, 0.3);
        }

        /* 右侧时间轴面板 */
        .academic-news-module .timeline-panel {
            flex: 0 0 30%;
            background: linear-gradient(160deg, #2c3e50 0%, #1a2530 100%);
            position: relative;
            display: flex;
            align-items: center;
            overflow: hidden;
        }

        .academic-news-module .timeline-wrapper {
            width: 100%;
            height: 100%;
            position: relative;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 30px 15px;
        }

        .academic-news-module .timeline-container {
            position: relative;
            width: 100%;
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            gap: 100px;
            transition: transform 0.6s cubic-bezier(0.4, 0, 0.2, 1);
            overflow-y: auto;
            scrollbar-width: none; /* Firefox */
        }

        .academic-news-module .timeline-container::-webkit-scrollbar {
            display: none; /* Chrome, Safari */
        }

        .academic-news-module .timeline-item {
            position: absolute;
            width: 100%;
            padding-left: 30px;
            cursor: pointer;
            opacity: 0;
            transform: scale(0.8) translateY(0);
            transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
            pointer-events: none;
            margin: 0;
        }

        .academic-news-module .timeline-item.position-prev {
            transform: translateY(-85px) scale(0.85);
            opacity: 0.4;
            pointer-events: all;
        }

        .academic-news-module .timeline-item.position-current {
            transform: translateY(0) scale(1);
            opacity: 1;
            pointer-events: all;
        }

        .academic-news-module .timeline-item.position-next {
            transform: translateY(85px) scale(0.85);
            opacity: 0.4;
            pointer-events: all;
        }

        .academic-news-module .timeline-item::before {
            content: '';
            position: absolute;
            left: 0;
            top: 7px;
            width: 12px;
            height: 12px;
            background: rgba(255, 255, 255, 0.3);
            border-radius: 50%;
            border: 2px solid rgba(255, 255, 255, 0.5);
            transition: all 0.5s ease;
        }

        .academic-news-module .timeline-item.position-current::before {
            width: 16px;
            height: 16px;
            background: var(--ac-secondary);
            border-color: var(--ac-bg);
            box-shadow: 0 0 0 4px rgba(52, 152, 219, 0.3);
            top: 4px;
        }

        .academic-news-module .timeline-date {
            color: var(--ac-text-light);
            font-weight: 700;
            margin: 0 0 5px 0;
            font-size: 13px;  /* 原来14px，缩小到12px */
            transition: all 0.5s ease;
        }

        .academic-news-module .timeline-item.position-current .timeline-date {
            font-size: 14px;  /* 原来15px，缩小到13px */
            color: #3498db;
        }

        .academic-news-module .timeline-title {
            color: rgba(255, 255, 255, 0.7);
            font-size: 13px;  /* 原来14px，缩小到12px */
            line-height: 1.4;
            transition: all 0.5s ease;
            margin: 0;
        }

        .academic-news-module .timeline-item.position-current .timeline-title {
            color: rgba(255, 255, 255, 0.95);
            font-size: 14px;  /* 原来15px，缩小到13px */
        }

        /* 连接线 */
        .academic-news-module .timeline-line {
            position: absolute;
            left: 37px;
            top: 50%;
            transform: translateY(-50%);
            width: 3px;
            height: 300px;
            background: linear-gradient(to bottom,
            transparent 0%,
            rgba(255,255,255,0.2) 30%,
            rgba(52,152,219,0.6) 50%,
            rgba(255,255,255,0.2) 70%,
            transparent 100%);
            pointer-events: none;
        }

        /* 边缘渐变效果 */
        .academic-news-module .timeline-panel::before,
        .academic-news-module .timeline-panel::after {
            content: '';
            position: absolute;
            left: 0;
            right: 0;
            height: 70px;
            pointer-events: none;
            z-index: 2;
        }

        .academic-news-module .timeline-panel::before {
            top: 0;
            background: linear-gradient(to bottom, #1a2530 0%, transparent 100%);
        }

        .academic-news-module .timeline-panel::after {
            bottom: 0;
            background: linear-gradient(to top, #1a2530 0%, transparent 100%);
        }

        /* 导航控制 - 固定在容器底部并默认隐藏 */
        .academic-news-module .nav-controls {
            position: absolute;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            align-items: center;
            gap: 25px;
            z-index: 100;
            opacity: 0;
            transition: all 0.4s ease;
            background: rgba(255, 255, 255, 0.95);
            padding: 12px 30px;
            border-radius: 35px;
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.15);
            backdrop-filter: blur(4px);
        }

        .academic-news-module .news-wrapper:hover .nav-controls {
            opacity: 1;
        }

        .academic-news-module .nav-button {
            width: 48px;
            height: 48px;
            border-radius: 50%;
            background: white;
            border: none;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.12);
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
            font-size: 18px;
            color: var(--ac-gray);
        }

        .academic-news-module .nav-button:hover:not(:disabled) {
            transform: translateY(-3px);
            box-shadow: 0 7px 20px rgba(0, 0, 0, 0.18);
            background: var(--ac-secondary);
            color: white;
        }

        .academic-news-module .nav-button:disabled {
            opacity: 0.4;
            cursor: not-allowed;
        }

        .academic-news-module .progress-counter {
            font-size: 15px;
            color: var(--ac-gray);
            font-weight: 600;
            background: white;
            padding: 8px 20px;
            border-radius: 20px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.07);
            margin: 0;
        }

        .academic-news-module .current-number {
            color: var(--ac-secondary);
            font-weight: 700;
            font-size: 16px;
        }

        .academic-news-module .auto-play-indicator {
            position: absolute;
            bottom: 15px;
            left: 15px;
            font-size: 12px;
            color: #3498db;
            display: flex;
            align-items: center;
            gap: 6px;
        }

        /* 响应式设计 */
        @media (max-width: 900px) {
            .academic-news-module .carousel-container {
                height: 600px;
                flex-direction: column;
            }

            .academic-news-module .content-panel {
                flex: 0 0 60%;
            }

            .academic-news-module .timeline-panel {
                flex: 0 0 40%;
            }

            .academic-news-module .achievement-card {
                padding: 25px;
            }

            .academic-news-module .achievement-title {
                font-size: 22px;
            }

            .academic-news-module .timeline-wrapper {
                flex-direction: row;
                height: 100%;
                padding: 15px;
            }

            .academic-news-module .timeline-container {
                flex-direction: row;
                gap: 15px;
            }

            .academic-news-module .timeline-item.position-prev {
                transform: translateX(-100px) scale(0.85);
            }

            .academic-news-module .timeline-item.position-current {
                transform: translateX(0) scale(1);
            }

            .academic-news-module .timeline-item.position-next {
                transform: translateX(100px) scale(0.85);
            }

            .academic-news-module .timeline-line {
                display: none;
            }

            .academic-news-module .nav-controls {
                bottom: 15px;
                opacity: 1;
                background: rgba(255, 255, 255, 0.95);
                padding: 10px 25px;
            }
        }

        @media (max-width: 600px) {
            .academic-news-module .achievement-card {
                padding: 20px;
            }

            .academic-news-module .achievement-title {
                font-size: 20px;
            }

            .academic-news-module .achievement-description {
                font-size: 14px;
            }

            .academic-news-module .tag {
                padding: 5px 12px;
                font-size: 12px;
            }

            .academic-news-module .carousel-container {
                height: 650px;
            }
        }

        /* 加载动画 */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
<!-- 完全封装的学术新闻模块 -->
<div class="academic-news-module">
    <div class="news-wrapper">
        <div class="carousel-container">
            <!-- 左侧内容面板 -->
            <div class="content-panel">
                <div class="achievement-wrapper">
                    <div class="achievement-card active" data-index="0">
                        <div class="achievement-date">2025-3</div>
                        <h3 class="achievement-title">Our paper was accepted by IJCNN2025</h3>
                        <p class="achievement-description">
                            Our research result "SWR-BIDeN: An Improved BIDeN Model for Severe Weather Removal in Image Processing" was accepted by the International Joint Conference on Neural Networks (IJCNN2025).
                        </p>
                        <div class="achievement-tags">
                            <span class="tag">CCF-C</span>
                            <span class="tag">Image Processing</span>
                            <span class="tag">CV</span>
                        </div>
                    </div>

                    <div class="achievement-card" data-index="1">
                        <div class="achievement-date">2025-4</div>
                        <h3 class="achievement-title">Our paper was accepted by ICIC2025</h3>
                        <p class="achievement-description">
                            Our research result "LightDrone-YOLO: A Novel Lightweight and Efficient Object Detection Network for Unmanned Aerial Vehicles" was accepted by the International Conference on Intelligent Computing (ICIC2025).
                        </p>
                        <div class="achievement-tags">
                            <span class="tag">CCF-C</span>
                            <span class="tag">Object Detection</span>
                            <span class="tag">UVA</span>
                        </div>
                    </div>

                    <div class="achievement-card" data-index="2">
                        <div class="achievement-date">2025-4</div>
                        <h3 class="achievement-title">Our paper was accepted by ICIC2025</h3>
                        <p class="achievement-description">
                            Our research result "Lightweight Remote Sensing Image Change Detection Based on Global Feature Fusion" was accepted by the International Conference on Intelligent Computing (ICIC2025).
                        </p>
                        <div class="achievement-tags">
                            <span class="tag">CCF-C</span>
                            <span class="tag">Remote Sensing</span>
                            <span class="tag">CV</span>
                        </div>
                    </div>

                    <div class="achievement-card" data-index="3">
                        <div class="achievement-date">2025-4</div>
                        <h3 class="achievement-title">Our paper was accepted by ICIC2025</h3>
                        <p class="achievement-description">
                            Our research result "GlintNet: A Lightweight Global-Local Integration Network with Spatial-Channel Mixed Attention for ReID" was accepted by the International Conference on Intelligent Computing (ICIC2025).
                        </p>
                        <div class="achievement-tags">
                            <span class="tag">CCF-C</span>
                            <span class="tag">Re-ID</span>
                            <span class="tag">CV</span>
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
                <i class="fas fa-chevron-left"></i>
            </button>
            <div class="progress-counter">
                <span class="current-number" id="currentNum">1</span> / <span id="totalNum">4</span>
            </div>
            <button class="nav-button" id="nextBtn">
                <i class="fas fa-chevron-right"></i>
            </button>
        </div>
    </div>
</div>

<script>
    document.addEventListener('DOMContentLoaded', function() {
        // 时间轴数据
        const timelineData = [
            { date: '2025-03', title: 'Our paper was accepted by IJCNN2025' },
            { date: '2025-04', title: 'Our paper was accepted by ICIC2025' },
            { date: '2025-04', title: 'Our paper was accepted by ICIC2025' },
            { date: '2025-04', title: 'Our paper was accepted by ICIC2025' }
        ];

        // 初始化变量
        let currentIndex = 0;
        let autoPlayInterval;
        const wrapper = document.querySelector('.academic-timeline-wrapper');
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
            } else {
                goToIndex(0);
            }
        }

        // 自动轮播功能
        function startAutoPlay() {
            autoPlayInterval = setInterval(() => {
                if (currentIndex < totalItems - 1) {
                    goToIndex(currentIndex + 1);
                } else {
                    goToIndex(0);
                }
            }, 5000);
        }

        // 停止自动轮播
        function stopAutoPlay() {
            clearInterval(autoPlayInterval);
        }

        // 事件监听器
        prevBtn.addEventListener('click', function() {
            stopAutoPlay();
            goPrev();
            setTimeout(startAutoPlay, 10000);
        });

        nextBtn.addEventListener('click', function() {
            stopAutoPlay();
            goNext();
            setTimeout(startAutoPlay, 10000);
        });

        // 初始化
        createTimelineItems();
        updateDisplay(0);
        startAutoPlay();

        // 当鼠标悬停在容器上时暂停自动轮播
        wrapper.addEventListener('mouseenter', stopAutoPlay);
        wrapper.addEventListener('mouseleave', startAutoPlay);

        // 键盘控制
        document.addEventListener('keydown', (e) => {
            if (e.key === 'ArrowLeft') {
                goPrev();
            } else if (e.key === 'ArrowRight') {
                goNext();
            }
        });

        // 触摸滑动支持
        let touchStartX = 0;
        let touchEndX = 0;

        wrapper.addEventListener('touchstart', (e) => {
            touchStartX = e.changedTouches[0].screenX;
        });

        wrapper.addEventListener('touchend', (e) => {
            touchEndX = e.changedTouches[0].screenX;
            handleSwipe();
        });

        function handleSwipe() {
            const diffX = touchStartX - touchEndX;
            const threshold = 50;

            if (diffX > threshold) {
                goNext();
            } else if (diffX < -threshold) {
                goPrev();
            }
        }

        // 时间轴滚轮滚动支持
        timelineContainer.addEventListener('wheel', (e) => {
            e.preventDefault();
            if (e.deltaY > 0) {
                // 向下滚动 - 下一个
                goNext();
            } else if (e.deltaY < 0) {
                // 向上滚动 - 上一个
                goPrev();
            }
        });
    });
</script>
</body>
</html>
