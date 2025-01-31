## Breadboard Diagram
![image](https://github.com/user-attachments/assets/b53d4194-ec74-4cd0-8220-963a333cef1c)

This Arduino project sequentially controls five LEDs connected to digital pins 10, 9, 8, 7, and 6. The program starts by setting these pins as outputs in the setup() function. In the loop(), each LED turns on one by one with a 1-second delay, creating a cascading effect. Once all LEDs are on, they turn off in reverse order, also with a 1-second delay. This process repeats continuously, producing a light-chasing effect. To use this project, connect five LEDs with appropriate resistors (220Ω - 1kΩ) to the designated pins, upload the code to an Arduino board, and observe the LEDs lighting up sequentially before turning off in the opposite order.
