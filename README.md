# Dino_Run_8051
Dino Run Game on 8051 Development Board

This project is a Dino Run Game implemented on an 8051 microcontroller development board. The game is displayed on a 16×2 LCD display and controlled using push buttons and DIP switches.

It is a hardware-based recreation of the classic Chrome Dino Run game, built fully in Embedded C for 8051.

📌 Features

Fun jump-and-avoid obstacles game.

Displayed on a 16×2 LCD module.

Push button / DIP switch for Dino jump control.

Real-time score tracking using 7-segment displays.

Game Over screen when Dino collides with cactus.

🛠️ Components Used

8051 Development Board (AT89C51/AT89S52).

16×2 LCD Display.

Push buttons / DIP switches for input.

7-segment displays for score.

Resistors, jumper wires, breadboard (if prototyping).

⚙️ Working

The game starts with a welcome screen on the LCD.

A cactus moves across the screen, while the Dino stays fixed.

The player uses a push button/DIP switch to make the Dino jump over the cactus.

Each avoided obstacle increases the score, displayed on 7-segment displays.

If the Dino collides with a cactus, the LCD shows “GAME OVER”.

📖 Future Improvements

Add difficulty levels (faster cactus movement).

Add sound/buzzer feedback.

Use a larger LCD or OLED for smoother graphics.

Store high scores in EEPROM.
