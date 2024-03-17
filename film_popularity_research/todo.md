# On English (automaticaly)
**To do**
- There is a block of functions `run_code_only_once`, which allows you to run the code once per launch of the entire notebook. It is necessary to make this unit work autonomously, i.e. The cell execution flag should be written inside the function, and not at the end of the cell.
- Use regex function to replace line splitting and whitespace removal functions in 'film_studio'
- Understand how OneHot coding works through mlb. Postponed as they will explain it in the Workshop in the "AI" module
- Add more frequent checking of data.info() to avoid loss
- I tried to make sure that when restarting individual cells without rebooting the notebook, the notebook would not break. However, due to lack of time, I was forced not to complete this undertaking in this work.
- For convenience, duplicate the background information that is written under the headings into conclusions
- Move the columns so that columns carrying the same information are next to each other.
- Display not the entire table through head, but only those columns that will be useful (the main difference from the previous work, I started using data['column'].head() more often instead of data.head(), but this can be improved. data.loc[:, ['column1', 'column2']].head())
- Follow Occam's razor principle more often, for example in the `bugdet_gos_support_percent` section
- Add a note to each plotly graph indicating that it is scalable
- I would use loops more often to reduce the amount of code, for example, under the cell "Apply the function `round_box_office` to the columns `mean_film_box_office`, `median_film_box_office` and `total_box_office` from the table `year_age_restriction_grouped_box_office_15_19` to get easy-to-read values" you can use loops.
- Explain the data obtained from each graph

# На русском
**To do**
- Есть блок функций `run_code_only_once`, который позволяют запустить код один раз за запуск всей тетради. Нужно сделать так, чтобы этот блок работал автономно, т.е. записывать флаг о выполнении ячейки нужно внутри функции, а не в конце ячейки.
- Использовать функцию regex для замены функций разделения строки и удаления пробелов в 'film_studio'
- Разобраться как работает OneHot кодирование через mlb. Отложил так как будут объяснять в Практикуме в модуле "ИИ"
- Добавить более частую проверку data.info() во избежание потери 
- Старался сделать так, чтобы при повторном запуске отдельных ячеек без перезагрузки тетреди, тетрадь не ломалась. Однако, в связи с недостатком времени, был вынужден не закончить эту затею в этой работе.
- Для удобства продублировать справочную информацию, которая написана под заголовками, в выводы
- Переместить столбцы так, чтобы столбцы, несущие одну информацию, были рядом друг с другом.
- Выводить не всю таблицу через head, а только те столбцы, которые будут полезны (основное отличие от прошлой работы, я более часто начал использовать data['column'].head() вместо data.head(), но это можно улучшить. data.loc[:, ['column1', 'column2']].head())
- Более часто следовать принципу бритвы Оккама, например, в разделе `bugdet_gos_support_percent`
- Добавить к каждому графику plotly надпись о том, что он масштабируется
- Более часто использовал бы циклы для сокращения количества кода, например, под ячейкой "Применим функцию `round_box_office` к столбцам `mean_film_box_office`, `median_film_box_office` и `total_box_office` из таблицы `year_age_restriction_grouped_box_office_15_19`, чтобы получить легко читаемые значения" можно использовать циклы.
- Пояснить данные полученные с каждого графика
