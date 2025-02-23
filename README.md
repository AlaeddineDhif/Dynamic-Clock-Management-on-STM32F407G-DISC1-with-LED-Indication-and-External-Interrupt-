# STM32 Clock Switching Project 🚀

This project demonstrates **dynamic system clock switching** on the STM32F407G-DISC1 using an **external interrupt (PA0)**.

## 📌 Files:
- `main.c` → Contains the main application logic.
- `stm32f4xx_it.c` → Handles external interrupts for clock switching.

## 🔧 Hardware & Tools:
- **STM32F407G-DISC1**
- **STM32CubeIDE**
- **HAL API**

## 🛠️ How It Works:
✅ **Green LED (PD12) ON when HSE is active** (168MHz) ⚡ LEDs blink fast  
✅ **Red LED (PD14) ON when HSI is active** (32MHz) ⚡ LEDs blink slow  

---

