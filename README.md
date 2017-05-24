# UDPSlidingWindow-daegyeom
UDPSlidingWindow
 
 
UDP를 이용한 파일 전송 프로그램
 
UDP를 사용하여 파일을 전송하기위한 클라이언트 및 서버 프로그램을 코딩
클라이언트가 파일에 대한 정보를 보냅니다.
데이터를 전송하는 중에 오류가있을 수 있다고 가정합니다.
누락 된 데이터 그램을 탐지하고 오류가있는 데이터 그램을 복구하기 위해 "슬라이딩 윈도우 프로토콜"을 구현합니다.
수신 된 파일이 저장된 후에도 서버가 계속 실행된다.
클라이언트 프로그램에서 서버 이름과 포트 이름을 인수(argument)로 받을 수 있습니다.
서버 프로그램에서 포트 이름을 인수(argument)로 지정할 수 있습니다.


by KimDaeGyeom, YoonHyeonWoo, SeoYongJae
