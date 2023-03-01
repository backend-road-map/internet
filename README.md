# internet

✨ 인터넷은 어떻게 작용하는가 ?
  인터넷은 웹의 핵심적인 기술이다. 인터넷의 가장 기본적인 것은, 컴퓨터들이 서로 통신 가능한 거대한 네트워크라는 것이다.

## 단순한 네트워크
두 개의 컴퓨터가 통신이 필요할 때, 우리는 다른 컴퓨터와 물리적으로 또는 무선으로 연결되어야 한다. 모든 현대 컴퓨터들은 이러한 연결 중 하나를 이용하여 연결을 지속할 있다.
이러한 네트워크는 두 대의 컴퓨터로 제한되지 않는다. 연결하고 싶은 만큼 연결할 수 있지만 컴퓨터가 늘어날 수록 직접 또는 무선으로 연결해줘야 하는 연결 경로가 많아져 복잡해진다.

이 문제를 해결하기 위해 네트워크의 각 컴퓨터는 `라우터`라고 하는 특수한 소형 컴퓨터에 연결한다. 라우터는 단 하나의 작업만을 하는데, 철도역의 신호원처럼 주어진 컴퓨터에서 보낸
메세지가 올바른 대상 컴퓨터에 도착하는지 확인한다. A컴퓨터가 B컴퓨터에 메세지를 보내고 싶을 때 라우터에게 "B컴퓨터에게 메세지를 보내고 싶어요" 하면 되는것이다.

라우터 시스템을 추가하면 기존에 각 컴퓨터끼리 연결해줘야 했던 복잡함과 추가연결 하는 컴퓨터 또한 라우터에 연결만 해주면 해당 라우터에 연결된 모든 컴퓨터와 정보를 주고 받을 수 있다.


## 네트워크 속 네트워크

이제 수백, 수천, 수십억 대의 컴퓨터를 연결하는 것은 어떨까? 라우터도 단순하게 생각하면 컴퓨터일 뿐이다. 라우터를 통해서 여러 컴퓨터를 연결했던 것처럼 해당 소규모 네트워크를 연결하는
라우터가 있다면 말이다. 컴퓨터를 라우터에 연결하고, 라우터에서 라우터로, 무한하게 확장할 수 있다.

위 방법으로 형성한 네트워크는 우리가 인터넷이라고 부르는 것에 매우 가깝지만, 우리는 뭔가 놓치고 있다. 위 방법을 통해서 친구, 이웃 등 그 누구나 연결하여 이루어진 네트워크를 가질 수 있다.
하지만 그밖에 다른 지역, 다른 나라에 케이블을 연결할 수는 없다. 이 문제를 어떻게 처리할 수 있을까? 예를 들어 전력 및 전화와 같이 이미 집에 연결된 케이블이 있다. 전화기 기반의 시설은
이미 세계 어느 곳과도 연결되어 있으므로 우리가 필요로 하는 완벽한 배선이라고 할 수 있다. 따라서 우리의 네트워크를 전화 시설과 연결하기 위해선, `모뎀`이라는 특수 장비가 필요하다.
이 모뎀은 우리 네트워크의 정보를 전화 시설에서 처리할 수 있는 정보로 바꾸며, 그 반대의 경우도 마찬가지다.

그 다음 단계는 우리의 네트워크에서 도달하려는 네트워크로 메세지를 보내는 것이다. 그렇게 하기 위해 네트워크를 인터넷 서비스 제공 업체(Internet Service Provider, ISP)에 연결한다.
ISP는 모두 함께 연결되는 몇몇 특수한 라우터를 관리하고 다른 ISP의 라우터에도 엑세스 할 수 있는 회사다. 따라서 우리 네트워크의 메세지는 ISP 네트워크의 네트워크를 통해 대상 네트워크로
전달되는 것이다. 인터넷은 이러한 전체 네트워크의 인프라로 구성된다.

## 컴퓨터 찾기

컴퓨터에 메세지를 보내려면 메세지를 받을 특정 컴퓨터를 지정해야 한다. 따라서 네트워크에 연결된 모든 컴퓨터에는 IP주소라는 고유한 주소가 있다.
이는 점으로 구분 된 네 개의 숫자로 구성된다. 예: 192.168.2.10.

컴퓨터는 이러한 주소로 다른 컴퓨토를 찾아가는데 문제가 없다. 그러나 사람은 IP주소를 기억하기 어렵다. 그래서 `도메인` 이라고 하는 사람이 읽을 수 있는 IP주소의 이름을 지정할 수 있다.
예를 들어 `googole.com` 은 IP 주소로 `173.194.121.32`이다.


## 인터넷과 웹

웹 브라우저를 사용하여 웹을 탐색 할 때 일반적으로 도메인 이름을 사용하여 웹 사이트에 접속한다. 그것은 인터넷과 웹이 같은 것을 의미할까?
이 내용은 그렇게 간단하지 않다. 앞에서 보았 듯이 인터넷은 수십억 대의 컴퓨터를 모두 연결하는 기술 인프라다. 이러한 컴퓨터들 중에 일부는 '웹 서버'로서 웹 브라우저가 이해할 수 있는
서비스를 제공한다. 인터넷은 인프라이며, 웹은 그 인프라 기반 위에 구축된 서비스이다. 웹 뿐만 아니라 인터넷 위에 구축된 다른 서비스들도 있음을 알아야한다.



출처: https://developer.mozilla.org/ko/
