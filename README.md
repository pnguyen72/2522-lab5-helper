# COMP 2522 Lab 5 Helper

Who has the time to manually create 91 authors and 100 books? Not me.

Usage:
1. Create a local MySQL database.

2. In the terminal (not in MySQL), run
```sh
mysql -u <user-name> <db-name> -p < 2522lab5.sql

# for example, 
# mysql -u root 2522lab5 -p < 2522lab5.sql
```
If that fails for whatever reason, go to `jsonToSql.js` and replace your `USER_NAME`, `PASSWORD`, `DATABASE_NAME`, and run

```sh
node jsonToSql.js
```

3. Add `Database.java` to your project. Add the package declaration and/or edit the imports to match how you structure your project. See the javadoc for usage.

3. Download the library `mysql-connector-j-9.2.0` via IntelliJ.

## License

**BY USING THIS SOFTWARE YOU AGREE TO WEAR A HAWAIIAN SHIRT TO THE EXAM.**