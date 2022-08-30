# 그림과 실습으로 배우는 도커&쿠버네티스
![l9791158393038](https://user-images.githubusercontent.com/110037747/184579439-40172139-4136-4324-8c49-c54e3dcc575b.jpg)

- (22.08.15) 도커, 도커 엔진, 서버, 컨테이너, 이미지, 리눅스 (Page 1 ~ 30) [도커_이론](https://github.com/karlbulee/ML/blob/main/Docker/%EB%8F%84%EC%BB%A4_%EC%9D%B4%EB%A1%A0.ipynb "도커 이론")

- (22.08.16) 이미지, 컨테이너, 도커 허브, 컨테이너 생애주기, 도커 장단점, 윈도우용 도커, WSL2, 도커 실행 조건 (Page 31 ~ 60) [도커_이론_2](https://github.com/karlbulee/ML/blob/main/Docker/%EB%8F%84%EC%BB%A4_%EC%9D%B4%EB%A1%A0_2.ipynb "도커 이론 2")

- (22.08.17) 도커 설치, 도커 데스크톱, 명령 프롬프트, 도커 엔진, 컨테이너, 커맨드, 옵션, 인자 (Page 60 ~ 89) [도커_실습](https://github.com/karlbulee/ML/blob/main/Docker/%EB%8F%84%EC%BB%A4_%EC%8B%A4%EC%8A%B5.ipynb "도커 실습")

- (22.08.18) 도커 명령어, 컨테이너 생성/삭제/실행/정지, 컨테이너 통신, 웹 브라우저, 포트(Page 90 ~ 119) [도커_실습_2](https://github.com/karlbulee/ML/blob/main/Docker/%EB%8F%84%EC%BB%A4_%EC%8B%A4%EC%8A%B5_2.ipynb "도커 실습 2")

- (22.08.19) Ngix, MySQL, Wordpress(Page 120 ~ 148) [도커_실습_3](https://github.com/karlbulee/ML/blob/main/Docker/%EB%8F%84%EC%BB%A4_%EC%8B%A4%EC%8A%B5_3.ipynb "도커 실습 3")

- (22.08.22) Redmine, MySQL, Wordpress, MariaDB, 컨테이너_호스트_파일_복사(Page 149 ~ 178) [도커_컨테이너_실습](https://github.com/karlbulee/ML/blob/main/Docker/%EB%8F%84%EC%BB%A4_%EC%BB%A8%ED%85%8C%EC%9D%B4%EB%84%88_%EC%8B%A4%EC%8A%B5.ipynb "도커 컨테이너 실습")

- (22.08.23) 스토리지 마운트, 볼륨 마운트, 바인드 마운트, 컨테이너_이미지, commit, Dockerfile(Page 179 ~ 205) [도커_컨테이너_실습_2](https://github.com/karlbulee/ML/blob/main/Docker/%EB%8F%84%EC%BB%A4_%EC%BB%A8%ED%85%8C%EC%9D%B4%EB%84%88_%EC%8B%A4%EC%8A%B5_2.ipynb "도커 컨테이너 실습 2")

- (22.08.24) 컨테이너 개조, /bin/bash, docker exec, 도커 허브, 도커 컴포즈, YAML(Page 206 ~ 239) [도커_컴포즈_이론](https://github.com/karlbulee/ML/blob/main/Docker/%EB%8F%84%EC%BB%A4_%EC%BB%B4%ED%8F%AC%EC%A6%88_%EC%9D%B4%EB%A1%A0.ipynb "도커 컴포즈 이론")

- (22.08.26) 도커 컴포즈 파일 작성, 도커 컴포즈 실행, 쿠버네티스, 마스터 노드, 워커 노드, 클러스터, 로드밸런싱(Page 240 ~ 267) [쿠버네티스_이론](https://github.com/karlbulee/ML/blob/main/Docker/%EC%BF%A0%EB%B2%84%EB%84%A4%ED%8B%B0%EC%8A%A4_%EC%9D%B4%EB%A1%A0.ipynb "쿠버네티스 이론")

- (22.08.29) 쿠버네티스 관련 용어, Pod, 서비스, 레플리카세트, 디플로이먼트, 쿠버네티스 설치, 매니페스트 파일, metadata, spec(Page 268 ~ 301) [매니페스트_파일_작성](https://github.com/karlbulee/ML/blob/main/Docker/%EB%A7%A4%EB%8B%88%ED%8E%98%EC%8A%A4%ED%8A%B8_%ED%8C%8C%EC%9D%BC_%EC%9E%91%EC%84%B1.ipynb "매니페스트 파일 작성")

- (22.08.30 / 종료) 매니페스트 서비스 파일 생성, kubectl (Page 302 ~ 327) [쿠버네티스_명령어](https://github.com/karlbulee/ML/blob/main/Docker/%EC%BF%A0%EB%B2%84%EB%84%A4%ED%8B%B0%EC%8A%A4_%EB%AA%85%EB%A0%B9%EC%96%B4.ipynb "쿠버네티스 명령어")

# Error

- (22.08.22) MySQL, MariaDB 컨테이너 생성 및 실행 시 바로 exited 문제 발생
  - 문제 원인 : 인자 띄어쓰기 문제
  - 문제 인자 : --collation-server= utf8mb4_unicode_ci
  - 해결 : - --collation-server= utf8mb4_unicode_ci => --collation-server=utf8mb4_unicode_ci
