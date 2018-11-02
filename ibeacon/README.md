<pre>AT+RENEW 
응답:OK+RENEW
(공정초기화:짧은시간을 기다린 뒤 다음커맨드 전송)</pre>

<pre>AT+RESET 
응답:OK+RESET
(BLE리셋:짧은시간을 기다린 뒤 다음커맨드 전송)</pre>

<pre>AT
응답:OK
(OK응답이 온다면 정상상태)</pre>

<pre>AT+MARJ0X1234
응답:OK+SET:0x1234
(ibeacon의 매이저값을 0x1234로 설정, 16진수, 이 과정은 생략가능)</pre>

<pre>AT+MINO0xFA01
응답:OK+SET:0xFA01
(ibeacon의 MIN값을 0xFA01로 설정, 16진수, 이 과정은 생략가능)</pre>

<pre>AT+ADVI5
응답:OK+SET:5
(신호 송출 간격을 5로 설정)</pre>

<pre>AT+NAMEDOPEY
응답:OK+SET:DOPEY
(BLE 모듈의 이름을 DOPEY로 설정, 원하는 이름으로 변경가능)</pre>

<pre>AT+ADTY3
응답:OK+SET:3
(non-connection 상태로 만듬, 절전효과)</pre>

<pre>AT+IBEA1
응답:OK+SET:1
(iBEACON 모드로 변경)</pre>

<pre>AT+DELO2
응답:OK+DELO2
(iBEACON broadcast 전용 모드로 만듬, 절전효과)</pre>

<pre>AT+PWRM0
응답:OK+SET:0
(auto sleep 활성화, 소비전력이 감소)</pre>

<pre>AT+RESET
응답:OK+RESET
(auto sleep 활성화, 소비전력이 감소)</pre>
