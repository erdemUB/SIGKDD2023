# Motif Transition Model

This is a C++ implementation of motif transition model (MTM).

To compile the code
`cd src`
`make`

To run the code
`./MTM inputfile l_max delta output_number`

Format of the inputfile (source node, target node, timestamp)
`u1 v1 t1`
`u2 v2 t2`
`...`

# Temporal Motif Counting

Please refer to `/Temporal_Motifs_Counting` for details of it.

## Table generation in the paper

In order to generate table and figures given in the paper below, you may leverage this repository as well.

Table 1: Please generate the output graphs by following the instructions for Motif Transition Model (MTM) above. Then, use graph statistics to measure selected metrics in the output graphs. <br />
Table 2: You can utilize `/Temporal_Motif_Counting` for counting the [2,4]-event motifs in the generated graphs. <br />
Table 3: Running MTM code will also provide you the details of runtime analysis. You may leverage that output for creating Table 3. <br />

### Reference
```
@inproceedings{10.1145/3534678.3539234,
author={Liu, Penghang and Sarıyüce, Ahmet Erdem},
title = {Using Motif Transitions for Temporal Graph Generation},
year = {2023},
doi = {10.1145/3580305.3599540},
booktitle = {Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining}
}

```
