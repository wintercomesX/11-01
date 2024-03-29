# Домашнее задание к занятию "`11-01`" - `Кандала Кирилл `


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

`Приведите ответ в свободной форме........`

1. `Для бюджетирования проектов, формирования финансовых аналитических отчетов и прогнозирования рисков, а также обеспечения целостности и четкой структуры данных, рекомендуется использовать реляционные СУБД, такие как Oracle или Microsoft SQL Server. Для ускорения работы с хешами можно использовать специализированные API для работы с хеш-функциями, такие как OpenSSL или Botan.`
2. `Для хранения данных лендингов и CRM, требующих гибкости и скорости, можно использовать комбинацию реляционных и NoSQL СУБД. Например, MongoDB для лендингов и PostgreSQL для CRM. Отдельные задачи можно решить с помощью одной СУБД, но для оптимальной производительности и гибкости рекомендуется использовать соответствующие СУБД для каждой задачи`
3. `Для отдела контроля качества, создания базы по корпоративным нормам и правилам, рекомендуется использовать реляционные СУБД с простой и понятной структурой, такие как MySQL или Microsoft Access. Для интеграции существующей СУБД из предыдущих задач рекомендуется использовать ETL (Extract, Transform, Load) процессы для переноса данных и создания связей между ними.`
4. `Для департамента логистики, требующего быстрое формирование маршрутов доставки и распределения курьеров, рекомендуется использовать графовые СУБД, такие как Neo4j. Для учета отдела закупок можно рассмотреть интеграцию с существующей СУБД логистики с помощью API или создание отдельной СУБД с последующей интеграцией.`
5. `Возможно использование одной универсальной СУБД, такой как PostgreSQL, для решения всех перечисленных задач. Однако, для оптимальной производительности и эффективности рекомендуется использовать комбинацию различных типов СУБД в зависимости от требований каждой задачи.`


### Задание 2

`Приведите ответ в свободной форме........`

1. `Авторизация: Система должна автоматически идентифицировать пользователя и проверить его данные для обработки автоплатежа.`
2. `Подтверждение наличия средств: Перед выполнением транзакции система должна проверить наличие достаточных средств на банковском счете или кредитной карте пользователя`
3. `Генерация транзакции: Система должна автоматически сгенерировать транзакцию пополнения счета телефона на основании заранее установленных параметров автоплатежа.`
4. `Проведение платежа: Сформированная транзакция должна быть проведена через платежный шлюз или банковскую систему.`
5. `Обновление баланса: После успешного проведения платежа, система должна обновить баланс счета телефона пользователя в соответствии с суммой автоплатежа.`
6. `Отчет и уведомление: Пользователю следует отправить уведомление о проведенной транзакции и произведенном пополнении счета.`
7. `* В случае автоплатежа данные шаги осуществляются автоматически без необходимости интерактивного подтверждения от пользователя. Система самостоятельно инициирует платеж по заранее заданным параметрам (например, ежемесячно), что повышает удобство и оперативность процесса пополнения баланса счета телефона.`


### Задание 3

`Приведите ответ в свободной форме........`

1. `Структурированные данные: SQL базы данных обеспечивают четкую структуру данных с определенными схемами, что делает их более предсказуемыми и удобными для работы с табличными данными.`
2. `Мощный язык запросов: SQL предлагает эффективный и мощный язык запросов, что упрощает извлечение, обновление и управление данными.`
3. `Транзакционная целостность: SQL обеспечивает транзакционную целостность, гарантируя, что операции будут либо выполнены полностью, либо откатываться до исходного состояния в случае ошибки.`
4. `Сложные запросы и аналитика: SQL отлично подходит для выполнения сложных аналитических запросов и сводных таблиц, делая его идеальным для бизнес-аналитики и отчетности.`
5. `Надежность и зрелость: SQL-системы имеют более длинную историю развития, что обеспечивает высокую надежность, масштабируемость и интеграционные возможности.`
6. `* Преимущества NewSQL систем перед SQL и NoSQL могут включать в себя сочетание характеристик обеих моделей, таких как поддержка транзакционной целостности и SQL-подобных запросов с масштабируемостью, горизонтальным распределением и высокой доступностью, что делает их привлекательными для современных высоконагруженных приложений требующих гибкости NoSQL и традиционной надежности SQL.`


### Задание 4

`Приведите ответ в свободной форме........`

1. `Масштабируемость: Одним из ключевых критериев выбора является способность СУБД масштабироваться горизонтально для обработки большого объема данных на сети множества машин.`
2. `Производительность: Важно выбрать СУБД и модель вычислений, которые обеспечат высокую производительность при обработке данных на 1000 машинах.`
3. `Отказоустойчивость: Необходимо обеспечить, чтобы система вычислений была отказоустойчивой, способной продолжать работу даже при сбоях на отдельных узлах.`
4. `Удобство использования: Выбор модели распределенных вычислений также должен учитывать удобство использования и интеграции с имеющимися бизнес-процессами и системами.`

