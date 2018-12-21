Тестовое задание Domoidostavim.ru (frontend) 
---


Наш сервис это каталог продуктов и товаров повседневного спроса.

Перед вами макет корзины, необходимо сверстать макет, написать небольшое Single Page Application на AngularJS

![Cart](/layouts/cart_descktop.png)


В корзине может быть 2 типа товоарв весовой и не весовой, товар имеет свойство цены `price` (для весовых оно значит цена за 1 кг).
 
При нажатии на вес товара в корзине должен появляться селект с выбором веса (500 г, 1000 г, 1500 г), по умолчанию в корзину весовой твоар доабвляется с весом 1000 г.
 
Приложение должно реализовывать корзину товаров, оно должно уметь добавлять, удалять, менять количество и вес товаров.

В зависимости от изменения товаров в корзине и их свойств (количества и веса) должна пересчитываться итоговая сумма корзны.

Под корзиной должно быть 3 карточки товара:

1. Бананы, весовой товар с произвольной ценой
2. Йогурт, не весовой товар с произвольной ценой
3. Кофе, не весовой товар с произвольной ценой 

По нажатию на кнопку Добавть в карточке товара, он попадает в корзину. 

Условия: 

- Используйте HTML, CSS (или SASS), JavaScript
- Используйте AngularJS
- Responsive
