# config spring

## spring project git push
!! 수업과의 동일환경을 위해 bitbucket에 푸시 !!

https://bitbucket.org/devsacti/devsacti-springboot-webservice/src/master/

## deploy
/home/ec2-user에서 작업하던 스프링 부트 수업과 달리,

/ 디렉토리, 즉 루트 디렉토리에 원래 존재하는
opt라는 디렉토리에서 작업함

/opt에서 tomcat이라는 디렉토리에서 톰캣설치 후, webapp이란 디렉토리를 또 만들고 여기에 war를 올린다.

그리고 기존에 설정되서 제공된 server.xml과 가동된 톰캣을 바탕으로 review란 디렉토리가 또 생성되고 웹서비스가 실행
