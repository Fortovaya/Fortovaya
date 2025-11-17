<table>
<tr>
    <td width="320" valign="top" style="padding-top: 30px; text-align: center;">
      <img src="https://github.com/Fortovaya/Fortovaya/blob/main/img/TravelSchedule.gif?raw=true" width="300" alt="TravelSchedule Demo"><br>
      <div style="text-align: center; margin: 15px 0; line-height: 1.6;">
        <img src="https://img.shields.io/badge/Architecture-MVVM-blueviolet?style=flat&logoColor=white" height="24" title="Архитектура: MVVM">
<img src="https://img.shields.io/badge/Persistence-Core_Data-0D47A1?style=flat&logo=apple&logoColor=white" height="24" title="Хранение данных: Core Data">
<img src="https://img.shields.io/badge/Settings-UserDefaults-009688?style=flat&logo=gear&logoColor=white" height="24" title="Настройки: UserDefaults">
<img src="https://img.shields.io/badge/Layout-Auto_Layout-34C759?style=flat&logo=xcode&logoColor=white" height="24" title="Вёрстка кодом, Auto Layout">
<img src="https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white" height="24" title="Swift">
<img src="https://img.shields.io/badge/UIKit-2396F3?style=flat&logo=apple&logoColor=white" height="24" title="UIKit">
<img src="https://img.shields.io/badge/CollectionView-2396F3?style=flat&logo=apple&logoColor=white" height="24" title="Сетка трекеров на UICollectionView">
<img src="https://img.shields.io/badge/Localization-RU%20%7C%20EN%20%7C%20FR-7952B3?style=flat" height="24" title="Локализация: русский, английский, французский">
<img src="https://img.shields.io/badge/Design-Figma-F24E1E?style=flat&logo=figma&logoColor=white" height="24" title="Дизайн по макетам Figma">
<img src="https://img.shields.io/badge/Analytics-Yandex_Metrica-FF6D00?style=flat" height="24" title="Аналитика: Яндекс.Метрика">
<img src="https://img.shields.io/badge/iOS-13.4%2B-000000?style=flat&logo=apple&logoColor=white" height="24" title="Минимальная версия iOS 13.4+">
      </div>
    </td>
    <td valign="top">
    
## 🚆 <sub>🔗 <a href="https://github.com/Fortovaya/TravelSchedule"> TravelSchedule </a></sub>

**Мобильное приложение для поиска и просмотра расписания поездок между станциями с использованием API Яндекс.Расписания.**

✨ **Основной функционал**

- **Поиск маршрута «откуда / куда»** с автодополнением городов и станций.
- **Экран выбора города** с live-search по названию.
- **Экран станций** выбранного города с поиском в реальном времени.
- **Экран расписания рейсов** между выбранными станциями: время отправления/прибытия, длительность, тип транспорта.
- **Фильтры маршрута** по времени отправления и наличию пересадок.
- **Карточка перевозчика**: логотип, описание, сайт, телефон, быстрый звонок и переход в браузер.
- **Лента сторис о путешествиях** с полноэкранным просмотром, индикаторами прогресса и автопереключением.
- **Экран настроек**: выбор темы (светлая/тёмная), информация о версии и об использовании API Яндекс.Расписаний.
- Обработка **состояний загрузки, ошибок и пустых списков**.
- Встроенная **аналитика поведения пользователя**.

📱 **Навигация**

- Таббар: стартовый экран расписания и экран настроек.
- Переходы между экранами по схеме **master–detail**.
- Сторис открываются **модально** поверх стартового экрана.

🔧 **Технологии**

- **SwiftUI + MVVM**, реактивный подход на **Combine**.
- **Async/await** и структурированная конкурентность.
- Кодогенерация сетевого слоя для работы с **API Яндекс.Расписаний**.
- Локализация интерфейса минимум на **русский и английский** языки.
- **Unit- и UI-тесты** основных сценариев.

🧪 **Требования**

