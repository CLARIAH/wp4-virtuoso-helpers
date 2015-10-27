# Virtuoso Helpers

Tools for interacting with OpenLink Virtuoso Open Source edition

### Loading files into Virtuoso

The files `graph_mappings.csv` and `virtuoso_graph_files.py` introduced in [1e5c5fc](https://github.com/CLARIAH/wp4-virtuoso-helpers/commit/f88e55a62fa082e68b3f751e4b62cb1c122db081) can be used to batch load RDF files into virtuoso.

These were adopted from the [Data2Semantics/RinkeHoekstra:b42ac64](https://github.com/Data2Semantics/raw2ld/commit/254389803dedc7ecb41ddc159a850439e04371e6) work.

`graph_mappings.csv` is a CSV file that maps filenames to RDF Named Graph URIs. If a file is not in the mapping file, the `virtuoso_graph_files.py` script will use the default base as specified in the `GRAPH_BASE` variable. 
