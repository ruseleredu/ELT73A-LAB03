# ELT73A-LAB03
Atividades do LAB03

```c
// Toggle built-in LED attached to PC13
HAL_GPIO_WritePin(GPIOC, GPIO_PIN_13, GPIO_PIN_RESET); // LED ON
HAL_Delay(100); /* Insert delay 100 ms */
HAL_GPIO_WritePin(GPIOC, GPIO_PIN_13, GPIO_PIN_SET); // LED OFF
HAL_Delay(100); /* Insert delay 100 ms */
```