```diff
+ Поддержка iPhone (iOS 17+)
+ Адаптивный дизайн под разные диагонали
- iPad не поддерживается
```
  <tr>
    <td width="320" valign="top" style="padding-top: 30px; text-align: center;">
      <img src="https://github.com/Fortovaya/Fortovaya/blob/main/img/Tracker.gif?raw=true" width="300" alt="Tracker Demo"><br>
      <div style="text-align: center; margin: 15px 0; line-height: 1.6;">
        <img src="https://img.shields.io/badge/Architecture-MVVM-blueviolet?style=flat&logoColor=white" height="24" title="Архитектура: MVVM">
<img src="https://img.shields.io/badge/Persistence-Core_Data-0D47A1?style=flat&logo=apple&logoColor=white" height="24" title="Хранение данных: Core Data">
<img src="https://img.shields.io/badge/Settings-UserDefaults-009688?style=flat&logo=gear&logoColor=white" height="24" title="Настройки: UserDefaults">
<img src="https://img.shields.io/badge/Layout-Auto_Layout-34C759?style=flat&logo=xcode&logoColor=white" height="24" title="Вёрстка кодом, Auto Layout">
<img src="https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white" height="24" title="Swift">
<img src="https://img.shields.io/badge/UIKit-2396F3?style=flat&logo=apple&logoColor=white" height="24" title="UIKit">
<img src="https://img.shields.io/badge/CollectionView-2396F3?style=flat&logo=apple&logoColor=white" height="24" title="Сетка трекеров на UICollectionView">
<img src="https://img.shields.io/badge/Localization-RU%20%7C%20EN%20%7C%20FR-7952B3?style=flat" height="24" title="Локализация: русский, английский, французский">
<img src="https://img.shields.io/badge/Design-Figma-F24E1E?style=flat&logo=figma&logoColor=white" height="24" title="Дизайн по макетам Figma">
<img src="https://img.shields.io/badge/Analytics-Yandex_Metrica-FF6D00?style=flat" height="24" title="Аналитика: Яндекс.Метрика">
<img src="https://img.shields.io/badge/iOS-13.4%2B-000000?style=flat&logo=apple&logoColor=white" height="24" title="Минимальная версия iOS 13.4+">
      </div>
    </td>
    <td valign="top">

## 📝 <sub>🔗 <a href="https://github.com/Fortovaya/Tracker"> Tracker </a> </sub>

**Трекинг привычек с календарём, фильтрами и подробной статистикой выполнения**

<b>✨ Основные возможности</b>

- Онбординг при первом запуске приложения.
- Создание трекеров привычек и нерегулярных событий.
- Настройка расписания по дням недели.
- Категории трекеров: добавление, редактирование, удаление.
- Выбор эмодзи и цвета для визуального различения трекеров.
- Календарь для просмотра запланированных привычек по дате.
- Поиск по названию и фильтры: все, на сегодня, завершённые, незавершённые.
- Закрепление важных трекеров в отдельный блок «Закреплённые».
- Экран статистики: лучший период, идеальные дни, завершённые трекеры, среднее значение.
- Поддержка светлой и тёмной темы.
- Локальное хранение данных о привычках (Core Data).
- 🌐 Локализация интерфейса: русский, английский, французский.

---

### 📱 Требования

