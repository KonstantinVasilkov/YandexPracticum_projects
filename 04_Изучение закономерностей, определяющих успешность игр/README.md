# Определение закономерностей, определяющих успешность игр.

### Использованные инструменты:
* Python
* Pandas
* Matplotlib
* описательная статистика
* проверка статистических гипотез
* math
* Seaborn

### Задача:
Интернет-магазин **«Стримчик»** продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

### Данные:
- `Name` — название игры
- `Platform` — платформа
- `Year_of_Release` — год выпуска
- `Genre` — жанр игры
- `NA_sales` — продажи в Северной Америке (миллионы проданных копий)
- `EU_sales` — продажи в Европе (миллионы проданных копий)
- `JP_sales` — продажи в Японии (миллионы проданных копий)
- `Other_sales` — продажи в других странах (миллионы проданных копий)
- `Critic_Score` — оценка критиков (максимум 100)
- `User_Score` — оценка пользователей (максимум 10)
- `Rating` — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.

### Описание проекта
* Выявлены параметры, определяющие успешность игры в разных регионах мира. 
* Выявлен потенциально популярный продукт и спланированы рекламные кампании.
* Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. 
* Проверены гипотезы: 
    * средние пользовательские рейтинги платформ Xbox One и PC одинаковые;
    * средние пользовательские рейтинги жанров Action и Sports разные. 
* При анализе использовались критерий Стьюдента для независимых выборок.
### Краткий вывод:
* Cейчас находятся на подъеме: PS4, X-box One и WiiU (особенно для Японии). Так же не стоит сбрасывать со счетов 3DS, PSV и старый-добрый PC.
* Из жанров следует сосредоточиться на динамичных играх для Европы и Для Северной Америки, а в Японии сделать ставку на ролевые.
* Стоит больше ориентироваться на оценки критиков, чем пользовательские рейтинги.