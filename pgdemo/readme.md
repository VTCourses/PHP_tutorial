## Setup 

1. Create a `app_db_cfg.php` configuration file
    ```
    cp app_db_cfg.php.sample app_db_cfg.php
    ```

2. Edit the database information in the `app_db_cfg.php`
    ```
    DEFINE('DB_USER', '');
    DEFINE('DB_PASSWORD', '');
    DEFINE('DB_HOST', '');
    DEFINE('DB_NAME', '');
    ```

3. See example `basic.php` 

4. Never commit `app_db_cfg.php` configuration file!!!
    See [.gitignore](../.gitignore)