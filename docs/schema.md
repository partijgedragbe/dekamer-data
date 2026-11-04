## questions.parquet

| Column      | Type   | Nullable | Description                                                                  |
| ----------- | ------ | -------- | ---------------------------------------------------------------------------- |
| question_id | string | no       | Stable ID derived from ...                                                   |
| meeting_id  | string | no       | FK to meetings.parquet                                                       |
| speaker     | string | yes      | Name as printed in the report                                                |
| text        | string | no       | Full transcript of the speech, unaltered apart from whitespace normalisation |
| source_url  | string | no       | Original report on dekamer.be                                                |
