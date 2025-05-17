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
    <title>Academic Carousel</title>
    <style>
        .academic-carousel {
            --ac-primary: #2c3e50;
            --ac-secondary: #3498db;
            --ac-text-light: #ecf0f1;
            --ac-bg: #fff;
            font-family: system-ui, -apple-system, sans-serif;
            max-width: 750px;
            margin: 20px auto;
        }

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
            background: white;
        }

        .academic-carousel .content-carousel {
            display: flex;
            position: absolute;
            width: 73%;
            height: 100%;
            left: 0;
            transition: transform 0.6s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .academic-carousel .content-item {
            flex: 0 0 100%;
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
            font-size: 0.95em;
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
            overflow-y: auto;
            scroll-behavior: smooth;
            scrollbar-width: none;
            -ms-overflow-style: none;
        }

        .academic-carousel .timeline-carousel::-webkit-scrollbar {
            display: none;
        }

        .academic-carousel .timeline-item {
            position: relative;
            padding-left: 30px;
            margin: 40px 0;
            opacity: 0.3;
            transition: all 0.4s ease;
            cursor: pointer;
            flex-shrink: 0;
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
            transform: translateY(-50%);
        }

        .academic-carousel .timeline-date {
            color: var(--ac-text-light);
            font-weight: 600;
            margin-bottom: 5px;
            font-size: 0.95em;
        }

        .academic-carousel .timeline-desc {
            color: rgba(255,255,255,0.85);
            font-size: 0.85em;
            line-height: 1.4;
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
            transition: transform 0.3s ease, background 0.2s ease;
            font-weight: 700;
            user-select: none;
        }

        .academic-carousel .arrow:hover {
            transform: scale(1.1);
            background: rgba(255,255,255,1);
        }

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
                padding: 15px 20px;
                overflow-x: auto;
                scroll-snap-type: x mandatory;
            }

            .academic-carousel .timeline-item {
                margin: 0 15px;
                padding-left: 25px;
                min-width: 140px;
                scroll-snap-align: center;
                transform: none !important;
            }

            .academic-carousel .timeline-item.active {
                transform: none !important;
            }

            .academic-carousel .nav-arrows {
                opacity: 1;
                visibility: visible;
                padding: 0 10px;
            }

            .academic-carousel .arrow {
                width: 35px;
                height: 35px;
                font-size: 0.9em;
            }
        }
    </style>
