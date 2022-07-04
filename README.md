# 🏪 RunSmart
Интернет-магазина, специализирующегося на продажах пульсометров. Демонстрация проекта: https://elhilarion.github.io/RunSmart/

Stack: • HTML5 • CSS3 • SASS • JavaScript • Gulp

## 💡 Реализованный функционал:

- Валидация форм "Заказать звонок" или "Заказать консультацию". Функция "validateForms" делает обязательными к заполнению поля формы: Ваше имя, Ваш телефон и Email. В случае если все поля заполнены, но почта имеет неправильный формат, запрос все равно не отправляется. Форма уведомляет пользователя о корректности заполненных полей. 

- Плавный скролинг и перелистывание страниц. Функция "scroll" отслеживает высоту на которую пролиснул страницу пользователь. Если она более 1100px, то появляется в правом нижнем углу экрана стрелочка. Клик на стрелку возвращает нас в верхнюю часть сайта.   

- Фильтрация пульсометров по назначению: для фитнеса, для бега, для триатлона. Анонимная функция добавляет html-класс "catalog__tab_active" елементу списка "catalog__tabs", если по нему был произведен клик. Если вкладка активна, то она выводит соответствующие этой категории пульсометры. 

- Гугл-карта с местоположением магазина. Использется API Google Карт, где задается конкретный адрес, который закрепляется за импортируемой в проект ссылкой. 



