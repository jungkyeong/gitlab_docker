
1. 저장소 파일 구성
/home/git/data/gitlab 경로에 
backups  config  data  logs  ssl 추가
ssl 폴더 내에 인증서 설치

# 컨테이너 실행
docker-compose up -d
docker start gitlab

# 기존 컨테이너 삭제
docker-compose down -v


## 인증서는 무조건 [IP].key 이런 식으로 생성되어야 함
