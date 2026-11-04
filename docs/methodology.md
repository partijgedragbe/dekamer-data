This dataset is compiled from official documents published by the Belgian Chamber of Representatives (https://www.dekamer.be), including plenary and committee reports, parliamentary documents and dossiers.

The process is as follows:

1. Plenary and committee reports are read from the official website of the Belgian Chamber of Representatives (https://www.dekamer.be).

2. Some corrections and fixes are applied on the reports. This is done for known mistake in the reports such as misspellings or incorrect formatting that cause issues with later parsing of the reports.

3. These reports are parsed and data is extracted from them in a structured format. This is done based on specific patterns (based on content and layout) that the reports use.

4. The extracted data is stored in a structured format (.parquet) for easy access and analysis.

5. The generated .parquet files are validated automatically to ensure data quality.
