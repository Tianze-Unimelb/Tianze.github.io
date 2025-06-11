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
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #f5f7fa 0%, #e4edf5 100%);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
            color: #333;
        }

        .container {
            width: 100%;
            max-width: 1200px;
            padding: 20px;
        }

        .header {
            text-align: center;
            margin-bottom: 40px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }

        .header h1 {
            font-size: 2.8rem;
            color: #2c3e50;
            margin-bottom: 15px;
            font-weight: 600;
            position: relative;
            display: inline-block;
        }

        .header h1:after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: #3498db;
            border-radius: 2px;
        }

        .header p {
            color: #5a6c7d;
            font-size: 1.1rem;
            line-height: 1.6;
            max-width: 700px;
            margin: 0 auto;
        }

        /* 封装后的新闻模块样式 - 使用唯一命名空间 */
        .academic-news-container {
            width: 95%;
            max-width: 1000px;
            margin: 0 auto 40px;
            --ac-primary: #2c3e50;
            --ac-secondary: #3498db;
            --ac-text-light: #ecf0f1;
            --ac-bg: #fff;
            --ac-gray-light: #f8f9fa;
            --ac-gray: #6c757d;
            --ac-shadow: 0 10px 30px rgba(0,0,0,0.1);
            --ac-shadow-hover: 0 15px 40px rgba(0,0,0,0.15);
        }

        .academic-news-wrapper {
            color: #333;
            overflow: hidden;
            border-radius: 16px;
            background: rgba(255, 255, 255, 0.95);
            box-shadow: 0 12px 40px rgba(0, 0, 0, 0.1);
            position: relative;
            animation: academic-fadeInUp 0.8s ease-out;
            height: 100%;
        }

        @keyframes academic-fadeInUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .academic-news-carousel {
            position: relative;
            height: 340px;
            border-radius: 14px;
            overflow: hidden;
            box-shadow: 0 8px 25px rgba(0,0,0,0.08);
            background: var(--ac-bg);
            display: flex;
            border: 1px solid rgba(0,0,0,0.05);
        }

        .academic-news-content {
            flex: 0 0 70%;
            position: relative;
            background: var(--ac-bg);
            overflow: hidden;
        }

        .academic-news-achievements {
            position: relative;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 15px;
        }

        .academic-news-card {
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

        .academic-news-card.active {
            opacity: 1;
            transform: translateY(0) scale(1);
            pointer-events: all;
            z-index: 2;
        }

        .academic-news-card.prev,
        .academic-news-card.next {
            z-index: 1;
        }

        .academic-news-card.prev { transform: translateY(-30px) scale(0.95); }
        .academic-news-card.next { transform: translateY(30px) scale(0.95); }

        .academic-news-date {
            color: var(--ac-secondary);
            font-size: 16px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin: 0 0 15px 0;
            display: inline-block;
            position: relative;
            padding-left: 24px;
        }

        .academic-news-date::before {
            content: '';
            position: absolute;
            left: 0;
            top: 50%;
            transform: translateY(-50%);
            width: 14px;
            height: 3px;
            background: var(--ac-secondary);
        }

        .academic-news-title {
            font-size: 24px;
            font-weight: 700;
            margin: 0 0 20px 0;
            color: var(--ac-primary);
            line-height: 1.3;
        }

        .academic-news-description {
            font-size: 16px;
            line-height: 1.7;
            color: #5a6c7d;
            margin: 0 0 25px 0;
        }

        .academic-news-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 0;
            padding: 0;
            list-style: none;
        }

        .academic-news-tag {
            display: inline-block;
            padding: 6px 15px;
            background: rgba(52, 152, 219, 0.1);
            color: var(--ac-secondary);
            border-radius: 20px;
            font-size: 13px;
            font-weight: 600;
            border: 1px solid rgba(52, 152, 219, 0.2);
            transition: all 0.3s ease;
            margin: 0;
        }

        .academic-news-tag:hover {
            background: var(--ac-secondary);
            color: white;
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(52, 152, 219, 0.3);
        }

        .academic-news-timeline {
            flex: 0 0 30%;
            background: linear-gradient(160deg, #2c3e50 0%, #1a2530 100%);
            position: relative;
            display: flex;
            align-items: center;
            overflow: hidden;
        }

        .academic-news-timeline-wrapper {
            width: 100%;
            height: 100%;
            position: relative;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 30px 15px;
        }

        .academic-news-timeline-container {
            position: relative;
            width: 100%;
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            gap: 100px;
            transition: transform 0.6s cubic-bezier(0.4, 0, 0.2, 1);
            overflow-y: auto;
            scrollbar-width: none;
        }

        .academic-news-timeline-container::-webkit-scrollbar { display: none; }

        .academic-news-timeline-item {
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

        .academic-news-timeline-item.position-prev {
            transform: translateY(-85px) scale(0.85);
            opacity: 0.4;
            pointer-events: all;
        }

        .academic-news-timeline-item.position-current {
            transform: translateY(0) scale(1);
            opacity: 1;
            pointer-events: all;
        }

        .academic-news-timeline-item.position-next {
            transform: translateY(85px) scale(0.85);
            opacity: 0.4;
            pointer-events: all;
        }

        .academic-news-timeline-item::before {
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

        .academic-news-timeline-item.position-current::before {
            width: 16px;
            height: 16px;
            background: var(--ac-secondary);
            border-color: var(--ac-bg);
            box-shadow: 0 0 0 4px rgba(52, 152, 219, 0.3);
            top: 4px;
        }

        .academic-news-timeline-date {
            color: var(--ac-text-light);
            font-weight: 700;
            margin: 0 0 5px 0;
            font-size: 14px;
            transition: all 0.5s ease;
        }

        .academic-news-timeline-item.position-current .academic-news-timeline-date {
            font-size: 15px;
            color: #3498db;
        }

        .academic-news-timeline-title {
            color: rgba(255, 255, 255, 0.7);
            font-size: 14px;
            line-height: 1.4;
            transition: all 0.5s ease;
            margin: 0;
        }

        .academic-news-timeline-item.position-current .academic-news-timeline-title {
            color: rgba(255, 255, 255, 0.95);
            font-size: 15px;
        }

        .academic-news-timeline-line {
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

        .academic-news-nav-controls {
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

        .academic-news-wrapper:hover .academic-news-nav-controls {
            opacity: 1;
        }

        .academic-news-nav-button {
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

        .academic-news-nav-button:hover:not(:disabled) {
            transform: translateY(-3px);
            box-shadow: 0 7px 20px rgba(0, 0, 0, 0.18);
            background: var(--ac-secondary);
            color: white;
        }

        .academic-news-nav-button:disabled {
            opacity: 0.4;
            cursor: not-allowed;
        }

        .academic-news-counter {
            font-size: 15px;
            color: var(--ac-gray);
            font-weight: 600;
            background: white;
            padding: 8px 20px;
            border-radius: 20px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.07);
            margin: 0;
        }

        .academic-news-current-num {
            color: var(--ac-secondary);
            font-weight: 700;
            font-size: 16px;
        }

        @media (max-width: 900px) {
            .academic-news-carousel {
                height: 600px;
                flex-direction: column;
            }

            .academic-news-content { flex: 0 0 60%; }
            .academic-news-timeline { flex: 0 0 40%; }
            .academic-news-card { padding: 25px; }
            .academic-news-title { font-size: 22px; }

            .academic-news-timeline-wrapper { flex-direction: row; padding: 15px; }
            .academic-news-timeline-container { flex-direction: row; gap: 15px; }

            .academic-news-timeline-item.position-prev { transform: translateX(-100px) scale(0.85); }
            .academic-news-timeline-item.position-next { transform: translateX(100px) scale(0.85); }
            .academic-news-timeline-line { display: none; }

            .academic-news-nav-controls {
                bottom: 15px;
                opacity: 1;
                padding: 10px 25px;
            }
        }

        @media (max-width: 600px) {
            .header h1 {
                font-size: 2.2rem;
            }

            .header p {
                font-size: 1rem;
            }

            .academic-news-card { padding: 20px; }
            .academic-news-title { font-size: 20px; }
            .academic-news-description { font-size: 14px; }
            .academic-news-tag { padding: 5px 12px; font-size: 12px; }
            .academic-news-carousel { height: 650px; }
        }

        .footer {
            text-align: center;
            color: #5a6c7d;
            margin-top: 30px;
            font-size: 0.9rem;
            padding: 20px;
        }

        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin: 40px 0;
        }

        .feature-card {
            background: white;
            border-radius: 10px;
            padding: 20px;
            width: 200px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            transition: all 0.3s ease;
        }

        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
        }

        .feature-card i {
            font-size: 2rem;
            color: #3498db;
            margin-bottom: 15px;
        }

        .feature-card h3 {
            color: #2c3e50;
            margin-bottom: 10px;
        }

        .feature-card p {
            color: #5a6c7d;
            font-size: 0.9rem;
        }
    </style>
</head>
    <!-- 封装后的新闻模块 -->
    <div class="academic-news-container">
        <div class="academic-news-wrapper">
            <div class="academic-news-carousel">
                <!-- 左侧内容面板 -->
                <div class="academic-news-content">
                    <div class="academic-news-achievements">
                        <div class="academic-news-card active" data-index="0">
                            <div class="academic-news-date">2025-3</div>
                            <h3 class="academic-news-title">Our paper was accepted by IJCNN2025</h3>
                            <p class="academic-news-description">
                                Our research result "SWR-BIDeN: An Improved BIDeN Model for Severe Weather Removal in Image Processing" was accepted by the International Joint Conference on Neural Networks (IJCNN2025).
                                The model achieved advanced performance in image restoration tasks under severe weather conditions such as heavy rain and haze.
                            </p>
                            <div class="academic-news-tags">
                                <span class="academic-news-tag">CCF-C</span>
                                <span class="academic-news-tag">Image Processing</span>
                                <span class="academic-news-tag">CV</span>
                                <span class="academic-news-tag">IJCNN2025</span>
                            </div>
                        </div>

                        <div class="academic-news-card" data-index="1">
                            <div class="academic-news-date">2025-4</div>
                            <h3 class="academic-news-title">Our paper was accepted by ICIC2025</h3>
                            <p class="academic-news-description">
                                Our research result "LightDrone-YOLO: A Novel Lightweight and Efficient Object Detection Network for Unmanned Aerial Vehicles" was accepted by the International Conference on Intelligent Computing (ICIC2025).
                                This model significantly reduces the computational complexity while maintaining high accuracy, and is suitable for resource-constrained UAV platforms.
                            </p>
                            <div class="academic-news-tags">
                                <span class="academic-news-tag">CCF-C</span>
                                <span class="academic-news-tag">Object Detection</span>
                                <span class="academic-news-tag">UVA</span>
                                <span class="academic-news-tag">ICIC2025</span>
                            </div>
                        </div>

                        <div class="academic-news-card" data-index="2">
                            <div class="academic-news-date">2025-4</div>
                            <h3 class="academic-news-title">Our paper was accepted by ICIC2025</h3>
                            <p class="academic-news-description">
                                Our research result "Lightweight Remote Sensing Image Change Detection Based on Global Feature Fusion" was accepted by the International Conference on Intelligent Computing (ICIC2025).
                                This method significantly reduces the computational complexity while maintaining high accuracy.
                            </p>
                            <div class="academic-news-tags">
                                <span class="academic-news-tag">CCF-C</span>
                                <span class="academic-news-tag">Remote Sensing</span>
                                <span class="academic-news-tag">CV</span>
                                <span class="academic-news-tag">ICIC2025</span>
                            </div>
                        </div>

                        <div class="academic-news-card" data-index="3">
                            <div class="academic-news-date">2025-4</div>
                            <h3 class="academic-news-title">Our paper was accepted by ICIC2025</h3>
                            <p class="academic-news-description">
                                Our research result "GlintNet: A Lightweight Global-Local Integration Network with Spatial-Channel Mixed Attention for ReID" was accepted by the International Conference on Intelligent Computing (ICIC2025).
                                The model has reached advanced levels in multiple pedestrian re-identification benchmarks.
                            </p>
                            <div class="academic-news-tags">
                                <span class="academic-news-tag">CCF-C</span>
                                <span class="academic-news-tag">Re-ID</span>
                                <span class="academic-news-tag">CV</span>
                                <span class="academic-news-tag">ICIC2025</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 右侧时间轴面板 -->
                <div class="academic-news-timeline">
                    <div class="academic-news-timeline-line"></div>
                    <div class="academic-news-timeline-wrapper">
                        <div class="academic-news-timeline-container" id="academicTimelineContainer"></div>
                    </div>
                </div>
            </div>

            <!-- 导航控制 -->
            <div class="academic-news-nav-controls">
                <button class="academic-news-nav-button" id="academicPrevBtn">
                    <i class="fas fa-chevron-left"></i>
                </button>
                <div class="academic-news-counter">
                    <span class="academic-news-current-num" id="academicCurrentNum">1</span> /
                    <span id="academicTotalNum">4</span>
                </div>
                <button class="academic-news-nav-button" id="academicNextBtn">
                    <i class="fas fa-chevron-right"></i>
                </button>
            </div>
        </div>
    </div>
</div>

<script>
    (function() {
        document.addEventListener('DOMContentLoaded', function() {
            const timelineData = [
                { date: '2025-03', title: 'Our paper was accepted by IJCNN2025' },
                { date: '2025-04', title: 'Our paper was accepted by ICIC2025' },
                { date: '2025-04', title: 'Our paper was accepted by ICIC2025' },
                { date: '2025-04', title: 'Our paper was accepted by ICIC2025' }
            ];

            // 使用组件容器作为作用域
            const container = document.querySelector('.academic-news-container');
            if (!container) return;

            const wrapper = container.querySelector('.academic-news-wrapper');
            const achievementCards = container.querySelectorAll('.academic-news-card');
            const timelineContainer = container.querySelector('#academicTimelineContainer');
            const prevBtn = container.querySelector('#academicPrevBtn');
            const nextBtn = container.querySelector('#academicNextBtn');
            const currentNum = container.querySelector('#academicCurrentNum');
            const totalNum = container.querySelector('#academicTotalNum');

            let currentIndex = 0;
            let autoPlayInterval;
            const totalItems = achievementCards.length;

            // 组件初始化
            function initComponent() {
                totalNum.textContent = totalItems;
                createTimelineItems();
                updateDisplay(0);
                startAutoPlay();
                setupEventListeners();
            }

            // 创建时间轴项目
            function createTimelineItems() {
                timelineData.forEach((item, index) => {
                    const timelineItem = document.createElement('div');
                    timelineItem.className = 'academic-news-timeline-item';
                    timelineItem.setAttribute('data-index', index);
                    timelineItem.innerHTML = `
                            <div class="academic-news-timeline-date">${item.date}</div>
                            <div class="academic-news-timeline-title">${item.title}</div>
                        `;
                    timelineItem.addEventListener('click', () => goToIndex(index));
                    timelineContainer.appendChild(timelineItem);
                });
                updateTimelinePositions();
            }

            // 更新显示状态
            function updateDisplay(index) {
                achievementCards.forEach((card, i) => {
                    card.classList.remove('active', 'prev', 'next');
                    if (i === index) card.classList.add('active');
                    else if (i < index) card.classList.add('prev');
                    else card.classList.add('next');
                });
                updateTimelinePositions();
                currentNum.textContent = index + 1;
                prevBtn.disabled = index === 0;
                nextBtn.disabled = index === totalItems - 1;
            }

            // 更新时间轴位置
            function updateTimelinePositions() {
                const items = timelineContainer.querySelectorAll('.academic-news-timeline-item');
                items.forEach((item, i) => {
                    item.classList.remove('position-prev', 'position-current', 'position-next');
                    if (i === currentIndex - 1) item.classList.add('position-prev');
                    else if (i === currentIndex) item.classList.add('position-current');
                    else if (i === currentIndex + 1) item.classList.add('position-next');
                });
            }

            // 导航功能
            function goToIndex(index) {
                if (index >= 0 && index < totalItems) {
                    currentIndex = index;
                    updateDisplay(currentIndex);
                }
            }

            function goPrev() {
                if (currentIndex > 0) goToIndex(currentIndex - 1);
            }

            function goNext() {
                if (currentIndex < totalItems - 1) goToIndex(currentIndex + 1);
                else goToIndex(0);
            }

            // 自动播放控制
            function startAutoPlay() {
                autoPlayInterval = setInterval(goNext, 3000);
            }

            function stopAutoPlay() {
                clearInterval(autoPlayInterval);
            }

            // 事件监听器设置
            function setupEventListeners() {
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

                wrapper.addEventListener('mouseenter', stopAutoPlay);
                wrapper.addEventListener('mouseleave', startAutoPlay);

                // 键盘控制
                document.addEventListener('keydown', (e) => {
                    if (e.key === 'ArrowLeft') goPrev();
                    else if (e.key === 'ArrowRight') goNext();
                });

                // 触摸滑动支持
                let touchStartX = 0;
                wrapper.addEventListener('touchstart', (e) => {
                    touchStartX = e.changedTouches[0].screenX;
                });

                wrapper.addEventListener('touchend', (e) => {
                    const touchEndX = e.changedTouches[0].screenX;
                    const diffX = touchStartX - touchEndX;
                    if (Math.abs(diffX) > 50) {
                        diffX > 0 ? goNext() : goPrev();
                    }
                });

                // 时间轴滚轮滚动
                timelineContainer.addEventListener('wheel', (e) => {
                    e.preventDefault();
                    e.deltaY > 0 ? goNext() : goPrev();
                });
            }

            // 初始化组件
            initComponent();
        });
    })();
</script>
</body>
</html>

