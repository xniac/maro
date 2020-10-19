# Performance

Below are the final environment metrics of the onlineLP in different topologies.
For each experiment, we setup the environment and test for a duration of 1 week
with environment random seed 0, 128, 1024.  Besides the parameter listed in the
table, the experiment is configured with the default parameter value in the file
`examples/citi_bike/online_lp/config.yml`

## Future demand and supply from BE

Topology  | Total Requirement | Shortage | #Repositioning
----------|------------------:|---------:|--------------:
toy.3s_4t | 15,071            | 8,168    | 173
toy.4s_4t | 10,128            | 4,061    | 1,628
toy.5s_6t | 15,983            | 6,562    | 2,505
ny.201908 |
ny.201910 |
ny.202001 |
ny.202004 |
ny.202006 |

## Future demand and supply by One-step Fixed-window Moving Average

Topology  | Total Requirement | Shortage | #Repositioning
----------|------------------:|---------:|--------------:
toy.3s_4t | 15,071            | 8,167    | 1
toy.4s_4t | 10,128            | 3,711    | 2,462
toy.5s_6t | 15,983            | 6,628    | 2,194
ny.201908 |
ny.201910 |
ny.202001 |
ny.202004 |
ny.202006 |