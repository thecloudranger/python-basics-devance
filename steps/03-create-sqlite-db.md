# Create a SQLite Database

In the previous step you created a simple Flask Web App. In this step you will create a Sqlite database and a new table.

## Sqlite Database

* In VS Code, Open the integrated terminal with **(Cmd/Ctrl + `)**
* Move to the root of the project

```sh
sqlite3 games.db
```

* Display the database that was created with the `.databases` command
  
```
.databases
```

* Type `.quit` to exit the SQLite prompt
* Open the Command Prompt **(Cmd/Ctrl + Shift + P)**
* Select **SQLite: Open Database**
* Select **Choose database from file** in the prompt
* Type `<project-path>/games.db` in the prompt
* Notice there is now a **SQLite Explorer** view in the bottom left corner.
* Right-click the `games.db` database and select **New Query**
* Add the following queries to:
  * Create a table
  * Insert a game
  * Select a record
```sql
-- SQLite

CREATE TABLE IF NOT EXISTS games(
  id INTEGER PRIMARY KEY AUTOINCREMENT,
  name TEXT NOT NULL,
  price REAL NOT NULL,
  rate INTEGER NOT NULL
)

INSERT INTO games (id, name, price, rate)
VALUES (1,'Cuphead','185.0','95');

SELECT * FROM games;  
)
```
* Each block must be run by itself. Highlight the block to run.
* Open the Command Palette and select **SQLite: Run Selected Query**
* View the query results in split pane mode

## Next step

In this step you created a Sqlite database, created a new table, inserted a new record and queried the record. In the [next step](./04-read-db-api.md) you will create a API route, connect to the database and query the records in Python.