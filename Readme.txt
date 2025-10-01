
1. 저장소 파일 구성
/home/git/data/gitlab 경로에 
backups  config  data  logs  ssl 추가

# 컨테이너 실행
docker-compose up -d
docker start gitlab

# 기존 컨테이너 삭제
docker-compose down -v