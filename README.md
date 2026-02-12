<div align="center">

  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&center=true&vCenter=true&width=780&lines=Hello%2C+I'm+Asem+Alroomy!;Embedded+Software+%26+Mechatronics+Engineer"
    alt="Hello, I'm Asem Alroomy"
    style="max-width:95%;"
  />
  <br/>

  <img
    src="https://github.com/SP-XD/SP-XD/blob/main/images/dev-working_rounded.gif?raw=true"
    alt="Workspace"
    style="width:360px; max-width:80%; border-radius:18px;"
  />
  <br/><br/>

  <details>
    <summary><strong>Busy building firmware & vibing to 🎧</strong></summary>

    <!-- Optional: add your Spotify user link here -->
    <!-- [![Spotify](https://spotify-readme.sp-xd.vercel.app/api/spotify)](https://open.spotify.com/user/YOUR_SPOTIFY_USER_ID) -->
  </details>

  <br/>

  <img src="https://komarev.com/ghpvc/?username=AsemAlroomy&style=flat&color=orange&label=PROFILE+VIEWS" alt="Profile Views" />

  <br/><br/>

  <a href="mailto:asem_h@outlook.com">
    <img src="https://img.shields.io/badge/Email-asem_h%40outlook.com-grey?style=flat&logo=gmail" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/asem-alroomy-6779bb18b?utm_source=share&amp;utm_campaign=share_via&amp;utm_content=profile&amp;utm_medium=ios_app">
    <img src="https://img.shields.io/badge/LinkedIn-Asem%20Alroomy-grey?style=flat&logo=linkedin" alt="LinkedIn" />
  </a>

</div>

---

## 👋 Hi, I’m **Asem Alroomy**
🧩 **Embedded Software Engineer / Mechatronics Engineer** — **R&D @ Pyramakerz (Jan 2025 – Present)**  
⚙️ I develop **embedded firmware**, implement **MCU drivers**, and integrate **sensors/actuators** into real-world prototypes and products.

---

## 🧠 What I work on
- 🧷 **Bare-metal firmware** in **C / Embedded C**
- 🔌 **MCU peripherals & drivers**: GPIO, Timers, ADC, PWM, UART, I2C, SPI, External Interrupts, ICU, EEPROM
- 🧪 **Bring-up & debugging**: datasheets, peripherals validation, hardware/software integration
- 🏗️ **R&D prototyping**: turning ideas into functional embedded systems

---

## 🚀 Tools & Tech

**Languages**  
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![Embedded C](https://img.shields.io/badge/Embedded%20C-111111?style=flat&logo=arduino&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-basic-FFD43B?style=flat&logo=python&logoColor=darkgreen)

**Embedded**  
![AVR](https://img.shields.io/badge/AVR-0A0A0A?style=flat&logo=microchip&logoColor=white)
![ARM](https://img.shields.io/badge/ARM-basic-0091BD?style=flat&logo=arm&logoColor=white)
![RTOS](https://img.shields.io/badge/RTOS-basic-222222?style=flat&logo=linux&logoColor=white)

**Tools**  
![Git](https://img.shields.io/badge/GIT-E44C30?style=flat&logo=git&logoColor=white)
![GNU/Linux](https://img.shields.io/badge/GNU%2FLinux-FCC624?style=flat&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-0078D4?style=flat&logo=visual%20studio%20code&logoColor=white)
![Proteus](https://img.shields.io/badge/Proteus-1f1f1f?style=flat)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat&logo=arduino&logoColor=white)

---

## ⭐ Featured Repositories
- 🔥 **Embedded Drivers & HAL (AVR)** — https://github.com/AsemAlroomy/REPO_NAME_1  
- 🔐 **Door Locker Security System** — https://github.com/AsemAlroomy/REPO_NAME_2  
- 📏 **Ultrasonic Distance Measuring** — https://github.com/AsemAlroomy/REPO_NAME_3  
- 🌡️ **Temperature-Based Fan Controller** — https://github.com/AsemAlroomy/REPO_NAME_4  

---

## 🧩 Highlight Projects (Embedded)
- 🔐 **Door Locker Security System (ATmega32)** — Keypad/LCD/Timers/UART/I2C/EEPROM/DC motor/Buzzer  
- 📏 **Distance Measuring System (ATmega32)** — Ultrasonic + ICU + LCD  
- 🌡️ **Fan Speed Controller w/ Temperature (ATmega32)** — LM35 + ADC + PWM + DC motor + LCD  
- ⏱️ **Stopwatch (ATmega32)** — Timers + External Interrupts + 7-Segment  

---
## 🧾 Quick “About” in C 😄

```c
/*
 * Asem Alroomy — Embedded Software / Mechatronics Engineer
 * R&D @ Pyramakerz (Jan 2025 – Present)
 * Build: drivers, peripherals, prototypes ⚙️
 */

#define COUNT_OF(x) ((int)(sizeof(x) / sizeof((x)[0])))

typedef struct {
  const char* name;
  const char* role;
  const char* org;
  const char* since;

  const char* languages[4];
  const char* mcu_focus[4];
  const char* peripherals[10];
  const char* tools[6];
  const char* platforms[3];
} Profile;

static const Profile asem = {
  .name        = "Asem Alroomy",
  .role        = "Embedded Software Engineer / Mechatronics Engineer",
  .org         = "Pyramakerz | R&D",
  .since       = "Jan 2025",

  .languages   = {"C", "Embedded C", "C++", "Python (basic)"},
  .mcu_focus   = {"AVR (ATmega32)", "ARM (basic)", "Arduino", "Bare-metal"},
  .peripherals = {"GPIO", "Timers", "ADC", "PWM", "UART", "I2C", "SPI", "EXTI", "ICU", "EEPROM"},
  .tools       = {"Git/GitHub", "Proteus", "AVR-GCC", "VS Code", "Debugging", "Datasheets"},
  .platforms   = {"GNU/Linux", "Windows", "MCU"}
};

int main(void) {
  // printf("Hi, I'm %s — %s @ %s (since %s)\n", asem.name, asem.role, asem.org, asem.since);
  // printf("Peripherals: %d | Tools: %d\n", COUNT_OF(asem.peripherals), COUNT_OF(asem.tools));
  return 0;
}
```
