# GoIT JS Homework 02 - Control Structures & Methods
JavaScript homework assignment for the GoIT course (Module 2). Topic: branching (`if...else`, `switch`), logical operators, string methods, and input validation.

**What was done:**
- Set up the repository `goit-js-hw-02` and configured the project structure according to the course requirements
- **Task 1 (Droid Purchase with Validation):** Implemented the `makeTransaction` function with conditional branching to check if the customer has enough credits (`customerCredits >= totalPrice`), returning a success message or `"Insufficient funds!"`
- **Task 2 (Message Formatting):** Implemented the `formatMessage` function to truncate strings exceeding `maxLength` using string methods and append an ellipsis (`...`), or return the original string intact
- **Task 3 (Spam Checking):** Implemented the `checkForSpam` function using case-insensitive string searching (`toLowerCase()`) to detect forbidden keywords (`"spam"` or `"sale"`), returning a boolean value (`true` or `false`)
- **Task 4 (Shipping Cost Calculation):** Implemented the `getShippingCost` function using a `switch` statement to evaluate delivery countries (China, Chile, Australia, Jamaica) and return corresponding shipping costs or a default unavailability message
- Verified code formatting with Prettier and ensured zero errors or warnings in the browser console across all tasks via GitHub Pages

---

# Домашнє завдання 02 GoIT JS — Розгалуження та методи
Практичне завдання з курсу JavaScript від GoIT (Модуль 2). Тема: розгалуження (`if...else`, `switch`), логічні оператори, методи рядків та перевірка умов.

**Що зроблено:**
- Створено репозиторій `goit-js-hw-02` та налаштовано структуру проєкту відповідно до вимог курсу
- **Задача 1 (Замовлення дроїдів з перевіркою коштів):** Реалізовано функцію `makeTransaction` з умовною перевіркою наявності достатньої кількості кредитів на рахунку клієнта (`customerCredits >= totalPrice`), яка повертає успішне замовлення або повідомлення `"Insufficient funds!"`
- **Задача 2 (Форматування повідомлення):** Реалізовано функцію `formatMessage` для обрізання рядків, що перевищують `maxLength`, із додаванням трикрапки (`...`) на кінці або збереженням оригінального тексту
- **Задача 3 (Перевірка спаму):** Реалізовано функцію `checkForSpam` для пошуку заборонених слів (`"spam"` або `"sale"`) незалежно від регістру за допомогою методу `toLowerCase()`, із поверненням логічного значення (`true` або `false`)
- **Задача 4 (Розрахунок вартості доставки):** Реалізовано функцію `getShippingCost` з використанням інструкції `switch` для визначення вартості доставки в залежності від країни (Китай, Чилі, Австралія, Ямайка) або повернення повідомлення про відсутність доставки
- Перевірено форматування коду за допомогою Prettier, а також відсутність будь-яких помилок чи попереджень у консолі на живій сторінці GitHub Pages
