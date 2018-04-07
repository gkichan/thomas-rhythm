# Landing Thomas Rhythm

### Используемые в проекте технологии
1.	`jQuery`
2.	`Google map API`
### Плагины
1.	`slicknav`- стилизация мобильного меню
2.	`header-scroll` - анимация появления меню
3.	`scroll-to` - анимация скрола по странице
### Иконки
1.	`Font-Awesome` - иконочный шрифт
2.	`Et line icons` - иконочный шрифт
### Шрифты 
*	`Dosis:300,400`
*	`Open Sans:300,400`

### Стандартные компоненты и классы

***Default classes:***

1.	Выравнивание текста :

		.text-center - выравнивание по центру
		.text-right - выравнивание по правому краю
		.text-justify - выравнивание на всю ширину

2.	Цвет фона :

		.bg-black - черный фон
		.bg-grey - серый фон

3.	Позиционирование :

		.m-auto - отмена float и центрирование
		.pull-left - float: left;
		.pull-right - float: right;

***Default component***

1. Отступы между стандартными блоками 

		.default-section

2. Отступы между маленькими блоками

		.small-section

3.	Держим ширину 1200px

		.container
        
4.	Не держим ширину :)

		.container-fluid
        
5. Заголовки 

		.title  - дефолтный заголовок
        .title.title-white - белый цвет текста
        .title.section-title - заголовок секции
        .title.section-title-light - заголовок поменьше
        
6.	Дефолтный текст

		.default-text
7.	Цитата

		blockquote,
		.blockquote - текст цитаты
        blockquote span,
		.blockquote span - автор цитаты
        
8.	Кнопки

		.btn - дефолтная кнопка (неполноценная)
        .btn[disabled] - недоступная кнопка
        .btn.btn-default - дефолтная кнопка        
        .btn.btn-black - черная кнопка        
        .btn.btn-xs - маленькая кнопка
        
9.	Форма

		.form-control - дефолтная форма
        .form-control[disabled],
		.form-control.disabled - недоступная форма
        .form-control.error - неправильно заполненая форма
        .form-info - подпись под формой
        
10. Иконки

		.icon - дефолтный размер et line иконки
        .rhomb-icon - иконка ромбик
        .rhomb-icon i - выравнивание самой иконки внутри ромбика
        .rhomb-icon.black-icon - черный фон ромба
        .rhomb-icon.white-icon - белый фон ромба
        .rhomb-icon.transparent-icon - прозрачная иконка
        .arrow-up - стрелочка скрол вверх
        
***

***Основные контрольные точки media-запросов***

		@media (max-width: 991px) - устройства c разрешением до 991px
		@media (max-width: 767px) - устройства c разрешением до 767px
        @media (max-width: 576px) - мобильные устройства c разрешением до 576px
        
***

***Структура папок***

Название файла  | Содержание файла
----------------|----------------------
style       | Папка со стилями
fonts       | Папка со шрифтами
js   | Папка со скриптами
img      | Папка с картинками
guide.html   | Гайд с примерами дефолтных класов
index.html      | Файл с разметкой
