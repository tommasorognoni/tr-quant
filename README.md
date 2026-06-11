# Quant Research Platform

A point-in-time equity research platform: scheduled ingestion → BigQuery
warehouse with as-of-date correctness → cross-sectional factor research +
event-driven backtester.

**Known limitations (free data):** survivorship bias in the universe;
fundamentals are restated, not as-first-reported; availability dates for
fundamentals are approximated with a conservative reporting lag. See
`docs/limitations.md`.
