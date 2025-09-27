# Project. «Лаборатории исследований гражданского общества». Определение уязвимых групп населения

## Table of contents
[1. Project Description](https://github.com/Evgi23/dst_gigio/blob/main/Projects/Final%20work/README.md#project-description)

[2. What case we are solving?](https://github.com/Evgi23/dst_gigio/blob/main/Projects/Final%20work/README.md#what-case-we-are-solving)

[3. Short data information](https://github.com/Evgi23/dst_gigio/blob/main/Projects/Final%20work/README.md#short-data-information)

[4. Project work stage](https://github.com/Evgi23/dst_gigio/blob/main/Projects/Final%20work/README.md#project-work-stage)

[5. Result](https://github.com/Evgi23/dst_gigio/blob/main/Projects/Final%20work/diplom.ipynb)

[6. Conclusions](https://github.com/Evgi23/dst_gigio/blob/main/Projects/Final%20work/README.md#conclusions)

### Project Description
* Задача проекта определить по статистическим данным уязвимые регионы и группы населения  
* Python: Очистка данных (Numpy, Pandas), Визуализация (Seaborn, Matplot), Feature Engineering ( Pipeline, PCA,  StandardScaler) ML (Sklearn - KMeans, DBSCAN, AgglomerativeClustering, GaussianMixture, LogisticRegression, RandomForestClassifier, hyperopt, GridSearchCV)

:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/blob/main/Projects/Final%20work/README.md#table-of-contents)

### What case we are solving?
Проект состоит из 4 частей:

1. Часть 1. Знакомство с данными. Очистка от пропусков и дубликатов. Предварительный анализ данных;

2. Часть 2:  Статистический анализ
    2.1 Проверка распределений на нормальность
    2.2. Корреляционный анализ

3. Часть 3: Кластеризация. Определение уязвимых регионов и групп населения

4. Часть 4: Запуск в продакшн



**Competition conditions**


**Quality metric**
Visual Representation of the Clusters
accuracy
f1-score

**What we practice**
The main objective of the project was to learn the following skills:

* Data cleaning

* Data exploration (including quality of visualizations, generation of ideas, hypotheses, and providing comments)

* Feature generation

* Feature selection

* Feature transformation

* ML clustering, classifying

:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/blob/main/Projects/Final%20work/README.md#table-of-contents)

### Short data information

Статистические данные о доходах, заболеваемости, социальнонезащищённых слоях населения России и другие экономические и демографические данные. [Росстат](http://ssl.rosstat.gov.ru/) и пр

### Project work stage
* Часть 1. Знакомство с данными. Очистка от пропусков и дубликатов. Предварительный анализ данных - загрузили данные, отчистили от пропусков и дубликатов,преобразовали к единому формату название регионов, создали единый дата фрейм с средними статистическими показателями.
* Часть 2 Статистический анализ - Проверили признаки на нормальность распределения, выявили корреляцинную зависимость с признаком бедности, определили пизначи, имеющие статистическую связь с признаком бедности
* Часть 3 Кластеризация. Определение уязвимых регионов и групп населения - Запустили 5 различных алгоритмов и выявили наилучший, который кластиризует наши признаки лучшим образом. Наши 16 уязвимых регионов и 
* Часть 4 Запуск в продакшн -  подготовили pipeline, который помогает относится ли человек к уязвимой группе или нет.



### Result
Result [here](https://github.com/Evgi23/dst_gigio/blob/main/Project-1.ipynb)

:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/blob/main/Projects/Final%20work/README.md#table-of-contents)

### Conclusions
1. Мы провели кластеризацию и выявили:
* уязвимые регионы - 'Республика Алтай', 'Республика Адыгея', 'Республика Бурятия', 'Республика Дагестан', 'Республика Ингушетия', 'Кабардино-Балкарская Республика', 'Республика Калмыкия', 'Карачаево-Черкесская Республика', 'Республика Крым', 'Республика Марий Эл', 'Республика Мордовия', 'Республика Северная Осетия-Алания', 'Республика Тыва', 'Чеченская Республика', 'Забайкальский край', 'Ставропольский край'
* уязвимые группы населения - пожилые люди и дети до 16 лет, живущие в домах с неблогаприятными условиями.

2. Провели классификацию и добились результата accuracy 0.86,  f1-score 0.57. Теперь наш алгоритм готов к тому, чтобы предсказать, к какой группе относится человек с заданными стат показателями.





:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/blob/main/Projects/Final%20work/README.md#table-of-contents)

