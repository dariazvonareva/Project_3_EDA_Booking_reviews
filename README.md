# Booking reviews. Прогнозирование рейтинга отеля на Booking
## Оглавление
[1. Описание проекта](https://github.com/dariazvonareva/Project_3_EDA_Booking_reviews/blob/main/README.md#Описание-проекта)

[2. Какой кейс решаем](https://github.com/dariazvonareva/Project_3_EDA_Booking_reviews/blob/main/README.md#Описание-проекта)

[3. Краткая информация о данных](https://github.com/dariazvonareva/Project_3_EDA_Booking_reviews/blob/main/README.md#Описание-проекта)

[4. Этапы проекта](https://github.com/dariazvonareva/Project_3_EDA_Booking_reviews/blob/main/README.md#Этапы-проекта)

[5. Результат](https://github.com/dariazvonareva/Project_3_EDA_Booking_reviews/blob/main/README.md#Результаты)
### Описание проекта
Представьте, что вы работаете дата-сайентистом в компании Booking. Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из способов обнаружения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель ведёт себя нечестно, и его стоит проверить.

:arrow_up:[к оглавлению](https://github.com/dariazvonareva/Project_3_EDA_Booking_reviews/blob/main/README.md#Оглавление)

### Какой кейс решаем
1. создаем свою первую модель, основанную на алгоритмах машинного обучения;

2. принимаем участие в соревновании на Kaggle;

3. отрабатываем навык, как подготавливать данные, чтобы предстказательная модель работала лучше.

Что от нас требуется?

Модель машинного обучение нам дана в готовом виде, также к данному соревнованию создано базовое решение.

Главная задача — при помощи шагов предварительного и разведывательного анализа повысить качество предсказания. Чтобы понять, что качество улучшилось, ориентируемся на метрику MAPE: чем она меньше, тем лучше.

### Краткая информация о данных

Нам предоставлен набор данных, который содержит сведения о 515 738 отзывах на отели Европы. Изначально датасет разбит на тренировочные и тестовые данные, а также предоставлен файла submission.csv в который необходимо записать результат работы модели.

Признаки

- hotel_address - адрес отеля
- review_date - дата, когда рецензент разместил соответствующий отзыв.
- average_score - средний балл отеля, рассчитанный на основе последнего комментария за последний год
- hotel_name - название отеля
- reviewer_nationality - национальность рецензента
- negative_review - отрицательный отзыв, который рецензент дал отелю.
- review_total_negative_word_counts - общее количество слов в отрицательном отзыв
- positive_review - положительный отзыв, который рецензент дал отелю
- review_total_positive_word_counts - общее количество слов в положительном отзыве
- reviewer_score - оценка, которую рецензент поставил отелю на основе своего опыта
- total_number_of_reviews_reviewer_has_given - количество отзывов, которые рецензенты дали в прошлом
- total_number_of_reviews - общее количество действительных отзывов об отеле
- tags - теги, которые рецензент дал отелю.
- days_since_review - продолжительность между датой проверки и датой очистки
- additional_number_of_scoring - есть также некоторые гости, которые просто поставили оценку сервису, а не оставили отзыв. Это число указывает, сколько там действительных оценок без проверки.
- lat - широта отеля
- lng - долгота отеля

### Этапы проекта
1. Знакомство с данными
2. Очистка от пропущенных значений.
3. Преобразование строковых значений.
4. Создание новых признаков. 
5. Преобразование признаков.
6. Отбор признаков.

**Условия соревнования:**
- Данное соревнование является бессрочным и доступно для всех потоков.

- Срок выполнения соревнования устанавливается индивидуально в каждом потоке.

- Тестовая выборка представлена в LeaderBoard целиком.

- Делаем реальный ML продукт, который потом сможет нормально работать на новых данных.

### Результат:
После обработки данных модель отрабатывает с точностью MAPE = 0.1274

[Ноутбук с выполненными заданиями и выводами](https://github.com/dariazvonareva/Project_3_EDA_Booking_reviews/blob/main/project-3-hotels-eda-feature-engineering.ipynb)
:arrow_up:[к оглавлению](https://github.com/dariazvonareva/Project_3_EDA_Booking_reviews/blob/main/README.md#Оглавление)