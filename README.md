# 🐧 Linux 레벨업 학습 볼트 (Obsidian)

[리얼리눅스(RealLinux) 레벨업 챌린지 실습문제](https://github.com/linuxgeek-Inc/levelup-tests)를
**Obsidian 볼트(Vault)** 로 재구성하고, 주제별 학습 지도(MOC)와 위키링크로 묶어
**그래프 뷰에서 명령어 간 관계를 시각적으로 실습**할 수 있도록 만든 개인 학습용 프로젝트입니다.

> 원본은 환경(배포판)별로 나뉜 단순한 문제 모음입니다.
> 이 볼트는 거기에 **"같은 일을 하는 명령어끼리 묶어 보는" 주제별 시점**을 더해,
> Rocky ↔ Ubuntu, Docker ↔ Kubernetes ↔ Swarm 처럼 평행 비교하며 외우기 좋게 정리했습니다.

---

## 📂 디렉터리 구조

```
linux_study_obsidian/
├── .obsidian/            # Obsidian 볼트 설정 (그래프 뷰, 플러그인 등)
├── 00-study-maps/        # ⭐ 직접 작성한 주제별 학습 지도(MOC)
│   ├── 🏠 Linux Study Home.md          # 모든 학습의 출발점
│   ├── 🧭 System Basics.md             # 시스템 기초·정보
│   ├── ⚙️ Process Management.md        # 프로세스 관리
│   ├── 📦 Package Management.md        # 패키지 관리
│   ├── 🌐 Networking.md                # 네트워크
│   ├── 📑 Logs & Monitoring.md         # 로그·모니터링
│   ├── ⏰ Scheduling (cron & at).md    # 스케줄링
│   ├── 🗂️ Files, Search & Compression.md  # 파일·검색·압축
│   ├── 🔐 Users & Permissions.md       # 사용자·권한
│   ├── 🖥️ Shell Environment & Misc.md  # 쉘 환경·라이브러리·기타
│   ├── 🐳 Docker.md
│   ├── ☸️ Kubernetes.md
│   ├── 🐝 Docker Swarm.md
│   └── 🔄 Container Orchestration Comparison.md  # 오케스트레이션 비교
└── levelup-tests/        # 원본 실습문제 (linuxgeek-Inc/levelup-tests)
    ├── quest1/ ~ quest7/ # 배포판(환경)별 문제 .md 파일
    └── README.md         # 원본 저장소의 README
```

- **`levelup-tests/`** — 원본 저장소 내용 그대로입니다. 각 문제는 `questN/문제번호.md` 형식이며, 명령어(`bash`) · 기술 태그(`tech`) · 설명(`desc`) 블록으로 구성되어 있습니다.
- **`00-study-maps/`** — 이 프로젝트에서 직접 추가한 부분입니다. 환경별로 흩어진 문제를 **주제(시스템·프로세스·네트워크·컨테이너 등)** 로 다시 묶고, `[[문제번호|설명]]` 위키링크로 원본 문제와 연결합니다. 파일명은 영어, 본문 설명은 한국어로 작성되어 있습니다.

---

## 🧭 학습 환경(퀘스트) 구성

원본 저장소는 실습 환경(배포판)에 따라 `quest1` ~ `quest7`로 나뉩니다.

| 퀘스트 | 배포판 | 문제 번호 | 문제 수 |
| --- | --- | --- | --- |
| quest1 | 🪨 Rocky-9.3 | Q.1\~15, 20\~36, 41\~67, 81\~85, 112\~118 | 64+ |
| quest2 | 🟠 Ubuntu-22.04 | Q.16\~19, 76\~80, 114 | 9+ |
| quest3 | 🐳 Docker | Q.37\~40, 68\~75, 111, 120\~122 | 12+ |
| quest4 | ☸️ Kubernetes | Q.87\~100, 123\~124 | 14+ |
| quest5 | 🐝 Swarm | Q.102\~110 | 9 |
| quest6 | ☸️ Kubernetes (설치 전용) | Q.86 | 1 |
| quest7 | 🐝 Swarm (설치 전용) | Q.101 | 1 |

🔗 **웹 기반 터미널 실습:** [reallinux.co.kr/level-up/home](https://reallinux.co.kr/level-up/home)
위 링크에서 브라우저만으로 실제 리눅스 명령어를 실습할 수 있습니다.

---

## 🚀 사용 방법

### 1. Obsidian으로 열기

1. [Obsidian](https://obsidian.md/) 을 설치합니다.
2. Obsidian 실행 → **`Open folder as vault`(폴더를 볼트로 열기)** 선택
3. 이 프로젝트 폴더(`linux_study_obsidian`)를 지정합니다.
   - `.obsidian/` 설정이 함께 들어 있어 그래프 뷰·플러그인 설정이 그대로 적용됩니다.

### 2. 학습 시작하기

1. **`00-study-maps/🏠 Linux Study Home.md`** 를 엽니다. → 모든 학습의 출발점(MOC)입니다.
2. 표에서 공부할 **주제 지도**를 선택해 들어갑니다. (예: `[[📦 Package Management]]`)
3. 주제 지도 안의 **`[[20|Rocky 패키지 설치]]`** 같은 링크를 클릭하면 원본 실습 문제로 바로 이동합니다.
4. 문제 속 명령어를 [웹 터미널](https://reallinux.co.kr/level-up/home)에서 직접 실행해 보며 익힙니다.

### 3. 그래프 뷰로 관계 파악하기 ⭐

- **`Ctrl/Cmd + G`** 로 그래프 뷰를 엽니다.
- 학습 지도(MOC)와 실습 문제들이 위키링크로 연결되어 **명령어 간의 관계가 한눈에** 보입니다.
- 한 문제가 여러 주제에 걸쳐 있으면(예: "포트를 점유한 프로세스 찾기" → 프로세스 + 네트워크) 그래프에서 자연스럽게 교차 연결점이 드러납니다.

### 4. 평행 비교로 묶어 외우기

- [[📦 Package Management]] : Rocky(`dnf`) ↔ Ubuntu(`apt`) 를 나란히 비교
- [[🔄 Container Orchestration Comparison]] : Docker ↔ Kubernetes ↔ Swarm 의 "같은 일을 하는 명령어"를 평행 배치

> 💡 배포판이 달라도 **하는 일이 같은 명령**을 나란히 보면 훨씬 빠르게 외워집니다.

---

## 🛠️ 직접 확장하기

새 문제가 추가되거나 자신만의 메모를 더하고 싶다면:

1. `levelup-tests/questN/` 에 원본 형식(`bash`/`tech`/`desc` 블록)에 맞춰 문제를 추가합니다.
2. `00-study-maps/` 의 알맞은 주제 지도에 `[[문제번호|한 줄 설명]]` 형식으로 링크를 추가합니다.
3. 그래프 뷰를 새로고침하면 새 노드가 연결된 형태로 나타납니다.

---

## 📜 출처 및 라이선스

이 볼트는 아래 저장소의 내용을 기반으로 재구성되었습니다.

- **원본 저장소:** [linuxgeek-Inc/levelup-tests](https://github.com/linuxgeek-Inc/levelup-tests)
- **제공:** 리얼리눅스(RealLinux) — [reallinux.co.kr](https://reallinux.co.kr)
- **원본 실습 환경:** [reallinux.co.kr/level-up/home](https://reallinux.co.kr/level-up/home)

> ⚠️ **라이선스에 대하여**
> 원본 저장소(`linuxgeek-Inc/levelup-tests`)에는 작성 시점 기준 **별도의 라이선스가 명시되어 있지 않습니다.**
> 따라서 `levelup-tests/` 디렉터리 안의 모든 실습문제 콘텐츠에 대한 **저작권은 원작자(linuxgeek-Inc / 리얼리눅스)에게 있습니다.**
>
> 이 프로젝트는 **개인 학습 목적**으로 원본 콘텐츠를 Obsidian 볼트 형태로 재배치하고,
> 학습 지도(`00-study-maps/`)와 위키링크를 추가한 것입니다.
> 상업적 이용이나 재배포를 원하시는 경우, 반드시 **원저작자의 허락**을 먼저 받으시기 바랍니다.
>
> 이 볼트에서 **직접 작성한 부분**(`00-study-maps/`의 학습 지도 노트, 본 README, `.obsidian` 설정)은
> 자유롭게 참고·수정하셔도 좋으나, 원본 문제 콘텐츠와는 출처가 다르다는 점을 유의해 주세요.

원본 콘텐츠의 오류 제보나 수정은 원본 저장소에 직접 기여해 주세요:
- 🐞 [Issues](https://github.com/linuxgeek-Inc/levelup-tests/issues)
- 🔧 [Pull Requests](https://github.com/linuxgeek-Inc/levelup-tests/pulls)

---

## 🙏 감사의 말

양질의 리눅스 실습 문제를 공개해 주신 **리얼리눅스(linuxgeek-Inc)** 와 레벨업 챌린지 운영진께 감사드립니다.
이 볼트는 그 문제들을 더 잘 학습하기 위한 보조 도구이며, 학습의 핵심 가치는 모두 원본 저장소에서 비롯되었음을 밝힙니다.