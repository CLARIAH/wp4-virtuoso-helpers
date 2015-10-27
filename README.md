# Virtuoso Helpers

Tools for interacting with OpenLink Virtuoso Open Source edition

### Loading files into Virtuoso

The files `graph_mappings.csv` and `virtuoso_graph_files.py` introduced in f88e55a62fa082e68b3f751e4b62cb1c122db081 can be used to batch load RDF files into virtuoso.

These were adopted from the Data2Semantics/RinkeHoekstra@f88e55a62fa082e68b3f751e4b62cb1c122db081 work.

`graph_mappings.csv` is a CSV file that maps filenames to RDF Named Graph URIs. If a file is not in the mapping file, the `virtuoso_graph_files.py` script will use the default base as specified in the `GRAPH_BASE` variable. 
