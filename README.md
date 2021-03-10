
# Docker LAMP
Linux + Apache + MariaDB (MySQL) + PHP 8.0 on Docker Compose. Mod_rewrite enabled by default.

## 사용방법
.yml 파일이 있는 경로에서 "docker-compose up -d" 실행

## 주의사항
- 포트설정 기존컨테이너와 중복되지 않도록 (따로 파일 관리)
- db서버 계정정보 수정해야함 (따로 파일 관리)
- 서버내부 엔진을 restart 시 컨테이너가 종료되지 않도록 restart : always 필수

## 버전
- apache2 : 2.4.41
- php : 8.0.3
- mariadb : 10.5.9
