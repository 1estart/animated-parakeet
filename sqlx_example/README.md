database_url postgres://world:world123@localhost:5432/world-db  

sqlx mirgrate add create_todos_table.sql  
sqlx mirgrate run

example from  
https://github.com/transact-rs/sqlx/tree/main/examples/postgres/todos 
