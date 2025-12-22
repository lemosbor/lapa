[![ru](https://img.shields.io/badge/lang-ru-yellowgreen.svg)](https://github.com/lemosbor/lapa/blob/main/README.ru.md)
<p align="center">
  <img src="https://raw.githubusercontent.com/lemosbor/lapa/main/img/logo1.png">
</p>
Lapa (Russian: Лапа, paw) - split keyboard-mouse with 36 keys (40%) and mouse sensor for typing without moving the hands.

![1](img/v25_s1.jpg)

## Design
The main purpose of the Lapa allow to focus on main work and reduce the fuss of using the keyboard:
- minimizing hand and finger movement (I don't want to constantly move my hand to the mouse or move my fingers from corner to corner of the keyboard)
- minimizing visual attention on the keyboard (I don't want to shift my gaze from the PC screen to the keyboard and back; all finger movements should be intuitive). Therefore, I don't plan to include screens or LED indicators in  keydoard.
Your hands should not adapt to the keyboard; the keyboard must adapts to your hands.

![1](img/v25_s2.jpg)

## Features
- left half is also the mouse. The most important function. I don't need to to move my hand to the mouse and fuss.
- thumbstick on the right side. I use it instead of the cursor keys, and it's very convenient. The thumbstick is shaped like a bur, so my thumb grips it easily and doesn't slip.
- thumb toggle switch on the left side. I use it to switch the keyboard from the Russian alphabet to the English alphabet. The toggle switch's position is tactilely feels, so I don't need additional indicators to know which alphabet the keyboard is currently in.
- thumbstick on the left side. I use it to switch between tabs and programs on PC.
- solenoid under the left wrist. When switching layers (including automatic switching), the solenoid taps a certain number of times, so I know which layer I'm on. When (rarely) I typing English letters, the solenoid always taps slightly, so I don't confuse Russian letters with English ones.


https://github.com/user-attachments/assets/0789943b-65f5-4b6d-8f2f-c9d544a59301


![1](img/v25_s3.jpg)

## Keys
It was important to me that the keys were as light and tactile as possible.
I use Kailh White V2 switches with 30g springs.
The switches are positioned so that their center axis aligns with the axis of the distal phalanx of my finger when pressed.
To make the keys lighter, I made very lightweight oval-shaped keycaps (the shape of my fingertips and the shape of first typewriter keycaps).
This allowed me to type much easier and more accurately than on square keycaps.
At first, the round keycaps seemed odd to me, but I soon realized that for shape keyboards, they are much more aesthetically.
However, there was a problem with the gaps between the keys. The switches were visible through them, it was very ugly.
So, I designed the case so that the switches are mounted on the bottom instead of the top.
I completely repeated the shape of the switch in the case, so that they are held only by friction without latches or glue.

https://github.com/user-attachments/assets/f72d6f9e-822e-4e21-b76c-098d1167319c


![1](img/v25_s4.jpg)

## Mouse
The greatest challenge is using the keyboard as a mouse. It's difficult to design it so that it moves easily like a mouse but doesn't shift during intense typing.
A light wrist rest allows you to control the keyboard like a mouse and not have to move it while typing quickly.
For better movement, I unloaded the right half as much as possible—133g (is lighter than the MX Master mouse).
The right wrist rest is also lightened and is honeycombed perforated, improving hand contact.

![1](img/v25_s5.jpg)

## Layout

Especially for the keyboard, I developed russian layout that provides the maximum frequency of trigrams with rolls and the minimum frequency same finger.
English alphabet is mapped with the Russian alphabet by phonetic: а - a, с - s, ш - sh, etc.
The A/P-key is used to switch the alphabet.

![1](img/v25_s6.jpg)

## BOM
1. RP2040 - 2
2. Optical sensor board ADNS9800 - 1
3. Kailh Box White v2 switch - 36
4. Diodes 1N4148 - 37
5. Resistor 4.7 KOm - 2
6. Bolt M2.5 6 mm with a conical head - 6
7. Nut M2.5 - 6
8. 5-way switch - 2
9. Q24 toggle switch - 1
10. Solenoid 8-20 (3v) - 1

![4](img/v25_s7.jpg)

![1](img/v25_s8.jpg)

![1](img/v25_s9.jpg)

## [2024 version](v24.md)
## [2023 version](v23.md)

