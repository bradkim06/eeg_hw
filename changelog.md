## Version 0.2

### 2024.06.13

한샘디지텍 견적가격이 높아 단가를 낮추기 위해 개발용 보드 전용 버전으로 수정

> 추후 양산보드일때 개발보드 적용사항을 원복해야됨

단가 감소

- PCB Board size up (50x50)
- blind via 제거 (전체 레이아웃 수정)
- AVDD 전력평면 추가
- ADS1299 안쓰는핀 GND
- ADS1299 배치 변경 (Layout Reference 적용)

개발보드만 적용사항

- Pin Header size up 1.27 → 2.54mm
- PCB Size 50x50(mm)

## Version 0.1

### 2024.05.30

- Reference Circuit 확인
- bom 갱신
- EMC Layout 확인
- ERC 확인
- Gerber
- SMT 요청서

### 2024.05.29

- Sample Board 기능
  - USB-C Type Power & Charge
  - npm1300 BMS(Battery Manage System)
  - EEG 4Channel (ADS1299)
  - Dual Core Chip (NRF5340)
  - gyro accelerometer sensor (BMI270)
