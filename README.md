# MicroProcessor
마이크로프로세서 교과목에서 작업했던 코드들입니다. ARM Nucleo-F411 개발보드, Mbed OS를 사용하였습니다. 

3장. STM32F411 GPIO 
GPIO
STM32F411RE GPIO 포트 구조
GPIO 레지스터
GPIO 레지스터 위치 
레지스터 예: GPIOA_MODER
GPIO 프로그래밍 예
C/C++ 논리/비트연산
논리/비트 연산
연산자 우선순위
디지털 출력
Digital 입력/출력
mbed DigitalOut 클래스
DigitalOutt 멤버함수
DigitalOut 연산자 오버로드 
코드 LED Blink
LED 제어
LED
브레드보드
LED 회로 구현 
GPIO를 이용한 LED 제어 실습 
코드 LEDs Blink
병렬 디지털 출력 
mbed PortOut 클래스
PortOut 멤버함수
PortOut 연산자 오버로드 
코드 LEDs 동시제어 
4. 디지털 I/O DigitalIn Class
mbed DigitalIn 클래스
DigitalIn 멤버함수 
DigitalIn 연산자 오버로드
코드 - 버튼 LED ON/OFF
Tact Switch 
Pull Up/Pull Down 저항 
STM32F411 내부 풀업/다운저항
버튼 bouncing
하드웨어 디바운싱
코드, 실습회로 - 논리연산 
코드 - 2진 카운트 
5. Analog Input
아날로그 vs Digital
물리세께와 컴퓨팅시스템의 연결
Transducer 
ADC
DAC 
STM32 ADC 
SAR 
mebed API AnalogIn class 
클래스
생성자
멤버함수
연산자 오버로드
가변저항
가변저항 입력 테스트 
아날로그입력 회로
코드 - 아날로그 입력 
Nucleo 보드 모니터링 
Nucleo 시리얼 포트
터미널 프로그램 연결 
코드 - 시리얼 통신 테스트
printf() %f 지정자 사용하기 
—-------------------
기말
6. 센서 응용
	온도센서 LM35DZ
		온도센서 LM35DZ
		LM35DZ 온도계산 
		LM35DZ 회로
		TMP36 온도센서
		TMP36GT 온도계산
		코드 5-1-1 : 온도측정 LM35DZ 
		실습문제 5-1 
	조도센서 (CdS 센서)
		CdS 조도센서
		CdS 조도센서 저항
		전압분배
		CdS 조도센서 회로
		코드 5-2: 조도측정
		실습문제 5-2
	거리측정센서 HC-SR04
		능동(active) 거리 측정 센서
		HC-SR04 초음파 센서
		HC-SR04를 이용한 거리 측정
		HC-SR04 실습회로 
		Mbed Timer API
		코드 5-3: 거리측정
		실습문제 5-3 
	수동적외선(PIR)센서 - Arduino PIR 모듈 
		Passive Infra-Red 센서
		YwRobot PIR 센서모듈 
		PIR 실습 회로 
		코드 5-4 움직임 감지 
		연습문제 5-4 
7. 통신 인터페이스 응용
3p I2C (Inter-Integrated Curcuit)
4p I2C 버스구조
5p 논리게이트 출력 타입
6p Open Collector(Drain)
7p STM32F411 GPIO 핀 구조
8p I2C 어드레스
9p I2C 기본 동작
10p 버스 동작 예: WRITE
11p 버스 동작 예: READ
14p mbed I2C class
19p DS3231 Real Time Clock
21p RTC 내부 동작 예시
22p DS3231 내부 레지스터
23p RTC 실습회로
24p 코드 6-1 : I2C 주소 스캐닝
26p 코드 6-2: DS3231 시간설정
32p 실습문제 6-1
33p 실습문제 6-2: DS3231 내장기능

8. SSD1306 OLED 모듈
2p OLED 디스플레이
3p SSD1306 OLED 모듈
4p SSD1306 디스플레이 메모리
5p Adafruit_SSD1306_I2C class
7p SSD1306 OLED 실습회로
8p mbed Adafruit_SSD1306 라이브러리 import
9p mbed Adafruit_SSD1306 라이브러리 수정
10p 코드 7-1: OLED 제어 
13p 실습문제 7-1
14p 실습문제 7-2
9. Timer/Counter PWM 응용
	Timer/Counter
	Modulation
	PWM
	PWM 듀티사이클
	STM32F411 Timers
	STM32F4 Timer 예
	STM32F4 PWM 펄스 생성 
	Mbed PWM API
	Nucleo-F411 PWM pins 
	LED 밝기 제어
	코드 8-1: LED 밝기 제어
	실습문제 8-1
	Buzzer 제어
		피에조(Piezo) 소자
		피에조 버저(Buzzer)
		부저 회로
		코드 8-2: 버저 제어
		실습문제 8-2
11. Interrupt
Cortex-M 인터럽트
Mbed InterruptIn Class
	비동기 이벤트
	인터럽트 처리 기본
	고려할 사항들
Cortex M4 Interrupt 개요
	Cortex-M4 Exceptions
	System Exception
	External Interrupt
	NVIC
	Cortex-M 레지스터 
	레지스터 값 저장
	Interrupt Vector Table
	인터럽트 처리 사이클 
GPIO 외부인터럽트 EXTIn
	EXTIn 외부인터럽트
	GPIO 외부인터럽트 처리과정
	GPIO 인터럽트 설정 코드 예
mebed InterruptIn class
	InterruptIn 클래스
	클래스 생성자
	클래스 메쏘드
		ISR
	코드 10-1: 인터럽트 연습
	연습문제 10-1
	연습문제 10-2
	연습문제 10-3
	연습문제 10-4
12. RTOS
mbed RTOS 활용
RTOS
mbed RTOS API
	Real Time Operating System
	임베디드 프로그램 구조
	mbed RTOS API
	mbed RTOS Thread API
	클래스 생성자
	클래스 메쏘드
	RTOS 연습
	코드 11-1
	연습문제 11-1 
	연습문제 11-2 
