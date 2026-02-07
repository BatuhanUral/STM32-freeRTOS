<!-- ===================== HEADER ===================== -->

<h1 align="center">FreeRTOS on STM32</h1>

<p align="center">
  Embedded Real-Time Operating System (RTOS) examples using FreeRTOS on STM32
</p>

<p align="center">

  <a href="https://www.youtube.com/@eng.BatuhanUral" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-Channel-red?logo=youtube" />
  </a>
    <a href="https://github.com/BatuhanUral" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Profile-black?logo=github" />
  </a>
  <a href="https://www.linkedin.com/in/batuhan-ural/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin" />
  </a>
</p>

<hr/>

<!-- ===================== OVERVIEW ===================== -->

## 📌 Overview

Bu repo, **STM32 mikrodenetleyiciler üzerinde FreeRTOS kullanımı**nı öğretmek amacıyla
hazırlanmış **basit, anlaşılır ve modüler** örnekler içermektedir.

Projeler:
- Eğitim amaçlıdır
- Gerçek gömülü sistem senaryolarını baz alır
- **YouTube eğitim serisi** ile birebir uyumludur

---

<!-- ===================== VIDEO ===================== -->

## 📺 Video Anlatımlar

<p align="left">
  <a href="https://www.youtube.com/@eng.BatuhanUral" target="_blank">
    <img src="Docs/Images/ytb.png" width="40" alt="YouTube Kanalım">
  </a>
  &nbsp;&nbsp;
  <a href="https://www.youtube.com/@eng.BatuhanUral">
    YouTube Eğitim Serisi
  </a>
</p>

---

<!-- ===================== CONTENT ===================== -->

## 🧠 İçerik

- Task Management  
  - Task Creation  
  - Task Notification  
  - Task Deletion  

- Inter-Task Communication  
  - Queue  
  - Binary & Counting Semaphore  
  - Mutex & Priority Inversion  

- Time Management  
  - Software Timers  
  - vTaskDelay vs vTaskDelayUntil  

- Event Management  
  - Event Groups  

- System Hooks  
  - Idle Hook  
  - Malloc Failed Hook  
  - Stack Overflow Hook  

---

<!-- ===================== WHY ===================== -->

## ❓ Neden FreeRTOS?

- Deterministic task scheduling
- Event-driven mimari
- Daha düşük CPU yükü
- Ölçeklenebilir sistem tasarımı
- Endüstriyel standart RTOS altyapısı

---

<!-- ===================== ROADMAP ===================== -->

## 🗺️ FreeRTOS Yol Haritası

Aşağıdaki diyagram, bu repoda izlenen öğrenme ve uygulama sırasını göstermektedir:

![RoadMap](Docs/Images/roadmap.png)

---

<!-- ===================== STRUCTURE ===================== -->

## 🧱 Proje Yapısı

```text
FreeRTOS-STM32/
├── Core/
│   ├── Inc/
│   └── Src/
├── FreeRTOS PDF/
├── Docs/
│   └── images/
├── README.md
