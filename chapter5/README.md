# 스프링 마이크로서비스 코딩 공작소 개정 2판
## 5장. 스프링 클라우드 컨피그 서버로 구성 관리

### 실습한 내용
- native로 애플리케이션 외부 정보 구성
- git으로 애플리케이션 외부 정보 구성
- valut로 애플리케이션 외부 정보 구성

위의 3가지 방식 모두 LicenseController의 엔드포인트 핸들러 메서드인 GET, PUT, POST, DELETE가 정상적으로 동작하는 것을 확인하였습니다.<br>
마지막 valut 방식은 http://localhost:8200/ui/vault 에서 licensing-service를 클릭하면 default와 dev가 있는 것을 확인하였습니다.

### 구동 명령어 순서
1. mvn clean package
2. mvn package dockerfile:build
3. docker-compose up
   
