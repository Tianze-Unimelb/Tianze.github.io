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
    <title>学术成就时间轴</title>
    <style>
.academic-timeline-wrapper {
    --ac-primary: #2c3e50;
    --ac-secondary: #3498db;
    --ac-text-light: #ecf0f1;
    --ac-bg: #fff;
    --ac-gray-light: #f8f9fa;
    --ac-gray: #6c757d;
    --ac-shadow: 0 10px 30px rgba(0,0,0,0.1);
    --ac-shadow-hover: 0 15px 40px rgba(0,0,0,0.15);
    
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
    color: #333;
    overflow: hidden;
    padding: 10px 10px;
    margin: 20px 0;
    border-radius: 12px;
    box-sizing: border-box;
}

.academic-timeline-wrapper * {
    box-sizing: border-box;
}

/* 主容器 */
.academic-timeline-wrapper .academic-showcase {
    width: 100%;
    max-width: 900px;
    margin: 0 auto;
    animation: fadeInUp 0.8s ease-out;
}

.academic-timeline-wrapper .section-title {
    text-align: center;
    font-size: 36px;
    font-weight: 300;
    margin: 0 0 50px 0;
    color: var(--ac-primary);
    position: relative;
}

.academic-timeline-wrapper .section-title::after {
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
.academic-timeline-wrapper .carousel-container {
    position: relative;
    height: 325px;
    border-radius: 16px;
    overflow: hidden;
    box-shadow: var(--ac-shadow);
    background: var(--ac-bg);
    display: flex;
}

/* 左侧成就展示区 */
.academic-timeline-wrapper .content-panel {
    flex: 0 0 70%;
    position: relative;
    background: var(--ac-bg);
    overflow: hidden;
}

.academic-timeline-wrapper .achievement-wrapper {
    position: relative;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
}

.academic-timeline-wrapper .achievement-card {
    position: absolute;
    width: 90%;
    max-width: 600px;
    padding: 35px;
    opacity: 0;
    transform: translateY(30px) scale(0.95);
    transition: all 0.6s cubic-bezier(0.4, 0, 0.2, 1);
    pointer-events: none;
    margin: 0;
}

.academic-timeline-wrapper .achievement-card.active {
    opacity: 1;
    transform: translateY(0) scale(1);
    pointer-events: all;
}

.academic-timeline-wrapper .achievement-card.prev {
    transform: translateY(-30px) scale(0.95);
}

.academic-timeline-wrapper .achievement-card.next {
    transform: translateY(30px) scale(0.95);
}

.academic-timeline-wrapper .achievement-date {
    color: var(--ac-secondary);
    font-size: 13px;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1px;
    margin: 0 0 10px 0;
    display: inline-block;
    position: relative;
    padding-left: 22px;
}

.academic-timeline-wrapper .achievement-date::before {
    content: '';
    position: absolute;
    left: 0;
    top: 50%;
    transform: translateY(-50%);
    width: 12px;
    height: 2px;
    background: var(--ac-secondary);
}

.academic-timeline-wrapper .achievement-title {
    font-size: 22px;
    font-weight: 700;
    margin: 0 0 15px 0;
    color: var(--ac-primary);
    line-height: 1.3;
}

.academic-timeline-wrapper .achievement-description {
    font-size: 14px;
    line-height: 1.6;
    color: #5a6c7d;
    margin: 0 0 20px 0;
}

.academic-timeline-wrapper .achievement-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin: 0;
    padding: 0;
    list-style: none;
}

.academic-timeline-wrapper .tag {
    display: inline-block;
    padding: 4px 12px;
    background: rgba(52, 152, 219, 0.1);
    color: var(--ac-secondary);
    border-radius: 16px;
    font-size: 12px;
    font-weight: 500;
    border: 1px solid rgba(52, 152, 219, 0.2);
    transition: all 0.3s ease;
    margin: 0;
}

.academic-timeline-wrapper .tag:hover {
    background: var(--ac-secondary);
    color: white;
    transform: translateY(-1px);
    box-shadow: 0 3px 10px rgba(52, 152, 219, 0.3);
}

/* 右侧时间轴面板 */
.academic-timeline-wrapper .timeline-panel {
    flex: 0 0 30%;
    background: var(--ac-primary);
    position: relative;
    display: flex;
    align-items: center;
    overflow: hidden;
}

