# IT_for_Financiers


Шаги по настройке:

	1. Данные (файлы base_prices.xlsx и bond_description.xlsx) следует поместить в папку с кодом (IT_Risks.ipynb).
	
	2. Необходимо установить PostgreSQL и Jupyter Notebook. Запустить PostgreSQL Server (pgAdmin 4), настроить сервер: указать пользователя, пароль для подключения, сервер (localhost по умолчанию), название базы данных и порт.
		Далее эти данные настройки PostgreSQL необходимо будет внести в Prestage стадию в файле IT_Risks_task1_2_v4.ipynb как указано в инструкции.
		Ссылка для установки PostgreSQL: https://www.postgresql.org/download/
	
	3. Установить библиотеки (также перечислены стандартные библиотеки): psycopg2, weasyprint, cairocffi, sqlalchemy, pandas, numpy, matplotlib, datetime, scipy, jinja2.
		Для x64 Python может потребоваться установка пакета отсюда: https://github.com/tschoonj/GTK-for-Windows-Runtime-Environment-Installer/releases (версия 3.х)
		Детальная инструкция: https://weasyprint.readthedocs.io/en/latest/install.html#gtk64installer 
	
	
Краткое содержание процедуры запуска:
	0. Поместить файл cbr_rates.xlsx в папку с кодом IT_Risks.ipynb;
	
	1. Запустить файл IT_Risks.ipynb;
	
	2. Следовать шагам, указанным в файле.
	
	
	Файл разбит на главы, соответствующие номерам домашних заданий, и на стадии (Stages), соответствующие пунктам домашнего задания:
	
	0. Prestage -- необходимые действия для запуска и подключения Python к PostgreSQL.
	
	1. Task 1 -- соответствует Homework 1
	
	2. Task 2 -- соответствует Homework 2
	
	3. Task 3 -- соответствует Homework 3
	
	4. Task 4 -- соответствует Homework 4

	Пример: Homework 2, Stage 2.a соответствует д/з 2, пункту 2.а.
	
	Результат выполнения пункта отмечен восклицательным знаком (!). Пример: (!) Result of Homework 2, Stage 2.a: table bond_issuers
	
	
	Для ознакомления с результатом выполнения задания #4 приложены файлы isin_yields.csv, Credit_Spread_Histogram.png, report.pdf.
