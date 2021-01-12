# Проект «Седона»

[Рабочий пример](https://inspiring-mahavira-ed0a4e.netlify.app/)

# Техническое задание

## 1. Общие технические требования

* 1.1. Стандарты вёрстки: HTML, CSS, прогрессивное улучшение.
* 1.2. Сетка: определена в макете.
* 1.3. Адаптивность вёрстки: нет.
* 1.4. Используемые фреймворки: нет.
* 1.5. Кроссбраузерность: Chrome, Firefox, Safari.
* 1.6. Типографика: частично определена в макете, прочее — на усмотрение разработчика.
* 1.7. Используемый шрифт: PT Sans. Шрифт есть в папке с макетом и на Google Fonts.
* 1.8. С макетом предоставлен стайлгайд, содержащий прорисовку состояний элементов интерфейса. При любых расхождениях с макетами он должен иметь наивысший приоритет.

## 2. Пояснения для учащихся

* 2.1. В разделе «Обязательные требования» описано поведение блоков, которое должно быть реализовано для успешной защиты проекта. Требования из раздела «Дополнительные требования» можно реализовать по желанию для выполнения дополнительных критериев.

## 3. Обязательные требования

### Все макеты

* 3.1. Контентная область центрируется и не может быть уже макетной ширины.
* 3.2. Логотип не является пунктом меню. Его нужно размечать отдельным элементом.
* 3.3. Главное меню: пункт «Информация» не является ссылкой на главную страницу.
* 3.4. Главное меню: четыре ячейки одинаковой ширины. Для первых двух пунктов выравнивание текста по левому краю, для двух последних — по правому.
* 3.5. Ссылки в главном меню: кликабельным должен быть только текст.
* 3.6. Слева и справа от контентной области должен быть серый фон, на который сайт бросает лёгкую тень.
* 3.7. В трёх блоках футера контент расположен по центру.
* 3.8. Логотип Академии в подвале ведёт на лендинг интенсива «HTML и CSS. Профессиональная вёрстка сайтов».

### Index

* 3.9. Крупное фото: фотография занимает всю ширину, в её нижней части есть белая маска.
* 3.10. По умолчанию форма поиска гостиницы должна быть открыта.
* 3.11. Кнопка «Поиск гостиницы в Седоне» управляет отображением формы поиска гостиницы. Вёрстка блока с формой поиска гостиницы обязательна.
* 3.12. Иконка календаря в поле ввода даты должна быть добавлена отдельным элементом, чтобы в будущем на неё программист мог повесить событие нажатия для открытия календаря с возможностью выбора даты.
* 3.13. Блок карты: достаточная реализация — обычное изображение.

### Hotels

* 3.14. Логотип — это ссылка на главную страницу.
* 3.15. Главное меню и футер совпадают с главной страницей.
* 3.16. Крупное фото: фотография занимает всю ширину, но отличается от главной страницы — она размыта и меньше по высоте.
* 3.17. Фильтр: верстать с помощью формы, кнопка «Показать» отвечает за отправку формы на адрес `https://echo.htmlacademy.ru/`.
* 3.18. Блок «Стоимость в сутки»: при взаимодействии с любым из маркеров в качестве указателя допускается использовать любой подходящий тип курсора. Делать маркеры интерактивными не обязательно, стоимость меняться не должна.

## 4. Дополнительные требования

### Index

* 4.1. При инициализации JS на форму добавляется класс, который её скрывает.
* 4.2. Кнопка «Поиск гостиницы в Седоне» управляет отображением формы поиска гостиницы. Появление формы необходимо дополнить анимацией «выезда» сверху вниз относительно кнопки, а не окна браузера.
* 4.3. Блок карты: интерактивная карта, которая тянется на всю ширину контейнера. Реализация по желанию.

### Hotels

* 4.4. Фильтр: клик по кнопке «Показать» отправляет форму.
