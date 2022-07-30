## Проект 1 (финальное задание). Анализ вакансий из HeadHunter 

## Оглавление
[1. Описание проекта](https://github.com/Savo4ek89/sf_data_science/tree/main/project_0_final_task#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)  
[2. Какой кейс решаем?](https://github.com/Savo4ek89/sf_data_science/tree/main/project_0_final_task#%D0%BA%D0%B0%D0%BA%D0%BE%D0%B9-%D0%BA%D0%B5%D0%B9%D1%81-%D1%80%D0%B5%D1%88%D0%B0%D0%B5%D0%BC)  
[3. Краткая информация о данных](https://github.com/Savo4ek89/sf_data_science/tree/main/project_0_final_task#%D0%BA%D1%80%D0%B0%D1%82%D0%BA%D0%B0%D1%8F-%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D1%8F-%D0%BE-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85)  
[4. Этапы работы над проектом](https://github.com/Savo4ek89/sf_data_science/tree/main/project_0_final_task#%D1%8D%D1%82%D0%B0%D0%BF%D1%8B-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B-%D0%BD%D0%B0%D0%B4-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%BE%D0%BC)  
[5. Результаты](https://github.com/Savo4ek89/sf_data_science/tree/main/project_0_final_task#%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D1%8B)  
[6. Выводы](https://github.com/Savo4ek89/sf_data_science/tree/main/project_0_final_task#%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4%D1%8B)

### Описание проекта
Анализ дата-сета, содержащего резюме с сайта поиска вакансий hh.ru.

:arrow_up:[к оглавлению](https://github.com/Savo4ek89/sf_data_science/tree/main/project_0_final_task#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)


### Какой кейс решаем?
Определение желаемого уровня заработной платы соискателей.    
В рамках кейса также произведены анализ, преобразование и очистка данных.

**Условия задачи:**
- Скачать и прочитать файлы;
- Провести базовый анализ структуры данных;
- Преобразовать данные (включая объединение таблиц);
- Провести разведывательный анализ;
- Очистить данные.

**Что практикуем**  
- Учимся писать хороший код на Python;
- Учимся работать с IDE;
- Учимся работать с GitHub;
- Учимся предобрабатывать данные;
- Учимся строить информативные графики, отображающие взаимосвязь различных признаков, закономерности, а также помогающие в поиске аномалий.


### Краткая информация о данных
_ База резюме, выгруженная с сайта поиска вакансий hh.ru (файл "dst-3.0_16_1_hh_database.csv");
- Выгрузка курсов валют, встречающихся в базе резюме, за период с 29.12.2017 по 05.12.2019 (файл "ExchangeRates.csv").
    
Ссылка на файлы: https://drive.google.com/drive/u/0/folders/1Q8TqExR-f0_8d1Sa_KHEDM2vugar6S7X    

В результате анализа дата-сета построены графики, отображающие взаимосвязь между различными признаками с помощью интерактивной визуализации в Plotly. Учитывая тот факт, что GitHub ее не поддерживает, в папке проекта ("Project_1_final_task") создана папка "plotly", в которой сохранены построенные графики в формате .jpg.

Ссылка на папку: https://github.com/89sms89/sf_df/tree/main/Project_1_final_task/plotly

:arrow_up:[к оглавлению](https://github.com/Savo4ek89/sf_data_science/tree/main/project_0_final_task#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)


### Этапы работы над проектом
1. Исследование структуры данных.
2. Преобразование данных.    
В рамках этапа к таблице с резюме ("hh_data" присоединена таблица с курсами валют "exchange_rates". Объединенная таблица - "merged_data").    
3. Исследование зависимостей в данных.
4. Очистка данных.    
В рамках этапа удалены дубликаты, пропуски в данных, касающихся части с резюме, выбросы.

:arrow_up:[к оглавлению](https://github.com/Savo4ek89/sf_data_science/tree/main/project_0_final_task#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)


### Результаты
Таблица ("cleaned"), в которой содержатся данные о делаемом уровне заработной платы для всех соискателей, удалены дубликаты, аномальные значения, а также пропуски в данных (в части, относящейся к резюме).    
Кроме того, таблица содержит информативные и читабельные признаки, полученные в рамках предобработки данных, и, соответственно, очищена от признаков, предсталвенных в неудобном для анализа формате.

:arrow_up:[к оглавлению](https://github.com/Savo4ek89/sf_data_science/tree/main/project_0_final_task#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)


### Выводы
...

:arrow_up:[к оглавлению](https://github.com/Savo4ek89/sf_data_science/tree/main/project_0_final_task#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)