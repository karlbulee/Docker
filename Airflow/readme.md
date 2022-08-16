# Apache Airflow 기반의 데이터 파이프라인
![l9791191600681](https://user-images.githubusercontent.com/110037747/184601137-bd9427fa-4570-4123-bc30-5b3d58dd64b2.jpg)

- (22.08.15) schedule_interval, Cron, timedelta, 증분, execution_date, 데이터 파티셔닝, catchup, 원자성, 멱등성 (Page 36 ~ 66) [Airflow_스케줄링](https://github.com/karlbulee/ML/blob/main/Airflow/Airflow_%EC%8A%A4%EC%BC%80%EC%A4%84%EB%A7%81.ipynb "Airflow_스케줄링")

# Error
1. 2022.08.11 
- Windows 10 conda 환경에서 실행 시 airflow webserver 명령어에서 패키지 문제 발생(pwd : 리눅스에서 위치 알려주는 명령어)
- 결정적으로 airflow 내부 소스에서 UNIX 호환 시스템에서만 사용할 수 있는 pwd 라이브러리를 사용하기에 결론적으론 성공 사례를 찾을 수 없었다
- 출처 : https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=occidere&logNo=221773113221
