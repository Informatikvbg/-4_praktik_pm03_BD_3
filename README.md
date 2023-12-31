## Институт экономической безопасности

# ПМ 03 "Сопровождение и продвижение программного обеспечения отраслевой направленности"

##  работа на тему: Построение ER моделей. Прямой инжиниринг.

В ходе выполнения данной практической работы вы создадите простейшую ER модель базы данных.
Последовательно выполняйте задания согласно Вашего варианта. Результаты работы будут представлены Вами в виде 
•	файл pdf, в котором будет созданая Вами УК модель базы данных. 
•	экспортированный sql дамп физической базы данных, созданной методом прямого инжиниринга из УК модели.
Файл назвать Группа_ФИО_тема варианта.sql,pdf, например, 7120B_IvanovAM_teatr.sql (7120B_IvanovAM_teatr.pdf) и выложить в репозиторий GitHub Classroom.

Варианты заданий аналогичны Практической работе №1 и приложены в конце задания.

# Задание 1.
В соответствии с темой варианта разработайте примерную схему взаимодействия внутри организации. Выделите основные сущности (не менее 4), которые участвуют в работе организации и их атрибуты. 
# Задание 2.
Открыть рабочую область программы MySQL Workbench для создания ER моделей. Создать ER модель  по Вашему заданию. 
• название таблицы 
• названия столбцов таблицы 
В каждой таблице задать первичный ключ и столбцы-атрибуты. Определить типы данных столбцов.
# Задание 3.
Установить нотации таблиц и связей в формат IDEF1X.
Определить типы (1:1, 1:n, n:n) и связи (идентифицирующие и неидентифицирующие) между сущностями . 
Создать связи между таблицами.
Проверить наличие и расположение внешних ключей (FK) в дочерних таблицах.
# Задание 4.
Сохранить модель.
Сделать экспорт модели (диаграммы) в одностраничный pdf файл.
Файл назвать «Группа_ФИО_тема варианта.pdf», например, 7120B_IvanovAM_teatr.pdf
# Задание 5.
Сделать прямой инжиниринг диаграммы в физическую базу данных на локальном сервере с параметрами:
•	hostname: localhost
•	port: 3306
•	username: root
•	password: не устанавливаем.
Базу данных назвать Группа_ФИО_тема варианта, например, 7120B_IvanovAM_teatr

# Задание 6.
В MySQL Workbench установить соединение с созданной в предыдущем пункте физической базой данных. 
Сделать экспорт физической базы данных в файл дампа sql. Файл назвать «Группа_ФИО_тема варианта.sql», например, 7120B_IvanovAM_teatr.sql
# Задание 7.
Выложить файлы sql и pdf в репозиторий задания на GitHub Classroom.


