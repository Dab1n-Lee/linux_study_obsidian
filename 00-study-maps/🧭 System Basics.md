# 🧭 System Basics

> 서버에 접속하면 가장 먼저 확인하는 "이 시스템은 지금 어떤 상태인가?"에 대한 명령어들입니다.
> ⬅️ [[🏠 Linux Study Home]]

## ⏱️ 시간·가동 상태
- [[1|서버가 얼마나 켜져 있었는지 보기 (uptime)]] — `uptime`, `uptime -p/-s`, `date`
- [[2|서버 시간을 한국시간(KST)으로 바꾸기]] — `timedatectl set-timezone Asia/Seoul`

## 🖥️ 하드웨어·리소스 현황
- [[41|커널 버전 확인하기 (uname)]] — `uname -a`, `/proc/version`
- [[42|메모리 사용 현황 확인 (free)]] — `free -h`, `top`
- [[43|디스크 용량 확인 (df)]] — `df -h`
- [[44|용량 많이 차지하는 폴더 찾기 (du)]] — `du -sh *`, `sort`

## 🔗 함께 보면 좋은 것
- 메모리를 많이 쓰는 **프로세스**를 찾으려면 → [[45|메모리 Top 5 프로세스]] ([[⚙️ Process Management]])
- 디스크가 가득 찼을 때 큰 파일 찾기 → [[49|find로 파일 찾기]] ([[🗂️ Files, Search & Compression]])
- 시스템 로그로 상태 추적 → [[📑 Logs & Monitoring]]
