# Team30-noname
For MakeOhio 10’s Team 30


This Arduino code implements a joystick-controlled system with visual, audio, and some tactile feedback. The setup includes a joystick, LEDs, an active buzzer, and an I2C LCD screen. The joystick represents the movement of the user, which in the future will be tracked by a gyroscope sensor. The joystick's X and Y coordinates are continuously read, and based on predefined thresholds, corresponding LEDs are lit to indicate direction (left, right, forward, backward). Morse code messages are also played through the buzzer to provide additional feedback for each direction, which can also be felt by touching the buzzer. Additionally, the coordinates can only be reset to move on to the next set of directions once the user has moved the joystick within threshold. The code structure follows a modular approach, enhancing readability and maintainability, and is extensively commented.