</head>
<body>
<div class="academic-carousel">
    <div class="carousel-container">
        <div class="content-carousel">
            <div class="content-item active">
                <h2>Our Work</h2>
                <p>SWR-BIDeN: An Improved BIDeN Model for Severe Weather Removal in Image Processing was accepted by IJCNN2025</p>
            </div>
            <div class="content-item">
                <h2>Our Work</h2>
                <p>LightDrone-YOLO: A Novel Lightweight and Efficient Object Detection Network for Unmanned Aerial Vehicles was accepted by ICIC2025</p>
            </div>
            <div class="content-item">
                <h2>Our Work</h2>
                <p>Lightweight Remote Sensing Image Change Detection Based on Global Feature Fusion was accepted by ICIC2025</p>
            </div>
            <div class="content-item">
                <h2>Our Work</h2>
                <p>GlintNet: A Lightweight Global-Local Integration Network with Spatial-Channel Mixed Attention for ReID was accepted by ICIC2025</p>
            </div>
        </div>

        <div class="timeline-carousel">
            <div class="timeline-item active">
                <div class="timeline-date">2024-03</div>
                <div class="timeline-desc">Paper Acceptance</div>
            </div>
            <div class="timeline-item">
                <div class="timeline-date">2024-04</div>
                <div class="timeline-desc">Paper Acceptance</div>
            </div>
            <div class="timeline-item">
                <div class="timeline-date">2024-04</div>
                <div class="timeline-desc">Paper Acceptance</div>
            </div>
            <div class="timeline-item">
                <div class="timeline-date">2024-04</div>
                <div class="timeline-desc">Paper Acceptance</div>
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
        const container = document.querySelector('.academic-carousel');
        if (!container) return;

        // Configuration
        const config = {
            interval: 2500,
            keyboard: true,
            hoverPause: true,
            touchSensitivity: 50,
            wheelSpeed: 0.5,
            infiniteLoop: true  // 添加无限循环开关
        };

        // Component State
        let currentIndex = 0;
        let autoPlayTimer;
        let isTransitioning = false;
        const mobileMedia = window.matchMedia("(max-width: 768px)");

        // DOM Elements
        const items = container.querySelectorAll('.content-item');
        const timelineItems = container.querySelectorAll('.timeline-item');
        const prevBtn = container.querySelector('.prev');
        const nextBtn = container.querySelector('.next');
        const carousel = container.querySelector('.carousel-container');
        const contentCarousel = container.querySelector('.content-carousel');
        const timelineCarousel = container.querySelector('.timeline-carousel');

        // Core Functions
        function scrollToTimeline(index) {
            if (!mobileMedia.matches) return;

            const activeItem = timelineItems[index];
            const containerWidth = timelineCarousel.offsetWidth;
            const itemWidth = activeItem.offsetWidth;

            let scrollPosition = activeItem.offsetLeft - (containerWidth - itemWidth) / 2;
            const maxScroll = timelineCarousel.scrollWidth - containerWidth;
            scrollPosition = Math.max(0, Math.min(scrollPosition, maxScroll));

            timelineCarousel.scrollTo({
                left: scrollPosition,
                behavior: 'smooth'
            });
        }

        function centerTimelineItem() {
            if (mobileMedia.matches) return;

            const activeItem = timelineItems[currentIndex];
            const containerHeight = timelineCarousel.clientHeight;
            const itemHeight = activeItem.offsetHeight;
            const scrollPos = activeItem.offsetTop - (containerHeight - itemHeight) / 2;

            timelineCarousel.scrollTo({
                top: scrollPos,
                behavior: 'smooth'
            });
        }

        function updateActive() {
            items.forEach((item, i) => {
                item.classList.toggle('active', i === currentIndex);
            });

            timelineItems.forEach((item, i) => {
                const wasActive = item.classList.contains('active');
                const nowActive = i === currentIndex;

                item.classList.toggle('active', nowActive);

                if (nowActive) {
                    requestAnimationFrame(() => {
                        mobileMedia.matches ? scrollToTimeline(i) : centerTimelineItem();
                    });
                }
            });
        }

        function slideTo(index) {
            if (isTransitioning || index === currentIndex) return;

            isTransitioning = true;
            contentCarousel.style.transform = `translateX(-${index * 100}%)`;
            currentIndex = index;

            setTimeout(() => {
                updateActive();
                isTransitioning = false;
            }, 600);

            resetAutoPlay();
        }

        function slide(direction) {
            if (!config.infiniteLoop &&
                ((direction === 1 && currentIndex === items.length - 1) ||
                    (direction === -1 && currentIndex === 0))) {
                return;
            }

            const newIndex = (currentIndex + direction + items.length) % items.length;
            slideTo(newIndex);
        }
        // Auto-play Control
        function startAutoPlay() {
            if (!autoPlayTimer && config.infiniteLoop) {
                autoPlayTimer = setInterval(() => {
                    slide(1);  // 自动向后滑动
                }, config.interval);
            }
        }


        function resetAutoPlay() {
            clearInterval(autoPlayTimer);
            autoPlayTimer = null;
            startAutoPlay();
        }

        // Event Handlers
        function handleWheel(e) {
            if (mobileMedia.matches) return;

            e.preventDefault();
            timelineCarousel.scrollTop += e.deltaY * config.wheelSpeed;
        }

        function initEvents() {
            // Navigation
            prevBtn.addEventListener('click', () => slide(-1));
            nextBtn.addEventListener('click', () => slide(1));

            // Timeline Interaction
            timelineItems.forEach((item, index) => {
                item.addEventListener('click', () => slideTo(index));
            });

            // Keyboard
            if (config.keyboard) {
                document.addEventListener('keydown', (e) => {
                    if (document.activeElement !== document.body) return;
                    if (e.key === 'ArrowLeft') slide(-1);
                    if (e.key === 'ArrowRight') slide(1);
                });
            }

            // Hover Control
            if (config.hoverPause) {
                carousel.addEventListener('mouseenter', () => clearInterval(autoPlayTimer));
                carousel.addEventListener('mouseleave', startAutoPlay);
            }

            // Touch Handling
            let touchStartX = 0;
            carousel.addEventListener('touchstart', e => {
                touchStartX = e.touches[0].clientX;
            }, { passive: true });

            carousel.addEventListener('touchend', e => {
                const touchEndX = e.changedTouches[0].clientX;
                const deltaX = touchStartX - touchEndX;

                if (Math.abs(deltaX) > config.touchSensitivity) {
                    slide(deltaX > 0 ? 1 : -1);
                }
            }, { passive: true });

            // Wheel Handling
            timelineCarousel.addEventListener('wheel', handleWheel);
        }

        // Initialization
        function init() {
            updateActive();
            initEvents();
            startAutoPlay();

            // Responsive Handling
            window.addEventListener('resize', () => {
                if (!mobileMedia.matches) {
                    centerTimelineItem();
                }
            });
        }

        init();
    })();
</script>
</body>
</html>
