# Batch Processing with PySpark

This project processes NYC taxi trip data in batch using Apache Spark, exploring partitioning, transformations, and zone-level analysis.

## What I built

- Loaded and explored yellow and green taxi parquet datasets
- Repartitioned data and analyzed partition file sizes
- Filtered trips by date and computed trip durations
- Joined trip data with zone lookup tables for location-based analysis
- Built revenue reports aggregated by zone and taxi type

## How I run it

```bash
uv run jupyter notebook --allow-root
```

## Why I made this

This project focuses on batch processing fundamentals: working with large parquet datasets, understanding Spark partitioning, applying DataFrame transformations, and producing aggregated reports.

## Resources

- [PySpark docs](https://spark.apache.org/docs/latest/api/python/)
- [NYC TLC Trip Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
