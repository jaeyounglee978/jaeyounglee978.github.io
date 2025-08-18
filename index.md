---
layout: post
title: "Jaeyoung Lee CV"
---

<header class="post-header">
  <h1 class="post-title">이재영 <span class="nobreak-container">Lee Jae Young</span></h1>
  <p class="post-meta">{{ page.date | date: "%b %-d, %Y" }}{% if page.author %} • {{ page.author }}{% endif %}{% if page.meta %} • {{ page.meta }}{% endif %}</p>
  <div class="footer-col-wrapper">
  <a href="mailto:{{ site.email }}" class="nobreak-container">
    <span class="icon  icon--github">
      <svg class="svg-icon" viewBox="2 2 16 16">
        <path d="M17.388,4.751H2.613c-0.213,0-0.389,0.175-0.389,0.389v9.72c0,0.216,0.175,0.389,0.389,0.389h14.775c0.214,0,0.389-0.173,0.389-0.389v-9.72C17.776,4.926,17.602,4.751,17.388,4.751 M16.448,5.53L10,11.984L3.552,5.53H16.448zM3.002,6.081l3.921,3.925l-3.921,3.925V6.081z M3.56,14.471l3.914-3.916l2.253,2.253c0.153,0.153,0.395,0.153,0.548,0l2.253-2.253l3.913,3.916H3.56z M16.999,13.931l-3.921-3.925l3.921-3.925V13.931z"></path>
      </svg>
    </span>
    <span class="username">{{ site.email }}</span>
  </a>
  <a href="https://github.com/{{ site.github_username }}" class="nobreak-container">
    <span class="icon  icon--github">
      <svg viewBox="0 0 16 16">
        <path fill="#828282" d="M7.999,0.431c-4.285,0-7.76,3.474-7.76,7.761 c0,3.428,2.223,6.337,5.307,7.363c0.388,0.071,0.53-0.168,0.53-0.374c0-0.184-0.007-0.672-0.01-1.32 c-2.159,0.469-2.614-1.04-2.614-1.04c-0.353-0.896-0.862-1.135-0.862-1.135c-0.705-0.481,0.053-0.472,0.053-0.472 c0.779,0.055,1.189,0.8,1.189,0.8c0.692,1.186,1.816,0.843,2.258,0.645c0.071-0.502,0.271-0.843,0.493-1.037 C4.86,11.425,3.049,10.76,3.049,7.786c0-0.847,0.302-1.54,0.799-2.082C3.768,5.507,3.501,4.718,3.924,3.65 c0,0,0.652-0.209,2.134,0.796C6.677,4.273,7.34,4.187,8,4.184c0.659,0.003,1.323,0.089,1.943,0.261 c1.482-1.004,2.132-0.796,2.132-0.796c0.423,1.068,0.157,1.857,0.077,2.054c0.497,0.542,0.798,1.235,0.798,2.082 c0,2.981-1.814,3.637-3.543,3.829c0.279,0.24,0.527,0.713,0.527,1.437c0,1.037-0.01,1.874-0.01,2.129 c0,0.208,0.14,0.449,0.534,0.373c3.081-1.028,5.302-3.935,5.302-7.362C15.76,3.906,12.285,0.431,7.999,0.431z"></path>
      </svg>
    </span>
    <span class="username">{{ site.github_username }}</span>
  </a>
  </div>
</header>

### Career

2022.08.07 &ndash;

: Ignite<small>Backend dev</small>\\
<small>Java, Kotlin, Spring.</small>

- [KIA CPO service][kiaCpo]
  - Developed and maintained user-facing services and request data flows.
  - Integrated external APIs to provide estimated car prices and managed request status throughout the purchase process.
  - Implemented search functionality using Elasticsearch (AWS OpenSearch Service).
  - Built internal tools to support QA processes.

- Hyundai Internal Service 1
  - Developed APIs for menu, user notifications, and organizational charts.
  - Integrated Hyundai-provided APIs for internal web services.
  - Implemented asynchronous notification delivery with Kafka and Spring Batch, including retry mechanisms.

- Hyundai Internal Saas
  - Monolithic, Spring with Java21. With MongoDB

<br><br>

2022.06.13 &ndash; 2023.07.28 &nbsp;&nbsp;&nbsp;

: Bepro 11<small>Camera Infra Engineer</small>\\
<small>Python, Data Processing Pipelines</small>

- Managed camera infrastructure for automated football match recording and video processing.
- Developed and maintained scripts to schedule recordings, retrieve files, run processing pipelines, and upload results.
- Refactored scripts by modularizing logic and introducing multiprocessing/threading for efficiency.
- Designed new scripts for services on Ubuntu-based systems, supporting new camera hardware.
- Gained experience with HLS format and emphasized robust logging for debugging and error tracking.

