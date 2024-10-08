# IMEI Generator for Windows XP
![imeigen winxp screenshot](https://github.com/user-attachments/assets/2553d8dd-af72-4ddd-b6c3-bbef0b1a435b)![imeigen winxp with pm flag screenshot](https://github.com/user-attachments/assets/65be1b8f-2894-482c-a4af-49206f1b20df)

ONLY FOR WINDOWS XP & SERVER 2003. THIS PROGRAM IS NOT WORKING ON NEWER WINDOWS VERSIONS!

For newer versions of Windows, please use version based on [tkinter](https://github.com/SakuraSakuraro/imeigen/) or [pyqt5](https://github.com/SakuraSakuraro/imeigen_pyqt5/)

This adaptation for Windows XP is not forked from source code version 1.0.4. It is entirely based on alpha version (first non-public release), which was not published under any license, but this adaptation includes a number of improvements:

1. Added an analog of dropdown list from version 1.0.4 (run with "-pm" flag)
2. Added checking generated IMEIs by using Luhn algorithm (similar to 1.0.4, but realised differently)

Allowed formatting for phone_models.txt file:

(A-Z)(1-9)(A-Z)(1-9):device name:first 8 digits imei
- (A-Z) - Uppercase letters (A to Z)
- (1-9) - Digits (1 to 9)
- device name - Name of the device (only Latin letters and other symbols)
- first 8 digits imei - First 8 digits of the IMEI  (allowed only digits)

Code from version 1.0.4 is not used in any way here, and I have full right to release it under Apache 2.0 license instead of GPLv3



**Disclaimer:** This IMEI generator is intended primarily for entertainment purposes and for generating IMEIs for virtual machines for purposes of development or/and testing, but it also has uses in educational purposes. I am not responsible for any illegal use of the program (for example: generating IMEIs for stolen phones as purposes to replacing legitimate IMEIs). Users are solely responsible for their actions and use of this program. I strongly condemn any use of this program for purposes that violate Japanese laws or any countries.

I'm sincerely hope that you understand this and will not use the program for any illegal activities, ありがとうございます！
