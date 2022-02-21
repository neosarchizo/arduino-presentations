---
marp: true
author: neosarchizo
size: 4K
---

# I2C

- 핀 2개 사용
  - SCL : 클럭 핀
  - SDA : 데이터 핀
- 주소 설정 가능
  - 최대 127개
  - `I2C address`

---

# 중복해서 사용하는 경우

- 일부 부품의 경우 주소 2개 중 선택 가능
- 주소 변경이 안되는 부품의 경우 `SPI` 통신 가능한지 확인