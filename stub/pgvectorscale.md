
--------

## Usage


```sql
CREATE EXTENSION vectorscale CASCADE;

CREATE TABLE IF NOT EXISTS document_embedding  (
    id BIGINT PRIMARY KEY GENERATED BY DEFAULT AS IDENTITY,
    metadata JSONB,
    contents TEXT,
    embedding VECTOR(1536)
);
  
CREATE INDEX document_embedding_idx ON document_embedding
USING diskann (embedding);

SELECT *
FROM document_embedding
ORDER BY embedding <=> $1
LIMIT 10
```

This fdw is read-only for now.
