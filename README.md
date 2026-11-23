<div align="center">

# ⚡ SMI HELPER AI BRIDGE & CONTROL CENTER
### *Next-Gen Cyberpunk Glassmorphism UI & Cloud PRO Rules Suite*

[![Theme: Cyberpunk Glassmorphism](https://img.shields.io/badge/Theme-Cyberpunk_Glassmorphism-00f3ff?style=for-the-badge&logo=css3&logoColor=white)](#-palette--design-system)
[![Tech: HTML5 & CSS3](https://img.shields.io/badge/Tech-HTML5_&_CSS3-b026ff?style=for-the-badge&logo=html5&logoColor=white)](#-ui-components)
[![Platform: Arizona RP](https://img.shields.io/badge/Platform-Arizona_RP_Drake-00ff88?style=for-the-badge&logo=target&logoColor=white)](#-pro-rules-architecture)
[![Status: Production Ready](https://img.shields.io/badge/Status-Production_Ready-ffaa00?style=for-the-badge&logo=checkmarx&logoColor=white)](#-quick-start)

<p align="center">
  <b>Ультрасовременный веб-интерфейс управления, аналитики и облачной синхронизации регламентов ПРО для СМИ Arizona RP</b>
</p>

---

</div>

## 🌌 Visual Design Concept

Интерфейс спроектирован по канонам эстетики **Cyberpunk 2077 & High-Tech HUD**:
- **Глубокий матовый фон** (`#07090e`) с градиентным свечением фоновых сфер.
- **Glassmorphism 2.0**: полупрозрачные карточки с эффектом матового стекла (`backdrop-filter: blur(20px)`), ультратонкие неоновые рамки и реактивная подсветка при наведении.
- **Микро-интерактивность**: пружинные CSS-анимации (`cubic-bezier(0.175, 0.885, 0.32, 1.275)`), плавные градиентные переходы и динамические пульсирующие индикаторы статуса.

---

## 🎨 Palette & Design System

| Элемент | Hex-код | Образец | Назначение |
| :--- | :--- | :---: | :--- |
| **Deep Void** | `#07090e` | `⬛` | Основной фон страницы |
| **Glass Card** | `rgba(13, 18, 28, 0.78)` | `🔲` | Контейнеры с размытием фона |
| **Neon Cyan** | `#00f3ff` | `🟦` | Акцентные рамки, кнопки, логотип, свечение |
| **Electric Purple** | `#b026ff` | `🟪` | Фокусы полей, бейджи, вторичные индикаторы |
| **Emerald Green** | `#00ff88` | `🟩` | Успешные статусы, валидация, готовые объявления |
| **Amber Gold** | `#ffaa00` | `🟨` | Предупреждения, лимиты символов (<= 65), важные метрики |
| **Crimson Red** | `#ff0055` | `🟥` | Отклонения, критические ошибки, блокировки |

---

## 🖥️ UI Components & Layout

1. **Top HUD Bar**:
   - Логотип с неоновым градиентом и версией ядра.
   - Живые индикаторы активных аккаунтов и состояния облачной синхронизации.
   - Кнопка мгновенной проверки состояния сервисов.
2. **Telemetry Dashboard**:
   - Статистика успешных отправок и процент соблюдения регламента.
   - Скорость обработки и уровень фильтрации ошибок.
3. **Interactive Tabs**:
   - **Управление сессиями**: визуальные карточки аккаунтов с бейджами готовности и кнопками управления.
   - **Регламент ПРО (Master Prompt)**: редактор 16 канонических разделов правил с подсветкой синтаксиса.
   - **Дообученные правила (Custom Rules)**: отдельный реестр пользовательских исключений (`CUSTOM_LEARNED_RULES.txt`).
   - **Интерактивный тренажер (Playground)**: панель мгновенного тестирования входящих текстов от игроков с визуализацией изменений.
4. **Glassmorphic Modals & Toasts**:
   - Сплывающие уведомления с таймером исчезновения.
   - Диалоговые окна подтверждения с анимацией масштабирования.

---

## 🚀 Quick Start (Запуск интерфейса)

Интерфейс полностью автономен и не требует сторонних серверов для просмотра:

1. Склонируйте или скачайте репозиторий:
   ```bash
   git clone https://github.com/alucard5552/smi-pro-rules.git
   ```
2. Откройте файл `index.html` в любом современном браузере (Chrome, Edge, Firefox, Opera, Safari).
3. Интерфейс адаптирован под любое разрешение экрана (Full HD, 2K, 4K, мобильные устройства).

---

## 📜 PRO Rules Architecture

Репозиторий служит доверенным облачным источником правил:
- **`GEMINI_NEW_CHAT_MASTER_PROMPT.txt`** — официальный регламент ПРО из 16 разделов (транспорт, недвижимость, аксессуары, бизнес, наборы в банды/мафии/БК, радиовещание).
- **`CUSTOM_LEARNED_RULES.txt`** — журнал динамически дообученных правил, добавляемых игроком непосредственно из игрового редактора.
- **`templates/ADS.json`** — эталонные шаблоны объявлений с защитой от огрызков и обрезки номеров.

---

<div align="center">
  <sub>Designed with ❤️ for Arizona RP Drake [31] • Cyberpunk Glassmorphism UI System</sub>
</div>
