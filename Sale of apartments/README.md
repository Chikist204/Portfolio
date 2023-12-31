# Исследование объявлений о продаже квартир

## Описание проекта

Используя данные сервисы Яндекс.Недвижимость, необходимо провести исследовательский анализ данных и установить параметры, которые влияют на цену объектов, что позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. 

## Данные

В распоряжении имелись данные с параметрами добычи и очистки:
- airports_nearest — расстояние до ближайшего аэропорта в метрах (м)
- balcony — число балконов
- ceiling_height — высота потолков (м)
- cityCenters_nearest — расстояние до центра города (м)
- days_exposition — сколько дней было размещено объявление (от публикации до снятия)
- first_day_exposition — дата публикации
- floor — этаж
- floors_total — всего этажей в доме
- is_apartment — апартаменты (булев тип)
- kitchen_area — площадь кухни в квадратных метрах (м²)
- last_price — цена на момент снятия с публикации
- living_area — жилая площадь в квадратных метрах (м²)
- locality_name — название населённого пункта
- open_plan — свободная планировка (булев тип)
- parks_around3000 — число парков в радиусе 3 км
- parks_nearest — расстояние до ближайшего парка (м)
- ponds_around3000 — число водоёмов в радиусе 3 км
- ponds_nearest — расстояние до ближайшего водоёма (м)
- rooms — число комнат
- studio — квартира-студия (булев тип)
- total_area — общая площадь квартиры в квадратных метрах (м²)
- total_images — число фотографий квартиры в объявлении

## Используемые библиотеки

- pandas
- matplotlib
- seaborn

##

## Результаты

Была проведена предобработка данных, обработаны прпоуски данных и аномальные значения. Были изучены все данные и выявлены предпочтения людей. Проанализированы зависимости цены от разных факторов. Посчитана средняя скорость продажи квартиры, средняя цена квадратного метра для 10 самых крупных населенных пунктов. Для наглядности использовались графики (гистограммы, круговые диаграммы, а также графики размаха).

