## Requirements
You must have set your path to the right mysqli.bin

## Usage

```bash
git clone ssh://git@git.42l.fr:42084/rboisselet/piscine_php_d05_check.git && piscine_php_d05_check/setup
./sql_test [your_mysql_login] [your_mysql_password] [your_42_login (i.e. 'rboissel')]
```

If not differences, it should just echo this error message several times :

```
mysql.bin: [Warning] Using a password on the command line interface can be insecure.
```
