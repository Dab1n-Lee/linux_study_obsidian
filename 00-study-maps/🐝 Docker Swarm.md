# 🐝 Docker Swarm

> 클러스터 초기화 → 서비스 배포/복제 → 롤링업데이트/복구 → 운영 조회 순으로 학습합니다.
> ⬅️ [[🏠 Linux Study Home]] · 오케스트레이션 비교는 [[🔄 Container Orchestration Comparison]]

## 🏗️ 클러스터 구성
- [[101|Swarm 설치 및 초기화]] — `docker swarm init`, join 토큰, `docker node ls`

## 🚀 서비스 배포·복제
- [[102|Nginx 웹 서버 서비스 배포]] — `docker service create`
- [[103|3개 복제본 Nginx 서비스 생성]] — `--replicas 3`
- [[104|서비스 롤링 업데이트]]
- [[105|Task가 죽었을 때 자동 복구]]

## 🔎 운영·조회
- [[106|docker 전체 작업 상태 조회]]
- [[107|서비스 상세 정보 확인 (inspect)]]
- [[108|서비스 이름·상태·포트 조회 (service ls)]]
- [[109|서비스 컨테이너 실행 로그 확인]]
- [[110|서비스 특정 포트 외부 접속 확인]] — 라우팅 메시

## 🔗 함께 보면 좋은 것
- 같은 작업을 Docker/K8s로 → [[🔄 Container Orchestration Comparison]]
- Swarm은 Docker 위에서 동작 → [[🐳 Docker]]
