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

<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>学术成果轮播</title>
    <style>
        /* 新增箭头隐藏样式 */
        .nav-arrows {
            opacity: 0;
            visibility: hidden;
            transition: all 0.3s ease;
        }

        .carousel-container:hover .nav-arrows {
            opacity: 1;
            visibility: visible;
        }

        /* 保持原有其他样式不变 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #f0f2f5;
            font-family: 'Arial', sans-serif;
        }

        .carousel-container {
            width: 750px;
            height: 325px;
            position: relative;
            overflow: hidden;
            border-radius: 12px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }

        .content-carousel {
            position: absolute;
            width: 73%;
            height: 100%;
            left: 0;
            display: flex;
            transition: transform 0.6s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .content-item {
            min-width: 100%;
            padding: 40px;
            background: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            opacity: 0;
            transform: scale(0.9);
            transition: all 0.6s ease;
        }

        .content-item.active {
            opacity: 1;
            transform: scale(1);
        }

        .timeline-carousel {
            position: absolute;
            width: 27%;
            height: 100%;
            right: 0;
            background: #2c3e50;
            padding: 40px;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        .timeline-item {
            position: relative;
            padding-left: 30px;
            margin: 25px 0;
            opacity: 0.3;
            transition: all 0.4s ease;
        }

        .timeline-item::before {
            content: '';
            position: absolute;
            left: 0;
            top: 5px;
            width: 12px;
            height: 12px;
            background: #3498db;
            border-radius: 50%;
            border: 2px solid white;
        }

        .timeline-item.active {
            opacity: 1;
            transform: translateX(10px);
        }

        .timeline-date {
            color: #ecf0f1;
            font-weight: bold;
            margin-bottom: 5px;
        }

        .timeline-desc {
            color: #bdc3c7;
            font-size: 0.9em;
        }

        .nav-arrows {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            width: 100%;
            display: flex;
            justify-content: space-between;
            padding: 0 20px;
            z-index: 2;
        }

        .arrow {
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

        .arrow:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
<div class="carousel-container">
    <!-- 保持原有结构不变 -->
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

<script>
    // 新增自动轮播逻辑
    let autoPlayTimer;
    const intervalDuration = 5000; // 5秒间隔

    function startAutoPlay() {
        autoPlayTimer = setInterval(() => {
            slide(1);
        }, intervalDuration);
    }

    function resetAutoPlay() {
        clearInterval(autoPlayTimer);
        startAutoPlay();
    }

    // 修改原有slide函数
    function slide(direction) {
        currentIndex = (currentIndex + direction + items.length) % items.length;
        document.querySelector('.content-carousel').style.transform =
            `translateX(-${currentIndex * 100}%)`;
        updateActive();
        resetAutoPlay(); // 每次操作后重置计时器
    }

    // 添加鼠标事件
    const carousel = document.querySelector('.carousel-container');
    carousel.addEventListener('mouseenter', () => clearInterval(autoPlayTimer));
    carousel.addEventListener('mouseleave', startAutoPlay);

    // 初始化自动播放
    startAutoPlay();

    // 保持原有其他逻辑不变
    const items = document.querySelectorAll('.content-item');
    const timelineItems = document.querySelectorAll('.timeline-item');
    const prevBtn = document.querySelector('.prev');
    const nextBtn = document.querySelector('.next');
    let currentIndex = 0;

    function updateActive() {
        items.forEach((item, index) => {
            item.classList.toggle('active', index === currentIndex);
        });

        timelineItems.forEach((item, index) => {
            item.classList.toggle('active', index === currentIndex);
        });
    }

    prevBtn.addEventListener('click', () => slide(-1));
    nextBtn.addEventListener('click', () => slide(1));

    document.addEventListener('keydown', (e) => {
        if (e.key === 'ArrowLeft') slide(-1);
        if (e.key === 'ArrowRight') slide(1);
    });
</script>
</body>
</html>
