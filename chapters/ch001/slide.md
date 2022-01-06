---
marp: true
author: neosarchizo
size: 4K
---

# 아두이노가 뭔가요?

---

# 그냥 AVR 보드 아냐?

---

# 아두이노 = **하드웨어 플랫폼**

---

# 하드웨어 시장

- 다양한 벤더 : ST, TI, Atmel 등
- 다양한 프로세서 : 8비트, ARM 기반 등
- 각 벤더, 프로세서의 MCU마다 명령어가 다름

---

# 만약 아두이노 호환 보드라면?


---

# 동일한 명령어로 똑같이 제어 가능

```
pinMode(D8, OUTPUT);
digitalWrite(D8, HIGH);
```

---

# 핀맵도 호환?!

---

![](https://cdn.shopify.com/s/files/1/0506/1689/3647/products/A000066_03.front_970c6014-61ab-4226-a20f-14cc6d8d682c_1000x750.jpg?v=1629816078)

---

![](https://www.open-electronics.org/wp-content/uploads/2014/02/WifiShield2.png)
출처 : https://www.open-electronics.org/a-new-wi-fi-shield-to-connect-your-arduino-to-the-internet/

---

# 아두이노의 장점은?

---

# 빠른 프로토타입 제작!!!

---

# 만약 미세먼지 측정기기를 만들고 싶다면?

---

# 바로 PCB 설계하고 제작??

---
# 현실 = 돈...

---

1. 제품에 적합한 미세먼지 센서 선정
2. 아두이노에 호환되는 미세먼지 센서 쉴드 또는 브레이크 아웃 보드 확보
3. 아두이노용 해당 센서 라이브러리 확보
4. 테스트 실시

---

# 아두이노의 단점은?

---

# 프로토타입까지는 좋은데... 양산은 좀...

---

- 제품에 대한 프로토타입을 아두이노로 빨리 개발 후 확인
- 제품 기능에 충족하는 가성비 및 공급 문제없는 MCU 선정
- 선정한 MCU를 사용한 개발 키트 확보
- 펌웨어 새로 개발
- 테스트 및 동작 확인 후 PCB 설계
- 저렴한 샘플 PCB로 보드 검증 및 테스트
- 문제 없을시 양산

---

# 5V 동작 아두이노 : 아두이노 UNO

![height:400px](https://cdn.shopify.com/s/files/1/0506/1689/3647/products/A000066_03.front_970c6014-61ab-4226-a20f-14cc6d8d682c_1000x750.jpg?v=1629816078)

---

# 5V 동작 아두이노 : 아두이노 MEGA 2560

![height:600px](https://cdn.shopify.com/s/files/1/0506/1689/3647/products/A000067_00.front_1000x750.jpg?v=1637830354)

---

# 3.3V 동작 아두이노 : 아두이노 DUE

![height:600px](https://cdn.shopify.com/s/files/1/0506/1689/3647/products/A000062_00.front_1000x750.jpg?v=1637829938)

---

# 앞으로 진행할 내용

- GPIO 제어
- 인터페이스 제어 : SPI, I2C, UART 등
- 라이브러리 만드는 방법

---

# 그 외 아두이노 관련해 배우고 싶은 것 댓글로~~