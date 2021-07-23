# AWS server config with Jira issue
텍스트와 글을 저장하기 위한 RDS,s3 생성, 로그인 기능 구현 등 이슈를 Jira에 등록한 뒤 이를 바탕으로 문제 해결

## DBeaver란 DB툴을 통한 DB접근
나는 기존 mysql workbench 활용

새로운 스키마 생성; devsacti_spring_webservice
charset/collations; 강의와 같이, utf8mb4, utf8mb4_general_ci

![columns](https://user-images.githubusercontent.com/82523058/126755463-aab56727-711e-49ce-bc9c-349ab844956f.JPG)

## application.properties와 pom.xml 설정
기존 플젝도 8080이라, 8081로 설정(참고로 장고는 8000)
나의 경우, 최근 rds이고, mariadb라 정확하게 변경함

        	<dependency>
			<groupId>org.mariadb.jdbc</groupId>
			<artifactId>mariadb-java-client</artifactId>
			<scope>runtime</scope>
		</dependency>
