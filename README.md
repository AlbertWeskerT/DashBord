# DashBord
<div align="center">

```
███████╗██╗   ██╗███████╗    ██████╗ ██████╗ ██████╗ ███████╗
██╔════╝╚██╗ ██╔╝██╔════╝   ██╔════╝██╔═══██╗██╔══██╗██╔════╝
███████╗ ╚████╔╝ ███████╗   ██║     ██║   ██║██████╔╝█████╗
╚════██║  ╚██╔╝  ╚════██║   ██║     ██║   ██║██╔══██╗██╔══╝
███████║   ██║   ███████║██╗╚██████╗╚██████╔╝██║  ██║███████╗
╚══════╝   ╚═╝   ╚══════╝╚═╝ ╚═════╝ ╚═════╝ ╚═╝  ╚═╝╚══════╝
```

# SYS//CORE v7.0

### Cyberpunk Life Management System

[![React](https://img.shields.io/badge/React-18.3-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-5.4-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-11-FF0055?style=for-the-badge&logo=framer&logoColor=white)](https://www.framer.com/motion/)
[![PWA](https://img.shields.io/badge/PWA-Ready-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)](https://web.dev/progressive-web-apps/)

> *"Твоє реальне життя. Геймофіковане. Оптимізоване. Оцифроване."*

</div>

---

## 🧠 Що таке SYS//CORE?

**SYS//CORE** — це персональна панель управління життям у стилі кіберпанк. Замість нудних трекерів і таблиць — термінальний інтерфейс з неоновим свіченням, XP-системою та анімованим завантаженням. Ти не просто живеш — ти **прокачуєш персонажа**.

Відстежуй біометрику, контролюй фінанси, синхронізуй розклад, виконуй місії та підвищуй рівень — все в одному інтерфейсі, оптимізованому для мобільних і десктопу.

---

## ⚡ Можливості

### 🫀 Biometrics — Моніторинг тіла
- Вага, % жиру, м'язова маса
- Пульс, якість і тривалість сну
- Візуальні графіки трендів
- Попередження про застарілі дані
- XP-нагорода за регулярні чекіни

### 💰 Economy — Фінансовий центр
- Баланс доходів, витрат і заощаджень
- Бюджетні категорії з прогрес-барами
- Трекер цілей на техніку / залізо
- Журнал транзакцій та місячний знімок

### 📡 ClassroomSync — Академічний модуль
- Сітка тижневого розкладу
- Трекер завдань і дедлайнів
- XP за предметами та стріки виконання
- Журнал оцінок і продуктивності

### 🎯 MissionLog — Місії та задачі
- Місії з XP-нагородами та рівнями складності
- Щоденні, тижневі й разові квести
- Стріки та історія виконання
- Черга пріоритетів з алертами дедлайнів

### 🔗 NeuralLink — Звички та фокус
- Ланцюги щоденних звичок
- Таймер фокус-сесій (Pomodoro-стиль)
- Візуалізація стріків
- Composite Neural Score

### 🎵 MusicPlayer — Атмосфера
- Плейлист кіберпанк-ембієнту
- Анімований візуалізатор
- Фонове відтворення

### 🚀 Система
- **Boot Sequence** — термінальна анімація запуску
- **XP & Levels** — прокачуй профіль через всі модулі
- **PWA** — встановлюй на головний екран, працює офлайн
- **Dark Cyberpunk Theme** — неон на чорному тлі

---

## 🛠 Стек технологій

| Шар | Технологія |
|---|---|
| **Framework** | React 18.3 |
| **Build Tool** | Vite 5.4 |
| **Стилі** | Tailwind CSS 3.4 + CSS-in-JS токени |
| **Анімації** | Framer Motion 11 |
| **Іконки** | Lucide React |
| **PWA** | vite-plugin-pwa + Workbox |
| **Мова** | JavaScript ES Modules |

---

## 🚀 Запуск

### Вимоги
- Node.js 18+
- npm 9+

### Встановлення

```bash
git clone https://github.com/YOUR_USERNAME/sys-core-v7.git
cd sys-core-v7
npm install
npm run dev
```

Відкрий [http://localhost:5173](http://localhost:5173)

### Збірка для продакшну

```bash
npm run build
npm run preview
```

---

## 📁 Структура проекту

```
sys-core-v7/
├── index.html
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
├── public/
│   ├── manifest.json
│   ├── service-worker.js
│   └── icons/
└── src/
    ├── main.jsx            # Точка входу React
    ├── App.jsx             # Кореневий компонент
    ├── tokens.js           # Дизайн-токени (кольори, константи)
    ├── globalCSS.js        # Глобальні стилі
    ├── hooks.js            # usePersist, usePWA, useBioStale
    ├── ui.jsx              # Shared UI-примітиви
    ├── Header.jsx          # Хедер + XP-бар + оверлей левел-апу
    ├── BootSequence.jsx    # Анімований термінальний запуск
    ├── Biometrics.jsx      # Модуль здоров'я
    ├── Economy.jsx         # Модуль фінансів
    ├── ClassroomSync.jsx   # Академічний модуль
    ├── MissionLog.jsx      # Система квестів
    ├── NeuralLink.jsx      # Звички та фокус
    ├── HardwareGoals.jsx   # Трекер цілей на техніку
    └── MusicPlayer.jsx     # Музичний плеєр
```

---

## 🎨 Дизайн-система

Кастомна система токенів у `tokens.js`:

```js
C.cyan    = "#00f0ff"  // Основний акцент
C.magenta = "#ff00ff"  // Другорядний акцент
C.green   = "#00ff88"  // Успіх / XP
C.yellow  = "#ffe600"  // Попередження
C.red     = "#ff3355"  // Небезпека / HP
C.bg      = "#07070f"  // Фон — глибокий чорний
```

---

## 📄 Ліцензія

MIT — використовуй, форкай, вдосконалюй.

---

<div align="center">

**SYS//CORE** — *Ініціалізація. Оптимізація. Домінування.*

`> SYSTEM ONLINE ██████████ 100%`

</div>
