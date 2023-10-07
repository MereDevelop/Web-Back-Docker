### Docker 사용방법 

> 초기 셋팅
  1. ``git clone [https_url] ``
>  실행 방법
  1. 새로운 커밋이 있다면 ``git pull origin master``
  2. 터미널에 ``docker-compose up`` 입력 📌 docker-compose.yml이 있는 위치
  3. ``http://localhost:9091/swagger-ui/#/``

      
>  주의사항
* 도커와 같은 포트를 쓰고있는 프로그램을 ``실행 전``에 미리 종료 해 두어야함
  * ``3306`` : mysql, ``9091`` : server, ``6379`` : redis
* 만약 image를 자동으로 pull되지않아 실행이 안된다면 우측 하단의 ``package``에서 직접 image들을 ``docker pull [image_name]`` 한 다음에 진행