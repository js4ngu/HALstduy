# STM NUCLERO-F103RB를 이용한 HAL 라이브러리 스터디
- Peripheral
- GPIO 
  - ```c
    //PA5가 내부 LED
    HAL_GPIO_WritePin(GPIOA, GPIO_PIN_5, GPIO_PIN_SET); //H
    HAL_GPIO_WritePin(GPIOA, GPIO_PIN_5, GPIO_PIN_RESET);
    HAL_GPIO_TogglePin(GPIOA, GPIO_PIN_5);
  ```