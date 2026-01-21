<!-- Profile README for jgm0327 -->

<h1 align="center">jgm0327</h1>
<p align="center">
  운영 안정성과 성능을 지표로 증명하는 Backend Developer입니다.
</p>

<p align="center">
  <a href="https://solved.ac/jgm0327">
    <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=jgm0327" alt="Solved.ac Badge" />
  </a>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jgm0327&show_icons=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jgm0327&layout=compact" alt="Top Languages" />
</p>

## 핵심 키워드
- 운영 안정성, Blue Green 배포와 빠른 롤백을 기본값으로 둡니다.
- 관측 가능성, Prometheus와 Grafana로 병목과 이상 징후를 수치로 확인합니다.
- 성능 개선, 부하 테스트에서 시작해 Cache와 Query 최적화로 마무리합니다.
- 협업, 자동화와 문서화로 팀의 흐름이 끊기지 않게 합니다.

<h2>🛠 Tech Stack</h2> <br/>
Backend

<p> <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/Hibernate(JPA)-59666C?style=for-the-badge&logo=hibernate&logoColor=white"> <img src="https://img.shields.io/badge/QueryDSL-07ADEE?style=for-the-badge&logo=databricks&logoColor=white"> </p>

Database & Cache

<p> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"> </p>

Infrastructure & Cloud

<p> <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white"> <img src="https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"> <img src="https://img.shields.io/badge/RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white"> <img src="https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"> <img src="https://img.shields.io/badge/CloudFront-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white"> </p>

DevOps & CI/CD

<p> <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"> <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"> </p>

Monitoring

<p> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"> <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"> </p>

## 대표 프로젝트
### DO DREAM AI 기반 시각 장애인 학습 플랫폼
Infra와 운영을 주도하며 재현 가능한 배포 구조를 구축했습니다.
- AWS EC2 RDS, Docker Compose, Nginx Reverse Proxy
- Jenkins CI CD, Blue Green 배포, health check 기반 트래픽 전환
- Prometheus Grafana 모니터링, Vault secrets 관리
- S3 Presigned URL, CloudFront로 안전하고 빠른 콘텐츠 제공
Repo https://github.com/jgm0327/DO-DREAM

### danggunMarket 결제 시스템이 존재하는 중고 거래 사이트
성능과 일관성을 함께 고려한 백엔드 개인 프로젝트입니다.
- nGrinder 부하 테스트 후 Caffeine Cache TTL 2초 적용, TPS 15에서 586으로 개선
- JPQL fetch join으로 N plus 1 문제 해결
- JPA pessimistic lock으로 가격 변경 동시성 제어
Repo https://github.com/jgm0327/danggunMarket

### solsol backend 출석률 기반 쿠폰 발급 시스템
해커톤 환경에서 끝까지 완성하는 실행력을 증명한 프로젝트입니다.
- 매일 03 10 KST 스케줄러 기반 자동 발급, 페이징 기반 배치 처리
- QueryDSL bulk update와 lock으로 중복 발급 방지
Repo https://github.com/CANSHOOT/solsol-backend

## 성장과 태도
- 알고리즘 문제 1000개 이상 풀이로 문제 해결력을 꾸준히 강화했습니다.
- Kakao Cloud School에서 협업과 주도성을 인정받아 모범상을 수상했습니다.
- 좋은 코드, 안정적인 배포, 빠른 피드백을 습관으로 만들고 있습니다.
