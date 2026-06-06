# 🐳 Docker

> 설치 → 컨테이너 실행/관리 → 이미지/볼륨/네트워크 → 트러블슈팅 순서로 학습합니다.
> ⬅️ [[🏠 Linux Study Home]] · 오케스트레이션 비교는 [[🔄 Container Orchestration Comparison]]

## 🛠️ 설치·시작
- [[37|Rocky9 도커 설치하기]] — 저장소 추가, 엔진 설치, `usermod -aG docker`

## 📦 컨테이너 기본 다루기
- [[38|도커로 웹서버 실행하기 (docker run)]]
- [[39|실행 중인 컨테이너 목록 확인 (docker ps)]]
- [[40|컨테이너 내부로 들어가기 (docker exec)]]
- [[68|컨테이너 로그 보기 (docker logs)]]
- [[71|컨테이너 중지하고 삭제하기]]

## 🌐 포트·볼륨·네트워크
- [[69|컨테이너 포트 외부로 열기 (-p)]]
- [[70|컨테이너 볼륨 연결하기 (-v)]]
- [[74|컨테이너끼리 통신하기 (docker network)]]
- [[120|docker0 기본 네트워크 구조 확인 (bridge)]]

## 🧱 이미지·자원
- [[73|Dockerfile로 이미지 만들기 (docker build)]]
- [[72|안 쓰는 이미지·컨테이너 정리 (prune)]]
- [[75|컨테이너 CPU·메모리 제한하기]]

## 🩹 트러블슈팅
- [[111|제한된 용량 Docker에서 용량 오류 날 때]]
- [[121|도커 네트워크와 iptables 충돌 문제]]
- [[122|도커 컨테이너 포트 충돌 문제 해결]]

## 🔗 함께 보면 좋은 것
- 같은 작업을 K8s/Swarm으로 → [[🔄 Container Orchestration Comparison]]
- 호스트 네트워크 기초 → [[🌐 Networking]]
