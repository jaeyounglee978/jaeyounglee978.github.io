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

2022.06.13 &ndash;

: Bepro 11<small>Camera Infra Engineer</small>\\
<small>Using python to manage data processing pipeline.</small>

- Camera infrastructure management.
  - To start recording on the pitch on the time, retreive video files, pass video files to video processing program, and upload result video to server, I managed dedicated script for service and overall service.
  - Refactor script. Extract logic and make it to Process to simplify main script, and clarify managing point.
  - Make new script for new service. Running on Ubuntu machine and successfully support new recording service with new camera.
  - Experience the importance of logging. Finding error and reason from large size of log file.

<br><br>

2019.01.21 &ndash; 2022.06.10 &nbsp;&nbsp;&nbsp;

: NAVER<small>Server Engineer</small>\\
<small>Mainly Using Java, Kotlin, Spring.</small>

- 2022.01

  - Release service: Company Internal Service for healthcare.
    - Use FHIR, global standard for medical information. Main data storage architecture.
    - Use MySQL, MongoDB. Spring with java, kotlin. Ktor as a framework for small server.
    - Ktor is simple framework using Kotlin, very easy to start.
    - Since we planned to store a lots of complicated medical information. Choose MongoDB, to store info in more loosen form and prepare for future spec change.

<br>
- 2020.11

  - Release service: LINE ドクター <small>([news][lindDoctorNews])</small><small>Server Engineeer</small>
    - User account managing and authenticate service as service of MSA.
    - Use MySQL as mainDB, Redis as cache, Kafka, and spring.
    - Use JWT as authentication token. Simple but enough to manage user login info.
    - By using Spring Filter, authorize user access to API endpoint by given JWT token from header.
    - In case of JWT modification, Redis is used not only for cache but for managing token info.

  - Side Project: Workflow Service
    - Support Delayed Job service for other projects. Select execution time and do http call at selected time. also support periodic execution.
    - Use MongoDB as mainDB, Redis as SupportDB, Kotlin(+ coroutine) + Spring Webflux. Apache Pulsar.
    - Consists of three parts. API, Scheduler, and Executor.
    - Apache pulsar supports delayed message queue service. Use this to make message containing information about job to execute and receive it when it is time to start it.
    - Available to execute requested 10,000 HTTP request jobs per second. Used this service to serve internal needs. Like alarm services.

<br>
- 2019.11

  - Release service: LINE ヘルスケア <small>([news][lineHealthCareNews])</small><small>Server Engineeer</small>
    - User account managing and authenticate service as service of MSA.
    - Use MongoDB as mainDB, Redis as cache, and spring webflux

  - Release service: LINE 弁護士相談 <small>([news][lineLaywerConsultNews])</small><small>Server Engineer </small>
    - User account managing and authenticate service as service of MSA.
    - Use MongoDB as mainDB, Redis as cache, and spring webflux

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
: [AIRSIX Webpage][airsix-webpage]
<small>Sideproject to make website serving IPSC/USPSA based match result.</small>
<small>Vue 3 for Frontend, Flask for Backend, and MongoDB for database</small>
<small>Using github action, build docker images and upload them to github registry.</small>
<small>Run 4 docker images on single AWS EC2 instance with docker compose.</small>

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
