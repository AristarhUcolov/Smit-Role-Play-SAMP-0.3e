# Smit Role Play (SAMP 0.3e)

[![SA-MP](https://img.shields.io/badge/SA--MP-0.3e-orange)](https://www.sa-mp.com/)
[![Language](https://img.shields.io/badge/language-Pawn-blue)](https://www.compuphase.com/pawn/pawn.htm)
[![License](https://img.shields.io/badge/license-Open%20Source-green)]()

A Role Play gamemode for San Andreas Multiplayer (SA-MP) 0.3e.

---

## 📖 About / О проекте

### English

Hello everyone! I'm Aristarh Ucolov, also known as Jon_Stark.

Once upon a time, I was a scripter on this project. Many knew me by the nickname Jon_Stark, though most remember me as a kind Administrator =).

Back in 2016-18, I was a hidden coder on this project. I mainly released it online in 2019 and decided to upload it to GitHub as well.

Since the project is now closed, I'm sharing it here.

### Русский

Всем привет! С вами Аристарх Уколов (Aristarh Ucolov), а точнее Jon_Stark.

Когда-то давно я был скриптером на данном проекте. Многие знали меня под ником Jon_Stark, при этом помнят меня больше в формате доброго Администратора =).

В далёком 2016-18 году я был скрытным кодером на данном проекте, но в основном я выложил его в сеть в 2019 году и подумал залить на GitHub.

Поскольку проект уже закрыт, то я залью его.

---

## 📁 Project Structure / Структура проекта

```
├── gamemodes/
│   ├── Smit.pwn          # Main gamemode source code
│   └── Smit.amx          # Compiled gamemode
├── plugins/              # Server plugins
│   ├── mysql_static.so   # MySQL plugin
│   ├── streamer.so       # Object streamer plugin
│   ├── sscanf.so         # SSCANF plugin
│   ├── YSF.so            # YSF plugin
│   └── ...               # Other plugins
├── бд/
│   └── EVEBAS.sql        # Database schema
└── pawno.zip             # PAWNO compiler
```

---

## 🔧 Requirements / Требования

- SA-MP Server 0.3e
- MySQL Server
- Linux Server (plugins are `.so` files)

---

## 🚀 Installation / Установка

### English

1. Download and set up SA-MP Server 0.3e
2. Copy the `gamemodes` folder to your server directory
3. Copy the `plugins` folder to your server directory
4. Import the database schema from `бд/EVEBAS.sql` into your MySQL server
5. Configure your `server.cfg` file to use the `Smit` gamemode
6. Start the server

### Русский

1. Скачайте и установите SA-MP Server 0.3e
2. Скопируйте папку `gamemodes` в директорию сервера
3. Скопируйте папку `plugins` в директорию сервера
4. Импортируйте схему базы данных из `бд/EVEBAS.sql` в MySQL сервер
5. Настройте файл `server.cfg` для использования мода `Smit`
6. Запустите сервер

---

## 📋 Plugins Used / Используемые плагины

| Plugin | Description |
|--------|-------------|
| mysql_static | MySQL database connectivity |
| streamer | Object streaming for large maps |
| sscanf | String parsing |
| YSF | Extended SA-MP functions |
| regex | Regular expressions support |
| AntiDDoS_Guard | DDoS protection |

---

## 📝 License / Лицензия

This project is released as open source for educational and reference purposes.

---

## 👤 Author / Автор

**Aristarh Ucolov (Jon_Stark)**

---

*This is a legacy project from 2016-2019.*