.academic-timeline-wrapper .timeline-wrapper {
    width: 100%;
    height: 70%;
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 30px 20px;
}

.academic-timeline-wrapper .timeline-container {
    position: relative;
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 25px;
    transition: transform 0.6s cubic-bezier(0.4, 0, 0.2, 1);
}

.academic-timeline-wrapper .timeline-item {
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

.academic-timeline-wrapper .timeline-item.position-prev {
    transform: translateY(-65px) scale(0.85);
    opacity: 0.4;
    pointer-events: all;
}

.academic-timeline-wrapper .timeline-item.position-current {
    transform: translateY(0) scale(1);
    opacity: 1;
    pointer-events: all;
}

.academic-timeline-wrapper .timeline-item.position-next {
    transform: translateY(65px) scale(0.85);
    opacity: 0.4;
    pointer-events: all;
}

.academic-timeline-wrapper .timeline-item::before {
    content: '';
    position: absolute;
    left: 0;
    top: 6px;
    width: 10px;
    height: 10px;
    background: rgba(255, 255, 255, 0.3);
    border-radius: 50%;
    border: 2px solid rgba(255, 255, 255, 0.5);
    transition: all 0.5s ease;
}

.academic-timeline-wrapper .timeline-item.position-current::before {
    width: 14px;
    height: 14px;
    background: var(--ac-secondary);
    border-color: var(--ac-bg);
    box-shadow: 0 0 0 3px rgba(52, 152, 219, 0.3);
    top: 3px;
}

.academic-timeline-wrapper .timeline-date {
    color: var(--ac-text-light);
    font-weight: 600;
    margin: 0 0 4px 0;
    font-size: 12px;
    transition: all 0.5s ease;
}

.academic-timeline-wrapper .timeline-item.position-current .timeline-date {
    font-size: 14px;
}

.academic-timeline-wrapper .timeline-title {
    color: rgba(255, 255, 255, 0.7);
    font-size: 11px;
    line-height: 1.3;
    transition: all 0.5s ease;
    margin: 0;
}

.academic-timeline-wrapper .timeline-item.position-current .timeline-title {
    color: rgba(255, 255, 255, 0.9);
    font-size: 12px;
}

/* 连接线 */
.academic-timeline-wrapper .timeline-line {
    position: absolute;
    left: 35px;
    top: 50%;
    transform: translateY(-50%);
    width: 2px;
    height: 130px;
    background: linear-gradient(to bottom,
    transparent 0%,
    rgba(255,255,255,0.2) 30%,
    rgba(52,152,219,0.5) 50%,
    rgba(255,255,255,0.2) 70%,
    transparent 100%);
    pointer-events: none;
}

/* 导航控制 */
.academic-timeline-wrapper .nav-controls {
    position: absolute;
    bottom: 30px;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    align-items: center;
    gap: 25px;
    z-index: 10;
}

.academic-timeline-wrapper .nav-button {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background: rgba(255, 255, 255, 0.95);
    border: none;
    box-shadow: 0 3px 12px rgba(0, 0, 0, 0.1);
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: all 0.3s ease;
    font-size: 16px;
    color: var(--ac-gray);
    padding: 0;
    margin: 0;
}

.academic-timeline-wrapper .nav-button:hover:not(:disabled) {
    transform: translateY(-2px);
    box-shadow: 0 5px 16px rgba(0, 0, 0, 0.15);
    background: white;
    color: var(--ac-secondary);
}

.academic-timeline-wrapper .nav-button:disabled {
    opacity: 0.3;
    cursor: not-allowed;
}

.academic-timeline-wrapper .progress-counter {
    font-size: 13px;
    color: var(--ac-gray);
    font-weight: 500;
    background: white;
    padding: 6px 16px;
    border-radius: 16px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
    margin: 0;
}

.academic-timeline-wrapper .current-number {
    color: var(--ac-secondary);
    font-weight: 700;
    font-size: 14px;
}

/* 边缘渐变效果 */
.academic-timeline-wrapper .timeline-panel::before,
.academic-timeline-wrapper .timeline-panel::after {
    content: '';
    position: absolute;
    left: 0;
    right: 0;
    height: 60px;
    pointer-events: none;
    z-index: 1;
}

.academic-timeline-wrapper .timeline-panel::before {
    top: 0;
    background: linear-gradient(to bottom, var(--ac-primary) 0%, transparent 100%);
}

.academic-timeline-wrapper .timeline-panel::after {
    bottom: 0;
    background: linear-gradient(to top, var(--ac-primary) 0%, transparent 100%);
}

/* 响应式设计 */
@media (max-width: 768px) {
    .academic-timeline-wrapper .academic-showcase {
        width: 95%;
    }

    .academic-timeline-wrapper .carousel-container {
        height: 325px;
        flex-direction: column;
    }

    .academic-timeline-wrapper .content-panel {
        flex: 0 0 65%;
        min-height: auto;
    }

    .academic-timeline-wrapper .timeline-panel {
        flex: 0 0 35%;
        width: 100%;
        height: auto;
    }

    .academic-timeline-wrapper .achievement-card {
        padding: 25px;
    }

    .academic-timeline-wrapper .achievement-title {
        font-size: 20px;
    }

    .academic-timeline-wrapper .timeline-wrapper {
        flex-direction: row;
        height: 100%;
        padding: 15px;
    }

    .academic-timeline-wrapper .timeline-container {
        flex-direction: row;
    }

    .academic-timeline-wrapper .timeline-item.position-prev {
        transform: translateX(-100px) scale(0.85);
    }

    .academic-timeline-wrapper .timeline-item.position-current {
        transform: translateX(0) scale(1);
    }

    .academic-timeline-wrapper .timeline-item.position-next {
        transform: translateX(100px) scale(0.85);
    }

    .academic-timeline-wrapper .timeline-line {
        display: none;
    }

    .academic-timeline-wrapper .nav-controls {
        bottom: 15px;
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
</style>
</head>
<body>
<div class="academic-timeline-wrapper">
    <div class="academic-showcase">
        <div class="carousel-container">
            <!-- 左侧内容面板 - 70% -->
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

            <!-- 右侧时间轴面板 - 30% -->
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
                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5">
                    <path d="M15 18l-6-6 6-6"/>
                </svg>
            </button>
            <div class="progress-counter">
                <span class="current-number" id="currentNum">1</span> / <span id="totalNum">4</span>
            </div>
            <button class="nav-button" id="nextBtn">
                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5">
                    <path d="M9 18l6-6-6-6"/>
                </svg>
            </button>
        </div>
    </div>
</div>

<script>
    (function() {
        // 使用立即执行函数避免全局变量污染
        
        // 时间轴数据
        const timelineData = [
            { date: '2025-03', title: 'Our work was accepted by IJCNN2025' },
            { date: '2025-04', title: 'Our work was accepted by ICIC2025' },
            { date: '2025-04', title: 'Our work was accepted by ICIC2025' },
            { date: '2025-04', title: 'Our work was accepted by ICIC2025' }
        ];

        // 初始化变量 - 使用容器内的元素查询
        let currentIndex = 0;
        const wrapper = document.querySelector('.academic-timeline-wrapper');
        const achievementCards = wrapper.querySelectorAll('.achievement-card');
        const timelineContainer = wrapper.querySelector('#timelineContainer');
        const prevBtn = wrapper.querySelector('#prevBtn');
        const nextBtn = wrapper.querySelector('#nextBtn');
        const currentNum = wrapper.querySelector('#currentNum');
        const totalNum = wrapper.querySelector('#totalNum');
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

        // 键盘控制 - 只在元素获得焦点时才响应
        wrapper.addEventListener('keydown', (e) => {
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

        // 使wrapper可以获得焦点
        wrapper.setAttribute('tabindex', '0');

        // 鼠标滚轮控制 - 仅在容器内部
        let isScrolling = false;
        const carouselContainer = wrapper.querySelector('.carousel-container');

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

        // 窗口大小改变时调整
        window.addEventListener('resize', () => {
            updateTimelinePositions();
        });

        // 添加平滑过渡
        function smoothTransition() {
            const items = timelineContainer.querySelectorAll('.timeline-item');
            items.forEach((item) => {
                item.style.transition = 'all 0.5s cubic-bezier(0.4, 0, 0.2, 1)';
            });
        }

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

        // 初始化
        createTimelineItems();
        updateDisplay(0);
        smoothTransition();

        // 预加载动画
        setTimeout(() => {
            wrapper.querySelector('.academic-showcase').style.opacity = '1';
        }, 100);

    })();
</script>
</body>
</html>
