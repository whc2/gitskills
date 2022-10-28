# softwares
### tools
[long read tools summary](https://long-read-tools.org/index.html)

[ccs](https://github.com/PacificBiosciences/ccs)

[purge_dups](https://github.com/dfguan/purge_dups)


assmbler | publication | author
-------- | ----------- | ------
[hifi_asm](https://github.com/chhylp123/hifiasm) | 
[hifiasm-meta](https://github.com/xfengnefx/hifiasm-meta) | 
[Canu](https://github.com/marbl/canu) |
Falcon | 2016 nm Phased diploid genome assembly with single-molecule real-time sequencing | Chen-Shan Chin
[wtdbg2](https://github.com/ruanjue/wtdbg2) |
[Peregrine](https://github.com/cschin/peregrine) | 2019 [Human Genome Assembly in 100 Minutes](https://www.biorxiv.org/content/10.1101/705616v1) | Chen-Shan Chin
[Necat](https://github.com/xiaochuanle/NECAT) | |
[Mecat](https://github.com/xiaochuanle/MECAT2) | |
[shasta](https://github.com/chanzuckerberg/shasta) | |
[Hinge](https://github.com/HingeAssembler/HINGE) | | 
[wengan](https://github.com/adigenova/wengan) | | 
[spades](https://cab.spbu.ru/software/spades/) | |
[NextDenovo](https://github.com/Nextomics/NextDenovo) | |
[raven](https://github.com/lbcb-sci/raven) | |
[HERA](https://github.com/liangclab/HERA) | |
[RagTag](https://github.com/malonge/RagTag) | |
[MARVEL](https://github.com/schloi/MARVEL/) | |
[LJA](https://github.com/AntonBankevich/LJA) | |
[Flye](https://github.com/fenderglass/Flye)  | |

### assembly polish
polisher | specific to | 
-------- | ----------- | 
[Nanopolish](https://github.com/jts/nanopolish) | Nanopore original signals [doc](https://nanopolish.readthedocs.io/en/latest/index.html) |
[medaka](https://nanoporetech.github.io/medaka/index.html) | Nanopore reads |
[pepper](https://github.com/kishwarshafin/pepper) | Nanopore | 
[Racon](https://github.com/isovic/racon) | |


### Assembly-based structural variant calls
variation caller | publication | author
---------------- | ----------- | ------
[pbsv](https://github.com/PacificBiosciences/pbsv) | 
[Sniffles](https://github.com/fritzsedlazeck/Sniffles) |
[deepvariant](https://github.com/google/deepvariant)| | learning-based callers, [hifi usage](https://github.com/google/deepvariant/blob/r1.0/docs/deepvariant-pacbio-model-case-study.md)
[GATK] | | model-based callers
[Bonito](https://github.com/nanoporetech/bonito) | |
https://medium.com/dnanexus/an-exploration-of-machine-learning-based-variant-callers-for-snv-and-small-indel-using-pacbio-hifi-f6efec6bee04

### evaluation
methods | publication | author
------- | ----------- | ------
[BUSCO](https://busco.ezlab.org/) | |
[yak](https://github.com/lh3/yak) qv | | yak count -b37 -t <nThreads> -o <sr.yak> <short-reads.fastq>; yak qv -t <nThreads> <sr.yak> <contigs.fa>
[LTR_retriever](https://github.com/oushujun/LTR_retriever) | |
[pacbio discuss](https://www.pacb.com/blog/beyond-contiguity/) | |
[merqury](https://github.com/marbl/merqury) | |

### Hi-C process
methods | publication | author
------- | ----------- | -------
[HiC-Pro](https://github.com/nservant/HiC-Pro) | |
[ALLHiC](https://github.com/tangerzhang/ALLHiC) | |
[juicer](https://github.com/aidenlab/juicer) | | Arrowhead for finding contact domains
[3d-dna](https://github.com/aidenlab/3d-dna) | |
[SALSA](https://github.com/marbl/SALSA) | |
[scaffHiC](https://github.com/wtsi-hpag/scaffHiC) | |
[pin_hic](https://github.com/dfguan/pin_hic) | |
[Homer](http://homer.ucsd.edu/homer/interactions/) | |
[Cooltools](https://cooltools.readthedocs.io/en/latest/) | |
[cooler](https://github.com/open2c/cooler) | |
[pairtool](https://github.com/open2c/pairtools) | |

# annotation
[pacbio full length transcriptome](https://www.pacb.com/applications/rna-sequencing/)

[iso-seq example](https://downloads.pacbcloud.com/public/dataset/redwood2020/isoseq/)

[intro rna-seq](https://mbernste.github.io/posts/rna_seq_basics/)

[RepeatModeler](https://github.com/Dfam-consortium/RepeatModeler), [http://www.repeatmasker.org/RepeatModeler/](http://www.repeatmasker.org/RepeatModeler/)

[Dfam](https://www.dfam.org/classification/tree)

# references
[protocal for ccs](https://www.biorxiv.org/content/10.1101/519025v2)
