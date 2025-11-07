# Анализ датасета Global Music Hits YouTube Top 100 2025
- ✅ Датасет можно получить по [ссылке](https://www.kaggle.com/datasets/wardabilal/global-music-hits-youtube-top-100-2025?resource=download)

## Описание репозитория
Репозиторий содержит 4 файла:
1. YouTubeHits.ipynb - основной файл с кодом и описанием проделанной работы.
2. youtube_top_100.pbix - дэшборд PowerBi
3. youtube-top-100-songs-2025.csv - исходный файл датасета
4. youtube_top_100_clean_sql_ready.csv - обработанный при помощи **pandas** датасет.

## Используемые технологии
- **Python 3**.
- Для предварительной очистки датасета перед импортированием в PostgreSQL использовалась библиотека [**pandas**](https://pandas.pydata.org/) для Python.
- Для работы с SQL при помощи Python использовалась библиотека [**psycopg2**](https://www.psycopg.org/docs/index.html).
- В качетсве СУБД для проекта использовалась [**PostgreSQL**](https://www.postgresql.org/).
- Для визуализации результатов использовался инструмент **Microsoft PowerBi**.

## Проведенная работа
В ходе работы, исходный датасет был проанализирован по следующим категориям:
- ТОП-10 Самых просматриваемых клипов 2025 года.
- ТОП-10 Самых продуктивных каналов.
- Средняя длина хитового трека.
- ТОП-10 Видео по отношению просмотров к подписчикам(эффективность трека).

Так же вышеописанным категориям была проведена визуализация данных при помощи инструмента PowerBi:
![youtube_top_100_view](https://github.com/user-attachments/assets/77059350-32bd-4378-882b-ce64fc6c644f)
![youtube_top_100_deep](https://github.com/user-attachments/assets/9cabb683-760c-4345-8210-1b09a11fe7bc)