```diff
+ iPhone (iOS 13+)
+ Адаптировано под iPhone SE и выше
- iPad не поддерживается
```
  <tr><td colspan="2" style="padding: 15px 0;"></td></tr>
  <tr>
   <td width="320" valign="top" style="padding-top: 30px; text-align: center;">
      <img src="https://github.com/Fortovaya/Fortovaya/blob/main/img/mockupImageFeed.gif?raw=true" width="300" alt="MovieQuiz Demo"><br>
      <div style="text-align: center; margin: 15px 0; line-height: 1.6;">
        <img src="https://img.shields.io/badge/Architecture-MVP-blueviolet?style=flat&logoColor=white" height="24" title="MVP">
        <img src="https://img.shields.io/badge/Network-URLSession-important?style=flat" height="24" title="URLSession"><br>
        <img src="https://img.shields.io/badge/Layout-AutoLayout-9cf?style=flat" height="24" title="AutoLayout">
        <img src="https://img.shields.io/badge/Testing-XCTest-009688?style=flat&logo=testing-library" height="24" title="Unit Tests"><br>
        <img src="https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white" height="24" title="Swift 5.7+">
        <img src="https://img.shields.io/badge/UIKit-2396F3?style=flat&logo=apple&logoColor=white" height="24" title="UIKit">
        <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white" height="24" title="Figma Design">
        <img src="https://img.shields.io/badge/Xcode-147EFB?logo=xcode&logoColor=white" height="24" title="Xcode">
      </div>
    </td>
    <td valign="top">
    
## 📸 <sub>🔗 <a href="https://github.com/Fortovaya/ImageFeed"> ImageFeed </a> </sub>

**Бесконечная лента фотографий** с авторизацией через Unsplash API

<b>✨ Основные возможности</b>

- ♾ Бесконечная прокрутка фотографий из [Unsplash API](https://unsplash.com/developers)
-  Авторизация через OAuth 2.0
-  Полностью программный интерфейс
-  **Просмотр** изображений с зумом
-  Профиль пользователя с данными из Unsplash
-  Лайки фотографий
-  Поделиться фотографиями
- **Синхронизация** избранного между устройствами
-  Сохранение в галерею

---

### 📱 Требования

```diff
+ iPhone (iOS 13+)
+ Только портретный режим
- iPad не поддерживается
```
  <tr><td colspan="2" style="padding: 15px 0;"></td></tr>
  <tr>
   <td width="320" valign="top" style="padding-top: 30px; text-align: center;">
      <img src="https://github.com/Fortovaya/Fortovaya/blob/main/img/mockupFive.gif?raw=true" width="300" alt="MovieQuiz Demo"><br>
      <div style="text-align: center; margin: 15px 0; line-height: 1.6;">
        <img src="https://img.shields.io/badge/Architecture-MVP-blueviolet?style=flat&logoColor=white" height="24" title="MVP">
        <img src="https://img.shields.io/badge/Network-URLSession-important?style=flat" height="24" title="URLSession"><br>
        <img src="https://img.shields.io/badge/Layout-AutoLayout-9cf?style=flat" height="24" title="AutoLayout">
        <img src="https://img.shields.io/badge/Testing-XCTest-009688?style=flat&logo=testing-library" height="24" title="Unit Tests"><br>
        <img src="https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white" height="24" title="Swift 5.7+">
        <img src="https://img.shields.io/badge/UIKit-2396F3?style=flat&logo=apple&logoColor=white" height="24" title="UIKit">
        <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white" height="24" title="Figma Design">
        <img src="https://img.shields.io/badge/Xcode-147EFB?logo=xcode&logoColor=white" height="24" title="Xcode">
      </div>
    </td>
    <td valign="top">

## 🎬 <sub>🔗 <a href="https://github.com/Fortovaya/MovieQuiz"> MovieQuiz </a> </sub>

**Интерактивный квиз** о фильмах из топ-250 IMDb с детальной статистикой ответов


<b>✨ Основной функционал</b>

- 10 вопросов о рейтинге фильмов ("Рейтинг > 7?")
- **Загрузка актуальных данных** через [IMDb API](https://imdb-api.com/api)
- Визуальный feedback (подсветка ответа)
-  Полная статистика после раунда:
   - Текущий результат
   - Лучший рекорд (с датой)
   - Средняя точность в %
-  Автопереход между вопросами (1 сек)
-  Повторная загрузка при ошибках сети
  
---

### 📱 Требования

```diff
+ Поддержка iPhone (iOS 15+)
+ Только портретный режим
- iPad и iPhone SE не поддерживаются
```
---
