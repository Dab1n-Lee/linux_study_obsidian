# 🔐 Users & Permissions

> 계정·그룹을 만들고, 소유권과 퍼미션(rwx)을 다루는 리눅스 권한 체계의 핵심입니다.
> ⬅️ [[🏠 Linux Study Home]]

## 👤 계정·그룹
- [[53|새 유저 계정 생성하기 (useradd)]]
- [[54|현재 계정·소속 그룹 확인 (id/groups)]]
- [[55|소유자·그룹 바꾸기 (chown/chgrp)]]
- [[56|특정 그룹만 파일 접근 허용 (그룹 권한)]]

## 🔑 파일 퍼미션 (rwx)
- [[57|파일 권한 정보 확인하기 (ls -l)]]
- [[58|읽기 권한 문제 해결 (Permission denied)]]
- [[59|쓰기 권한 문제 해결 (Permission denied)]]
- [[60|실행 권한 문제 해결 (Permission denied)]]

## 🧩 종합 트러블슈팅
- [[112|Nginx 403 권한 오류 해결]] — `getfacl`/ACL, 상위 폴더 `x` 권한, `usermod -aG`

## 🔗 함께 보면 좋은 것
- 권한과 시그널로 프로세스 제어 → [[⚙️ Process Management]]
- 컨테이너 사용자 권한 → [[37|도커 그룹에 사용자 추가]] ([[🐳 Docker]])
- SSH 키 권한 → [[9|비밀번호 없이 SSH 접속]] ([[🌐 Networking]])
