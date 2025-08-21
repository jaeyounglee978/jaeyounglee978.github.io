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
- Java
- Kotlin
- Spring
- Python
- Typescript
- Docker

### Career

2022.08.07 &ndash;

: 이그나이트<small>서버 개발자</small>\\
<small>주요 키워드: Java, Kotlin, Spring</small>

- [KIA CPO service][kiaCpo]
  - 기아 CPO 대고객 사이트 API 작업
  - ElasticSearch를 사용한 대고객 사이트 검색 기능 구현
  - 사용자 차량 가격 계산을 위한 외부 API 호출 작업. Spring AOP를 활용해 호출량 모니터링 로직 작업 
  - 기아 CPO 어드민에서 엑셀을 사용한 매입 데이터 생성 처리
    - 기획에서 요구한 새로운 유형의 차량 매입 플로우를 구현. batch를 이용한 데이터 처리
    - 처리 과정 중 중간에 실패하더라도 안전하도록 로직 구성
  - QA용 내부 툴 개발

- 현대 사내 서비스 A
  - 카프카와 Spring batch를 사용한 유저 기기 서비스 등록 및 알림 발송 로직 구현
    - 외부 API 연동 이슈와 유저의 로그인 플로우를 분리. 유저의 서비스 사용 경험 개선
    - 대량의 알림 발송을 위해 kafka 를 통한 비동기 알림 발송 구현. 알림 발송 대상 플랫폼 별 재시도 로직 구현
  - 사내 API 제공자들과의 적극적인 커뮤니케이션을 통한 요구사항 구현
  - 조직도, 홈화면 메뉴 노출/관리 로직 작업

- 현대 사내 서비스 B
  - Monolithic, Spring with Java21. With MongoDB

<br><br>

2022.06.13 &ndash; 2023.07.28 &nbsp;&nbsp;&nbsp;

: Bepro 11<small>카메라 인프라 엔지니어</small>\\
<small>주요 키워드: Python, Data Processing Pipelines</small>

- Bepro 카메라 데이터 처리
  - 경기장에 있는 카메라가 등록되어 있는 축구 경기 일정에 맞추어 자동으로 녹화를 시작하고, 고객에게 보여질 영상을 만드는 비디오 파이프라인에 데이터를 보내는 시스템 관리
  - 기존에 동작하고 있던 스크립트의 로직을 재작성하여 기능별로 모듈화를 적용하였고, 시스템 효율을 위해 멀티프로세싱, 멀티스레딩 도입.
  - 우분투 기반 시스템에서 동작하는 새로운 카메라 장치를 위한 신규 녹화 시스템 개발.
  - HLS 비디오 포맷에 대한 경험. 디버깅 및 에러 추적을 위한 로깅 경험.

<br><br>

2019.01.21 &ndash; 2022.06.10 &nbsp;&nbsp;&nbsp;

: NAVER<small>서버 개발자</small>\\
<small>주요 키워드: Java, Kotlin, Spring, MicroServices</small>

- 2022.01

  - 사내 헬스케어 서비스 Internal HealthCare Service
    - MySQL과 MongoDB를 모두 사용하여 정형화된 유저 데이터 및 복잡한 의료 데이터 핸들링
    - Spring 외, 경량 서버 프레임워크인 ktor 를 도입. 적은 코드와 읽기 쉬운 구조로 유지보수가 용이한 프로그램 작성  


- 2020.11

  - LINE ドクター <small>([news][lindDoctorNews])</small><small>Server Engineeer</small>
    - 마이크로 서비스 아키텍처로 운영된 서비스의 유저 인증 정보 처리 부분 담당.
    - Redis를 사용한 JWT 베이스 유저 인증/인가 데이터 관리 
    - Kafka를 사용한 메세징 처리 기능 구현.
    
  - Workflow 서비스(사내 사이드 프로젝트)
    - MongoDB, Redis, 코틀린 코루틴, Spring WebFlux, Apache Pulsar 를 사용한 delayed/periodic 작업 수행 시스템
    - 초당 1만 건이 넘는 HTTP 호출 작업을 스케줄링하여 실행시키는 성능 테스트 통과
    - 사내 타 서비스 지원(AFK 확인, 랭킹 호출 등)

- 2019.11

  - LINE ヘルスケア <small>([news][lineHealthCareNews])</small><small>Server Engineeer</small>
    - 마이크로 서비스 아키텍처로 운영된 서비스의 유저 인증 정보 처리 부분 담당.
    - Spring Webflux, Redis, MongoDB 사용

  - LINE 弁護士相談 <small>([news][lineLaywerConsultNews])</small><small>Server Engineer </small>
    - 마이크로 서비스 아키텍처로 운영된 서비스의 유저 인증 정보 처리 부분 담당.
    - Spring Webflux, Redis, MongoDB 사용

<br><br>

### Education

2013&ndash;2018

: [Korea Advanced Institute of Science and Technology][kaist], 학사 졸업 \\
- 물리학과, 전산학과 복수 전공

<br><br>

### 언어 능력

English

: TOEIC 895 (2018/02/25), Have no probelm in using English for business level.

Japanese

: JLPT N1 (2019/03/19), Available to use Japanese in daily life and work also.

<br><br>

### Personal Project

2022
: [AIRSIX Webpage][airsix-webpage](Currently not on service)
- 사격 스포츠 점수 기록 및 공유를 위한 웹사이트 사이드 프로젝트.
- 최초 시작은 Vue3 로 프론트 작업, Flask 로 백엔드, MongoDB 를 데이터베이스로 잡아 서비스 개발.
- 이후 서버를 Kotlin Spring MVC 로 재작업하였으며, AWS RDS 로 데이터베이스 변경.
  - EC2 인스턴스를 좀 더 낮은 사양으로 사용하는 것 + 당시 사용하던 데이터 구조가 mongoDB를 운영하여 얻는 이점이 없다고 판단. AWS에서 제공해주는 자동 DB 백업 기능을 활용. 
- 깃헙 액션을 사용하여 자동으로 도커 이미지를 제작하고, 이를 깃헙 레지스트리에 업로드하여 사용.
- EC2 인스턴스 한대에 frontend, backend, mongoDB, 인증서 갱신을 위한 letsencrypt 까지 네개의 컨테이너로 운영. 이후 DB를 제거한 3개의 컨테이너로 운영 


2017

: [Paladin who believes in God(DiscardedWarlock)][diswarlock]. 2017 여름 GGGGJ <small>([movie][paladinMovie])</small>\\
<small>게임 디자인, 프로그래머</small>\\


2016

: [Pray][pray]<small>(private link) ([movie][prayMovie])</small> \\
<small>프로그래머</small>

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
