# Part 1-3 Network
- GET, POST 방식의 차이점
- TCP 와 UDP 의 차이점
- HTTP 와 HTTPS 의 차이점
  - HTTP 의 문제점들
- OSI 7계층 

## GET, POST 방식의 차이점
### GET
- HTTP Request Message의 Header 부분에 url 이 담겨서 전송된다.
- url 이라는 공간에 담겨가기 때문에 전송할 수 있는 데이터의 크기가 제한적이다.
- 데이터가 키와 값이 결합된 형태로 url에 그대로 노출되므로 보안이 필요한 데이터에는 불적절하다.
### POST
- HTTP Request Message의 Body 부분에 데이터가 담겨서 전송된다.

## TCP 와 UDP 의 차이점
### TCP (Transmission Control Protocol, 전송제어 프로토콜)
- 양방향 연결형 서비스를 제공한다.
- 신뢰성 있는 경로를 확립하고 메시지 전송을 감독한다.
- 스트림 위주의 전달(패킷 단위)을 한다.
- 연결 설정은 3-way handshake 를 통해 행해진다.
### UDP
- 비연결형 서비스를 제공한다.
- 단순한 헤더 구조를 가지므로, 오버헤드가 적고, 흐름제어나 순서 제어가 없어 전송 속도가 빠르다.
- 실시간 전송에 유리하며, 신뢰성보다는 속도가 중요시되는 네트워크에서 사용된다.

## HTTP 와 HTTPS 의 차이점
### HTTP
### HTTPS

## OSI 7계층
