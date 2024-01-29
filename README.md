# test_task
Тестовая задача


1. Нет проверки на существование переменных $_REQUEST
2. Необходимо разделить логику класса Search, он отвечает за поиск и выдает результаты, чтобы придерживаться SOLID
а именно Single Responsibility Principle
3. Использование глобальной переменной не самая лучшая практика
4. Константы лучше вынести отдельно
5. Подключаться к бд в самом методе не самая лучшая идея, такие вещи лучше разделять, выносить в отдельный класс или использовать иньекцию зависимостей
6. Передавать параметры напрямую в запросах тоже может привести к SQL иньекциям, обработать ошибки в случае не успешного выполнения


