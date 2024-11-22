# Задание 1. Создание и документирование API

В рамках практической работы приведены возможные описания REST API и AsyncAPI двух микросервисов из первой части работы: HomeManagement и HeatManagement.

## HomeManagement

Микросервис HomeManagement позволяет создавать, изменять, удалять дома и устройства в них. Информация об устройствах публикуется в шине событий.

[REST API](./api/HomeManagement_OpenAPI.yaml)

[AsyncAPI](./api/HomeManagement_AsyncAPI.yaml)

## HeatManagement

Микросервис HeatManagement позволяет управлять обогревательными системами в доме. Подключен к шине событий: слушает события о появлении/удалении обогревательного оборудования в домах, слушает информацию от сервиса логики о необходимости включать или выключать систему, а также публикует информацию об изменении температуры с датчиков.

[REST API](./api/HeatManagement_OpenAPI.yaml)

[AsyncAPI](./api/HeatManagement_AsyncAPI.yaml)
