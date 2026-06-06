# 🔄 Container Orchestration Comparison

> 🐳 Docker · ☸️ Kubernetes · 🐝 Swarm 은 **같은 목표(컨테이너로 서비스 운영)** 를 서로 다른 방식으로 풉니다.
> "이 작업을 각 환경에서는 뭐라고 하지?"를 가로로 비교하면 개념이 한 번에 정리됩니다.
> ⬅️ [[🏠 Linux Study Home]]

## 🧩 개념 대응표

| 개념 | 🐳 Docker | ☸️ Kubernetes | 🐝 Swarm |
| --- | --- | --- | --- |
| 실행 단위 | Container | Pod | Task |
| 배포 관리 단위 | (run) | Deployment | Service |
| 외부 노출 | `-p` 포트 | Service | `--publish` |
| 명령 도구 | `docker` | `kubectl` | `docker service` |

## 🔁 작업별 평행 비교

### 🏗️ 설치·클러스터 구성
| 🐳 Docker | ☸️ Kubernetes | 🐝 Swarm |
| --- | --- | --- |
| [[37|도커 설치]] | [[86|K8s 설치·worker 등록]] | [[101|Swarm 설치·초기화]] |

### 🚀 웹서버 배포
| 🐳 Docker | ☸️ Kubernetes | 🐝 Swarm |
| --- | --- | --- |
| [[38|docker run으로 웹서버]] | [[87|Nginx Pod 구동]] | [[102|Nginx 서비스 배포]] |

### 🔢 복제본(스케일) 운영
| ☸️ Kubernetes | 🐝 Swarm |
| --- | --- |
| [[88|Deployment 3복제본]] | [[103|3복제본 서비스]] |

### ♻️ 롤링 업데이트
| ☸️ Kubernetes | 🐝 Swarm |
| --- | --- |
| [[90|Deployment 롤링 업데이트]] | [[104|서비스 롤링 업데이트]] |

### 🩹 자동 복구(self-healing)
| ☸️ Kubernetes | 🐝 Swarm |
| --- | --- |
| [[91|Pod 자동복구 테스트]] | [[105|Task 자동복구]] |

### 📜 로그 확인
| 🐳 Docker | ☸️ Kubernetes | 🐝 Swarm |
| --- | --- | --- |
| [[68|컨테이너 로그]] | [[97|Pod 로그]] | [[109|서비스 로그]] |

### 🔎 상태·자원 조회
| 🐳 Docker | ☸️ Kubernetes | 🐝 Swarm |
| --- | --- | --- |
| [[39|컨테이너 목록]] · [[75|자원 제한]] | [[92|리소스 조회]] · [[96|top 사용량]] | [[106|작업 상태]] · [[108|서비스 조회]] |

### 🌐 네트워크 구조
| 🐳 Docker | ☸️ Kubernetes |
| --- | --- |
| [[120|docker0 브리지 구조]] | [[123|K8s 네트워크 구조]] |

## 🔗 함께 보면 좋은 것
- 각 환경별 전체 문제 목록 → [[🐳 Docker]] · [[☸️ Kubernetes]] · [[🐝 Docker Swarm]]
