# HW2_Git_and_python
*This is the repo for the second homework of the BI Python 2023 course*

### Homework description
В качестве данного ДЗ вам будет необходимо познакомиться с командной работой через GitHub, а также освежить в памяти основые концепции языка Python, которые вы проходили во вступительном курсе. Прочтите внимательно все инструкции перед тем приступить к выполнению задания, при необоходимости задавайте вопросы в общем чате или личных сообщениях. Текст задания большой потому что подробный. Со временем подробностей в ДЗ будет меньше (хорошо ли это?).

#### Основное задание

В этом задании вам надо будет написать мини-программу `calculator.py`. Программа должна принимать на вход (через `input()`) строку с некоторым математическим выражением и печатать число - результат вычисления этого выражения. Гарантируется что выражение состоит из двух чисел (`int` или `float`) и математического оператора между ними (один из 4: `+ - * /`). Все указанные элементы разделены пробелами (пример: `5 - 3`). Реализуйте внутри скрипта 5 функций: `main` и 4 отдельные функции на каждый из типов математических операций. Функция `main` внутри себя должна принимать входное выражение, отдавать его на вычисление соответствующей функции, получать результат и печатать его на экран. Каждая из 4 функций лишь принимает определенное выражение от главной функции, вычисляет его и возвращает результат главной функции. 

**Tехническое требование к заданию.**

Это задание будет выполняться в командах по 4-5 человек. Каждый из членов команды должен внести <ins>***как минимум***</ins> 1 функцию в скрипт `calculator.py`. Каждое внесение функции должно сопровождаться коммитом с осмысленным описанием коммита. Ниже приведена последовательность действий для успешного выполнения задания:

1. Посмотрите состав своей команды здесь ([**ССЫЛКА**](https://plausible-cannon-091.notion.site/Teams-for-HW2-429f378d25db4723a2979cd5434efc95?pvs=4)). Самостоятельно выбирете тимлида в вашей команде. Распределите кто какую из 5-и функций будет писать.
2. Тимлид должен сделать форк данного репозитория (убедитесь что вы убрали галочку в пункте **`Copy the** master **branch only`)**. Тимлид **создает новую ветку** `HW2_<surname>`. После этого тимлид отправляет каждому ссылку на форкнутый репозиторий. 
3. Каждый член команды делает свой собственный форк с репозитория тимлида. После этого клонирует свой собственный форк к себе на локальный компьютер.
4. Локально в этом репозитории пишет в скрипте его часть работы. Скрипт  `calculator.py` должен лежать в папке `HW2_<surname>` и может быть либо создан тимлидом в пункте 2 (тогда члены команды пишут код в имеющемся файле), либо же каждый член команды создает локально данный файл независимо от коллег. Это на выбор команды.
5. Каждый член команды после завершения своей части работы коммитит свои локальные изменения с ************************осмысленным************************ сообщением коммита и делает push в свой удаленный репозиторий. На этом этапе вам может потребоваться сделать синхронизацию с репозиторием тимлида, если там уже произошли изменения (это во вкладке *sync fork* → *fetch*, см. скриншот в [Notion](https://plausible-cannon-091.notion.site/Python-course-8b1f0f28506543bcba2a74c9b411a6cb))
6. После этого из персональных удаленных репозиториев делается *pull-request* в репозиторий тимлида **в ветку** `HW2_<surname>` чтобы собрать все куски кода воедино (это во вкладке *contribute* → *open pull request*, см. скриншот)
7. Тимлид (или любой другой член команды) дополняет общий репозиторий файлом `README.md` который содержит описание вашей мини-программы и состав команды разработчиков. 
8. После завершения работы тимлид делает *pull-request* вашего командного репозитория обратно в репозиторий курса (в соответствующую ветку!) для проверки (также через *contribute*).

<ins>return</ins>:  прикрепите ссылку на pull-request тимлида в Google Class (можете сделать от лица каждого члена команды, но это не обязательно).

#### Советы

- Задание не требует написания большого или сложного кода на python, но является достаточно сложным с точки зрения синхронизации членов команды. Лучший способ сделать его - это устроить командный созвон в Zoom / Discord / Google meet / … и всем вместе выполнить его. Вы можете делать демонстрацию экрана тимлида чтобы все поняли что происходит или экранов коллег которым нужна помощь.
- В работе с Git всегда что-то может пойти не так. Существует несколько способов отмены изменений, которые стоит освоить в ходе учебы в ИБ. Тем не менее, первое время нет ничего плохого в том чтобы просто удалить всё и начать заново!
- Задание может вызывать трудности в работе с Git. Пока еще только начало сентября и скорее всего нет завалов по другим делам - я советую потратить лишнее время и разобраться в пробелах.

#### Дополнительное задание

1. Прикрепите в `README.md` файле скриншот созвона вашей команды.

#### Разбалловка 

- За каждую из 5 функций с осмысленным сообщением коммита и своим автором - **1.6 балла** (итого 1.6 * 5 = 8)
- За наличие полноценного README - **1 балл**
- За правильную структуру форков как описано выше  - **1 балл**
- За доп. задание - **1 доп. балл**

Баллы начисляются всем членам команды одинаково.

#### Предполагаемый **учебный результат**

Это задание позволит получить реальный опыт работы с Git и GitHub в командных проектах. Далее этот навык окажется незаменимым.  Также это задание позволит вам познакомиться с сокурсниками.

Удачи! ✨✨
