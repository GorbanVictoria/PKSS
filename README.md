```mermaid
mindmap
  root((Электронный деканат))
    Основные_функции
      Учёт_задолженностей
        Добавление_задолженности
        Модификация_задолженности
        Удаление_задолженности
        Просмотр_задолженности
      Учёт_студентов
        Добавление_студента
        Модификация_данных_студента
        Удаление_студента
        Просмотр_данных_студента
      Учёт_дисциплин
        Добавление_дисциплины
        Модификация_данных_дисциплины
        Удаление_дисциплины
        Просмотр_данных_дисциплины
      Отчётность
        Генерация_отчётов
        Экспорт_в_форматах
        Интерактивные_графики
      Просмотр_расписания
        Просмотр_расписания_для_группы
        Просмотр_расписания_для_студента
        Просмотр_расписания_для_преподавателя
      Выдача_справок
        Запрос_справки
        Формирование_справки
        Экспорт_справки_в_PDF
        Отправка_справки_по_email
    Дополнительные_функции
      Уведомления
        Email_уведомления
        SMS_уведомления
        Напоминания_в_пользовательском_интерфейсе
      Аналитика
        Статистика_по_задолженностям
        Анализ_производительности_студентов
      Интеграция
        API_для_интеграции_с_другими_системами
        Интеграция_с_учебной_платформой
    Пользовательский_интерфейс
      Панель_управления
      Пользовательские_роли
        Администратор
        Преподаватель
        Студент
      Доступность_и_удобство_использования
        Адаптивный_дизайн
        Поддержка_различных_устройств


journey
  title User Journey для Электронного деканата
  section Регистрация и авторизация
    Пользователь_регистрируется: 5: Пользователь
    Пользователь_авторизуется: 5: Пользователь
  section Учёт задолженностей
    Просмотр_задолженности: 4: Пользователь
    Добавление_задолженности: 3: Администратор
    Модификация_задолженности: 3: Администратор
    Удаление_задолженности: 3: Администратор
  section Учёт студентов
    Просмотр_данных_студента: 4: Пользователь
    Добавление_студента: 3: Администратор
    Модификация_данных_студента: 3: Администратор
    Удаление_студента: 3: Администратор
  section Учёт дисциплин
    Просмотр_данных_дисциплины: 4: Пользователь
    Добавление_дисциплины: 3: Администратор
    Модификация_данных_дисциплины: 3: Администратор
    Удаление_дисциплины: 3: Администратор
  section Отчётность
    Генерация_отчётов: 4: Администратор
    Экспорт_в_форматах: 4: Администратор
    Интерактивные_графики: 4: Администратор
  section Просмотр расписания
    Просмотр_расписания_для_группы: 4: Пользователь
    Просмотр_расписания_для_студента: 4: Пользователь
    Просмотр_расписания_для_преподавателя: 4: Пользователь
  section Выдача справок
    Запрос_справки: 4: Пользователь
    Формирование_справки: 3: Администратор
    Экспорт_справки_в_PDF: 3: Администратор
    Отправка_справки_по_email: 3: Администратор
  section Уведомления
    Email_уведомления: 4: Пользователь
    SMS_уведомления: 4: Пользователь
    Напоминания_в_пользовательском_интерфейсе: 4: Пользователь
  section Аналитика
    Статистика_по_задолженностям: 4: Администратор
    Анализ_производительности_студентов: 4: Администратор
  section Интеграция
    API_для_интеграции_с_другими_системами: 3: Администратор
    Интеграция_с_учебной_платформой: 3: Администратор
  section Пользовательский интерфейс
    Панель_управления: 4: Пользователь
    Пользовательские_роли: 4: Пользователь
    Доступность_и_удобство_использования: 5: Пользователь
