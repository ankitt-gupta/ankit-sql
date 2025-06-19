# Learning Strategy (SQL & PL/SQL):

### Start with SQL Fundamentals:

1. Basic Queries: SELECT, FROM, WHERE, ORDER BY.
2. Filtering: AND, OR, NOT, LIKE, IN, BETWEEN.
3. Aggregates: COUNT, SUM, AVG, MIN, MAX, GROUP BY, HAVING.
4. Joins: INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL JOIN. This is crucial!
5. Subqueries: IN, EXISTS, correlated subqueries.
6. DDL (Data Definition Language): CREATE TABLE, ALTER TABLE, DROP TABLE.
7. DML (Data Manipulation Language): INSERT, UPDATE, DELETE.

### Practice Extensively:

1. Online Platforms: Use platforms like HackerRank, LeetCode, SQL Zoo, or Stratascratch. These provide problems and an environment to test your SQL.
2. Your Local Database: Create your own tables, insert sample data, and then write queries against them. This hands-on approach is the most effective.
3. Idea: Design a simple database schema for a library, an online store, or a student management system. Then write SQL to manage it.
4. Move to PL/SQL:

### Once you're comfortable with SQL, start with PL/SQL.

1. Basics: Anonymous blocks (DECLARE...BEGIN...END;), variables, IF/ELSE, loops (LOOP, WHILE, FOR).
2. Cursors: Explicit and implicit cursors for row-by-row processing.
3. Stored Procedures and Functions: Creating reusable code blocks.
4. Packages: Organizing related procedures, functions, and variables into logical units.
5. Error Handling: EXCEPTION blocks.
6. Triggers: Automating actions based on DML events.

### Structured Learning Resources:

1. Oracle Documentation: The official source. It's comprehensive but can be dense.
2. Online Courses: Udemy, Coursera, LinkedIn Learning often have good SQL and PL/SQL courses.
3. YouTube Tutorials: Many channels offer free lessons.
4. Books: Look for highly-rated books on SQL and PL/SQL (e.g., "SQL Fundamentals" or "Oracle PL/SQL Programming" by Steven Feuerstein).

### Project Structure For Now:

		ankit-sql/
		├── src/
		│   ├── tables/
		│   │   └── # Your table creation scripts go here
		│   ├── functions/
		│   │   └── # Your function scripts go here
		│   ├── procedures/
		│   │   └── # Your procedure scripts go here
		│   └── packages/
		│       └── # Your package scripts go here (spec and body)
		├── scripts/
		│   └── install.sql           # This will be your main deployment script
		├── README.md
		└── .gitignore


