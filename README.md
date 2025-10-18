# PRT563 Neo4j Migration 

This folder contains the **exact scripts** required for Assessment 4 (Tasks 2–5) on **Neo4j Aura**.

## Files
- `import.txt` — **Task 2**: Constraints, node loads (12 CSVs), and relationship builds (idempotent).
- `queries.txt` — **Task 3**: Four business-use Cypher queries (catalog, suppliers, CRM, stock flows).
- `gds_centrality_pagerank.txt` — **Task 4**: PageRank centrality over Supplier–Product–Sales graph.
- `gds_similarity_nodesimilarity.txt` — **Task 5**: Product similarity via shared suppliers.
- `README.md` — this file with instructions + screenshot checklist.

## CSV Base Path
All `LOAD CSV` commands read from the public **RAW** URLs in repo:

```
https://raw.githubusercontent.com/shahsandesh30/PRT563_ADVANCED_DATA_MANAGEMENT/main/csv/
```

> Example: `https://raw.githubusercontent.com/shahsandesh30/PRT563_ADVANCED_DATA_MANAGEMENT/main/csv/Product.csv`

