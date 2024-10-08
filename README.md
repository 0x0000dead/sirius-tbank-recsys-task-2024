# Отборочное задание на смену в Сириус 2024
Для выполнения задания вам предстоит работать с датасетом от Кино.Триколор, который содержит информацию о просмотрах фильмов пользователями. Датасет включает 2.5 млн событий, связанных с взаимодействием пользователей (200 тысяч пользователей) с различными фильмами (10 тысяч фильмов). Основная задача состоит в предсказании следующих фильмов для просмотра пользователями на основе их истории взаимодействий.

Вы можете использовать любые методы и подходы для работы с тренировочной выборкой, в том числе парсинг интернета для получения дополнительных фичей. Важно подробно описать, какие фичи вы использовали и откуда их получили. Тестовую выборку изменять запрещается!

Датасет состоит из следующих файлов:

`train_data.csv` — данные для обучения, содержащие информацию о просмотрах фильмов пользователями.  
`test_data.csv` — данные для тестирования, на которых необходимо будет проверить вашу модель.  
`users_df.csv` — описание пользователей, которое может содержать дополнительную информацию о них.  
`items_df.csv` — описание фильмов, содержащее их характеристики и другие полезные фичи.  
`countries.csv`, `genres.csv`, `staff.csv` - вспомогательные данные (см intro_task.ipynb).  

### Цель задания — построить модель, которая на основе данных о предыдущих просмотрах пользователей сможет предсказать, какие фильмы им могут быть интересны в будущем.
