
## Description
Binary BIOS file for the Winbond 25Q64 chip.
#### Where is it from?
This file was extracted from my [Lenoovo thinkpad E570](https://www.lenovo.com/gb/en/laptops/thinkpad/edge-series/Thinkpad-E570/p/22TP2TEE570) bios chip after resetting the supervisor password. 
I removed the chip and extracted the binary using a Raspberry pi. 
BIOS settings were reset to default before extracting the file.

#### History
I used to have supervisor password on my old school laptop, and the school did not know what the passord was. 
So i spent many hours on google trying to find a binary file for my bios without any luck. (Execpt from sites where i had to pay for the file). 
After many attempts i finally managed to bruteforce the password using combinations of words and numbers related to my old school.
Therefore i am now sharing it just in case somebody else should need it.

#### Usage
This file is intended to be used as a backup for bricket / locked bios, do **not** use this if you do not know what you are doing. It could possibly damage or ruin your bios chip if not done correctly!
I used this [site](https://github.com/matiassingers/awesome-readme) as a guide to extract/flash the bios chips.
