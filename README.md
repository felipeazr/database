
# Database
## Tipos de Consulta de Dados

Existem cinco tipos principais de linguagens SQL, cada uma com uma finalidade específica. Abaixo, uma descrição detalhada de cada uma:

---

## 1. DDL - Data Definition Language (Linguagem de Definição de Dados)
A "D" em DDL vem de **Definição**. Os comandos DDL são usados para definir e alterar a estrutura de objetos no banco de dados, como tabelas e índices.

**Principais comandos DDL:**
- `CREATE` - Cria novos objetos no banco de dados.
- `ALTER` - Altera a estrutura de um objeto existente.
- `DROP` - Remove objetos do banco de dados.

---

## 2. DML - Data Manipulation Language (Linguagem de Manipulação de Dados)
A "M" em DML vem de **Manipulação**. Esses comandos permitem a manipulação dos dados armazenados nas tabelas do banco.

**Principais comandos DML:**
- `INSERT` - Insere novos registros em uma tabela.
- `DELETE` - Remove registros de uma tabela.
- `UPDATE` - Atualiza dados em uma tabela.

---

## 3. DQL - Data Query Language (Linguagem de Consulta de Dados)
A "Q" em DQL vem de **Consulta**. Este grupo contém os comandos de consulta, sendo o mais comum o `SELECT`.

**Principal comando DQL:**
- `SELECT` - Realiza consultas para recuperar dados do banco.

*Nota:* Em alguns contextos, o `SELECT` pode ser considerado parte da DML.

---

## 4. DTL - Data Transaction Language (Linguagem de Transação de Dados)
A "T" em DTL vem de **Transação**. Esses comandos permitem o controle de transações no banco de dados, assegurando que as operações sejam executadas de forma consistente.

**Principais comandos DTL:**
- `BEGIN TRANSACTION` - Inicia uma nova transação.
- `COMMIT` - Confirma as operações realizadas na transação.
- `ROLLBACK` - Reverte as operações realizadas na transação.

---

## 5. DCL - Data Control Language (Linguagem de Controle de Dados)
A "C" em DCL vem de **Controle**. Esses comandos são usados para controlar o acesso e a segurança dos dados.

**Principais comandos DCL:**
- `GRANT` - Concede permissões a um usuário ou papel.
- `REVOKE` - Remove permissões concedidas.
- `DENY` - Nega permissões a um usuário ou papel.

---


# Tipos primitivos PostgreSQL vs Java

| Tipo Primitivo PostgreSQL | Tipo Primitivo Java | Descrição                                                  |
|---------------------------|---------------------|------------------------------------------------------------|
| `boolean`                 | `boolean`           | Representa valores verdadeiros ou falsos                    |
| `smallint`                | `short`             | Números inteiros de 2 bytes                                 |
| `integer` (ou `int`)      | `int`               | Números inteiros de 4 bytes                                 |
| `bigint`                  | `long`              | Números inteiros de 8 bytes                                 |
| `real`                    | `float`             | Números de ponto flutuante de 4 bytes (precisão simples)    |
| `double precision`        | `double`            | Números de ponto flutuante de 8 bytes (precisão dupla)      |
| `numeric` ou `decimal`    | `BigDecimal`        | Números exatos de ponto flutuante com precisão arbitrária   |
| `serial`                  | `int`               | Sequência de números inteiros, autoincremento               |
| `bigserial`               | `long`              | Sequência de números inteiros grandes, autoincremento       |
| `char(n)`                 | `String`            | Cadeias de caracteres de tamanho fixo                       |
| `varchar(n)`              | `String`            | Cadeias de caracteres de tamanho variável                   |
| `text`                    | `String`            | Cadeias de caracteres de tamanho variável sem limite        |
| `bytea`                   | `byte[]`            | Dados binários                                             |
| `timestamp`               | `java.sql.Timestamp`| Data e hora sem fuso horário                                |
| `timestamptz`             | `java.sql.Timestamp`| Data e hora com fuso horário                                |
| `date`                    | `java.sql.Date`     | Data (sem hora)                                             |
| `time`                    | `java.sql.Time`     | Hora (sem data)                                             |
| `interval`                | `java.time.Duration`| Período de tempo (dias, meses, anos)                        |
| `uuid`                    | `java.util.UUID`    | Identificadores únicos universais (UUID)                    |

---