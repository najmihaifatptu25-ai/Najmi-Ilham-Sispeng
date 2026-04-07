# Najmi-Ilham-Sispeng

Sistem monitoring suhu & kelembaban berbasis ESP32 dengan fitur **Web Dashboard** modern.

## 🌟 Fitur Utama
- **Real-time Monitoring**: Tampilan suhu DHT11 & LM35 pada OLED 128x64.
- **Web Dashboard**: Pantau data melalui browser (HTML5/CSS3).
- **Data Logging**: Backup data otomatis ke SD Card (`.csv`).
- **Cloud Integration**: Sinkronisasi otomatis ke Google Sheets via Apps Script.

## 🔌 Skema Pin (Wiring)
| Komponen | Pin ESP32 |
| :--- | :--- |
| OLED SDA / SCL | GPIO 21 / GPIO 22 |
| DHT11 Sensor | GPIO 4 |
| LM35 Analog | GPIO 34 |
| SD Card CS | GPIO 5 |

## 🛠️ Instalasi
1. Clone repository ini.
2. Buka di Arduino IDE.
3. Install library: `Adafruit SSD1306`, `DHT sensor library`, `WiFi`, `HTTPClient`.
4. Sesuaikan SSID & Password WiFi pada kode.
5. Upload ke ESP32.
