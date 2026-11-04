# Belgian Chamber Data

Structured data from the Belgian Chamber of Representatives
(dekamer.be) as Parquet files.

Unofficial and independent. See [NOTICE.md](NOTICE.md).

## Data

| File                                       | Rows are  | Description                             |
| ------------------------------------------ | --------- | --------------------------------------- |
| `sessions/56/plenary/questions.parquet`    | questions | Questions from the plenary meetings.    |
| `sessions/56/commission/questions.parquet` | questions | Questions from the commission meetings. |

Column documentation: [docs/schema.md](docs/schema.md).

## Download

You can download the data here directly from GitHub or from Zenodo [https://zenodo.org/records/23956627](https://zenodo.org/records/23956627).

[![DOI](https://zenodo.org/badge/1432329037.svg)](https://zenodo.org/badge/latestdoi/1432329037)

## Citation

See `CITATION.cff` (GitHub's "Cite this repository" button). Please cite the
version DOI of the snapshot you used and the date you accessed the data.

## License

Compilation: CC BY 4.0 (see `LICENSE`). Underlying texts come from official
Chamber documents, see [NOTICE.md](NOTICE.md).

## Known limitations

See [docs/methodology.md](docs/methodology.md).
