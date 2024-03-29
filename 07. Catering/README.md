# Рынок заведений общественного питания Москвы

### Описание проекта
Мы решили открыть небольшое кафе в Москве. Оно оригинальное — гостей должны обслуживать роботы. Проект многообещающий, но дорогой. Вместе с партнёрами мы решились обратиться к инвесторам. Их интересует текущее положение дел на рынке — возможно ли снискать популярность на долгое время, когда все зеваки насмотрятся на роботов-официантов?


### Инструкция по выполнению проекта
### [Шаг №1. Загрузите данные и подготовьте их к анализу](#step1)
Загрузим данные о заведениях общественного питания Москвы. Убедимся, что тип данных в каждой колонке — правильный, а также отсутствуют пропущенные значения и дубликаты. При необходимости обработаем их.


### [Шаг №2. Анализ данных](#step2)
- [Исследуем соотношение видов объектов общественного питания по количеству. Построим график.](#item_1)
- [Исследуем соотношение сетевых и несетевых заведений по количеству. Построим график.](#item_2)
- [Для какого вида объекта общественного питания характерно сетевое распространение?](#item_3)
- [Что характерно для сетевых заведений: много заведений с небольшим числом посадочных мест в каждом или мало заведений с большим количеством посадочных мест?](#item_4)
- [Для каждого вида объекта общественного питания опишите среднее количество посадочных мест. Какой вид предоставляет в среднем самое большое количество посадочных мест? Построим графики.](#item_5)
- [Выделим в отдельный столбец информацию об улице из столбца address .](#item_6)
- [Построим график топ-10 улиц по количеству объектов общественного питания. Воспользуемся внешней информацией и ответим на вопрос — в каких районах Москвы находятся эти улицы?](#item_7)
- [Найдем число улиц с одним объектом общественного питания. Воспользуемся внешней информацией и ответим на вопрос — в каких районах Москвы находятся эти улицы?](#item_8)
- [Посмотрим на распределение количества посадочных мест для улиц с большим количеством объектов общественного питания. Какие закономерности можно выявить?](#item_9)

[Сделайем общий вывод и дадим рекомендации о виде заведения, количестве посадочных мест, а также районе расположения. Прокомментируем возможность развития сети.](#step_10)


### [Шаг №3. Подготовка презентации](#step3)
Подготовим презентацию исследования для инвесторов. Ссылка на презентацию в формате pdf приложена в конце проекта.

### Описание данных
#### Таблица rest_data:

- id — идентификатор объекта;
- object_name — название объекта общественного питания;
- chain — сетевой ресторан;
- object_type — тип объекта общественного питания;
- address — адрес;
- number — количество посадочных мест.

## Вывод:

В данном проекте мы провели исследование рынка заведений общественного питания в Москве. Для начала мы провели первичный анализ и предобработку данных. Привели данные в более удобный для исследования вид. А также удалили данные о заведениях общепита за пределами Москвы (Новую Москву в проекте решили не рассматривать). Исходя из проведенного анализа можем сделать следующие выводы:

- По количеству заведений в Москве лидируют кафе, затем следуют столовые, рестораны и фаст-фуды. Наименьшим количеством заведений в Москве представлены закусочные и кулинарии.
- По соотношению сетевых и несетевых заведений преобладают несетевые. На их долю приходится 80%.
- Среди всех типов заведений наибольшая доля приходится на несетевые. У сетевых заведений наиболее высокая доля предприятий быстрого питания (40%). Также высока доля у магазинов кулинарии (30%), ресторанов и кафе (по 23%). Минимальная доля сетевых заведений среди столовых (почти 100% приходится на несетевые) и буфеты(2%).
- Чем меньшим количеством заведений представлена сеть, тем больше в них посадочных мест. Такие крупные сети, как макдоналдс, шоколадница, кфс, бургер кинг имеют в среднем до 100 посадочных мест.
- Больше всего посадочных мест в столовых и ресторанах. Меньше всего - в закусочных и кулинариях.
- Среди столовых преобладают столовые при различных учебных заведениях (школах, колледжах, вузах).
- Cреди районов по количеству заведений лидирует Пресненский район (на его территории расположены крупные предприятия и деловые комплексы, самый известный и крупный в Москве комплекс Москва-Сити).
- Больше всего улиц с одним заведение общепита в центральном округе Москвы (Таганский, Басманный, Хамовники, Мещанский, Замоскворечье, Тверской округа).
- В заведениях, расположенных на улицах с большим количеством объектов общепита, мало посадочных мест. Причиной этому является дорогая аренда помещения.

Что касается рекомендаций, то как мне кажется без данных о посещаемости данных заведений, дать советы, которые могли бы помочь в развитии бизнеса в данной сфере будет непросто. Исходя из статистики, среди заведений общепита преобладают несетевые заведения, типа столовых (причем большинство столовых относится к различным учебным заведениям). На долю сетевых заведений приходится 80%. Но это не говорит о неуспешности сетевых заведений. Отнюдь, большинство заведений, которые у нас на слуху, являются именно сетевыми. Среди данного типа объектов большая доля приходится на предприятия быстрого питания, кулинарии, рестораны и кафе. Среди топ-10 улиц по количеству заведений преобладают достаточно крупные улицы, проходящие через большое количество районов Москвы. Лидером по количеству заведений является Пресненский район, известный большим количеством расположенных на его территории бизнес-центров (Москва-Сити). Среди заведений здесь преобладают кафе, рестораны и фаст-фуды. Как правило количество посадочных мест, которые заведения готовы предложить посетителям на таких популярных улицах, невелико встедствие большой аренды за помещения в данных районах. В Центральном округе Москвы есть достаточно много улиц, на которых располагается всего один объект питания (причем наибольшая часть из них приходится на столовые, которые, как мы уже говорили ранее относится к учебным заведениям, следовательно вероятность встретить общедоступные объекты питания на таких улицах крайне мала)
