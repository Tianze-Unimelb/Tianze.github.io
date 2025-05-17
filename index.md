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
    .academic-carousel {
        --ac-primary: #2c3e50;
        --ac-secondary: #3498db;
        --ac-text-light: #ecf0f1;
        --ac-bg: #fff;
        font-family: inherit;
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
            overflow-x: auto;
            scroll-behavior: smooth;
            scroll-snap-type: x mandatory;
        }

        .academic-carousel .timeline-item {
            margin: 0 15px;
            padding-left: 20px;
            min-width: 120px;
            scroll-snap-align: center;
        }
    }
</style>

<div class="academic-carousel">
    <div class="carousel-container">
        <div class="content-carousel">
            <!-- 内容项保持不变 -->
        </div>

        <div class="timeline-carousel">
            <!-- 时间轴项保持不变 -->
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

        const config = {
            interval: 5000,
            keyboard: true,
            hoverPause: true
        };

        let currentIndex = 0;
        let autoPlayTimer;
        let isTransitioning = false;
        const mobileMedia = window.matchMedia("(max-width: 768px)");

        const items = container.querySelectorAll('.content-item');
        const timelineItems = container.querySelectorAll('.timeline-item');
        const prevBtn = container.querySelector('.prev');
        const nextBtn = container.querySelector('.next');
        const carousel = container.querySelector('.carousel-container');
        const contentCarousel = container.querySelector('.content-carousel');
        const timelineCarousel = container.querySelector('.timeline-carousel');

        function scrollToTimeline(index) {
            if (!mobileMedia.matches) return;
            
            const activeItem = timelineItems[index];
            const containerWidth = timelineCarousel.offsetWidth;
            const itemWidth = activeItem.offsetWidth;
            const scrollLeft = activeItem.offsetLeft - (containerWidth - itemWidth) / 2;
            
            const maxScroll = timelineCarousel.scrollWidth - containerWidth;
            const finalScroll = Math.max(0, Math.min(scrollLeft, maxScroll));
            
            timelineCarousel.scrollTo({
                left: finalScroll,
                behavior: 'smooth'
            });
        }

        function updateActive() {
            items.forEach((item, i) => item.classList.toggle('active', i === currentIndex));
            timelineItems.forEach((item, i) => item.classList.toggle('active', i === currentIndex));
            
            requestAnimationFrame(() => {
                scrollToTimeline(currentIndex);
            });
        }

        function slide(direction) {
            if (isTransitioning) return;
            isTransitioning = true;
            
            const newIndex = (currentIndex + direction + items.length) % items.length;
            contentCarousel.style.transform = `translateX(-${newIndex * 100}%)`;
            currentIndex = newIndex;
            
            setTimeout(() => {
                updateActive();
                isTransitioning = false;
            }, 600);
            
            resetAutoPlay();
        }

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

        function initEvents() {
            prevBtn.addEventListener('click', () => slide(-1));
            nextBtn.addEventListener('click', () => slide(1));

            timelineItems.forEach((item, index) => {
                item.addEventListener('click', () => {
                    if (index === currentIndex || isTransitioning) return;
                    isTransitioning = true;
                    
                    contentCarousel.style.transform = `translateX(-${index * 100}%)`;
                    currentIndex = index;
                    
                    setTimeout(() => {
                        updateActive();
                        isTransitioning = false;
                    }, 600);
                    
                    resetAutoPlay();
                });
            });

            if (config.keyboard) {
                document.addEventListener('keydown', (e) => {
                    if (e.key === 'ArrowLeft') slide(-1);
                    if (e.key === 'ArrowRight') slide(1);
                });
            }

            if (config.hoverPause) {
                carousel.addEventListener('mouseenter', () => clearInterval(autoPlayTimer));
                carousel.addEventListener('mouseleave', startAutoPlay);
            }

            let touchStartX = 0;
            carousel.addEventListener('touchstart', e => {
                touchStartX = e.touches[0].clientX;
            }, { passive: true });
            
            carousel.addEventListener('touchend', e => {
                const touchEndX = e.changedTouches[0].clientX;
                const diff = touchStartX - touchEndX;
                
                if (Math.abs(diff) > 50) {
                    slide(diff > 0 ? 1 : -1);
                }
            }, { passive: true });
        }

        function init() {
            updateActive();
            initEvents();
            startAutoPlay();
            
            // 处理窗口大小变化
            let resizeTimer;
            window.addEventListener('resize', () => {
                clearTimeout(resizeTimer);
                resizeTimer = setTimeout(() => {
                    scrollToTimeline(currentIndex);
                }, 200);
            });
        }

        init();
    })();
</script>
