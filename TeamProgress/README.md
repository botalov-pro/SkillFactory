# TeamProgress / Прогресс команды

Скрипт для Jupyter Notebook, который строит прогресс команды на курсе SkillFactory.

## Подготовка к работе
  
  1. В каталоге "data" создать csv-файл (разделитель ";") с участниками команды вида:
  ```
  email;name
  ivanov@mail.test;"Иванов Иван Иванович"
  petrov@mail.test;"Петров Петр Петрович"
  sidorov@mail.test;"Сидоров Сидор Сидорович"
  ```  
  2. Сохранить "сырые данные" из Google Таблицы в csv-файл
  3. Изменить переменные в файле `TeamProgress_csv.ipynb`
		* __data_file__ - путь и наименование к файлу с данными
		* __myteam_file__ - путь и наименование файла с участниками команды
		* __course__ - наименование курса

