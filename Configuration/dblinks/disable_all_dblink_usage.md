# Как отключить использование DB-линков в БД

Количество возможные линков контролируется параметрами open_links (на сессию) и open_links_per_instance (на экземпляр), и составляет по умолчанию 4.

Для отключения необходимо выставить их в 0. Требуется перезагрузка экземпляра.