<br><br>

2019.01.21 &ndash; 2022.06.10 &nbsp;&nbsp;&nbsp;

: NAVER<small>Server Engineer</small>\\
<small>Java, Kotlin, Spring, MicroServices</small>

- 2022.01

  - Internal HealthCare Service
    - Built services based on FHIR (medical data standard).
    - Designed hybrid storage architecture using MySQL and MongoDB to handle complex medical records.
    - Used Spring (Java/Kotlin) and Ktor as a lightweight server framework  .

- 2020.11

  - LINE ドクター <small>([news][lindDoctorNews])</small><small>Server Engineeer</small>
    - Developed user authentication and account services within a microservice architecture.
    - MySQL, Redis, Kafka, Spring.
    - Implemented JWT-based authentication and authorization with Redis-backed token management.
    
  - Side Project: Workflow Service
    - Designed and implemented a delayed/periodic job execution system.
    - Stack: MongoDB, Redis, Kotlin coroutines, Spring WebFlux, Apache Pulsar.
    - Achieved throughput of 10,000+ scheduled HTTP jobs per second for internal services.

- 2019.11

  - Release service: LINE ヘルスケア <small>([news][lineHealthCareNews])</small><small>Server Engineeer</small>
    - Developed authentication and account management services using MongoDB, Redis, and Spring WebFlux.

  - Release service: LINE 弁護士相談 <small>([news][lineLaywerConsultNews])</small><small>Server Engineer </small>
    - Built account and authentication services for legal consultation platform.
    - Used MongoDB, Redis, and Spring WebFlux.

<br><br>

### Education

2013&ndash;2018

: [Korea Advanced Institute of Science and Technology][kaist], the Bachelor of Science \\
<small>Double Major in Physics and Computer Science</small>

2010&ndash;2012

: Graduate [Suji High school][sjhs]

[kaist]: http://www.kaist.ac.kr/
[sjhs]: http://www.suji.hs.kr/main.php

<br><br>

### Language Skills

English

: TOEIC 895 (2018/02/25), Have no probelm in using English for business level.

Japanese

: JLPT N1 (2019/03/19), Available to use Japanese in daily life and work also.

<br><br>

### Personal Project

2022
: [AIRSIX Webpage][airsix-webpage](Currently not on service)
<small>Sideproject to make website serving Competitve Shooting match result.</small>
<small>Started with Vue 3 for Frontend, Flask for Backend, and MongoDB for database.</small>
<small>Rebuilt with Vue 3 for Frontend, Spring MVC for Backend, and AWS RDS for database.</small>
<small>Using github action, automatically build docker images and upload these to github registry.</small>
<small>Run 4 -> 3 docker images on single AWS EC2 instance with docker compose.</small>

2018

: [MobileRunner][mobilerunner] as toyproject <small>([movie][mobileRunnerMovie])</small>\\
<small>Game design, Programmer</small>

2017

: [Paladin who believes in God(DiscardedWarlock)][diswarlock] for 2017 summer GGGGJ <small>([movie][paladinMovie])</small>\\
<small>Game design. Programmer</small>\\
[Chain Bomb][chainbomb] for HAJE autumn GameJam \\
<small>Game design, Programmer</small> \\
[2017 AI Game][2017aigame] for KAIST-POSTECH science war <small>([movie][2017aigamemovie])</small>\\
<small>External negotiation</small>

2016

: [Pray][pray]<small>(private link) ([movie][prayMovie])</small> \\
<small>Programmer</small>

<br><br>

### Activity

2016&ndash;2017

: KAIST Game development circle [HAJE][hajehp] Leader

[kiaCpo]: https://cpo.kia.com
[lineLaywerConsultNews]: https://linecorp.com/ja/pr/news/ja/2019/2987
[lineHealthCareNews]: https://linehealthcarecorp.com/ja
[lindDoctorNews]: https://japan.cnet.com/article/35163983/
[hajehp]: http://haje.org/
[mobilerunner]: https://github.com/jaeyounglee978/MobileRunner
[diswarlock]: https://bitbucket.org/jaeyounglee/discardedwarlock
[chainbomb]: https://bitbucket.org/jaeyounglee/chain-bomb
[2017aigame]: https://youtu.be/ComZNlHgpak
[pray]: https://bitbucket.org/zenta0027/pray
[prayMovie]: https://youtu.be/je0OS2ktQrE
[paladinMovie]: https://youtu.be/nnh19z0hYZg
[2017aigamemovie]: https://youtu.be/ComZNlHgpak
[mobileRunnerMovie]: https://youtu.be/dYTaNsyl4lw
[airsix-webpage]: https://air-six.com
