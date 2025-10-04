# Documentation

## ironBars
::: ironBars.ironSheets.gsheet_load
::: ironBars.ironSheets.gsheet_save
::: ironBars.ironSheets.fill_nans

## byteBars
::: ironBars.byteBars.byteBars
- Disk-backed, compressed, lazy-loading DataFrame-like storage.
- Supports row-wise, block-wise, and column-wise access.
- Stores Pandas DataFrames, Series, lists, and dictionaries efficiently.
- Provides SHA-256 integrity verification for data and index files.
- Full DataFrame-like interface via `.df` with `.iloc`, `.head()`, `.tail()`, and `.to_numpy()`.
