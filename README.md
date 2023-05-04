# Chrome-app
JS로 크롬앱 만들기 (노마드코더)

(https://nomadcoders.co/javascript-for-beginners)



---

1. Login 기능 구현
  
    * localstorage 이용하여 사용자 기록



2. Clock 기능 구현

	* 함수 즉시 호출
	```
	
	...
	getClock(); 	// 함수 즉시 호출 => 안해주면 00:00:00 상태에서 1초 후 현재시간 나타남 
	setInterval(getClock, 1000);
	
	```

	* padStart/padEnd 이용하여 숫자를 두자리씩 표현

	* String으로 나타내고 싶을때는 String()으로 감싸고 ()안에 코드 입력

	```
	
	String(date.getHours()).padStart(2, "0")
	
	// : 시간을 string으로 나타내고, string의 길이가 2가 아니라면 앞에 0을 추가해라
	
	```



3. Quotes 기능 구현
	
	* Math.randome 사용하여 배열에 들어 있는 값 랜덤으로 추출

	```
	Math.round() 	// ()안의 숫자 반올림
	Math.ceil() 	// ()안의 숫자 올림
	Math.floor() 	// ()안의 숫자 내림

	```





 

	
