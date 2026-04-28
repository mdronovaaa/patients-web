# Пациенты — Веб-приложение

Веб-приложение для управления списком пациентов с авторизацией и ролями.

## Функции

- Регистрация и вход в систему
- Роли: USER (только просмотр), ADMIN (добавление, удаление, обновление)
- CRUD-операции с таблицей пациентов
- Spring Security

## Технологии

Spring Boot, Spring Security, Thymeleaf, HTML/CSS, H2/PostgreSQL

## Таблица

| Столбец | Тип |
|---------|------|
| id | Long |
| full_name | String |
| birth_date | Date |
| diagnosis | String |
