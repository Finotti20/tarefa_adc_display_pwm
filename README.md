![68747470733a2f2f736f667465782e62722f77702d636f6e74656e742f75706c6f6164732f323032342f30392f456d6261726361546563685f6c6f676f5f417a756c2d31303330783432382e706e67](https://github.com/user-attachments/assets/efd58ef1-331a-4978-bb80-52925d9d4b1b)

📟 **Display OLED (SSD1306) via I2C**

🎮 **Joystick Analógico** (VRX e VRY)

🔘 **Botões físicos** (SW, A e B)

💡 **LEDs controlados** por PWM


**Fluxo do Código**

1️⃣ **Inicialização**

Configura **I2C** para o **display OLED**

Configura **ADC** para ler **VRX** e **VRY**

Configura **PWM** para os **LEDs**

Configura **botões e interrupções**

2️⃣ **Loop Principal**

Lê os valores do joystick

Atualiza a posição do quadrado na tela

Alterna a borda do display com o SW_PIN

Controla o brilho dos LEDs com PWM

Aguarda 100ms e repete

3️⃣ **Interrupções**

**SW_PIN** → Alterna borda e LED3

**BUTTON_A** → Liga/desliga LED vermelho

**BUTTON_B** → Liga/desliga LED azul

Vídeo explicativo: https://youtu.be/VH5nGM-DdCQ
