1. ���ɵ����

1.1 ����mysql�ļ�
./yii migrate/create   --migrationPath=@fecshop/migrations/mysqldb    fecshop_tables

1.2 ����mongodb�ļ�
./yii mongodb-migrate/create   --migrationPath=@fecshop/migrations/mongodb    fecshop_tables


2. Ǩ�Ƶ�����
2.1 mysql
./yii migrate --interactive=0 --migrationPath=@fecshop/migrations/mysqldb

2.2 mongodb
./yii mongodb-migrate/create  --interactive=0 --migrationPath=@fecshop/migrations/mongodb









