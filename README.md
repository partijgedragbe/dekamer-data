# Belgian Chamber Data

Structured data from the Belgian Chamber of Representatives
<<<<<<< Updated upstream
(dekamer.be) as Parquet files.
=======
(dekamer.be) as Parquet files: dossiers, meetings, votes, questions, speeches.
>>>>>>> Stashed changes

Unofficial and independent. See [NOTICE.md](NOTICE.md).

## Data

| File                                       | Rows are  | Description                             |
| ------------------------------------------ | --------- | --------------------------------------- |
| `sessions/56/plenary/questions.parquet`    | questions | Questions from the plenary meetings.    |
| `sessions/56/commission/questions.parquet` | questions | Questions from the commission meetings. |

Column documentation: [docs/schema.md](docs/schema.md).

## Download

Always the newest files:
`https://github.com/<you>/belgian-chamber-data/releases/download/latest/questions.parquet`

```python
import polars as pl
df = pl.read_parquet("https://github.com/<you>/belgian-chamber-data/releases/download/latest/questions.parquet")
```

```sql
-- DuckDB
SELECT * FROM read_parquet('https://github.com/<you>/belgian-chamber-data/releases/download/latest/questions.parquet') LIMIT 10;
```

Versioned snapshots for reproducible research: DOI `10.5281/zenodo.<concept-id>`.

## Citation

See `CITATION.cff` (GitHub's "Cite this repository" button). Please cite the
version DOI of the snapshot you used and the date you accessed the data.

## License

Compilation: CC BY 4.0 (see `LICENSE`). Underlying texts come from official
Chamber documents, see [NOTICE.md](NOTICE.md).

## Known limitations

See [docs/methodology.md](docs/methodology.md).
