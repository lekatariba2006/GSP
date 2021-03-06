## Game Server Programming, Step by Step
===================

## Программирование игрового сервера, шаг за шагом
NHN NEXT game server - это код задания для обучения программированию. Эта задача реализации завершения игрового серверного фреймворка выходит наружу. Образовательные программы, созданные с максимально возможным количеством кода, читаемого и легко записываемого, и (без черной магии) улучшают навыки решения проблем студентов(?) Жучок посажен.

(Примечание: это основано на кодовых службах для использования в различных кодах защиты, модульная обработка и обработка исключений и т. д. должны быть усилены.)

  Курсы программирования игровых серверов NHN NEXT включают в себя
  Игровой серверный фреймворк для разработки
  Игровой сервер с сохранением состояния (веб-сервер без состояния не покрывается)
  Макроскопический(?) Раздел по межсерверной архитектуре (масштабирование и т. д.)
  Необходимые знания (предметы)
  Лаборатория операционной системы и системного программирования (Windows)
  Практика программирования компьютерных сетей и сокетов
  Архитектура компьютерной системы
  База данных
  Цель обучения
  Игровой серверный код непосредственно относится к проектированию и реализации
  Многопоточность, IOCP, управление памятью, DB / SQL, обработка пакетов, …
  Оценка и улучшение производительности игрового сервера
  Производство фиктивных клиентов, профилирование, …
  Игровой сервер умер (?) При их анализе и модификации
  Настройка анализа аварийного дампа, ведения журнала и подсказок по отладке, …
  Что вы можете узнать из этого процесса
  Полное производство высокопроизводительных игровых серверов с IOCP
  Сетевой ввод-вывод и обработка нескольких клиентских сеансов с асинхронной неблокирующей обработкой
  Как бороться с TCP-потоки и сериализация/обратная сериализации пакеты по TCP-потоков
  Методы асинхронной обработки соединений (AcceptEx/DisconnectEx) и снижения загрузки процессора (нулевой байт recv, агрегированная отправка)
  Функция межсерверного соединения (ConnectEx) и объединение сокетов в пул
  Методы объединения Памяти без блокировки
  Объединение Памяти В Пул
  Объединение Объектов В Пул
  Заказ стл распределитель
  Для высокоэффективных многопоточных технологий
  Обнаружение взаимоблокировок с использованием иерархии блокировок
  Используемые методы локального хранения потоков
  Как создать диспетчер с помощью алгоритма Lock-free
  Как реализовать поток-эффективный таймеры
  Способ блокировки базы данных
  Как работать с SQL Server и обрабатывать логику данных с помощью хранимой процедуры
  Как обрабатывать запрос БД путем обертывания ODBC (DBHelper)
  Как настроить пулы потоков только для логики БД для разделения и обработки пулов потоков ввода-вывода (Half sync Half async pattern)
  Контекст Dababase и как с ним бороться
  Ведение журнала, отладочная информация, конфигурация, обработка исключений
  Как обрабатывать исключения через фильтр исключений Seh и оставить minidump
  Как оставить историю вызовов и стек вызовов для отслеживания
  Как оставить потокобезопасные журналы
  Функциональный блок метода проверки производительности
  Обработка пакетов и шифрование
  Как использовать Google protobuf в качестве пакета
  Как регистрировать и отправлять пакеты с помощью макросов
  Шифрование для обмена ключами и потоковое шифрование между сервером и клиентом как применять
  Другой
  Как управлять жизненным циклом указателя)
  Фиктивный клиент, использующий метод тестирования производительности на основе сценария (проект DummyClients)
  Анализ аварийного дампа (crash dump)

## Слайды лекций, используемые в этом курсе

* [Программирование игрового сервера #0-TCP и модель уведомления о событиях] (http://www.slideshare.net/sm9kr/gsp-0-tcpio)
* [Программа игрового сервера #1-IOCP] (http://www.slideshare.net/sm9kr/gsp-1-iocp)
* [Программа игрового сервера #2-IOCP Advanced] (http://www.slideshare.net/sm9kr/gsp-2-iocp)
* [Программирование игрового сервера #3-объединение памяти и объектов] (http://www.slideshare.net/sm9kr/gsp-3-pooling)
* [Программирование игрового сервера #4-многопоточное программирование] (http://www.slideshare.net/sm9kr/gsp-4-multithread)
* [Программирование игрового сервера #5-Обработка баз данных] (http://www.slideshare.net/sm9kr/gsp-5-database)
* [Программирование игрового сервера #6 - обработка исключений и ведение журнала] (http://www.slideshare.net/sm9kr/gsp-6)
* [Программирование игрового сервера #7-обработка пакетов и шифрование] (http://www.slideshare.net/sm9kr/gsp-7)
* [Программирование игрового сервера #8-оценка производительности] (http://www.slideshare.net/sm9kr/gsp-8)


###### Подтверждение

Вся учебная программа NHN NEXT была составлена Ким Чен Вон из NCSOFT, Ким Чжу Бок из NEXON и Ким Хен Чхоль из Bluehole Studio (канадасун).



