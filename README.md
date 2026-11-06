# 🌍 Orbis

**Минималистичный TUI-лаунчер Minecraft на Rust**

`v0.2.0` · 🐧 Linux · 🪟 Windows · 🍎 macOS

📜 [GPLv3](https://www.gnu.org/licenses/gpl-3.0) · 🦀 Rust (stable)

⭐ **Понравился Orbis? Поставьте звезду — это лучшая поддержка!** ⭐

---

## ✨ Что умеет

| 🖥 Интерфейс | ☕ Java | 👤 Аккаунты | 🎨 Темы |
|:---:|:---:|:---:|:---:|
| Уютный TUI | Авто-подбор | Оффлайн | На выбор |

| 🌐 Языки | ⚙️ Настройки | ⬇️ Загрузки | 💻 Платформы |
|:---:|:---:|:---:|:---:|
| RU + EN | Память · JVM | Параллельно | Linux · Win · Mac |

---

## 🖼 Скриншоты

![[assets/home.svg|Главная]] ![[assets/versions.svg|Версии]] ![[assets/settings.svg|Настройки]]

- 🏠 **Главная** — аккаунт, версия, запуск
- 📦 **Версии** — установлено слева, качается справа
- ⚙️ **Настройки** — язык, тема, память, Java

> [!note] Чтобы картинки отображались в Obsidian, положи файлы `home.svg`, `versions.svg`, `settings.svg` в папку `assets` внутри хранилища.

---

## 🔨 Сборка

> [!tip] Нужен [Rust](https://www.rust-lang.org/tools/install) и Cargo

```bash
# 1️⃣ клонируем
git clone https://github.com/silcaelis/orbis.git
cd orbis

# 2️⃣ собираем релиз
cargo build --release

# 3️⃣ готово — бинарник в target/release/orbis