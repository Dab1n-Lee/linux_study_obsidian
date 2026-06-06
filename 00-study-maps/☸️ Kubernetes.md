# ☸️ Kubernetes

> 클러스터 구성 → Pod/Deployment 배포 → 운영(조회·로그·디버깅) → 네트워크 순으로 학습합니다.
> ⬅️ [[🏠 Linux Study Home]] · 오케스트레이션 비교는 [[🔄 Container Orchestration Comparison]]

## 🏗️ 클러스터 구성
- [[86|쿠버네티스(K3s) 설치와 worker 등록]] — master/worker, 토큰, `kubectl get nodes`

## 🚀 배포 (Pod · Deployment)
- [[87|Nginx Pod 정상 구동 확인]] — `kubectl run`, `port-forward`
- [[88|웹서버 3개 복제본 Deployment 배포]] — `--replicas=3`
- [[89|YAML 파일로 Deployment 배포·수정]]
- [[90|Deployment 롤링 업데이트]]
- [[91|Pod 죽으면 자동복구되는지 테스트]]
- [[100|Pod 재시작 후 상태 변화 확인]]

## 🔎 운영·조회
- [[92|리소스 종류별 조회 (kubectl get)]]
- [[93|리소스 상세 정보 보기 (describe)]]
- [[94|get에 -o wide 옵션 붙이기]]
- [[95|네임스페이스별 리소스 현황]]
- [[96|CPU/메모리 사용량 확인 (kubectl top)]]
- [[97|Pod 로그 출력으로 실행 흐름 확인]]
- [[98|실행 중인 Pod 내부에서 명령 실행 (exec)]]
- [[99|Service 연결 상태를 curl로 테스트]]

## 🌐 네트워크
- [[123|쿠버네티스 네트워크 기본구조 확인]] — `cni0`, `veth`, podIP
- [[124|CoreDNS 장애 재현 및 복구]]

## 🔗 함께 보면 좋은 것
- 같은 작업을 Docker/Swarm으로 → [[🔄 Container Orchestration Comparison]]
- DNS 진단 기초 → [[117|DNS 문제 진단]] ([[🌐 Networking]])
