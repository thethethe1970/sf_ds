# PROJECT-2. Анализ вакансий из HeadHunter


## Оглавление  
[1. Описание проекта](#1-описание-проекта)  
[2. Состав и требования к оформлению проекта](#2-состав-и-требования-к-оформлению-проекта)  
[3. Краткая информация о данных](#3-краткая-информация-о-данных)  
[4. Результат](#4-результат)  
[5. Выводы](#5-выводы)     


### 1. Описание проекта    
✍ Представьте, что вы устроились на работу в кадровое агентство, которое подбирает вакансии для *IT*-специалистов. Ваш первый проект — создание модели машинного обучения, которая будет рекомендовать вакансии клиентам агентства, претендующим на позицию *Data Scientist*. Сначала вам необходимо понять, что из себя представляют данные и насколько они соответствуют целям проекта. В литературе эта часть работы над *ML*-проектом называется *Data Understanding*, или анализ данных.

**[к оглавлению](#оглавление)**


### 2. Состав и требования к оформлению проекта    

**Наш проект включает в себя несколько этапов**:   
- знакомство с данными;
- предварительный анализ данных;
- детальный анализ вакансий;
- анализ работодателей;
- предметный анализ.

**Требования к оформлению ноутбука-решения**
- Решение оформляется только в *Jupyter Notebook*.
- Решение оформляется в соответствии с [ноутбуком-шаблоном](https://lms.skillfactory.ru/assets/courseware/v1/a39c1eedaae738f78d85c950f78223fa/asset-v1:SkillFactory+DSPR-2.0+14JULY2021+type@asset+block/Project_2_%D0%9D%D0%BE%D1%83%D1%82%D0%B1%D1%83%D0%BA_%D1%88%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD.ipynb).
- Каждое задание выполняется в отдельной ячейке, выделенной под задание (в шаблоне они помечены как **ваш код здесь**). Не следует создавать много ячеек для решения задачи — это провоцирует неудобства при проверке.
- Текст *SQL*-запросов и код на *Python* должны быть читаемыми. Не забывайте про отступы в *SQL*-коде.
- Выводы по каждому этапу оформляются в формате *Markdown* в отдельной ячейке (в шаблоне они помечены как **ваши выводы здесь**).
- Выводы можно дополнительно проиллюстрировать с помощью графиков. Они оформляются в соответствии с теми правилами, которые приводены в модуле по [визуализации данных](https://lms.skillfactory.ru/courses/course-v1:SkillFactory+DSPR-2.0+14JULY2021/jump_to_id/1fa00a018157484a9bae5d4557ef3e7c).
- Не забудьте удалить ячейку с данными соединения перед фиксацией работы в *GitHub*.

⚡ По завершению проекта вылокладываете ноутбук на [GitHub](https://github.com/) и отправляете ссылку на него.

**Формат ноутбука с решением:**     
- Номер задания.
- Код для получения ответа.
- Результат запроса.
- Выводы по блоку заданий.
- Общий вывод в конце по результатам анализа, имеющихся данных по вакансиям.

**Критерии оценивания**:  
- 2 балла.	Правильность решения задач, логичность построения запросов.
- 2 балла.	Читабельность и верное форматирование запросов и кода на *Python*, наличие комментариев в запросах; аккуратность оформления решения.
- 2 балла.	Логичность и полнота выводов.
- 2 балла.	Дополнительные исследования данных.

**Максимальное количество баллов** за задание — 8.

**[к оглавлению](#оглавление)**


### 3. Краткая информация о данных

**Содержание**
- VACANCIES. Таблица хранит в себе данные по вакансиям.
- AREAS. Таблица-справочник, которая хранит код города и его название.
- EMPLOYERS. Таблица-справочник со списком работодателей.
- INDUSTRIES. Таблица-справочник вариантов сфер деятельности работодателей.
- EMPLOYERS_INDUSTRIES. Дополнительная таблица, которая существует для организации связи между работодателями и сферами их деятельности.

**[к оглавлению](#оглавление)**


### 4. Результат:  
   Выполненное задание соответствует критериям оценивания.

**[к оглавлению](#оглавление)**


### 5. Выводы:  
Представлены в ноутбуке (файл Project_2_HH.ipynb).

**[к оглавлению](#оглавление)**