# Lezione DUE - 7 dicembre 2015

## Argomenti

  * ripasso lezione precedente
  * prima versione database emufest
    * struttura: `emufest.schema`
    * dati di test: `emufest.fill`
  * esempi di ricerca:
    * ```sql
    select distinct * from titles,authors inner join authors_titles where titles.id = authors_titles.title_id and authors.id = authors_titles.author_id and authors.last = "Cerioni";
    ```
