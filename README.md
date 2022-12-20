# storehouse-of-knowledge

## Hosts
```
호스트파일의 역할
 - 호스트 이름에 대응하는 IP 주소가 저장되어 있어서 도메인 이름 시스템(DNS)에서 주소 정보를 제공받지 않고도 서버의 위치를 찾게 해준다.
 
로컬 PC의 Hosts를 수정하는 이유는
보통 IT 업체에서 고객사의 웹사이트 또는 홈페이지를 서비스하고있는데 이 서비스하고있는 웹사이트를
리뉴얼할때. 운영중인서버는 그대로두고, 개발서버에서 개발한뒤. 개발서버 ip로 변경하여 확인하곤했습니다.
즉 , 로컬에서 강력하게 DNS 설정을 해서 해당 ip로 바로 접근하게해서 운영중인서버는 다른 어떤 PC에서든 접속가능하게 하고 
내가 개발할 환경에서는 개발IP를 향하도록해서 개발과 운영에 차질없이 하게 하는 것

참조 - https://crone.tistory.com/24
```


## MobaXterm을 이용한 터널링
```
보안상의 이유로 대부분의 서비스는 외부에서 접근하는 경로 및 포트를 차단하는 경우가 많다. 
그렇지만, 개발 또는 테스트를 하기 위해서 원격서버에 연결해야하는 경우가 종종있다. 
여기서는 목적지 서비스(IP:PORT)에 직접 연결이 어려운 상황에서 터널링을 통해 목적지에 도달하고
원하는 서비스(IP:PORT)에 접근하는 방법

참조 - https://cloudlab.tistory.com/entry/MobaXterm-%ED%84%B0%EB%84%90%EB%A7%81%EC%9D%84-%ED%86%B5%ED%95%B4-OpenStack-Dashboard-%EC%A0%91%EA%B7%BC-%EB%B0%8F-%ED%99%9C%EC%9A%A9
```

## 프로젝트 설정 vscode로 springboot running
```
1. 기존에 프로젝트 import후 제대로된 빌드가 되지 않아서 오류가 생겼을 때 eclipse에서 project clean후 rebuild하듯이 
   VS Code에서는 ctrl+shift+p 후 Java Clean Java Language Server Workspace를 실행해보자.

2. VS Code에서는 실행 인자 전달을 위해서는 launch.json이라는 파일에서 값을 전달할 수 있다.

3. Extentions 목록 
  - Debugger for Java
  - Extension Pack for Java
  - Gradle Extension Pack
  - Gradle for Java
  - Gradle Language Support
  - IntelliCode
  - IntelliCode API Usage Examples
  - Language Support for Java(TM) by Red Hat
  - Maven for Java
  - Project Manager for Java
  - Spring Boot Dashboard
  - Spring Boot Extension Pack
  - Spring Boot Tools
  - Spring Initializr Java Support
  - Test Runner for Java
  - Vue
  - Vue Language Features(Volar)
```
