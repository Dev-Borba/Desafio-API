### Nessa aula aprenderemos a alterar o nome das tabelas, adicionar e deletar colunas do banco de dados.
---
```sql
-- Alterar nome da tabela:
ALTER TABLE users
RENAME TO clients


-- Adicionando coluna status:
ALTER TABLE users 
ADD status VARCHAR


-- Renomeando coluna status :
ALTER TABLE users 
RENAME COLUMN status to active


-- Deletando coluna status:
ALTER TABLE users 
DROP COLUMN status
```
---