# Exemplo Simples de SQL

## Tabelas de Exemplo

**Alunos**
| id | nome  | idade |
|----|-------|-------|
| 1  | Ana   | 17    |
| 2  | Bruno | 18    |
| 3  | Carla | 17    |

**Notas**
| id | aluno_id | nota |
|----|----------|------|
| 1  | 1        | 8.5  |
| 2  | 2        | 7.0  |
| 3  | 3        | 9.2  |
| 4  | 1        | 9.0  |

---

## 1. COUNT
Conta quantos registros existem em uma tabela ou coluna.

```sql
-- Conta quantos alunos existem
SELECT COUNT(*) AS total_alunos
FROM Alunos;
```

---

## 2. AVG
Calcula a média dos valores de uma coluna.

```sql
-- Calcula a média das notas
SELECT AVG(nota) AS media_notas
FROM Notas;
```

---

## 3. JOIN
Usado para juntar informações de duas ou mais tabelas.

```sql
-- Mostra o nome do aluno junto com suas notas
SELECT Alunos.nome, Notas.nota
FROM Alunos
JOIN Notas ON Alunos.id = Notas.aluno_id;
```

**Explicação do JOIN:**  
- `JOIN` une tabelas.  
- `ON Alunos.id = Notas.aluno_id` define a condição de união (quem se relaciona com quem).

