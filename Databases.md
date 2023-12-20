# Relational Databases
1. Relational databases model data by storing rows and columns in tables.
   - Tuples (rows)
   - Attributes (columns)
   - Relations (tables)
2. SQL (Structured Query Language)
   - the lang used to issue commands to the database
   - it is an imperative lang, not a procedural one
3. Web Applications w/ Databases
   - Application developers
   - Database Administrators (DBA)
4. Database Model/Schema
   - the structure or format of a database
5. Database Management Systems
   - Oracle: enterprise-scale
   - MySql: commercial open source
   - SqlServer: from Microsoft
   - *SqLite, embedded built-in system*
6. Database Design
   - **Basic rule:**
     - Don't put the same string data in twice - use a relationship instead
     - Integer Reference Pattern: we use integers to reference rows in another table
   - 3 Kinds of Keys: Primary key, Logical key, and Foreign key
     - Key Rules:
       - Never use your logical key as the primary key
         - logical keys may change, e.g. email addresses
7. Using **Join**
   - links across several tables using Select
   - Relational power
`Select Album.title, Artist.name from Album join Artist on Album.artist_id = Artist_id`
