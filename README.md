## FLO 운영자(Administrator) 웹 서버 애플리케이션
새로운 어드민의 RESTful API 웹 서버 애플리케이션입니다.

### 패키지 및 실행
패키지
```$xslt
mvn clean install
```

로컬 개발 환경 실행

```$xslt
mvn clean && mvn spring-boot:run -pl admin
```
### 참고
다음의 위키에 자세한 내용이 있습니다. 
http://wiki.skplanet.com/display/MUSICMATE/2.+BE

---

## floadmin.admin 패키지
- DB config 모두 다 porting (레거시 코드 다 옮겨올거니까)
- mapper & service 패키지 안에 legacy 패키지 만든다