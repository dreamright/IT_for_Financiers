# IT_for_Financiers

! Внимание: проект еще не готов.
! Attention: project is still on developement stage. 

Шаги по настройке:
	1. Данные (файлы base_prices.xlsx и bond_description.xlsx) следует поместить в папку с кодом.
	2. Необходимо установить PostgreSQL и Jupyter Notebook. Запустить PostgreSQL Server.
	
Краткое содержание процедуры запуска:
	1. Запустить файл IT_Risks_task1,2.ipynb;
	2. Следовать по шагам, указанным в файле.
	
Файл разбит на главы:
	0. Prestage -- необходимые действия для запуска и подключения Python к PostgreSQL.
	1. Task 1 -- соответствует Homework 1:
		a. Stage 1 -- соответствует п.1 задачи 1. Ожидается, что в PostgreSQL будут записаны таблицы из Excel. Т.к. PostgreSQL не поддерживает из коробки импорт Excel, импорт проходил через Python.
		b. Stage 2 -- соответствует п.2 задачи 1. Ожидается, что по результатам шага To-be dropped Columns определится список колонок, которые будут исключены из базы bond_description. Исключенные поля выносятся в отдельную таблицу на шаге Creating and writing to Database a table of dropped fields.
		c. Stage 3 -- соответствует п.3 задачи 1. Ожидается, что по результатам шага Stage 3: Result будет создана таблица с требуемыми характеристиками. Для справки в разделе FYI: SQL Script приведен SQL Script для получения результата.
	2. Task 2 -- соответствует Homework 2:
		Пояснения:
		
