---
title: "Основы тестирования: QA, QC, Verification и Validation"
description: "Подробный вводный материал для изучения ключевых аспектов тестирования и обеспечения качества."
---

### Ключевые термины

- **QA (Quality Assurance)**: Обеспечение качества, включает процессы, направленные на предотвращение дефектов на всех этапах разработки продукта.
- **QC (Quality Control)**: Контроль качества, включает процессы проверки и тестирования для выявления дефектов в готовом продукте.
- **Testing**: Процесс выполнения программы с целью выявления ошибок и подтверждения соответствия требованиям.
- **Verification**: Проверка того, что продукт разрабатывается правильно, в соответствии с техническими спецификациями.
- **Validation**: Проверка того, что конечный продукт удовлетворяет потребности пользователя и соответствует его ожиданиям.

---

### Основные цели тестирования

1. **Поиск дефектов**:

   - Выявление и фиксация ошибок, которые могут нарушить функциональность системы.

2. **Обеспечение качества**:
   - Подтверждение, что продукт соответствует требованиям и работает как ожидается.

---

### Виды тестирования

#### По уровням:

1. **Модульное (Unit Testing)**:
   - Тестирование отдельных модулей или компонентов системы.
   - **Примеры:**
     - Проверка работы функции, которая считает сумму двух чисел.
     - Тестирование отдельного API-метода на корректность ответа.
2. **Интеграционное (Integration Testing)**:

   - Проверка взаимодействия между компонентами системы.
   - **Примеры:**
     - Тестирование связи между базой данных и сервером.
     - Проверка взаимодействия клиентского приложения с серверным API.

3. **Системное (System Testing)**:

   - Полное тестирование всей системы на соответствие требованиям.
   - **Примеры:**
     - Проверка онлайн-магазина от выбора товара до оплаты.
     - Тестирование приложения для бронирования отелей.

4. **Приёмочное (Acceptance Testing)**:
   - Проверка готовности системы к использованию конечными пользователями.
   - **Примеры:**
     - Финальное тестирование перед релизом нового модуля.
     - Демонстрация системы заказчику для утверждения.

#### По функционалу:

1. **Функциональное тестирование**:

   - Проверка соответствия системы функциональным требованиям.
   - **Примеры:**
     - Проверка формы регистрации на корректность ввода данных.
     - Тестирование работы кнопки "Добавить в корзину".

2. **Нефункциональное тестирование**:
   - Проверка характеристик, не связанных с функциональностью (например, производительность).
   - **Примеры:**
     - Измерение времени загрузки веб-страницы при большом количестве пользователей.
     - Тестирование приложения на потребление оперативной памяти.

---

### Глоссарий терминов

1. **Дефект**: Несоответствие между ожидаемым и реальным поведением системы.
2. **Тест-кейс**: Набор шагов и условий для проверки определённой функциональности.
3. **Релиз**: Финальная версия продукта, доступная для пользователей.
4. **Баг**: Ошибка или дефект в программе, вызывающий её некорректное поведение.
5. **Логирование**: Запись информации о выполнении программы для анализа и отладки.

### Примеры из реальной жизни

#### Модульное тестирование:

- Проверка работы калькулятора на правильное сложение и умножение чисел.
- Тестирование отдельного метода обработки данных в приложении.

#### Интеграционное тестирование:

- Проверка работы умного дома: взаимодействие датчика движения и включения света.
- Тестирование связи между платежным шлюзом и онлайн-магазином.

#### Системное тестирование:

- Полный сценарий заказа пиццы через приложение.
- Проверка системы управления билетами на мероприятия.

#### Приёмочное тестирование:

- Тестирование новой версии CRM-системы перед внедрением.
- Проверка работы терминалов самообслуживания перед установкой в магазинах.
