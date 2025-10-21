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


### Skills
- Language: Java, Kotlin, Python, Typescript(a little bit)
- Framework: Spring, Spring Webflux, Django, Flask
- Infra: Docker
- Monitoring tool: Datadog, Pinpoint

### Career

2022.08.07 &ndash;

: IGNITE<small>Backend Engineeer</small>\\
<small>Main keywords: Java, Kotlin, Spring</small>

- [KIA CPO service][kiaCpo]
  - Developed APIs for Kia CPO customer-facing website
  - Implemented customer search functionality using ElasticSearch
  - Integrated external API for user vehicle price calculation; implemented call volume monitoring logic using Spring AOP
  - Processed vehicle purchase data creation via Excel in the Kia CPO admin system
    - Implemented a new type of vehicle purchase flow requested by planning, using batch processing for data
   - Developed an internal QA tool

<br><br>

- Hyundai Internal Service A
   - Implemented user device registration and notification logic using Kafka and Spring Batch
     - Decoupled external API integration issues from the user login flow, improving user service experience
     - Implemented asynchronous mass notification via Kafka, including platform-specific retry logic for delivery targets
   - Implemented requirements through active communication with internal API providers
   - Developed logic for organization chart and home screen menu display/management

<br><br>

- Hyundai Internal Service B
  - Monolithic, Spring with Java21. With MongoDB

<br><br>

2022.06.13 &ndash; 2023.07.28 &nbsp;&nbsp;&nbsp;

: Bepro 11<small>Camera Infra Engineer</small>\\
<small>Main keywords: Python, Data Processing Pipelines</small>

 - Bepro Camera Data Processing
   - Managed a system that automatically starts recording based on registered football match schedules, sending data to the video pipeline for customer-facing video creation
   - Refactored existing script logic for functional modularization; introduced multiprocessing and multithreading for system efficiency.
   - Developed a new recording system for new camera devices operating on Ubuntu-based systems.
   - Experience with HLS video format, and logging for debugging and error tracing.

<br><br>

2019.01.21 &ndash; 2022.06.10 &nbsp;&nbsp;&nbsp;

: NAVER<small>Backend Engineer</small>\\
<small>Main keywords: Java, Kotlin, Spring, MicroServices</small>

- 2022.01

   - Internal HealthCare Service
     - Handled structured user data and complex medical data using both MySQL and MongoDB
     - Introduced Ktor (lightweight server framework) alongside Spring; wrote maintainable programs with cleaner code and structure

<br><br>

- 2020.11

  - LINE ドクター <small>([news][lindDoctorNews])</small><small>Server Engineeer</small>
     - Managed user authentication information processing within a service operated with Microservice Architecture.
     - Managed JWT-based user authentication/authorization data using Redis
     - Implemented messaging processing functionality using Kafka.
    
<br><br>

 - Workflow Service (Internal Side Project)
   - Developed a system for delayed/periodic task execution using MongoDB, Redis, Kotlin Coroutines, Spring WebFlux, and Apache Pulsar
   - Passed performance tests, scheduling and executing over 10,000 HTTP call tasks per second
   - Supported other internal services (e.g., AFK check, ranking calls)

<br><br>

- 2019.11

  - LINE ヘルスケア <small>([news][lineHealthCareNews])</small><small>Server Engineeer</small>
     - Managed user authentication information processing within a service operated with Microservice Architecture.
     - Used Spring Webflux, Redis, MongoDB

<br><br>

  - LINE 弁護士相談 <small>([news][lineLaywerConsultNews])</small><small>Server Engineer </small>
    - Managed user authentication information processing within a service operated with Microservice Architecture.
    - Used Spring Webflux, Redis, MongoDB

<br><br>

### Education

2013&ndash;2018

: [Korea Advanced Institute of Science and Technology][kaist] (B.S. Degree) \\
- Major in Physics, Double Major in Computer Science

<br><br>

### Language Skill

English

: TOEIC 895 (2018/02/25), Have no probelm in using English for business level.

Japanese

: JLPT N1 (2019/03/19), Available to use Japanese in daily life and work also.

<br><br>

### Personal Project

2022
: [AIRSIX Webpage][airsix-webpage](Currently not on service)
 - A website side project for recording and sharing scores for shooting sports.
 - Initially developed the service with Vue3 for frontend, Flask for backend, and MongoDB as the database.
 - Later refactored the server to Kotlin Spring MVC and changed the database to AWS RDS.
   - Used a lower-spec EC2 instance and switched from MongoDB to AWS RDS, utilizing its automatic backup feature, as the existing data structure did not benefit from a NoSQL database.
 - Used GitHub Actions to automatically build and upload Docker images to the GitHub Registry.
 - Operated with four containers on a single EC2 instance: frontend, backend, MongoDB, and Let's Encrypt for certificate renewal. Later reduced to three containers after removing the DB.


2017

: [Paladin who believes in God(DiscardedWarlock)][diswarlock]. 2017 여름 GGGGJ <small>([movie][paladinMovie])</small>\\
<small>Game design, Programmer</small>\\


2016

: [Pray][pray]<small>(private link) ([movie][prayMovie])</small> \\
<small>Programmer</small>

<br><br>

### Activity

2016&ndash;2017

: KAIST Game development circle [HAJE][hajehp] Club President

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
