<p align="center">
<img src="https://github.com/ikozhuhar/sysadmin_skills/blob/main/img/sysadmin_preview.png">
</p>

<p align="center">
<i>Отличному администратору не обязательно знать все, но он должен быть в состоянии придумать потрясающие решения для невозможных проектов.</i>
</p>

<p align="center" style="margin-top: 200px;">
<i>Этот проект содержит 284 тестовых вопроса и ответа, которые можно использовать в качестве проверки ваших знаний или во время собеседования/экзамена на ​​должность системного администратора Linux.</i>
</p>

<div style="padding: 100px;"></div>
<hr>

### Содержание

<!------------------------------------------------------------------------------------------------------------------------------------------->
| Уровни | Кол-во вопросов | Описание |
| ---------- | :---: | ----------- |
| [Junior Sysadmin](#1) | 65 вопросов | Достаточно просто и понятно, основано на базовых знаниях. |
| Middle Sysadmin | 94 вопросов | Средний уровень вопросов, если у вас есть глубокие знания. |
| Senior Sysadmin | 99 вопросов | Сложные вопросы и загадки. Проверьте это, если хотите быть хорошим. |

<hr>

### [:large_blue_diamond:](#toc) <a name='1'>Младший системный администратор</a>

###### Системные вопросы (37)

<details style="margin-bottom: 30px;">
   <p><summary><b>Приведите несколько примеров дистрибутива Linux.</b></summary></p>

   1. **Ubuntu** — один из самых популярных и дружелюбных для новичков дистрибутивов, основанный на Debian.
   2. **Debian** — стабильный и универсальный дистрибутив, который служит основой для многих других.
   3. **Fedora** — дистрибутив, ориентированный на использование новейших технологий с фокусом на разработчиков.
   4. **Arch Linux** — дистрибутив для опытных пользователей, предоставляющий полную свободу в настройке системы.
   5. **Linux Mint** — дистрибутив, ориентированный на пользователей, привыкших к Windows, с простым и понятным интерфейсом.

[Популярные дистрибутивы Linux](https://blog.skillfactory.ru/glossary/linux/)

</details>




<details>
   <p><summary><b>В чем разница между Unix, Linux, BSD и GNU?</b></summary></p>

<b>GNU</b> на самом деле не является ОС. Это скорее набор правил или философий, регулирующих свободное программное обеспечение, которые в то же время породили множество инструментов при попытке создать ОС. Таким образом, инструменты GNU — это, по сути, открытые версии инструментов, которые уже существовали, но были переопределены, чтобы соответствовать принципам открытого программного обеспечения. <i>GNU/Linux представляет собой совокупность этих инструментов и ядра Linux</i>, образующую полноценную операционную систему, но существуют и другие GNU, например. GNU/Hurd.

<b>Unix и BSD</b> — это «старые» реализации POSIX, которые имеют различные уровни «закрытого исходного кода». Unix обычно имеет полностью закрытый исходный код, но существует столько же разновидностей Unix, сколько и Linux (если не больше). BSD обычно не считается «открытой», но на момент выпуска она считалась очень открытой. Его лицензирование также позволяло коммерческое использование с гораздо меньшими ограничениями, чем допускали более «открытые» лицензии того времени.

<b>Linux</b> — новейший из четырех. Строго говоря, это «просто ядро»; однако в целом она рассматривается как полноценная операционная система в сочетании с GNU Tools и несколькими другими основными компонентами.

Главные руководящие различия между ними заключаются в их идеалах. Unix, Linux и BSD реализуют разные идеалы. Все они соответствуют POSIX и в основном взаимозаменяемы. Некоторые из одних и тех же проблем они решают по-разному. Таким образом, кроме идеалов и способа реализации стандартов POSIX, разницы мало.
</details>




<details>
   <p><summary><b>Что такое CLI? Расскажите мне о ваших любимых инструментах CLI, советах и ​​приемах.</b></summary></p>

   <b>CLI</b> — это аббревиатура от «Интерфейс командной строки» или «Интерпретатор командного языка». Командная строка — один из самых мощных способов управления вашей системой/компьютером.

   В Unix-подобных системах <b>CLI</b> — это интерфейс, с помощью которого пользователь может вводить команды для выполнения системой. Интерфейс командной строки очень мощный, но не очень устойчив к ошибкам.

   <b>CLI</b> позволяет вам гораздо более точно манипулировать внутренними компонентами вашей системы и кодом. Он предлагает большую гибкость и контроль, чем графический интерфейс, независимо от того, какая ОС используется. Многие программы, которые вы, возможно, захотите использовать в своем программном обеспечении, размещенном, например, на Github, также требуют запуска некоторых команд в <b>CLI</b>, чтобы запустить их.

   <b>Мои любимые инструменты</b>
   
   1. `screen` — бесплатный мультиплексор терминала, я могу начать сеанс, и мои терминалы будут сохранены, даже если соединение потеряно, поэтому вы можете возобновить его позже или из дома.
   2. `ssh` — самая ценная команда для изучения, я могу использовать ее для некоторых удивительных вещей.
   3. `vi/vim` — самый популярный и мощный текстовый редактор, он универсальный, работает очень быстро даже с большими файлами.
   4. `bash-completion` — содержит ряд предопределённых правил завершения для оболочки.  

   <b>Советы и хаки</b>

- `!*` - все аргументы последней команды
- `!!` - вся последняя команда
- `!ssh` - последняя команда, начинающаяся с ssh
</details>




<details>
<p><summary><b>Какая ваша любимая оболочка и почему?</b></summary></p>

Нет однозначного мнения о любимой оболочке для Linux. Несколько вариантов, которые мне известны:

- **Bash**. Самая распространённая оболочка Linux, установлена по умолчанию в большинстве систем. Поддерживает различные сокращения и переменные, операторы цикла, контроль и подстановку вывода результатов, автодополнение имён файлов и каталогов.
- **Zsh**. Более гибкая и настраиваемая оболочка, популярная среди продвинутых пользователей. Имеет большое количество встроенных функций и поддерживает широкий спектр плагинов и тем.
- **Fish**. Подходит тем, кому нужен интерактивный терминал без особых настроек. В этой оболочке легко добавлять, удалять и использовать псевдонимы команд, а также настраивать приглашение и цветовую схему. Выбор любимой оболочки зависит от личных предпочтений и потребностей пользователя.
</details>



<details>
<p><summary><b>Как получить справку в командной строке?</b></summary></p>

Чтобы получить справку в командной строке Linux, можно использовать следующие команды:

- **help**. Предоставляет информацию о встроенных командах оболочки. Синтаксис: `help [команда]`. Например, чтобы узнать о команде cd, нужно ввести: `help cd`.
- **man**. Это сокращение от «manual» (руководство). Базовый синтаксис: `man [команда]`. Например, чтобы узнать о команде ls, нужно написать: `man ls`.
- **info**. Служит для получения более детализированной информации о командах, особенно для программ GNU. Базовый синтаксис: `info [команда]`. Например, чтобы узнать о ls, нужно ввести: `info ls`.
</details>



<details>
<p><summary><b>Ваши первые 5 команд на сервере *nix после входа в систему</b></summary></p>

- `w` — много полезной информации о времени безотказной работы сервера
- `top` — можно увидеть все запущенные процессы, а затем отсортировать их по ЦП, использованию памяти и т. д.
- `netstat` — узнать, какой порт и IP-адрес прослушивает ваш сервер и какие процессы их используют
- `df` — сообщает об объеме доступного дискового пространства, используемого файловыми системами
- `history` — сообщает, что ранее было запущено пользователем, к которому вы подключены в данный момент
</details>



<details>
<p><summary><b>Что означают поля в выводе ls -la?</b></summary></p>

В порядке вывода:

```
-rwxrw-r--    1    root   root 2048    Jan 13 07:11 db.dump
```

- права доступа к файлу,
- количество ссылок,
- имя владельца,
- группа владельцев,
- размер файла,
- время последнего изменения,
- имя файла/каталога

Права доступа к файлам отображаются следующим образом:

первый символ `-` или `l` или `d`, `d` обозначает каталог, a `-` представляет файл, `l` - это символическая ссылка (или мягкая ссылка) - специальный тип файла

три набора символов, три раза, обозначающие разрешения для владельца, группы и других:

- `r` = чтение
- `w` = запись
- `x` = исполнение

В нашем примере -rwxrw-r-- это означает, что отображается следующая строка:

- обычный файл (отображается как `-`)
- доступен для чтения, записи и выполнения владельцем (`rwx`)
- доступен только для чтения и записи группой (`rw-`)
- доступен только для чтения другими (`r--`)
</details>




<details>
<p><summary><b>Как получить список вошедших в систему пользователей?</b></summary></p>

Для получения сводки о вошедших в систему пользователях, включая каждое имя пользователя, к которому подключены пользователи терминала, дату/время входа в систему и, возможно, компьютер, с которого они выполняют подключение, введите:

```
# Команда использует файлы /var/run/utmp и /var/log/wtmp для получения подробной информации.
who
```

Для получения подробной информации, включая имя пользователя, терминал, IP-номер исходного компьютера, время начала входа, время простоя, циклы ЦП процесса, циклы ЦП задания и текущую запущенную команду, введите:

```
# Команда использует /var/run/utmp и их процессы /proc.
w
```

Также важно для отображения списка последних вошедших в систему пользователей, введите:

```
# Команда использует /var/log/wtmp.
last
```

**Полезные ресурсы:** [4 способа определить, кто вошел в систему Linux](https://www.thegeekstuff.com/2009/03/4-ways-to-identify-who-is-logged-in-on-your-linux-system/)
</details>




<details>
<p><summary><b>В чем преимущество выполнения запущенных процессов в фоновом режиме? Как это можно сделать?</b></summary></p>

Самым значительным преимуществом выполнения запущенного процесса в фоновом режиме является то, что вы можете выполнять любую другую задачу одновременно, пока другие процессы работают в фоновом режиме. Таким образом, больше процессов могут быть завершены в фоновом режиме, пока вы работаете над другими процессами. Этого можно добиться, добавив специальный символ `&` в конце команды.

Обычно приложения, которые выполняются слишком долго и не требуют взаимодействия с пользователем, отправляются в фоновый режим, чтобы мы могли продолжить работу в терминале.

Например, если вы хотите загрузить что-то в фоновом режиме, вы можете:
```
wget https://url-to-download.com/download.tar.gz &
```

При запуске указанной выше команды вы получите следующий вывод:
```
[1] 2203
```

Здесь `1` — серийный номер задания, а `2203` — PID задания.

Вы можете увидеть задания, работающие в фоновом режиме, с помощью следующей команды:
```
jobs
```

При запуске задания в фоновом режиме выводится PID задания. Вы можете завершить задание, работающее в фоновом режиме, с помощью следующей команды:

```
kill PID
```

Замените PID на PID задания. Если у вас запущено только одно задание, вы можете перевести его на передний план с помощью:

```
fg
```

Если у вас запущено несколько задач в фоновом режиме, вы можете перевести любую задачу на передний план с помощью:

```
fg %#
```

Замените `#` на серийный номер задания.

**Полезные ресурсы:**
1. [Запустить процесс Unix в фоновом режиме](https://servicenow.iu.edu/kb?id=kb_article_view&sysparm_article=KB0026038)
2. [Каковы преимущества работы приложений в фоновом режиме?](https://unix.stackexchange.com/questions/162186/what-is-are-the-advantages-of-running-applications-in-backgound)


</details>




<details>
<p><summary><b>Какие инструменты вы будете использовать для идентификации процессов?</b></summary></p>

Чтобы идентифицировать процессы в Linux, можно использовать следующие методы:

- **Использование файловой системы /proc**. В ней хранятся директории, названия которых соответствуют идентификаторам PID. Каждая из них описывает конкретный процесс, запущенный в ОС. Название процесса хранится в файле comm.
- **Использование утилит top и glances**. Утилита top отображает постоянно обновляемую сводную информацию о процессах и операционной системе. В колонках PID и COMMAND записаны идентификаторы процессов и названия, которые им соответствуют. Инструмент glances предоставляет полный обзор системных ресурсов в удобном и интерактивном интерфейсе.
- **Использование команды ps**. По умолчанию команда ps выводит на экран информацию только о текущих запущенных процессах. Однако у неё есть опции, которые позволяют отобразить в терминале данные о всех процессах ОС. Например, `a` — выводит на дисплей процессы всех пользователей, `u` — отображает дополнительную полезную информацию, `x` — выводит процессы, не связанные с каким-либо запущенным окном терминала.
</details>




<details>
<p><summary><b>Запуск команды от имени пользователя root. Это хорошая или плохая практика?</b></summary></p>

Запуск (всего) от имени root плох, потому что:

**Глупость**: ничто не мешает вам совершить неосторожную ошибку. Если вы попытаетесь изменить систему любым потенциально опасным способом, вам нужно использовать sudo, который обеспечивает паузу (пока вы вводите пароль), чтобы убедиться, что вы не собираетесь совершить ошибку.

**Безопасность**: сложнее взломать, если вы не знаете учетную запись администратора. root означает, что у вас уже есть половина рабочего набора учетных данных администратора.

**Вам это на самом деле не нужно**: если вам нужно запустить несколько команд от имени root, и вас раздражает необходимость вводить пароль несколько раз, когда срок действия sudo истек, все, что вам нужно сделать, это sudo -i, и вы теперь root. Хотите запустить несколько команд с помощью каналов? Тогда используйте sudo sh -c "command1 | command2".

**Вы всегда можете использовать его в консоли восстановления**: консоль восстановления позволяет вам восстановиться после серьезной ошибки или исправить проблему, вызванную приложением (которое вам все равно пришлось запустить как sudo). В этом случае в Ubuntu нет пароля для учетной записи root, но вы можете поискать в Интернете, как его изменить — это усложнит задачу для любого, кто имеет физический доступ к вашему ящику, чтобы нанести вред.
</details>




<details>
<p><summary><b>Как проверить статистику памяти и процессора?</b></summary></p>

Вы бы использовали `top/htop` для обоих. Используя команду `free` и `vmstat`, мы можем отобразить статистику физической и виртуальной памяти соответственно. С помощью команды `sar` мы видим загрузку ЦП и другую статистику (но sar даже не установлен в большинстве систем).
</details>




<details>
<p><summary><b>Что такое load average?</b></summary></p>

**Load Average** — это «средние значения нагрузки системы», которые показывают потребность запущенного потока (задачи) в системе как среднее число запущенных и ожидающих потоков. Это измеряет потребность, которая может быть больше, чем то, что система обрабатывает в данный момент. Большинство инструментов показывают три средних значения, за 1, 5 и 15 минут.

Эти 3 числа не являются числами для разных ЦП. Эти числа являются средними значениями числа нагрузки за определенный период времени (за последние 1, 5 и 15 минут).

**Load Average** обычно описывается как «средняя длина очереди выполнения». Поэтому несколько процессов или потоков, потребляющих ресурсы ЦП, могут поднять среднее значение нагрузки выше 1. Нет проблем, если **Load Average** меньше общего числа ядер ЦП. Но если оно становится больше числа ЦП, это означает, что некоторые потоки/процессы останутся в очереди, готовые к запуску, но ожидающие свободного ЦП.

Это предназначено для того, чтобы дать вам представление о состоянии системы, усредненном за несколько периодов времени. Поскольку он усредняется, требуется время, чтобы вернуться к 0 после того, как на систему была возложена большая нагрузка.

Некоторые толкования:
- если средние значения равны 0,0, то ваша система простаивает
- если среднее значение за 1 минуту выше, чем средние значения за 5 или 15 минут, то нагрузка увеличивается
- если среднее значение за 1 минуту ниже, чем средние значения за 5 или 15 минут, то нагрузка уменьшается
- если они выше, чем количество ваших ЦП, то у вас могут быть проблемы с производительностью

</details>




<details>
<p><summary><b>Где хранится мой пароль в Linux/Unix?</b></summary></p>

Пароли вообще нигде не хранятся в системе. В `/etc/shadow` хранятся так называемые хэши паролей.

Хеш некоторого текста создается путем выполнения так называемой односторонней функции над текстом (паролем), тем самым создавая строку для проверки. По замыслу «невозможно» (вычислительно неосуществимо) обратить этот процесс вспять.

Более старые версии Unix хранили зашифрованные пароли в `/etc/passwd` вместе с другой информацией о каждой учетной записи.

Более новые версии просто имеют `*` в соответствующем поле в `/etc/passwd` и используют `/etc/shadow` для хранения пароля, отчасти для того, чтобы никто не получил доступ на чтение паролей, когда им нужны только другие данные (**shadow обычно защищен сильнее, чем passwd**).

Для получения дополнительной информации обратитесь к `man crypt`, `man shadow`, `man passwd`.
</details>




<details>
<p><summary><b>Как рекурсивно изменить права доступа для всех каталогов, кроме файлов, и для всех файлов, кроме каталогов?</b></summary></p>

Чтобы изменить все каталоги, например, на 755 (drwxr-xr-x):
```
find /opt/data -type d -exec chmod 755 {} \;
```

Чтобы изменить все файлы, например, на 644 (-rw-r--r--):

```
find /opt/data -type f -exec chmod 644 {} \;
```
**Подробнее:** - [Как изменить разрешения для папки и ее подпапок/файлов?](https://stackoverflow.com/questions/3740152/how-do-i-change-permissions-for-a-folder-and-its-subfolders-files?rq=1)

</details>




<details>
<p><summary><b>Каждая команда завершается ошибкой command not found. Как отследить источник ошибки и устранить ее?</b></summary></p>

Похоже, что в какой-то момент происходит перезапись переменной среды PATH по умолчанию. Тип ошибок, которые у вас есть, указывает на то, что PATH не содержит, например, /bin, где находятся команды (включая bash).

One way to begin debugging your bash script or command would be to start a subshell with the `-x` option:

```
bash --login -x
```

Это покажет вам каждую команду и ее аргументы, которые выполняются при запуске этой оболочки.

Также очень полезно показать значения переменной PATH:

```
echo $PATH
```

Если вы запустите это:

```
PATH=/bin:/sbin:/usr/bin:/usr/sbin
```

Большинство команд должны начать работать - и тогда вы можете редактировать `~/.bash_profile` вместо `~/.bashrc` и исправить то, что сбрасывает `PATH` там. Значения переменной `PATH` по умолчанию для root и других пользователей находятся в файле `/etc/profile`.

</details>




<details>
<p><summary><b>Вы нажимаете CTRL + C, но ваш скрипт все еще выполняется. Как его остановить?</b></summary></p>

В большинстве случаев вы можете остановить работающий скрипт, используя комбинацию клавиш `CTRL + C`. Это посылает сигнал прерывания (SIGINT) скрипту, который завершает его выполнение. Если это не сработало и скрипт все еще выполняется, вы можете попробовать использовать комбинацию `CTRL + \`, которая посылает сигнал выхода (SIGQUIT) скрипту, который может немедленно завершить его.

В качестве альтернативы, если вы используете терминал или интерфейс командной строки, вы можете попробовать использовать команду `kill`, чтобы отправить сигнал процессу скрипта. Вы можете узнать идентификатор процесса (PID) скрипта, используя команду ps или top, а затем использовать `kill + PID`, чтобы остановить скрипт.

В некоторых случаях вам может потребоваться использовать команду `kill -9`, чтобы принудительно остановить скрипт, так как обычная команда `kill` может не сработать, если скрипт завис или не отвечает. Параметр `-9` посылает сигнал SIGKILL, который заставляет процесс немедленно остановиться.
</details>




<details>
<p><summary><b>Что такое команда grep? Как сопоставить несколько строк в одной строке?</b></summary></p>

Утилиты grep — это семейство инструментов Unix, включая egrep и fgrep.

grep ищет шаблоны файлов. Если вы ищете определенный шаблон в выводе другой команды, grep выделяет соответствующие строки. Используйте эту команду grep для поиска в файлах журналов, определенных процессах и т. д.

Для сопоставления нескольких строк:

```
grep -E "string1|string2" filename
```

или

```
grep -e "string1" -e "string2" filename
```

**Подробнее:** - [About grep](https://servicenow.iu.edu/kb?id=kb_article_view&sysparm_article=KB0026011)

</details>




<details>
<p><summary><b>Объясните команды содержимого файла вместе с описанием.</b></summary></p>

- `head`: для проверки начала файла.
- `tail`: для проверки конца файла. Это обратная команда head.
- `cat`: используется для просмотра, создания, объединения файлов.
- `more`: используется для отображения текста в окне терминала в виде пейджера.
- `less`: используется для просмотра текста в обратном направлении, а также обеспечивает перемещение по одной строке.

</details>




<details>
<p><summary><b>Что такое пакет, манеджер пакетов, менеджер зависимостей?</b></summary></p>

**Пакет** (package) — это специальным образом подготовленный архив, содержащий само программное обеспечение, его конфигурационные файлы, его данные и управляющую информацию. Управляющая информация пакета включает контрольные суммы устанавливаемых файлов, зависимости устанавливаемого пакета от других пакетов, краткое описание пакета, сценарии установки, сценарии удаления пакета и прочие данные, необходимые менеджеру пакетов.

**Менеджер пакетов** (_в debian-ветви используется `dpkg`, а в ветви redhat — `rpm`_) производит непосредственную установку и удаление пакетов программного обеспечения, а также ведет их учет в системе. Вспомогательная «грязная» работа по подбору зависящих друг от друга пакетов, получению их из репозиториев (например, скачивание с FTP/HTTP-серверов), выбору правильных версий пакетов, определению правильного их порядка установки достается менеджеру зависимостей.

При помощи менеджера пакетов всегда можно узнать имя пакета, в который входит та или иная установленная компонента операционной системы (например, /bin/date), или, наоборот, узнать список компонент, установленных из указанного пакета (например, coreutils). 

```
which -a date
dpkg -S /bin/date
dpkg -L coreutils
```

Условно, можно выделить две ветви операционной системы Linux — ветвь debian, к которой относятся дистрибутивы W:[Debian] и W:[Ubuntu], и ветвь redhat, куда нужно отнести W:[RHEL], W:[CentOS] и W:[Fedora], В debian-ветви используется пакетный менеджер `dpkg` и построенные над ним **менеджеры зависимостей** `apt`, `aptitude`, `synaptic` и `software-center`, а в ветви redhat — пакетный менеджер `rpm` и основной менеджер зависимостей `yum`.

Если при попытке выполнить ту или иную команду операционной системы Ubuntu Linux обнаружится, что нужный пакет с программным обеспечением не установлен, то при наличии доступа в Интернет можно тривиальным способом доустановить недостающие компоненты

```
sudo apt install finger
```

Когда нужно узнать, с каким, даже еще неустановленным, пакетом программного обеспечения поставляется тот или иной файл, может выручить утилита `apt-file`. В обратную сторону посмотреть список файлов, входящих в еще неустановленный пакет, можно этой же утилитой.

```
apt-file search bin/7z
apt-file show p7zip
```

**Чтобы посмотреть, что входит в пакет в Linux, можно использовать следующие команды:**

- **В дистрибутивах Debian/Ubuntu**. Нужно ввести команду dpkg с опцией `-L` и названием пакета в качестве аргумента. Например: `dpkg -L atom`.
- **В дистрибутивах CentOS/RHEL**. Следует использовать команду rpm с параметрами `-g` и `-l`, а также название пакета в качестве аргумента. Например: `rpm -ql <package-name>`.
- **С помощью утилиты apt-file**. Для этого нужно установить её командой `sudo apt-get install apt-file` и вывести список файлов для любого установленного пакета или пакета из репозитория командой `apt-file list имя_пакета`.

</details>




<details>
<p><summary><b>Как посмотреть что входит в пакет linux</b></summary></p>

**Чтобы посмотреть, что входит в пакет в Linux, можно использовать следующие команды:**

- **В дистрибутивах Debian/Ubuntu**. Нужно ввести команду dpkg с опцией `-L` и названием пакета в качестве аргумента. Например: `dpkg -L atom`.
- **В дистрибутивах CentOS/RHEL**. Следует использовать команду rpm с параметрами `-g` и `-l`, а также название пакета в качестве аргумента. Например: `rpm -ql <package-name>`.
- **С помощью утилиты apt-file**. Для этого нужно установить её командой `sudo apt-get install apt-file` и вывести список файлов для любого установленного пакета или пакета из репозитория командой `apt-file list имя_пакета`.

**Чтобы посмотреть установленные пакеты в Alt Linux, используйте команду:**

- `rpm -qa` — вывести список всех установленных пакетов.
- `rpm -q` — проверить, установлен ли пакет в системе.
- `rpm -ql` — посмотреть, что входит в пакет.

Также можно использовать команду `rpm -qa | grep` для поиска конкретного пакета.

</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>




<details>
<p><summary><b></b></summary></p>
</details>

###### Вопросы по сетям (23)

https://github.com/trimstray/test-your-sysadmin-skills/tree/master
