# Manipulator-@D
Sterowanie manipulatorem 2D w CODESYS
# 🛠️ 2D Manipulator Control – Sterowanie Manipulatorem 2D (CODESYS)

🇵🇱 **Opis projektu**  
Ten projekt przedstawia pełny algorytm sterowania manipulatorem 2D zrealizowany w środowisku CODESYS.  
Obejmuje obsługę trybu automatycznego, ręcznego oraz pracy krokowej – z wykorzystaniem bloków funkcyjnych i maszyn stanów.

🇬🇧 **Project Description**  
This project demonstrates a complete control algorithm for a 2D manipulator developed in CODESYS.  
It includes auto/manual/step-by-step operation based on function blocks and state machines.

---

## ⚙️ Technologie / Technologies

- **Platforma / Platform:** CODESYS v3.5.16
- **Język / Language:** Structured Text (ST)
- **Biblioteki / Libraries:** Timery, R_TRIG, TON, Enums
- **Biblioteka OSCAT

---

## 🧠 Tryby pracy / Operating Modes

- 🇵🇱 **Tryb manualny** – operator steruje ręcznie  
- 🇵🇱 **Tryb automatyczny** – w pełni automatyczne sterowanie  
- 🇵🇱 **Tryb krokowy** – praca etapami, krok po kroku  

- 🇬🇧 **Manual Mode** – operator-controlled actions  
- 🇬🇧 **Auto Mode** – fully automated logic  
- 🇬🇧 **Step-by-step Mode** – state-driven sequence operation  

---

## 🧩 Zawartość projektu / Project Content

- `PLC_PRG.st` – główny program sterujący / main program logic
- Bloki funkcyjne / Function blocks:
  - `Manipulator` – sterowanie chwytakiem
  - `PrzenosnikLewy` – podajnik pokrywek / lid feeder
  - `PrzenosnikPrawy` – podajnik podstaw / base feeder
  - `ManipulatorLimit` – czujniki krańcowe / limit switches
  - `TrybPracy1`, `TrybStan_FUN` – tryby i stany pracy

---

## 🚨 Zabezpieczenia / Safety & Alarms

- Obsługa przycisku awaryjnego (Emergency Stop)
- Czasowe alarmy z czujników (np. `xPartLeaving`)
- Czujniki pozycji bazowej i limity osi X/Z

---

## 💡 Użytkowanie / How to Run

1. Otwórz projekt w **CODESYS 3.5.16**
2. Załaduj projekt i skompiluj
3. Włącz symulację lub podłącz sprzęt
4. Użyj wizualizacji (HMI), aby przetestować działanie


---

## 👤 Autor / Author

Projekt wykonany przez [Twoje Imię] w ramach nauki automatyki przemysłowej.  
Project created by [Your Name] as part of industrial automation training.
