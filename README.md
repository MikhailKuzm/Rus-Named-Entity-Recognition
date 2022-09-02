## Распознавание именованных сущеностей с пакетом spacy на русском языке
 - Скрипт ner.ipynb использует пакет spacy и его модуль для русского языка "ru_core_news_sm" для распознавания новых именованных сущностей в разговорах менеджеров по телефону, а именно: фраза приветствия менеджера, фраза прощания менеджера, название компании менеджера, фраза представления менеджером себя, имя менеджера.
 - Для доубучения русскоязычного модуля spacy под собственные именованные сущености были использованы данные из файла TRAIN_DATA.json, написанные и маркерованные самостоятельно. А для тестирования был взят файл test_data.csv
 - В итоге создаётся таблица, где обозначено говорил ли менеджер слова приветствия и прощания своему клиенту.

Дальнейшее улушение точности выделения именованных сущеностей связано с увеличением обучающей выборки данных, а также использованием большого модуля spacy для русского языка.

