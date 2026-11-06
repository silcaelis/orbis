<div align="center">

<img src="assets/logo.svg" alt="Orbis" width="280" />

# 🌍 Orbis

**Минималистичный TUI-лаунчер Minecraft на Rust**

🐧 Linux · 🪟 Windows · 🍎 macOS

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-00AF5C?style=flat-square)](https://www.gnu.org/licenses/gpl-3.0)
![Rust](https://img.shields.io/badge/Rust-stable-00AF5C?style=flat-square&logo=rust)

⭐ **Понравился Orbis? Поставьте звезду — это лучшая поддержка!** ⭐

</div>

---

## ✨ Возможности

| 🖥 Интерфейс | ☕ Java | 👤 Аккаунты | 🎨 Темы |
|:---:|:---:|:---:|:---:|
| Уютный TUI | Авто-подбор | Оффлайн | На выбор |

| 🌐 Языки | ⚙️ Настройки | ⬇️ Загрузки | 💻 Платформы |
|:---:|:---:|:---:|:---:|
| RU + EN | Память · JVM | Параллельно | Linux · Win · Mac |

---

## Скриншоты
<div align="center">

<img src="assets/home.svg" alt="Главная" width="30%" />
&nbsp;
<img src="assets/versions.svg" alt="Версии" width="30%" />
&nbsp;
<img src="assets/settings.svg" alt="Настройки" width="30%" />

🏠 **Главная** — аккаунт, версия, запуск  
📦 **Версии** — установлено слева, качается справа  
⚙️ **Настройки** — язык, тема, память, Java

</div>

---

## 🔨 Сборка
💡 Нужен [Rust](https://www.rust-lang.org/tools/install) и Cargo

```bash
# 1. Клонируем репозиторий
git clone https://github.com/silcaelis/orbis.git
cd orbis

# 2. Собираем релиз
cargo build --release

# 3. Готово — бинарник в target/release/orbis
