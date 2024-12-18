```mermaid
gitGraph
    branch development
    commit id: "Добавление функционала регистрации"
    commit id: "Создание страницы профиля студента"

    branch feature/zadolzhennosti
    commit id: "Добавление функции просмотра задолженностей"
    commit id: "Реализация формы оформления задолженности"
    checkout development
    commit id: "Улучшение интерфейса"
    
    checkout feature/zadolzhennosti
    commit id: "Оптимизация поиска задолженностей"
    checkout development

    merge feature/zadolzhennosti id: "Слияние функционала задолженностей"

    branch feature/otchety
    commit id: "Добавление функционала генерации отчетов"
    checkout development

    merge feature/otchety id: "Слияние функционала отчетов"

    branch feature/notifications
    commit id: "Создание системы уведомлений"
    checkout development

    merge feature/notifications id: "Слияние функций уведомлений"

    branch feature/raspisanie
    commit id: "Добавление функционала просмотра расписания"
    checkout development

    merge feature/raspisanie id: "Слияние функционала расписания"

    branch feature/spravki
    commit id: "Добавление функционала выдачи справок"
    checkout development

    merge feature/spravki id: "Слияние функционала справок"

    branch feature/analytics
    commit id: "Добавление функционала аналитики"
    checkout development

    merge feature/analytics id: "Слияние функционала аналитики"

    branch feature/integration
    commit id: "Добавление функционала интеграции"
    checkout development

    merge feature/integration id: "Слияние функционала интеграции"

    commit id: "Подготовка к релизу"
