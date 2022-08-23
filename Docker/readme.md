# 그림과 실습으로 배우는 도커&쿠버네티스
![l9791158393038](https://user-images.githubusercontent.com/110037747/184579439-40172139-4136-4324-8c49-c54e3dcc575b.jpg)

- (22.08.15) 도커, 도커 엔진, 서버, 컨테이너, 이미지, 리눅스 (Page 1 ~ 30) [도커_이론](https://github.com/karlbulee/ML/blob/main/Docker/%EB%8F%84%EC%BB%A4_%EC%9D%B4%EB%A1%A0.ipynb "도커 이론")

- (22.08.16) 이미지, 컨테이너, 도커 허브, 컨테이너 생애주기, 도커 장단점, 윈도우용 도커, WSL2, 도커 실행 조건 (Page 31 ~ 60) [도커_이론_2](https://github.com/karlbulee/ML/blob/main/Docker/%EB%8F%84%EC%BB%A4_%EC%9D%B4%EB%A1%A0_2.ipynb "도커 이론 2")

- (22.08.17) 도커 설치, 도커 데스크톱, 명령 프롬프트, 도커 엔진, 컨테이너, 커맨드, 옵션, 인자 (Page 60 ~ 89) [도커_실습](https://github.com/karlbulee/ML/blob/main/Docker/%EB%8F%84%EC%BB%A4_%EC%8B%A4%EC%8A%B5.ipynb "도커 실습")

- (22.08.18) 도커 명령어, 컨테이너 생성/삭제/실행/정지, 컨테이너 통신, 웹 브라우저, 포트(Page 90 ~ 119) [도커_실습_2](https://github.com/karlbulee/ML/blob/main/Docker/%EB%8F%84%EC%BB%A4_%EC%8B%A4%EC%8A%B5_2.ipynb "도커 실습 2")

- (22.08.19) Ngix, MySQL, Wordpress(Page 120 ~ 148) [도커_실습_3](https://github.com/karlbulee/ML/blob/main/Docker/%EB%8F%84%EC%BB%A4_%EC%8B%A4%EC%8A%B5_3.ipynb "도커 실습 3")

- (22.08.22) Redmine, MySQL, Wordpress, MariaDB, 컨테이너_호스트_파일_복사(Page 149 ~ 178) [도커_컨테이너_실습](https://github.com/karlbulee/ML/blob/main/Docker/%EB%8F%84%EC%BB%A4_%EC%BB%A8%ED%85%8C%EC%9D%B4%EB%84%88_%EC%8B%A4%EC%8A%B5.ipynb "도커 컨테이너 실습")

- (22.08.23) 스토리지 마운트, 볼륨 마운트, 바인드 마운트, 컨테이너_이미지, commit, Dockerfile(Page 179 ~ 205) [도커_컨테이너_실습_2](https://github.com/karlbulee/ML/blob/main/Docker/%EB%8F%84%EC%BB%A4_%EC%BB%A8%ED%85%8C%EC%9D%B4%EB%84%88_%EC%8B%A4%EC%8A%B5_2.ipynb "도커 컨테이너 실습 2")


# Error

- (22.08.22) MySQL, MariaDB 컨테이너 생성 및 실행 시 바로 exited 문제 발생
  - 문제 원인 : 인자 띄어쓰기 문제
  - 문제 인자 : --collation-server= utf8mb4_unicode_ci
  - 해결 : - --collation-server= utf8mb4_unicode_ci => --collation-server=utf8mb4_unicode_ci
