# Housing-Prices-Analysis
Описание работы:
1) Сначала нужно собрать данные - я собирал данные используя библиотеки Python(requests,BeatifulSoup) через сайт https://www.kn.kz/. Грубо говоря,запарсил данные с этого веб сайта(адрес,цена квартиры,кол. комнат,площадь и тд.).Перед очисткой собрано - 20768 строк данных по квартирам в Астане и после очистки данные уменьшились на 2000 единиц.
2) Провести предобработку данных используя такие библиотеки Python как (numpy и pandas) для последущего импортирования готового датасета для визуализаций в PowerBI.
3) Использую возможности PowerQuery изменил data types(object -> int) некоторых мер.
4) Использовал также DAX чтобы добавить новый column для лучшего понимания визуализаций и также получения инсайтов с данных.(новый column = Price per m^2 = Price / area of flat)

Тенденций и инсайты:

Первая страница - это home page(где дается инфо по сайту и сути проекта)

Вторая страница - общая информация по квартирам.Самое интересное то что многие квартиры(дата постройки) приходится на последние 20 лет.Количество квартир 2022 года постройки превышает 2000.

Третяя страница - эта страница больше связано с ценами квартир.Район Алматы самый популярный район.В районах Есил и Нура цены с среднем выше чем в остальных районах Астаны.

Четвертая страница - эта страница идет как продолжение третьей,тоесть показывает нам ключевых факторов влияния на цены квартир,а также доп инфо по колиство квартир на комнатность квартир.Однокомнатные и также двухкомнатные крайне популярны.
