# mysql container for jp

Set `LC_ALL` as `ja_JP.UTF-8` and set character encoding settings of MySQL as `utf8mb4`.  
You can add any Emoji to database.

## Variables

```
mysql> show variables like "%character%";
+--------------------------+----------------------------+
| Variable_name            | Value                      |
+--------------------------+----------------------------+
| character_set_client     | utf8mb4                    |
| character_set_connection | utf8mb4                    |
| character_set_database   | utf8mb4                    |
| character_set_filesystem | binary                     |
| character_set_results    | utf8mb4                    |
| character_set_server     | utf8mb4                    |
| character_set_system     | utf8                       |
| character_sets_dir       | /usr/share/mysql/charsets/ |
+--------------------------+----------------------------+
8 rows in set (0.07 sec)
```

Any other variables which are able to change with environment variables in official mysql container are also configlable.


