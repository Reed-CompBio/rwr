# Random Walk with Restarts

An implementation of the source-targets random-walk-with-restarts and the general input random-walk-with-restarts algorithms.

Requires Python3 and `networkx`. More packaging information is available at `pyproject.toml`.

Licensed under MIT.

## Usage

RWR takes in a network file, and will either take in a nodes file under `RWR.py` or a sources file and a targets file under
`ST_RWR.py`. An output file also must be specified.

The network file is `|`-delimited, with newlines separating each entry. Each line contains two nodes, source and target, to
form a directed graph.
