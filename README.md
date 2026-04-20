<div align="center">

<img src="https://raw.githubusercontent.com/MrDogez/mrdogez.github.io/main/icon.png" width="120" alt="MrDogez"/>

# MrDogez Project

**Авторская разработка программ для людей — без рекламы, телеметрии и слежки.**

[![Website](https://img.shields.io/badge/website-mrdogez.github.io-7c6aef?style=for-the-badge)](https://mrdogez.github.io)
[![Telegram](https://img.shields.io/badge/telegram-@MrDogezProject-26a5e4?style=for-the-badge&logo=telegram)](https://t.me/MrDogezProject)
[![Version](https://img.shields.io/badge/version-5.0-10b981?style=for-the-badge)](https://mrdogez.github.io#download)
[![License](https://img.shields.io/badge/license-proprietary-eab308?style=for-the-badge)](#лицензия)

<br/>

---

</div>

## 🚀 Проекты

### 🌐 [MrDogez Ultimate v5.0](https://mrdogez.github.io)

Комплексное решение для обхода интернет-блокировок на Windows.

<table>
<tr>
<td><b>🛡 27 DPI-стратегий</b></td>
<td>Автоподбор под каждого провайдера через WinDivert. Работает на Ростелекоме, МТС, Билайне, Мегафоне и других.</td>
</tr>
<tr>
<td><b>⚡ Cloudflare WARP</b></td>
<td>Туннель на базе WireGuard через Argo Smart Routing. 43 страны, минимальный пинг.</td>
</tr>
<tr>
<td><b>🎭 AmneziaWG</b></td>
<td>Fork WireGuard с junk-пакетами для обхода DPI. 7 готовых пресетов + кастомные параметры.</td>
</tr>
<tr>
<td><b>🔐 Zero Logs</b></td>
<td>Ни логов трафика, ни телеметрии, ни рекламы. Open Source — любой может провести аудит.</td>
</tr>
<tr>
<td><b>🎯 Smart Connect</b></td>
<td>Параллельный тест 20+ прокси, ISP-кэш, hot-swap реконнект. Подключение за 1.8 секунды.</td>
</tr>
<tr>
<td><b>🔒 MITM-защита</b></td>
<td>TLS 1.3 + PFS, DNS-over-HTTPS, Kill Switch, Anti-Cheat система с 12 проверками целостности.</td>
</tr>
</table>

**[⬇ Скачать v5.0](https://mrdogez.github.io#download) · [📺 Канал](https://t.me/MrDogezProject) · [💬 Поддержка](https://t.me/MrDogez)**

### 🔮 Скоро

- **MrDogez Tools** — клинер, оптимизатор Windows, zero-knowledge менеджер паролей *(конец 2026)*
- **MrDogez Mobile** — нативные приложения для Android (Kotlin) и iOS (Swift) *(лето 2026)*
- **MrDogez Linux / macOS** — полноценные сборки под Unix *(2027)*

---

## 📊 Что мы разблокировали

<div align="center">

| 📺 YouTube | 💬 Discord | ✈️ Telegram | 🎮 Steam | 🎵 Spotify |
|:---:|:---:|:---:|:---:|:---:|
| 4K без буфера | Голос + видео | Все каналы | Игры и DLC | Оригинальные плейлисты |

| 🎬 Netflix | 🐦 X (Twitter) | 📷 Instagram | 💼 LinkedIn | 🤖 ChatGPT |
|:---:|:---:|:---:|:---:|:---:|
| Регион US/EU | Стримы и твиты | Reels + Live | Сообщения | GPT-4 + Plus |

</div>

---

## 🏗 Технологический стек

<div align="center">

![Python](https://img.shields.io/badge/Python-3.14-3776ab?style=flat&logo=python&logoColor=white)
![Qt](https://img.shields.io/badge/Qt6-C++-41cd52?style=flat&logo=qt&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171a?style=flat&logo=wireguard&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_WARP-f38020?style=flat&logo=cloudflare&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-10%2F11-0078d4?style=flat&logo=windows&logoColor=white)

</div>

- **Core**: Python 3.14 + PyInstaller, Qt6 C++ frontend, WebView2 HTML UI
- **DPI Bypass**: `winws` (форк zapret), WinDivert драйвер уровня ядра
- **VPN**: WireGuard, AmneziaWG (junk-пакеты), wireproxy
- **Прокси**: sing-box (SOCKS5/V2Ray), параллельный тестер, ISP-кэш
- **DNS**: 20+ DoH резолверов (Cloudflare, Quad9, Adguard, NextDNS)
- **Backend**: Cloudflare Workers (платежи, TG-бот, анти-чит телеметрия)
- **Crypto**: PBKDF2-SHA256 (100k iter), ChaCha20-Poly1305, Curve25519

---

## 🎯 Сравнение с альтернативами

|                      | **MrDogez Ultimate** | NordVPN      | ExpressVPN   | Mullvad     |
|----------------------|:---:|:---:|:---:|:---:|
| DPI Bypass (27 стратегий) | ✅ | ❌ | ❌ | ❌ |
| Работа в РФ без обхода    | ✅ | ⚠️ | ⚠️ | ⚠️ |
| Цена за 30 дней           | **249₽** | 990₽ | 1290₽ | €5 |
| Open Source клиент        | ✅ | ❌ | ❌ | ✅ |
| Обход DPI уровня ядра     | ✅ | ❌ | ❌ | ❌ |
| WireGuard + junk packets  | ✅ | ❌ | ❌ | ❌ |

---

## 📈 Статистика

```
├─ 12,400+  Активных пользователей
├─ 847,000+ Обойдённых блокировок
├─ 99.8%    Аптайм сервиса
├─ 43       Страны подключения
├─ 27       Стратегий DPI bypass
└─ 1.8с     Среднее время подключения
```

---

## 🛠 Как установить

**Системные требования:** Windows 10/11 x64, 500 MB свободно, админ-права.

1. Скачай MSI с [mrdogez.github.io](https://mrdogez.github.io#download)
2. Запусти установщик, согласись с UAC
3. Готово — прога в меню Пуск + ярлык на рабочем столе

---

## 📜 Лицензия

**Проприетарная.** Бесплатно для личного использования. Коммерческое использование, реверс-инжиниринг, модификация или перепродажа — запрещены. См. [Пользовательское соглашение](https://mrdogez.github.io#legal).

---

## 💬 Контакты

<div align="center">

[![Telegram Bot](https://img.shields.io/badge/Telegram_Bot-@MrDogez__bot-229ed9?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/MrDogez_bot)
[![Channel](https://img.shields.io/badge/Канал-@MrDogezProject-2aabee?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/MrDogezProject)
[![Support](https://img.shields.io/badge/Поддержка-@MrDogez-0088cc?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/MrDogez)

<br/>

<sub>© 2025–2026 MrDogez Project · Сделано в России 🔥</sub>

</div>
