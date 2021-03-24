# SQL Parser

[![Code Coverage](https://img.shields.io/badge/coverage-0%25-orange)](https://img.shields.io/badge/coverage-0%25-orange)
[![Go ReportCard](https://goreportcard.com/badge/kislerdm/sqlscan)](https://goreportcard.com/report/kislerdm/sqlscan)

The service to parse the sql queries to identify the link between the RDB objects on logical level, i.e. to identify the link between joined tables and the resulting table.

## Modus Operandi

The program consumes the *.sql file(s), parses it and outputs the tables dependency graph.

## Dependencies

- https://github.com/SebastiaanKlippert/go-wkhtmltopdf
- https://github.com/pganalyze/pg_query_go
