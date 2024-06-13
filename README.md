# PI_Project

https://huggingface.co/spaces/ASokirka/Pi_Project

PI_URFU_2023
Команда 1.5
Сокирка А.

Программная инженерия. Итоговый проект (PJ)

Цель проекта: разработать Web приложение машинного обучения и развернуть его в облаке. В проекте используется модель blanchefort/rubert-base-cased-sentiment.

Итоговый проект (PJ) доступен по ссылке на Hugging Face Spaces.
Анализатор комментариев
— это приложение, которое позволяет пользователю получить комментарии к видео, размещенному на YouTube, а также определить эмоциональную окраску этих комментариев и визуализировать результаты в виде диаграмм.

ссылка https://huggingface.co/spaces/ASokirka/Pi_Project

Основные функции
Приложение позволяет пользователю получить комментарии к видео из YouTube.
Приложение использует модель «blanchefort/rubert-base-cased-sentiment», основанную на RUbert, для определения эмоциональной окраски каждого комментария. Модель анализирует текст комментария и выдает оценку позитивной, негативной или нейтральной эмоциональной окраски.
После анализа эмоциональной окраски комментариев, приложение генерирует две диаграммы для наглядного представления результатов.
Диаграмма эмоциональной окраски. Первая диаграмма отображает процентное соотношение комментариев с различными эмоциональными окрасками, такими как позитивная, негативная или нейтральная. Это помогает пользователю лучше понять общую тональность комментариев и оценить эмоциональную реакцию зрителей на видео.
Диаграмма активности. Вторая диаграмма показывает, как распределяются комментарии по часам и датам. Это помогает пользователю понять, в какое время и в какие дни была наибольшая активность комментирования. Эта информация может быть полезной для определения популярности видео и оптимизации контента в будущем.
Технологии
Приложение разработано на языке Python, с использованием библилотеки Streamlit.
Приложение использует модель «blanchefort/rubert-base-cased-sentiment», основанную на RUbert, для определения эмоциональной окраски комментариев.
Приложение использует YouTube Data API v3 для загрузки комментариев к видео
Для визуализации результатов приложение использует библиотеки Matplotlib и Plotly.
Прриложение развернуто на платформе Hugging Face Spaces.
Установка и использование
Склонируйте репозиторий приложения с GitHub: ссылка.
Установите необходимые зависимости, выполнив команду pip install -r requirements.txt.
Запустите приложение, выполнив команду streamlit run project.pyв корневой папке проекта.
Откройте веб-браузер и перейдите по адресу http://localhost:8501.
Введите ссылку на видео YouTube в соответствующее поле и нажмите кнопку "Загрузить".
