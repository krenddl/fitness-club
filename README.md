# Fitness Club

Платформа управления фитнес-клубом: клиенты, тренеры, абонементы, тренировки и отчёты. Полный стек на **.NET 8**: REST API на ASP.NET Core и Blazor WebAssembly-клиент.

## Возможности

- Регистрация и авторизация клиентов и тренеров (JWT, ролевая модель)
- Управление абонементами и тарифными планами
- Запись на тренировки, учёт посещений
- Управление тренерами и расписанием
- Отчёты по клубу
- Внутренний чат между пользователями

## Стек

| Слой | Технология |
|------|------------|
| Бэкенд | ASP.NET Core 8 Web API |
| Фронтенд | Blazor WebAssembly (.NET 8) |
| Авторизация | JWT + ролевая модель |
| ORM | Entity Framework Core |

## Структура

```
Fitness_App/
├── api/Fitness_Api/     # ASP.NET Core Web API
└── client/Fitness_Client/ # Blazor WebAssembly клиент
```

## Запуск

```bash
# API
cd api/Fitness_Api/Fitness_Api
dotnet run

# Blazor-клиент
cd client/Fitness_Client/Fitness_Client
dotnet run
```