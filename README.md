# Boxmine - Simple Minecraft Launcher

[🇷🇺 Русский](#русский) | [🇬🇧 English](#english)

---

## 🇷🇺 Русский

**Boxmine** — это простой графический лаунчер для Minecraft, написанный на Python. Он позволяет выбрать нужную версию игры, ввести свой никнейм и быстро запуститься. Если выбранная версия не установлена, лаунчер скачает её автоматически.

### 🛠 Используемые библиотеки
- `PyQt5` — для создания графического интерфейса (окна, кнопки, выпадающие списки).
- `minecraft-launcher-lib` — для взаимодействия с серверами Minecraft (получение списка версий, скачивание файлов игры, генерация команды для запуска).
- `uuid` — для генерации уникального идентификатора пользователя (UUID).
- `subprocess` — для непосредственного запуска процесса игры в системе.
- `sys` — для управления параметрами запуска и завершения приложения.

### 🚀 Запуск
1. Установите необходимые зависимости через pip:
   ```bash
   pip install PyQt5 minecraft-launcher-lib
   ```
2. Запустите скрипт:
   ```bash
   python main.py
   ```
*(Замените `main.py` на имя вашего файла, если оно отличается)*

### 📜 Лицензия и авторство
**Автор:** [Dynasticcamp502](https://github.com/Dynasticcamp502)

С этим кодом можно свободно делать всё что угодно: изменять, улучшать, использовать в своих проектах. Главное и единственное условие — **обязательно указывать автора оригинального кода**.

---

## 🇬🇧 English

**Boxmine** is a simple graphical Minecraft launcher written in Python. It allows you to select a game version, enter your username, and launch the game easily. If the selected version is not installed, the launcher will download it automatically.

### 🛠 Libraries Used
- `PyQt5` - for creating the Graphical User Interface (GUI).
- `minecraft-launcher-lib` - for interacting with Minecraft servers (fetching versions, downloading assets, generating launch commands).
- `uuid` - for generating a unique user identifier (UUID).
- `subprocess` - for executing the game process on your operating system.
- `sys` - for handling application startup arguments and exit status.

### 🚀 How to Run
1. Install the required dependencies using pip:
   ```bash
   pip install PyQt5 minecraft-launcher-lib
   ```
2. Run the script:
   ```bash
   python main.py
   ```
*(Replace `main.py` with your actual filename if different)*

### 📜 License & Credits
**Author:** [Dynasticcamp502](https://github.com/Dynasticcamp502)

You are completely free to do whatever you want with this code: modify it, improve it, or use it in your own projects. The only strict requirement is that you **must credit the original author**.
