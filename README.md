# Graphs on GPUs


## Docker images:
Dockerfile for `erictdawson/base`: https://github.com/edawson/dawdl/blob/master/base/base.Dockerfile
minigraph (dockerhub): `erictdawson/minigraph`

## svaha2: build graphs for SVs in GFA (from FASTA and VCF)
source code: https://github.com/edawson/svaha2  
Docs are in README and in Eric Dawson's brain. Output should be GFA1. Easily converted to GFA2 with https://github.com/edawson/gfakluge

## minigraph: map reads to graph
source code: https://github.com/lh3/minigraph  
GAF (output) format: https://github.com/lh3/gfatools/blob/master/doc/rGFA.md#the-graph-alignment-format-gaf


## Workflow

![](docs/images/workflow.png)
