# Привет, я Алексей

Java-разработчик, фокус на бэкенд и алгоритмы.

---

## Обо мне
Обучаюсь в РТУ МИРЭА на 2-м курсе по направлению Программная инженерия(Разработка ПО и проектирование ИС). Изучаю Java-экосистему: Spring Boot, работу с кэшем, валидацию, интеграционное тестирование. Системно выстраиваю знания по алгоритмам.
**Сейчас активно ищу стажировку Java-бэкенд разработчиком в финтехе**

---

## Стек
- **Java**
- **Spring Boot**
- **Алгоритмы и структуры данных**
- **Gradle**
- **Docker**
- **PostgreSQL**

---

## Проект: Sentinel
Проект торгового робота на Spring Boot.

**Идея:** 
Робот загружает исторические свечи с MOEX (заложено масштабирование), хранит их в PostgreSQL,
прогоняет через торговую стратегию (заложено масштабирование) и выставляет заявки через
брокера в песочнице. Без плечей / заемных средств. 

**Стек:** 
Java 21, Spring Boot 4, PostgreSQL, Flyway, JPA/Hibernate, Docker, Gradle

**Реализовано:**
Слоистая архитектура, конфигурация по 12-factor, PostgreSQL + Flyway, клиент к MOEX с маппингом свечей в сущность `Candle`, синхронизация через `@Transactional`, тесты на репозиторий и сервис. Решения фиксирую в `DECISIONS.md`.

**Статус:** 
Активно развиваю как основной проект

[Sentinel](https://github.com/MorgachevAleksey/Sentinel)

---

## Также

[AlgorithmsAndDataStructures](https://github.com/MorgachevAleksey/AlgorithmsAndDataStructures) - В этом проекте я собрал свой путь по алгоритмам. Выстроил всё в порядке изучения: сначала теория, потом пишу руками, потом задачи на LeetCode и CodeWars. Иду от простого к сложному, стараюсь не прыгать.
Сейчас углубляю знания — прохожу второй круг

[Fundamentals](https://github.com/MorgachevAleksey/Fundamentals) - личная библиотека материалов и практик

[UniverJava](https://github.com/MorgachevAleksey/UniverJava) - собрание практик университетского курса программирования на языке java

---

## Контакты
- Telegram: [@NikTelegii](https://t.me/NikTelegii)
- Почта: [morgachev_aleksey@mail.ru](mailto:morgachev_aleksey@mail.ru)
