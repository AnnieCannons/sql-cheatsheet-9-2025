# PostgreSQL Cheatsheet

Each student will complete the Description and Example sections for the SQL clause assigned to them.

For each clause:

1. In the **Description**, explain what the clause does in plain language.main
2. In the **Example**, write a working SQL statement that shows how the clause is used (like the `SELECT and `CREATE TABLE` examples below).
3. As a reference, `SELECT` and `CREATE TABLE` are already done for you.

---

### 1. `SELECT`

**Description:** `SELECT *` returns all columns from the provided table. You can also do `SELECT column_name_1, column_name_2` to return specific columns from the provided table.

**Example:**

```sql
SELECT *
FROM movies;
```

### 2. `CREATE TABLE`

**Description:** `CREATE TABLE` creates a new table in a database. It allows one to specify the name of the table, the name of each column, and each column's data type in the table.

**Example:**

```sql
CREATE TABLE friends (
  friend_id SERIAL PRIMARY KEY,
  name VARCHAR,
  birthday DATE
);
```

### 3. `INSERT INTO` — assigned to Deja

**Description:**

**Example:**

```sql

```

### 4. `UPDATE` — assigned to Rucha

**Description:**

**Example:**

```sql

```

### 5. `DELETE FROM` — assigned to Lajoie

**Description:**

**Example:**

```sql

```

### 6. `GROUP BY` — assigned to Rachel

**Description:**

**Example:**

```sql

```

### 7. `ORDER BY` — assigned to Tamara

**Description:**

**Example:**

```sql

```

### 8. `INNER JOIN` — assigned to Nicole

**Description:**

**Example:**

```sql

```

### 9. `LIMIT` — assigned to Xavier

**Description:** `LIMIT` is a feature that makes sure there is specific amount of data in the _view_ of the schema in SQL when writing a query. This is done by using the `LIMIT` feature at the end of the query before the semi-colon which triggers a limit.

**Example:**

```sql
SELECT *
FROM 'created-table'
ORDER BY DESC 'specific-column-value-chosen'
LIMIT 10;
```

### 10. `ON CONFLICT` — assigned to **\_**

**Description:**

**Example:**

```sql

```

### 11. `LIKE` — assigned to **\_**

**Description:**

**Example:**

```sql

```
