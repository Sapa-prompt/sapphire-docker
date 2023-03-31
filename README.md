# sapphire-docker
사파고 학생들을 위한 통합 정보 시스템의 Docker 이미지입니다.

## 설치방법
먼저 다음 명령어를 실행합니다.
```
docker build -t sapphire .
```
그 후 다음 명령어를 실행합니다.
```
docker run -p 80:80 sapphire
(포트번호 설정 구간입니다. 80은 Public, 3000은 개발용 서버로 권장)
```
## 접속방법
```
localhost:(포트번호)
```
