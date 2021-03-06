# Определение возраста покупателей

### Использованные инструменты:
* Pandas
* keras
* Matplotlib
* Seaborn
* компьютерное зрение
* машинное обучение
* CV
* ResNet50

### Задача:

Построить модель, которая по фотографии определит приблизительный возраст человека. Есть набор фотографий людей с указанием возраста.

### Данные:
[DATASET](https://chalearnlap.cvc.uab.cat/dataset/26/description/#:~:text=The%20APPA-REAL%20database%20contains%207%2C591%20images%20with%20associated,very%20stable%20%280.3%20standard%20error%20of%20the%20mean%29.)

### Описание проекта
* Построена модель, которая по фотографии определит приблизительный возраст человека. 
* Проанализирован набор фотографий людей с указанием возраста при помощи компьютерного зрения с привлечением готовых нейронных сетей и библиотеки Keras.
### Краткий вывод:
В результате обучения модели мы видим, что с каждой новой эпохой модель все сильнее переообучалась на нашей выборке, тем не менее качество предсказания на валидационной выборке росло и мы смогли получить МАЕ < 8 и даже смогли приблизиться к результату команды из статьи, на которую есть ссылка на странице обучения модели.