10월 29일 ~ 11월
주간보고서
디지털포렌식 트랙 정다안

[TOC]
## 1. BISC 준비 문제출제


![스크린샷 2016-10-30 오후 9.15.07.png](/Users/dan/Desktop/스크린샷 2016-10-30 오후 9.15.07.png)

[10월 29일~ 10월 30일]
```
BISC 문제 1번 2번 완료
3번 공유기세팅 필요 세팅하면 문제 완료
4번 시나리오만 완성됨 
```

## 2. 안드로이드 개발 공부

결론: 블루투스 연결하여 패킷수집이 매우 힘듬 ㅠㅠ 

앱은 
메인 엑티비티에 블루투스 연결하는 버튼을 만들고
그 버튼을 만들면 안드로이드 블루투스 연결페이지 에 액티비티 넘김
뒤로넘어와서
블루투스 연결이 확인되게하고

블루투스로 
그전에 블루투스연결
일단 아이피주소 입력칸입력할 수 있게
텍스트 어플라이해서 
라즈베리파이에 적용

라즈베리파이에서 블루투스패킷을 받으면
일단 블루투스 모듈~

라즈베리파이에서 해야할 것이 어려움...


##3. 11월 3일 블루투스  
블루투스 문제는 기기를 못찾는것..  
```{r, engine='bash', count_lines}
root@kali:~# bluetoothctl  
[bluetooth]# list  
[bluetooth]# help  
Available commands:  
	list     	List available controllers  
	show [ctrl]	Controller information  
	select <ctrl>	Select default controller  
	devices     	List available devices  
	power <on/off>	Set controller power  
	pairable <on/off>	Set controller pairable mode  
	discoverable <on/off>	Set controller discoverable mode  
	agent <on/off>	Enable/disable agent  
	scan <on/off>	Scan for devices  
	info <dev>	Device information  
	pair <dev>	Pair with device  
	trust <dev>	Trust device  
	remove <dev>	Remove device  
	connect <dev>	Connect device  
	disconnect <dev>	Disconnect device  
	version     	Display version  
	quit     	Quit program  
[bluetooth]# power on  
No default controller available  
[bluetooth]# power on  
No default controller available  
[bluetooth]#  
```





