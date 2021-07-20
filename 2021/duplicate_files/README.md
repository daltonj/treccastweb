## Description of `marco_duplicates.txt`

Each line in the file consists of the original document id followed by a list of its duplicate document ids (0 or many seperated by comma).

A line in the file has the following form:
`d0:d1,d2,d3`

The first id `d0` corresponds to the original document id. The comma seperated document ids following the colon are the ones which are marked as duplicates of `d0`.

For example:
1) `MARCO_D135:MARCO_D2854269`  => `MARCO_D135` is the original document id and `MARCO_D2854269` is marked as its duplicate.
2) `MARCO_D590:MARCO_D1258790,MARCO_D7001097` => `MARCO_D590` is the original document id and `MARCO_D1258790` and `MARCO_D7001097` are marked as its duplicates.


## Description of `wapo-near-duplicates`

Each line in the file consists of documents that have more than one copy in the collection. The ids of these copies are the same, thus a line in the file has the following form:

`0000107b869682826003b04a40e63948 0000107b869682826003b04a40e63948 Vulnerable Senate Democrats think Republicans just handed them a lifeline on health care`

Just the first copy of the document is included in the final index.


