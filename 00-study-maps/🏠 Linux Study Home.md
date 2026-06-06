# 🏠 Linux Study Home

> 리얼리눅스 레벨업 챌린지 실습문제(`levelup-tests`)를 Obsidian에서 효율적으로 학습하기 위한 **출발점(MOC)** 입니다.
> 각 주제 지도를 따라가며 공부하고, 그래프 뷰(`Ctrl/Cmd + G`)로 명령어 간 관계를 눈으로 확인해 보세요.

---

## 🧭 주제별 학습 지도

| 지도 | 다루는 내용 |
| --- | --- |
| [[🧭 System Basics]] | 가동시간, 시간/타임존, 커널·메모리·디스크 현황 |
| [[⚙️ Process Management]] | 조회·우선순위·시그널·메모리·시스템콜 |
| [[📦 Package Management]] | Rocky(dnf) ↔ Ubuntu(apt) 평행 비교 |
| [[🌐 Networking]] | 연결확인·IP·DNS·포트·패킷추적 |
| [[📑 Logs & Monitoring]] | 부팅·SSH·서비스 로그, tail/journalctl |
| [[⏰ Scheduling (cron & at)]] | 반복 작업·일회성 예약·부팅 시 실행 |
| [[🗂️ Files, Search & Compression]] | find/locate/grep, zip/tar/gzip |
| [[🔐 Users & Permissions]] | 계정·그룹·소유권·퍼미션·ACL |
| [[🖥️ Shell Environment & Misc]] | alias·프롬프트·PATH·ldd·트러블슈팅 |
| [[🐳 Docker]] | 설치·컨테이너·이미지·볼륨·네트워크 |
| [[☸️ Kubernetes]] | Pod·Deployment·Service·운영·네트워크 |
| [[🐝 Docker Swarm]] | 서비스 배포·복제·롤링업데이트·운영 |
| [[🔄 Container Orchestration Comparison]] | Docker ↔ K8s ↔ Swarm 평행 비교 |

---

## 📚 배포판(퀘스트)별 환경

원본 저장소는 환경(배포판)에 따라 `quest1`~`quest7`로 나뉩니다.

| 퀘스트 | 배포판 | 문제 번호 |
| --- | --- | --- |
| quest1 | 🪨 Rocky-9.3 | Q.1\~15, 20\~36, 41\~67, 81\~85, 112\~118 |
| quest2 | 🟠 Ubuntu-22.04 | Q.16\~19, 76\~80, 114 |
| quest3 | 🐳 Docker | Q.37\~40, 68\~75, 111, 120\~122 |
| quest4 | ☸️ Kubernetes | Q.87\~100, 123\~124 |
| quest5 | 🐝 Swarm | Q.102\~110 |
| quest6 | ☸️ Kubernetes (설치) | Q.86 |
| quest7 | 🐝 Swarm (설치) | Q.101 |

🔗 웹 터미널 실습: [reallinux.co.kr/level-up/home](https://reallinux.co.kr/level-up/home)

---

## 💡 이 지도를 쓰는 법

1. **주제 지도부터 펼치기** — 위 표의 지도 노트를 열면 관련 문제들이 학습 순서대로 정리되어 있습니다.
2. **링크 클릭으로 이동** — `[[20|Rocky 패키지 설치]]`처럼 표시된 링크를 누르면 원본 실습 문제로 바로 이동합니다.
3. **평행 비교로 묶어 외우기** — [[📦 Package Management]]와 [[🔄 Container Orchestration Comparison]]는 배포판이 달라도 "같은 일"을 하는 명령을 나란히 보여줘 한 번에 익히기 좋습니다.
4. **그래프 뷰 활용** — 한 문제가 여러 지도에 걸쳐 있으면(예: 포트 점유 프로세스 찾기는 프로세스·네트워크 양쪽) 그래프에서 자연스럽게 연결점이 드러납니다.
