# 🎮 JavaScript Tetris Game | Тетрис на JavaScript

[English](#english) | [Русский](#русский)

---

## English

### 📋 Description
A classic Tetris game implementation in pure JavaScript, HTML, and CSS. This is a modern, refactored version that maintains the classic gameplay while using contemporary JavaScript syntax and best practices.

### 🎯 Features
- **Classic Tetris gameplay** with all 7 standard pieces (I, O, T, S, Z, J, L)
- **Next piece preview** - see what's coming next
- **Line clearing** with automatic scoring
- **Smooth piece rotation** and movement
- **Fast drop** functionality for quick placement
- **Game over detection** when pieces reach the top
- **Modern ES6+ JavaScript** with clean, maintainable code
- **Responsive design** that works in any modern browser

### 🎮 Game Controls
| Key | Action |
|-----|--------|
| ←→ (Arrow Keys) | Move piece left/right |
| ↓ (Down Arrow) | Fast drop (hold for continuous fast drop) |
| Spacebar | Rotate piece clockwise |

### 🏆 Scoring System
- **100 points** per completed line
- Lines are automatically cleared when completely filled
- Score is displayed in real-time during gameplay

### 🚀 Quick Start
1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. Start playing immediately - no installation required!

### 🛠️ Technical Details
- **No dependencies** - pure vanilla JavaScript
- **Modern ES6+ syntax** including:
  - Arrow functions
  - Template literals
  - Destructuring assignment
  - Array methods (map, filter, flatMap, etc.)
  - ES6 Classes
  - Const/let declarations
- **Efficient DOM manipulation** using modern APIs
- **Event-driven architecture** with clean separation of concerns
- **Configuration-based** game settings for easy customization

### 📊 Game Configuration
The game can be easily customized by modifying the `GAME_CONFIG` object:
```javascript
const GAME_CONFIG = {
    lines: 30,           // Game board height
    columns: 10,         // Game board width
    nextPreviewSize: 4,  // Preview area size
    initialDelay: 500,   // Normal fall speed (ms)
    fastDelay: 40,       // Fast drop speed (ms)
    lineScore: 100       // Points per cleared line
};
```

### 🔧 Code Structure
- **Modular design** with separated concerns
- **Clean utility functions** for game logic
- **Object-oriented approach** using ES6 classes
- **Data-driven piece definitions** for easy modification
- **Modern event handling** with efficient key mapping

### 🌟 Recent Improvements
- Refactored from legacy JavaScript to modern ES6+
- Reduced code size by ~60% while maintaining functionality
- Improved readability and maintainability
- Enhanced performance with better DOM manipulation
- Added comprehensive configuration system

---

## Русский

### 📋 Описание
Классическая реализация игры Тетрис на чистом JavaScript, HTML и CSS. Это современная, отрефакторенная версия, которая сохраняет классический геймплей, используя современный синтаксис JavaScript и лучшие практики разработки.

### 🎯 Особенности
- **Классический геймплей Тетриса** со всеми 7 стандартными фигурами (I, O, T, S, Z, J, L)
- **Предварительный просмотр** следующей фигуры
- **Очистка линий** с автоматическим подсчётом очков
- **Плавное вращение** и перемещение фигур
- **Быстрое падение** для быстрой установки фигур
- **Определение конца игры** при достижении фигурами верха поля
- **Современный JavaScript ES6+** с чистым, поддерживаемым кодом
- **Адаптивный дизайн**, работающий в любом современном браузере

### 🎮 Управление игрой
| Клавиша | Действие |
|---------|----------|
| ←→ (Стрелки) | Движение фигуры влево/вправо |
| ↓ (Стрелка вниз) | Быстрое падение (удерживайте для непрерывного быстрого падения) |
| Пробел | Поворот фигуры по часовой стрелке |

### 🏆 Система очков
- **100 очков** за каждую завершённую линию
- Линии автоматически очищаются при полном заполнении
- Счёт отображается в реальном времени во время игры

### 🚀 Быстрый старт
1. Клонируйте или скачайте этот репозиторий
2. Откройте `index.html` в любом современном веб-браузере
3. Начинайте играть немедленно - установка не требуется!

### 🛠️ Технические детали
- **Без зависимостей** - чистый vanilla JavaScript
- **Современный синтаксис ES6+**, включающий:
  - Стрелочные функции
  - Шаблонные литералы
  - Деструктурирующее присваивание
  - Методы массивов (map, filter, flatMap и др.)
  - ES6 классы
  - Объявления const/let
- **Эффективная DOM-манипуляция** с использованием современных API
- **Событийно-ориентированная архитектура** с чётким разделением ответственности
- **Конфигурационные** настройки игры для лёгкой кастомизации

### 📊 Конфигурация игры
Игру можно легко настроить, изменив объект `GAME_CONFIG`:
```javascript
const GAME_CONFIG = {
    lines: 30,           // Высота игрового поля
    columns: 10,         // Ширина игрового поля
    nextPreviewSize: 4,  // Размер области предпросмотра
    initialDelay: 500,   // Обычная скорость падения (мс)
    fastDelay: 40,       // Скорость быстрого падения (мс)
    lineScore: 100       // Очки за очищенную линию
};
```

### 🔧 Структура кода
- **Модульный дизайн** с разделением ответственности
- **Чистые утилитарные функции** для игровой логики
- **Объектно-ориентированный подход** с использованием ES6 классов
- **Данные-ориентированные определения фигур** для лёгкого изменения
- **Современная обработка событий** с эффективным маппингом клавиш

### 🌟 Недавние улучшения
- Рефакторинг с устаревшего JavaScript на современный ES6+
- Уменьшение размера кода на ~60% при сохранении функциональности
- Улучшенная читаемость и поддерживаемость
- Повышенная производительность с лучшей DOM-манипуляцией
- Добавлена комплексная система конфигурации

---

## 📝 License | Лицензия
This project is open source and available under the MIT License.

Этот проект с открытым исходным кодом и доступен под лицензией MIT.

## 🤝 Contributing | Участие в разработке
Contributions are welcome! Feel free to submit issues and pull requests.

Участие в разработке приветствуется! Не стесняйтесь отправлять issues и pull requests.

---
*Enjoy playing! | Приятной игры!* 🎉
