Compares the output of your commands with mine (absolutely no guarantee that mine are correct or better. If you have diffs I'd like to know it, my day might be lame). **From the english subject - SELECT queries (ex06 - ex21) only**

## Requirements
You must have set your path to the right mysqli.bin

## Usage

In you day repo (make a copy beforehand) :

```bash
git clone https://github.com/RBoisselet/piscine_php_d05_check.git && piscine_php_d05_check/setup

./sql_test [your_mysql_login] [your_mysql_password] [your_42_login (i.e. 'rboissel')]
```

If not differences, it should just echo this error message several times :

```
mysql.bin: [Warning] Using a password on the command line interface can be insecure.
```

## Exemple output

 ```bash
 ex:	ex06.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.

 ex:	ex07.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.

 ex:	ex08.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.

 ex:	ex09.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.

 ex:	ex10.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.
 0a1 > diff exemple
 ex:	ex11.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.

 ex:	ex12.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.

 ex:	ex13.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.

 ex:	ex14.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.

 ex:	ex15.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.

 ex:	ex16.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.

 ex:	ex17.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.

 ex:	ex18.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.

 ex:	ex19.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.

 ex:	ex20.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.

 ex:	ex21.sql
 mysql.bin: [Warning] Using a password on the command line interface can be insecure.
```
