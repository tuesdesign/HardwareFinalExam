# HardwareFinalExam

Idea: create a controller for the game Puzzle Bobble
![image](https://github.com/user-attachments/assets/e3b9d1cc-d5ed-4e1f-b7f3-95d4f6627893)
(image credit: XBOX)

The game requires the player to input an angle, and press a button to release a ball. The game displays the colors of upcoming balls to the player.
![image](https://github.com/user-attachments/assets/8d05beb4-871d-43c4-b640-bf8eeb892bc9)
Within the C is a rotary encoder, that the player can use to continually input the angle they want to aim
Within the L, Three RGB LEDs display the current and upcoming ball colours
Within the P, a push button is used to trigger the ball release, and a piezo buzzer is used for audio feedback.

I created an electronic prototype using TinkerCad. In this example, the LEDs are each set to a unique color, the pizeo is buzzing, and the button and rotary states are printed to the console. This is done to demonstrate that this would work electrically, but the real behaviour could be different.
![image](https://github.com/user-attachments/assets/18b8d9db-7dd7-40d1-839b-b3d83ce749f4)
https://www.tinkercad.com/things/0lAiLSAcy9b/editel?returnTo=%2Fdashboard&sharecode=EInS-p35oxa7BCVrA0eloDXBhGchZGWhMXeaIjozjBg
![image](https://github.com/user-attachments/assets/b4ced56e-dc0c-49f1-894e-8af54c81fba1)


I used Fusion 360 to create a 3D model of the device. I created a single body part with mounting holes for all the parts. This was done to increase structural rigidity and minimize build time. 
I wanted the large button in the middle to be made out of a squishy material, so I modeled it as part of the body - It would deform and press the micro switch underneath. It could be made out of a soft TPU or rubber. That way, you could slam the button to send the ball flying.

I had some issues importing the rotary encoder. I was unable to rename the shaft part of the encoder, and it did not import the cap, so I designed a simple one.
![image](https://github.com/user-attachments/assets/ad7d5507-8134-499f-8b82-899fb243623f)

Future improvements I would make include diffusion caps for the LEDs, holes for the piezo buzzer, and a more advanced pizeo cap that more resembles the pointer from the game.
