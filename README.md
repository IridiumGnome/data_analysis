> copy link to HTML file here to see reports https://html-preview.github.io/

# Проекты по анализу данных / Data Analysis Projects

Коллекция проектов по анализу данных в области телекоммуникаций, мобильных приложений, игровой индустрии, общественного питания и здравоохранения.

A collection of data analysis projects covering telecom, mobile apps, gaming, food service, and healthcare domains.

---

## [NPS](./NPS/NPS.ipynb) — Лояльность клиентов телеком-компании / Telecom Customer Loyalty

**RU:** Анализ индекса потребительской лояльности (NPS) для российской телекоммуникационной компании на основе данных из SQLite-базы. Клиенты сегментированы по возрасту, объёму трафика, стажу, геолокации и типу устройства. Результаты выгружены в CSV и визуализированы в дашборде Tableau.

**EN:** Analysis of Net Promoter Score (NPS) for a Russian telecom company using data from a SQLite database. Customers are classified into promoters, passives, and detractors, then segmented by age, traffic usage, tenure, location, and device type. Results exported to CSV and visualized in a Tableau dashboard.

---

## [SQL](./SQL/SQL_books.ipynb) — Анализ базы книг / Book Database Analysis

**RU:** SQL-анализ базы данных книг (1 000 наименований) для формирования ценностного предложения нового сервиса по подписке на книги. Определён ведущий издатель по объёму (Penguin Books — 42 книги), найден автор с наивысшим средним рейтингом среди популярных книг (Дж. К. Роулинг — 4,29), проанализировано поведение активных рецензентов.

**EN:** SQL-based analysis of a book database (1,000 titles) to shape the value proposition of a new book subscription service. Identified the top publisher by volume (Penguin Books — 42 books), the highest-rated popular author (J.K. Rowling — 4.29 avg), and analyzed power-user review behavior.

---

## [App Analysis](./app_analysis/app.ipynb) — Анализ мобильного приложения «Ненужные вещи» / Mobile Classifieds App Analysis

**RU:** Анализ поведения пользователей мобильного приложения для продажи вещей: 74 197 событий от 4 293 пользователей за октябрь–ноябрь 2019 года. Построены воронки конверсий и диаграммы Санкей, проверены гипотезы о конверсии по источникам трафика. Пользователи Google конвертируются чаще, пользователи Яндекса — быстрее.

**EN:** User behavior analysis for a classifieds mobile app with 74,197 events from 4,293 users (Oct–Nov 2019). Built conversion funnels (tips_show → contacts_show: 18%) and Sankey diagrams. Tested statistical hypotheses by traffic source — Google users convert more often, Yandex users convert faster.

---

## [Food Places](./food_places/food_places.ipynb) — Рынок общепита Москвы / Moscow Food Service Market

**RU:** Исследование рынка общественного питания Москвы: 8 406 заведений (лето 2022). Заведения разбиты по типам и районам, построены географические карты, проведён сравнительный анализ сетевых и несетевых форматов, рейтингов и среднего чека. Отдельно изучен сегмент кофеен (1 413 заведений).

**EN:** Market analysis of 8,406 food venues in Moscow (summer 2022). Venues categorized by type and district with geographic maps, comparing chain vs. independent formats, ratings, and pricing. Deep-dive into the coffee shop segment (1,413 venues; avg cup price 135–198 RUB by district).

---

## [Games](./games/games.ipynb) — Анализ продаж видеоигр / Video Game Sales Analysis

**RU:** Анализ продаж 16 715 видеоигр (акцент на 2013–2016 гг.) для определения перспективных платформ и жанров. Выявлена слабая положительная корреляция оценок критиков с продажами; пользовательские оценки корреляции не показывают. Составлены региональные профили покупателей: СА/ЕС предпочитают шутеры и экшены, Япония — RPG.

**EN:** Sales analysis of 16,715 video games (2013–2016 focus) to guide platform and genre selection. Critic scores show a weak positive correlation with sales; user scores show none. Regional profiles built — NA/EU favor Shooters/Action, Japan favors RPG. PS4 and Xbox One identified as most promising platforms.

---

## [Med](./med/med.ipynb) — Анализ цен медицинского центра / Medical Center Pricing Analysis

**RU:** Анализ 85 369 записей об оказанных медицинских услугах: сравнение выручки, среднего чека и числа клиентов в 2021 и 2022 годах. С апреля 2022 года цены выросли, а число клиентов упало — предположительно из-за обесценивания рубля и последовавшего оттока пациентов.

**EN:** Analysis of 85,369 medical service records comparing 2021 vs. 2022 revenue, pricing, and patient volume across 9 service categories. Starting April 2022, prices rose while client counts fell — attributed to ruble depreciation forcing price increases and subsequent patient attrition.
