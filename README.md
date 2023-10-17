# aws-rds-psql-cheatsheet
AWS RDS PSQL Cheatsheet

- SSH to the database
`psql -h hostname -p portNumber -U userName dbName -W`
- List Schemas
`\dn`
- Create a schema
`CREATE SCHEMA schema_name;`
- List all tables
`\dt`

