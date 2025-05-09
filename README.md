<table>
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
