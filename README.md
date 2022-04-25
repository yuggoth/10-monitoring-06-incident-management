# 10.06. Инцидент-менеджмент

## Краткое описание инцидента

21 октября 2018 года в 22:52 UTC проводились плановые работы, которые привели к потере связи между объектами инфраструктуры на восточном побережье США. Связь была восстановлена за 43 секунды, но сбой вызвал цепочку событий, которые привели к отображению устаревшей информации на сайте github.com и невозможности ее обновления. Работоспособность была восстановлена через 24 часа 11 минут, данные не были потеряны.

## Предшествующие события

Плановые работы по замене вышедшего из строя оптического оборудования 100G.

## Причина инцидента

Потеря связи между сетевым концентратором и основным центром обработки данных на восточном побережье США, вызванная плановыми работами.

## Воздействие

Сбой базы данных, ставший причиной появления непоследовательной информации на веб-сайте.

## Обнаружение

В 22:54 UTC благодаря сигналам от внутренних систем мониторинга инженеры группы быстрого реагирования определили, что топологии многочисленных кластеров баз данных находятся в непредвиденном состоянии.

## Реакция

Над устранением инцидента работали инженеры группы быстрого реагирования, координатор инцидента и группа реагирования на инциденты. Были вызваны дополнительные инженеры из группы разработки баз данных GitHub. Пользователи были оповещены через твиттер и блог GitHub.

## Восстановление

Базы данных были восстановлены из резервных копий, реплики на обоих сайтах были синхронизированы, возвращена исходная топология, а затем возобновлена обработка заданий в очереди.

## Таймлан

2018 October 21 22:52 UTC
2018 October 21 22:54 UTC
2018 October 21 23:07 UTC
2018 October 21 23:13 UTC
2018 October 21 23:19 UTC
2018 October 22 00:05 UTC
2018 October 22 00:41 UTC
2018 October 22 06:51 UTC
2018 October 22 07:46 UTC
2018 October 22 11:12 UTC
2018 October 22 13:15 UTC
2018 October 22 16:24 UTC
2018 October 22 16:45 UTC
2018 October 22 23:03 UTC

## Последующие действия
