==================================================
TARGET: IOT, DATA & INTELLIGENT SYSTEMS
==================================================
GOAL UTAMA:
1. Master ESP32/ESP8266 (Logic & Programming).
2. Integrasi Sensor -> Cloud -> Dashboard (End-to-End).
3. Implementasi Machine Learning Sederhana (TinyML) di Edge.
CATATAN: Skematik rumit/PCB serahkan ke tim, fokus di Logic & Data.

--------------------------------------------------
ROADMAP & TIMELINE
--------------------------------------------------

[STAGE 1: SENSOR & ACTUATOR LOGIC (Januari - Maret)]
- [ ] Deep Dive Library ESP32 (WiFi, Bluetooth, ESP-NOW)
- [ ] Reading Multi-sensor tanpa blocking (Multitasking/FreeRTOS dasar)
- [ ] Kontrol Motor/Servo via Logic Code (bukan rakit drivernya)

[STAGE 2: CONNECTIVITY & DATA (April - Mei)]
- [ ] Protokol Komunikasi (MQTT, HTTP, WebSocket)
- [ ] Kirim data ke Platform IoT (Blynk/Thingsboard/Custom Web)
- [ ] Data Logging (Simpan data ke SD Card atau Google Sheets)

[STAGE 3: INTELLIGENCE (Juni - Seterusnya)]
- [ ] Belajar konsep TinyML (Machine Learning di Mikrokontroler)
- [ ] Project: Klasifikasi gesture atau suara sederhana
- [ ] Integrasi penuh sistem IoT ke Web Frontend

--------------------------------------------------
SYSTEM LOG
--------------------------------------------------
[Tanggal] - Modul/Sensor - Progress Logic
Contoh:
[2026-03-01] Sensor Gyroscope. Berhasil baca data X,Y,Z stabil pakai filter.
...
