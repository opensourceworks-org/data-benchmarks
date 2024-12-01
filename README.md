# Data Benchmarks
Benchmarks on data.  

Comparing (relatively) new libraries (daft, datafusion, ballista, polars, duckdb, .. ) to the established ones (spark, pandas, ..).
While we're at it, we'll test on different data formats: parquet, csv, deltalake, iceberg, hudi, ...
Testing both local and distributed, read queries and updates (upsert).

We'll focus on python api's, but may include rust and other new kids on the coding block (mojo, ..).


## Testing environment
- kubernetes on aws, azure of gcp
- macbook air m1 16GB
- data on aws s3 (parquet, csv, delta, ..)


## local tests
- [ ] arrow
- [ ] datafusion
- [ ] polars
- [ ] pandas
- [ ] daft
- [ ] ..


## distributed
- [ ] arrow (?)
- [ ] datafusion
- [ ] polars
- [ ] pandas
- [ ] daft
- [ ] ..

## datasets

TPC-H
TPC-DS
custom..

## update service

A service which generates updates for data based on columns with datatypes (schema), value ranges and record count.

