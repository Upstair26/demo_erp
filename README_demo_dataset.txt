Dataset demo per Airbyte + dbt
- customers.csv: anagrafica clienti
- products.csv: catalogo prodotti
- orders.csv: testata ordini
- order_items.csv: righe ordine

Flusso consigliato:
1) Airbyte Source = File connector
2) Airbyte Destination = PostgreSQL
3) dbt-postgres su PostgreSQL per creare modelli staging/mart
