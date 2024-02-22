# Інструкція з встановлення користувацької розкладки клавіатури на macOS

Цей README надає інструкції щодо встановлення користувацької розкладки клавіатури, упакованої у файл `.bundle`, для macOS.

## Передумови

- Операційна система macOS
- Адміністративний доступ до вашого комп'ютера

## Етапи встановлення

1. **Завантажте пакет розкладки клавіатури**
   - Переконайтесь, що файл `.bundle` завантажено на ваш Mac.

2. **Відкрийте Finder**
   - Перейдіть до місця, де ви завантажили файл `.bundle`.

3. **Скопіюйте пакет**
   - Клацніть правою кнопкою миші по файлу `.bundle` і виберіть `Копіювати`.

4. **Перейдіть до директорії розкладок клавіатури**
   - У Finder натисніть `Shift` + `Command` + `G`, щоб відкрити діалог "Перейти до папки".
   - Введіть `/Library/Keyboard Layouts/` і натисніть `Перейти`.

5. **Вставте пакет**
   - Клацніть правою кнопкою миші у папці Keyboard Layouts і виберіть `Вставити елемент`, щоб скопіювати файл `.bundle` сюди.
   - Якщо буде запропоновано, введіть свій адміністративний пароль, щоб авторизувати копіювання.

6. **Активуйте користувацьку розкладку клавіатури**
   - Відкрийте `Системні налаштування` > `Клавіатура`.
   - Перейдіть на вкладку `Джерела вводу`.
   - Натисніть кнопку `+`, щоб додати нову розкладку клавіатури.
   - Знайдіть користувацьку розкладку клавіатури (вона має бути перелічена під мовою, для якої ви її налаштували) та додайте її.

7. **Виберіть користувацьку розкладку клавіатури**
   - У меню барі натисніть на іконку джерел вводу (іконка прапорця), щоб перемкнутися на вашу користувацьку розкладку клавіатури.

## Усунення неполадок

- Якщо користувацька розкладка не з'являється у списку, вийдіть із системи та увійдіть знову або перезавантажте комп'ютер.
- Переконайтесь, що ви розмістили файл `.bundle` у вірній директорії (`/Library/Keyboard Layouts/`).

## Видалення

Щоб видалити користувацьку розкладку клавіатури:

1. Перейдіть до `/Library/Keyboard Layouts/`.
2. Видаліть файл `.bundle`.
3. Вийдіть із системи та увійдіть знову
