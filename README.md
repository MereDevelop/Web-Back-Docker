### Docker 사용방법 


>  실행 방법
  1. ``packages``에서 최신 도커 이미지 ``pull``
  2. 터미널에 ``docker-compose up`` 입력 📌 docker-compose.yml이 있는 위치
  3. ``http://localhost:9091/swagger-ui/#/``

      
>  주의사항
* 도커와 같은 포트를 쓰고있는 프로그램을 ``실행 전``에 미리 종료 해 두어야함
  * ``3306`` : mysql, ``9091`` : server, ``6379`` : redis
[test]