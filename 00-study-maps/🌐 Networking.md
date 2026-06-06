# 🌐 Networking

> 연결 확인 → IP/DNS 점검 → 포트 진단 → 패킷 추적 순으로 점점 깊게 들어갑니다.
> ⬅️ [[🏠 Linux Study Home]]

## 🔌 연결·기본 정보
- [[24|서버 인터넷 연결 확인 (ping/curl)]]
- [[26|서버의 IP 주소 확인 (ip/ifconfig)]]
- [[25|DNS 설정 확인 (nmcli/dig)]]

## 🚪 포트 진단·제어
- [[27|외부에 열린 포트 조회 (nmap)]]
- [[12|특정 포트 사용 중인 프로세스 찾기 (ss/fuser)]] *(프로세스와 공유)*
- [[5|80번 포트 충돌 문제 해결]] — 점유 프로세스 확인·종료
- [[10|8080 포트 차단하기 (iptables)]]

## 🔑 원격 접속
- [[9|비밀번호 없이 SSH 접속 (키 인증)]] — `ssh-keygen`, `ssh-copy-id`

## 📡 경로·패킷 추적 (심화)
- [[11|구글까지 통신 경로 추적 (traceroute)]]
- [[115|ping ICMP 패킷 추적 (tshark)]]
- [[118|구글 웹서버 TCP 패킷 추적 (tshark)]]
- [[116|google.com DNS 패킷 추적 (tshark)]]
- [[117|DNS 문제 진단하기 (dig/nslookup)]]

## 🔗 함께 보면 좋은 것
- 컨테이너 네트워크로 확장 → [[120|Docker docker0 기본 구조]] · [[123|쿠버네티스 네트워크 구조]]
- DNS 장애 복구 실습 → [[124|K8s CoreDNS 장애 재현·복구]] ([[☸️ Kubernetes]])
- SSH 접속 로그 확인 → [[14|SSH 접속 시도 로그]] ([[📑 Logs & Monitoring]])
