# Проект: Путешествие по России

Это одностраничный сайт, посвященный путешествиям по России и ее различным природным достопримечательностям. Сайт адаптирован под разные размеры экранов различных устройств, таких как настольные компьютеры, ноутбуки, смартфоны.

Состоит из 7 основных блоков контента, именнованных и расположенных в файловой структуре согласно методологии БЭМ.

*Шапка сайта (header).* Содержит в себе логотип и кнопки-ссылки для переключения язковых версий сайта (на текущий англоязычная версия не реализована). В верстке шапки использованы технологии flexbox.

Ниже размещен блок *lead*, содержащий основной заголовок страницы, подзаголовок и декоративное изображение.

Блок *intro* указывает на различные факты.

Блок *photo-grid* состоит из изображений различных природных достопримечательностей России. Сверстан по технологии grid layout, и такое его свойство как auto-fit для автоматического переноса колонок на новую строку, тем самым решен вопрос отзывчивости, а также адаптивности данного блока.

Далее блок *places*. Здесь представлены 5 карточек с изображением, описанием различных природных уголков России и ссылкой на веб-страницу, посвященную месту, указанному в карточке. В верстке данного блока использованы технологии flexbox и grid непосредственно в каждой из карточек.

Блок *cover* представляет изображение-ссылку, при клике на которое осуществляется переход на страница-блок с заметками путешествующих доб озера Байкал на электричке.

В самом низу сайта по традиции размещен *footer* с навигацией по сервисам Яндекса и копирайтом. Изпользуется flex.

Для адаптивности сайта испольуются медиавыражения (media query) со следующими брейкпоинтами 1024px, 768px, 691px, 596px, 425px, 320px.

* [Ссылка на макет в Figma](https://www.figma.com/file/5S2WSbEFL6awjVWJ0NWL8Q/Sprint-3_-Russia-_-desktop-mobile?node-id=28503%3A0)

* [Ссылка на сайт](https://rustam240985.github.io/russian-travel/)
