# Весенний курс по дисциплине "Программирование" 2021

## Правила работы с репозиторием

- Для начала работы каждый студент делает форк (fork) репозитория на свой GitHub аккаунт.
- Каждый студент работает строго в своей директории FirstIO/ , где FirstIO - название директории в формате ФамилияИО на латинице. Если студент что-то изменяет в чужих директориях и во время пул-реквеста это замечается - студент это будет самостоятельно исправлять до корректного вида.
- Внутри директории студента должен находиться файл fio.txt, единственной строкой в котором является Фамилия И.О. студента записанные кириллицей
- Для каждой лабораторной требуется создавать отдельную директорию lab_#, где # - номер лабораторной от 1 до 6.
- Внутри должен быть файл с исходным кодом программы и, в случае если в программе встречается хотя-бы один оператор new - скриншот из программы Leak Checker | Valgrind сигнализирующий о том, что утечек в программе нет
- Для каждой лабораторной создается **отдельная новая ветка (branch)** (checkout -b < FirstIO\_lab_# >, где FirstIO - ФамилияИО, а # - номер работы).
- Для сдачи лабораторной работы создается пул-реквест (pull-request) из Вашей ветки с лабораторной работой в master-ветку общего репозитория курса. В начале заголовка пул-реквеста пишется "[READY] ", После - ФамилияИО, после - lab#.
- Для сдачи работы требуется закрытый пул-реквест со слиянием (merge) Вашей ветки в общий репозиторий. В таком случае работа считается **зачтенной**.
- Если имеются какие-либо нарекания к предложенным студентом файлам, то все замечания пишутся проверяющим в комментарии пул-реквеста, а так же изменяется лейбл на WIP.
- Напоминание: коммиты в ветку, которую студент отправляет на пул-реквест отображаются в самом пул-реквесте. **Делать новый пул-реквест не надо.**
- Закончив исправления, студент пишет об этом отдельным комментарием, указывая, возможно, пояснения к исправлениям, а так же меняет префикс заголовка пул-реквеста на [READY].
- Курс лабораторных считается завершенным полностью, если в основном репозитории находятся директории всех 4 лабораторных работ студента, а так-же защищены все помеченные работы.
