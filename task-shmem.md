## Домашнее задание "Общая память и Race Condition"(task-shmem)

Требуется написать две программы которые создают(shmget) и отображают(shmat) область общей памяти в собственное адресное пространство. Далее программы увеличивают целочисленную переменную из общей памяти на еденицу 10000 раз в цикле.

Можно написать одну программу которую нужно запускать дважды(n раз).

Важно удалять общую память когда она не нужна(shmctl), и инициализировать ее при создании в одной из программ.

Нужно показать, что общая память подвержена Состоянию гонки.
([Состояние гонки(wiki)](https://ru.wikipedia.org/wiki/Состояние_гонки))
