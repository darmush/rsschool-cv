<img src="./photo.png" alt="Дарья Подскребалина" width="140" align="right" />

# Дарья Подскребалина

### Frontend Developer

Email: podskrebalina.d@hotmail.com
Telegram / WhatsApp: +7 747 850 05 37
GitHub: [darmush](https://github.com/darmush "darmush")
Discord: darmush
Портфолио: [darmush.github.io/CV](https://darmush.github.io/CV/)

---

## О себе

Опыт в дизайне и иллюстрации прокачал внимание к деталям и любовь к аккуратным, понятным интерфейсам. Год в технической поддержке добавил к этому взгляд изнутри системы — я работала с API, логами, диагностировала баги. Хочу объединить это в разработке и делать классные продукты и интерфейсы

## Навыки

**Языки программирования:** JavaScript, TypeScript
**Технологии:** Vue.js, Pinia / Vuex, Tailwind CSS, HTML, CSS / SASS
**Инструменты:** Git (GitHub / GitLab), Webpack, Figma, Illustrator, Photoshop, After Effects
**Языки:** русский — родной, английский — B1

## Опыт работы

**Специалистка технической поддержки** — Starter · 2025–2026
Обработка обращений клиентов в Helpdesk от приёма до решения, диагностика сбоев (логи, API, Postman), настройка системы в админ-панели, работа с CRM, взаимодействие с партнёрами по интеграциям (iiko, R-Keeper); автоматизация процессов скриптами и дашбордами в Metabase

**Фронтенд-разработчица (pet-проекты)** — 2024
Самостоятельная проектная работа в процессе поиска работы. Проекты и код: [darmush.github.io/CV](https://darmush.github.io/CV/)

**Личный ассистент** — 2022–2024
Организация процессов, постановка и учёт задач, составление расписаний, планирование поездок

**Самозанятая керамистка** — 2020–2021
Бренд Gribooli: производство и продажи, участие в маркетах, ведение соцсетей

**Иллюстраторка и моушн-дизайнерка** — 2018–2020
Иллюстрации и анимация для сайтов и приложений по гайдлайнам и брендбукам; работа с digital-агентствами, дизайнерами и арт-директорами (Freelance, BeaverBrothers, PixelPoint)

## Образование

**JS Course, RS School** · 2023, 2026
Самообучение по открытым материалам, pet-проекты под руководством ментора

## Пример кода

Решение задачи с Codewars (сортировка объектов по типу материала):

```javascript
function recycle(array) {
  let result = [];
  let mat = ["paper", "glass", "organic", "plastic"];

  for (let i = 0; i < mat.length; i++) {
    let count = [];
    array.forEach(function (item) {
      if (item.material == mat[i] || item.secondMaterial == mat[i]) {
        count.push(item.type);
      }
    });
    result.push(count);
  }
  return result;
}
```
