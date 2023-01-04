# TH60JP
TH60JP is basic 60% kceyboard and support multiple layout.The feature is supported Japanese layout using CORSAIR PBT keycaps or FILCO majestouch keycaps for JP.Supporting below layouts.
![TH60JP_layout_v2](https://user-images.githubusercontent.com/39953146/207414944-4736ce80-fff7-4db2-9ceb-b5b155543873.png)

# Build
This repository is not commited qmk_firmware. So, you must do a few act.
1. Download and unzip this project.
2. Make "th60jp" directory in qmk_firmware/keyboards . 
3. Copy all contents to "th60jp" directory.
4. Run code on a comandline in qmk_firmware directory.
This is example of command.

```
make th60jp/rev2/f103:via
```
The path may change for your board because it has many revision(e.g. Prototype, Consumer, Custum...).
The directory named by varios things.
1. revx:PCB revision.
2. f103 or f303 or c6t6a: f103 is using STM32F103C8T6 and f303 is using STM32F303CBT6 and c6t6a is using STM32F103C6T6A.
