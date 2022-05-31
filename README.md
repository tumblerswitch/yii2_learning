# yii2-learning

##Запуск:
1. git clone
2. cd $project

###OpenServer:
1. Добавить в домены:
    1. Имя домена: ```yii2-learn.loc```
    2. Папка домена:```\yii2_learning\app\frontend\web```
    3. Имя домена: ```admin.yii2-learn.loc```
    4. Папка домена:```\yii2_learning\app\backend\web```
2. Добавить БД:
   1. Создать новую БД "exampleName"
   2. Изменить в app\config\main-local.php
      ```
      'dsn' => 'mysql:host=localhost;dbname=exampleName',
      ```
  