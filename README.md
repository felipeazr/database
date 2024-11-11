# Database

## Tipos primitivos PostgreSQL vs Java

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


# Tipos de consulta de dados 
teste
teste2
## DML DTL DQL DCL