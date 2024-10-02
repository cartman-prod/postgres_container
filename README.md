Данный репозиторий содержит docker-compose файл для создания docker-контейнеров postgres_container и pgadmin_container.
Для запуска контейнеров указать Имя и пароль.
Запуск командой sudo docker-compose up -d.

Основные команды для работы с docker-compose:
  docker-compose build — собрать проект
  docker-compose up -d — запустить проект
  docker-compose down — остановить проект
  docker-compose logs -f [service name] — посмотреть логи сервиса
  docker-compose ps — вывести список контейнеров
  docker-compose exec [service name] [command» — выполнить команду в контейнере
  docker-compose images — список образов
Если данные команды не работают использовать команду sudo.
