# Проведение A/B-теста системы оплаты курсов 📚
## ⚙️ Инструменты и библиотеки:
A/B-теста | T-тест | Bootstrap | тест Шапиро-Уилка | Хи-квадрат | EDA | SQL | Оптимизация запросов | Функции для ad-hoc запросов | API 
Метрики: CR, ARPU, ARPAU, ARPPU
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/jupyter/jupyter-original-wordmark.svg" title="Jupyter" alt="Jupyter" width="40" height="40"/>&nbsp;
  <img src="https://pandas.pydata.org/static/img/pandas_white.svg" title="Pandas" alt="Pandas" height="40"/>&nbsp;
  <img src="https://camo.githubusercontent.com/6631ab3e404c95feff2366126736bf6b3759e4be11357ea07405a3527b9a3138/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6e756d70792d2532333031333234332e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6e756d7079266c6f676f436f6c6f723d7768697465" title="Numpy" alt="Numpy" height="30"/>&nbsp;
  <img src="https://pingouin-stats.org/build/html/_images/logo_pingouin.png" title="Pingouin" alt="Pingouin" height="30"/>&nbsp;
  <img src="https://avatars.mds.yandex.net/i?id=ed4bb20472a95e34f0ee6dc8de3069ccf373f67d-8497452-images-thumbs&n=13" title="Statsmodels" alt="Statsmodels" height="30"/>&nbsp;
  <img src="https://camo.githubusercontent.com/9e175adcb5e76a230ffd53ed1e78034277d31171b77358865b2be148d0b523d3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d6174706c6f746c69622d2532336666666666662e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d4d6174706c6f746c6962266c6f676f436f6c6f723d626c61636b" title="Mathplotlib" alt="Mathplotlib" height="30"/>&nbsp;
  <img src="https://avatars.mds.yandex.net/i?id=3b1d13a52ed933827565a138d9a0f7b8cc7df932-12490006-images-thumbs&n=13" title="Seaborn" alt="Seaborn" height="30"/>&nbsp;
  <img src="https://avatars.mds.yandex.net/i?id=8f15f2ddbf0b080a77ed0a53bf419b1d11113da9-9829492-images-thumbs&n=13" title="ClickHouse" alt="ClickHouse" height="30"/>&nbsp;
</div>

## 👩🏻‍💻 Задачи:  
- Считать данные с помощью API
- Провести предобработку данных;
- Саставить итоговую таблицу для анализа данных;
- Выбрать метрики для оценки качества работы нового алгоритма системы оплаты;
- Расчитать метрики;
- Оценить, правда ли, что новый алгоритм улучшил качество сервиса;
- Написать оптимальный запрос, который даст информацию о количестве очень усердных студентов;
- Выгрузить следующую информацию о группах пользователей:  
    ARPU  
    ARPAU  
    CR в покупку  
    СR активного пользователя в покупку  
    CR пользователя из активности по математике
- Реализовать функцию, которая автоматически подгружает информацию из дополнительного файла;
- Реализуйте функцию, которая строит графики по получаемым метрикам.

## 🔎 Выводы:
1.1. Из итоговой таблицы были исключены записи, где клиент совершил покупку, но не заходил на сайт (149 клиентов).  
1.2. Среднее значение выручки, которую приносит пользователь, в экспериментальной группе статистически больше по сравнению с контрольной.  
1.3. Не удалось выявить статистически значимое различие конверсий (абсолютной и относительной конверсий) между экспериментальной и контрольной группами.   
1.4. Средние значения ARPU и ARPAU равны в двух группах.   
1.5. В группе "B" среднее значение ARPPU статистически значимо выше чем в группе "А".   
1.6. Необходимо вводить новую механику оплаты на сайте, так как она повлияла на основные метрики (среднее значение выручки и ARPPU).   
2.1 Было выявлено 136 усердных учеников, у которых 20 и более решенных задач в месяц.   
2.2 Из базы данных были выведены интересующие нас метрики.  
3.1 Написана функция для автоматизации ad-hoc запросов.   
3.2 Реализована функция для построения графиков.  
