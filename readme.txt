프로젝트 폴더중 셈플게임_SampleGame이라는 파일을 압축 해제해 사용하세요.
이 안에 플레이 가능한 데모 파일이 포함되어 있습니다.

download "셈플게임_SampleGame" and unzip it,
this file conclude latest version of game server, and playable game demo

최신 버전의 서버엔진 (serverengine file):
Simple_gameServer.zip

셈플 게임 목록 (sample game file)
samplegame_pingpong.zip
셈플게임_SampleGame.zip

이 아래는 셈플 게임에 대한 설명입니다.

caution: this server contains only to two player
주의사항 : 이 코드의 서버는 정원이 2명입니다. 

you can use either example code and server code. with no restriction.
but. simple redistribution should involve link to this git page 

예제와 서버 모듈은 모두 그냥 쓰셔도 됩니다. 단순히 재배포하는 경우에는 깃허브 링크를 붙여주세요.

how to play
1. change "sever" variables in "network.py" and "sever.py" it should be your ipv4 adress in case you play in local sever. else, it should be your host ip
2. Run "network.py" in host
3. Run "client.py" in each player's pc
4. enjoy!

게임 하는법
1.  "network.py" 와 "sever.py" 코드 안에 있는 "sever" 변수를 각각 
호스트의 주소로 변경해 줍니다. 
로컬 멀티플레이의 경우에, 호스트 주소는 ipv4 주소와 동일하므로 명령 프롬프트에서 ipconfig를 입력하여 쉽게 얻을수 있습니다.
온라인 호스팅을 통해 멀티플레이하는 경우, 호스트 서버의 ip 주소를 기입해 주시면 됩니다.
2. 호스트에서 "network.py"를 실행해줍니다.
3. 각각의 컴퓨터에서 "client.py"를 실행합니다.
4. 끝~
