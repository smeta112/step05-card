# закрепляем пройденный материал
## Задание - создать в центре экрана карточку товара (размер экрана неизвестен)

задали карточки фиксированный размер по высоте и ширине + воспользовались св-воом overflow со значением auto для формирования скрола, если контент не поместится внутри карточки...
Сфма карточка абсолютно спозиционированна: 50% от верха и левого края + выполнено смещение на -50% ширины и высоты самой карточки: transform: translate(-50%, -50%);
-познакомились с генераторами изображений p.s смотри карту: https://goo.su/front ветка 2 Изображения
-сформировали кнопку из тега a - добавили в кнопку:
   - display: inline-block;
  -border: 2px solid #b07d05e3;
  -text-transform: uppercase;
  -letter-spacing: 2px;и расстояние от букв
  -border-radius: 8px;
  -transition: 0.8s; время анимации
  - воспользовались свойством .btnCard:hover (свойства при наведении курсора мышки на блок
  -ограничили проект одним экраном html{height: 100%;}   
body{height: 100%;











# блоки блочные(везде и строчные(отталкивают только слева и справа
##display: inline-block; из строчного в блочный
text-align: center; в центр текст
margin: 25px 0; отступ только по бокам
<a href="#" class="btnCard"> #пишем в ссылке класс для работы с сss
            Купить
</a>

font-weight: bold; жирный текст

# shift + alt  копирование
alt перемещение

overflow: hidden; спрятать вылазуывающий элемент
 overflow: auto; спрятать вылазуывающий элемент, но можно проскролить

 transition: 0.8s; время переключения(анимация
