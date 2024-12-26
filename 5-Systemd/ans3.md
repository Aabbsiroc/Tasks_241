**1. Посмотретите журналы ssh**

![alt text](image-2.png)

Уточнение конкретной службы: Когда вы используете -u <имя_службы>, команда выводит только логи, относящиеся к указанной службе. 

**2. Выведите журналы в реальном времени**
![alt text](image-3.png)


Ключ -f в команде journalctl используется для отображения логов в режиме реального времени.

Если вы используете команду journalctl без ключа -f, она выводит все доступные журналы службы или системы, начиная с момента включения ведения логов.

**3. Выведите лог в реальном времени для службы sshd**

![alt text](image-4.png)

**4. Можно ли без комады journalctl прочитать логи systemd?**

Да, но это требует прямого обращения к бинарным файлам журналов systemd.

Журналы systemd хранятся в бинарном формате в каталоге:
/var/log/journal/

**5. Сколько будет 2-2?**

![alt text](image-6.png)