# 2022-08-31 수요일

----

# 주제 web & HTTP 

<div style="font-size=20px">


- URI >URL > HOST >PORT


</div>


## URI

통합 자원 식별자, 인터넷에 있는 자원을 나타내는 유일한 주소이다.<br>
URI의 존재는 인터넷에 요구되는 기본 조건으로서 인터넷 프로토콜에 항상 붙는다.<br>
URI 하위 개념으로 URL, URN등이 있다. 


## URL (Uniform Resource Locator)

네트워크 상에서 자원이 어디 있는지를 알려주기 위한 규약이다.<br>
컴퓨터 네트워크와 검색 메커니즘에서의 위치를 지정하는, 웹 리소스에 대한 참조이다.<br>
웹 사이트 주소로 알고 있지만, URL은 웹 사이트 주소뿐만 아니라 컴퓨터 네트워크상의 자원을 모두 나타낼 수 있다. <br>
그 주소에 접속하려면 해당 URL에 맞는 프로토콜을 알아야 하고, 그와 동일한 프로토콜로 접속해야 한다.


+@ URN(Uniform Resource Name, 통합 자원 이름)

urn:scheme 을 사용하는 URI를 위한 이름 이다.

URI 와 URL의 차이
 

![img_17.png](img_17.png)

EX) http://opentutorials.org:3000/main?id=HTML&page=12Visit

http://opentutorials.org:3000/mainVisit  ==> URL <br>
http://opentutorials.org:3000/main?id=HTML&page=12Visit ==> URI

URL은 자원의 위치를 나타내 주는 것이고 URI는 자원의 식별자인데

?id=HTML&page=12 이 부분은 위치를 나타내는 것이 아니라 <br>
id값이 HTML이고 page가 12인 것을 나타내주는 식별하는 부분이기 때문이다.
![img_15.png](img_15.png)

![img_16.png](img_16.png)


## HOST

네트워크 호스트는 네트워크 주소가 할당된 네트워크 노드이다. <br>
모든 서버는 호스트이지만 모든 호스트가 서버인 것은 아니다.

네트워크에 연결이 확립된 모든 장치는 호스트의 자격이 있는 반면, <br>
다른 장치(클라이언트)로부터의 연결을 수락하는 호스트만 서버가 될 수 있다.

## PORT

- 운영 체제 통신의 종단점이며, 네트워크 서비스나 특정 프로세스를 식별하는 논리 단위이다. <br>
- 주로 포트를 사용하는 프로토콜은 전송 계층 프로토콜이라 하며, <br>
예를 들어 전송 제어 프로토콜(TCP)와 사용자 데이터그램 프로토콜(UDP)가 있다.
- 각 포트는 번호로 구별되며 포트 번호라고 한다. 포트 번호는 IP 주소와 함께 쓰여 해당하는 프로토콜에 의해 사용된다.

ex) WWW
URL은 기본적으로 80번 포트를 사용하므로 웹 브라우저는 자동적으로 이를 다음과 같은 의미로 처리한다.<br>
http://000.000.000.000:80