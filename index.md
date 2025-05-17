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

<style>
/* 组件容器（确保唯一性） */
.academic-carousel {
    --ac-primary: #2c3e50;
    --ac-secondary: #3498db;
    --ac-text-light: #ecf0f1;
    --ac-bg: #fff;
    font-family: inherit;
    max-width: 750px;
    margin: 20px auto;
}

/* 作用域样式 */
.academic-carousel * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.academic-carousel .carousel-container {
    position: relative;
    height: 325px;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

.academic-carousel .content-carousel {
    position: absolute;
    width: 73%;
    height: 100%;
    left: 0;
    transition: transform 0.6s cubic-bezier(0.4, 0, 0.2, 1);
}

.academic-carousel .content-item {
    min-width: 100%;
    padding: 40px;
    background: var(--ac-bg);
    display: flex;
    flex-direction: column;
    justify-content: center;
    opacity: 0;
    transform: scale(0.9);
    transition: all 0.6s ease;
}

.academic-carousel .content-item.active {
    opacity: 1;
    transform: scale(1);
}

.academic-carousel .content-item h2 {
    color: var(--ac-primary);
    margin-bottom: 15px;
    font-size: 1.8em;
}

.academic-carousel .content-item p {
    color: #666;
    line-height: 1.6;
}

.academic-carousel .timeline-carousel {
    position: absolute;
    width: 27%;
    height: 100%;
    right: 0;
    background: var(--ac-primary);
    padding: 40px;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.academic-carousel .timeline-item {
    position: relative;
    padding-left: 30px;
    margin: 25px 0;
    opacity: 0.3;
    transition: all 0.4s ease;
    cursor: pointer;
}

.academic-carousel .timeline-item::before {
    content: '';
    position: absolute;
    left: 0;
    top: 5px;
    width: 12px;
    height: 12px;
    background: var(--ac-secondary);
    border-radius: 50%;
    border: 2px solid var(--ac-bg);
}

.academic-carousel .timeline-item.active {
    opacity: 1;
    transform: translateX(10px);
}

.academic-carousel .timeline-date {
    color: var(--ac-text-light);
    font-weight: bold;
    margin-bottom: 5px;
}

.academic-carousel .timeline-desc {
    color: rgba(255,255,255,0.7);
    font-size: 0.9em;
}

.academic-carousel .nav-arrows {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    width: 100%;
    display: flex;
    justify-content: space-between;
    padding: 0 20px;
    z-index: 2;
    opacity: 0;
    visibility: hidden;
    transition: opacity 0.3s ease;
}

.academic-carousel:hover .nav-arrows {
    opacity: 1;
    visibility: visible;
}

.academic-carousel .arrow {
    cursor: pointer;
    width: 40px;
    height: 40px;
    background: rgba(255,255,255,0.9);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    transition: transform 0.3s ease;
}

.academic-carousel .arrow:hover {
    transform: scale(1.1);
}

/* 响应式设计 */
@media (max-width: 768px) {
    .academic-carousel {
        max-width: 95%;
    }
    
    .academic-carousel .carousel-container {
        height: 500px;
    }
    
    .academic-carousel .content-carousel,
    .academic-carousel .timeline-carousel {
        width: 100%;
        height: 70%;
    }
    
    .academic-carousel .timeline-carousel {
        top: 70%;
        height: 30%;
        flex-direction: row;
        padding: 15px;
    }
    
    .academic-carousel .timeline-item {
        margin: 0 15px;
        padding-left: 20px;
    }
}
</style>

<div class="academic-carousel">
    <div class="carousel-container">
        <div class="content-carousel">
            <div class="content-item active">
                <h2>量子计算新突破</h2>
                <p>在《Nature》发表量子比特稳定性研究成果，实现误差率降低40%...</p>
            </div>
            <div class="content-item">
                <h2>人工智能算法优化</h2>
                <p>开发新型神经网络架构，在ImageNet数据集上达到98.7%准确率...</p>
            </div>
            <div class="content-item">
                <h2>学术会议主题演讲</h2>
                <p>在ICML 2024大会发表关于联邦学习的前沿技术报告...</p>
            </div>
        </div>
        
        <div class="timeline-carousel">
            <div class="timeline-item active">
                <div class="timeline-date">2024-03</div>
                <div class="timeline-desc">论文发表</div>
            </div>
            <div class="timeline-item">
                <div class="timeline-date">2024-02</div>
                <div class="timeline-desc">算法优化</div>
            </div>
            <div class="timeline-item">
                <div class="timeline-date">2024-01</div>
                <div class="timeline-desc">学术报告</div>
            </div>
        </div>
        
        <div class="nav-arrows">
            <div class="arrow prev">←</div>
            <div class="arrow next">→</div>
        </div>
    </div>
</div>

<script>
(function() {
    // 组件初始化
    const container = document.querySelector('.academic-carousel');
    if (!container) return;

    // 配置参数
    const config = {
        interval: 5000,
        keyboard: true,
        hoverPause: true
    };

    // 组件状态
    let currentIndex = 0;
    let autoPlayTimer;
    
    // DOM元素
    const items = container.querySelectorAll('.content-item');
    const timelineItems = container.querySelectorAll('.timeline-item');
    const prevBtn = container.querySelector('.prev');
    const nextBtn = container.querySelector('.next');
    const carousel = container.querySelector('.carousel-container');

    // 核心功能
    function updateActive() {
        items.forEach((item, i) => item.classList.toggle('active', i === currentIndex));
        timelineItems.forEach((item, i) => item.classList.toggle('active', i === currentIndex));
    }

    function slide(direction) {
        currentIndex = (currentIndex + direction + items.length) % items.length;
        container.querySelector('.content-carousel').style.transform = 
            `translateX(-${currentIndex * 100}%)`;
        updateActive();
        resetAutoPlay();
    }

    // 自动播放控制
    function startAutoPlay() {
        if (!autoPlayTimer) {
            autoPlayTimer = setInterval(() => slide(1), config.interval);
        }
    }

    function resetAutoPlay() {
        clearInterval(autoPlayTimer);
        autoPlayTimer = null;
        startAutoPlay();
    }

    // 事件绑定
    function initEvents() {
        // 箭头控制
        prevBtn.addEventListener('click', () => slide(-1));
        nextBtn.addEventListener('click', () => slide(1));
        
        // 时间轴点击
        timelineItems.forEach((item, index) => {
            item.addEventListener('click', () => {
                currentIndex = index;
                container.querySelector('.content-carousel').style.transform = 
                    `translateX(-${currentIndex * 100}%)`;
                updateActive();
                resetAutoPlay();
            });
        });

        // 键盘导航
        if (config.keyboard) {
            document.addEventListener('keydown', (e) => {
                if (document.activeElement === document.body) {
                    if (e.key === 'ArrowLeft') slide(-1);
                    if (e.key === 'ArrowRight') slide(1);
                }
            });
        }

        // 悬停暂停
        if (config.hoverPause) {
            carousel.addEventListener('mouseenter', () => clearInterval(autoPlayTimer));
            carousel.addEventListener('mouseleave', startAutoPlay);
        }
    }

    // 初始化
    function init() {
        updateActive();
        initEvents();
        startAutoPlay();
    }

    init();
})();
</script>

