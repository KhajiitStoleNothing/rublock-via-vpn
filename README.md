Точечный обход ру-блокировок через VPN на прошивке от [Merlin](https://www.snbforums.com/forums/asuswrt-merlin.42/) ([Fork](https://www.snbforums.com/threads/fork-asuswrt-merlin-374-43-lts-releases-v34e3.18914/))
===================

Для работы необходимо:
------

1. Сконфигурирован OpenVPN Client с параметром "route-noexec" и выключенным дефолтным роутингом
2. Установлена среда EntWare
3. Настроен DNSSEC + DNS over TLS

TODO:
------

1. Сделать 1-click инициализацию (WIP)
2. Написать Wiki с траблшутингом
3. Сделать ветку с поддержкой .onion доменов и TOR (и/или аналогичный функционал решения, используя только TOR)
4. Отрефакторить