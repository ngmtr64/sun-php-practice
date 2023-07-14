__shares___
* id (INT, PRIMARY, AUTO_INCREMENT)
* user_id (INT)
* title (VARCHAR (255))
* body (TEXT)
* link (VARCHAR (255))
* create_date (DATETIME, CURRENT_TIMESTAMP())

__users__
* id (INT, PRIMARY, AUTO_INCREMENT)
* name (VARCHAR (255))
* email (VARCHAR (255))
* password (VARCHAR (500))
* register_date (DATETIME, CURRENT_TIMESTAMP())
