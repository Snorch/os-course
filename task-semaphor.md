## Домашнее задание "Семафоры и Барьер"(task-semaphore.md)

Необходимо написать программу использующую IPC или POSIX семафоры оранизующую барьер для n процессов.

Есть точка в программе в которой запущеные процессы должны дождаться прихода к этой точке всех оставшихся n-1 процессов и только потом продолжить исполнение. Для убедительности выведите во всех процессах что они продолжили работу сразу после барьера.

Ключевые системные вызовы IPC: ftok, semget, semop, semctl и команды ipcs, ipcrm; POSIX: sem_init, sem_post, sem_wait.