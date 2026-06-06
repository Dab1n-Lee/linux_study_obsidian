# 📑 Logs & Monitoring

> 문제가 생겼을 때 "어디를 봐야 하나?" — 부팅·서비스·접속 로그를 읽는 법입니다.
> ⬅️ [[🏠 Linux Study Home]]

## 📜 로그 보기
- [[13|부팅 로그 보기 (dmesg/journalctl)]]
- [[14|SSH 접속 시도 로그 확인]] — `journalctl`, `/var/log/secure`
- [[4|웹서버 404 에러 로그만 골라보기]] — `grep`, `awk`
- [[15|로그의 최신 10줄만 보기 (tail)]] — `tail -n`, `tail -f`

## ⏱️ 실행 확인
- [[30|crontab이 정상 실행됐는지 확인하기]] — `journalctl`, cron 로그 *(스케줄링과 공유)*

## 🔗 함께 보면 좋은 것
- 컨테이너/오케스트레이션 로그 → [[68|Docker 컨테이너 로그]] · [[97|K8s Pod 로그]] · [[109|Swarm 서비스 로그]]
- 로그에서 검색 → [[51|grep으로 파일내용 검색]] ([[🗂️ Files, Search & Compression]])
- 실시간 상태 감시 `watch` → [[⚙️ Process Management]] · [[☸️ Kubernetes]]
