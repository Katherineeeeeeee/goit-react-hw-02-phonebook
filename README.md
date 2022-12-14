## goit-react-hw-02-phonebook

Цей проєкт був створений за допомогою [Create React App](https://github.com/facebook/create-react-app). Для знайомства та налаштування додаткових можливостей [звернись до документації](https://facebook.github.io/create-react-app/docs/getting-started).


## Критерії приймання

- Створені репозиторії goit-react-hw-02-feedback і goit-react-hw-02-phonebook.
- При здачі домашньої роботи є два посилання: на вихідні файли та робочі сторінки кожного завдання на GitHub Pages.
- Під час запуску коду завдання в консолі відсутні помилки та попередження.
- Для кожного компонента є окремий файл у папці src/components.
- Для компонентів описані propTypes.
- Все, що компонент очікує у вигляді пропсів, передається йому під час виклику.
- JS-код чистий і зрозумілий, використовується Prettier.
- Стилізація виконана CSS-модулями або Styled Components.


## Книга контактів

Напиши застосунок зберігання контактів телефонної книги.
## 

Крок 1

Застосунок повинен складатися з форми і списку контактів. На поточному кроці реалізуй додавання імені контакту та відображення списку контактів. Застосунок не повинен зберігати контакти між різними сесіями (оновлення сторінки).

Кожен контакт повинен бути об'єктом з властивостями name та id. Для генерації ідентифікаторів використовуй будь-який відповідний пакет, наприклад nanoid. Після завершення цього кроку, застосунок повинен виглядати приблизно так.

Крок 2

Розшир функціонал застосунку, дозволивши користувачам додавати номери телефонів. Для цього додай input type="tel" у форму і властивість для зберігання його значення в стані.

Крок 3

- Додай поле пошуку, яке можна використовувати для фільтрації списку контактів за ім'ям.
- Поле пошуку – це інпут без форми, значення якого записується у стан (контрольований елемент).
- Логіка фільтрації повинна бути нечутливою до регістру.
- Коли ми працюємо над новим функціоналом, буває зручно жорстко закодувати деякі дані у стан. Це позбавить необхідності вручну вводити дані в інтерфейсі для тестування роботи нового функціоналу. Наприклад, можна використовувати такий початковий стан.

Крок 4

Якщо твій застосунок реалізований в одному компоненті App, виконай рефакторинг, виділивши відповідні частини в окремі компоненти. У стані кореневого компонента App залишаться тільки властивості contacts і filter.
Достатньо виділити чотири компоненти: форма додавання контактів, список контактів, елемент списку контактів та фільтр пошуку.

Крок 5

Заборони користувачеві можливість додавати контакти, імена яких вже присутні у телефонній книзі. При спробі виконати таку дію виведи alert із попередженням.

Крок 6

Розшир функціонал застосунку, дозволивши користувачеві видаляти раніше збережені контакти.
