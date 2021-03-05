# iTerator

## Modular bioinformatics workflow for:


### Module 1 - multi-assembly of short-reads for an optimized assembly product

![iT m1 diagram](https://github.com/c-leber/iTerator/blob/main/iT_diagram_1.png)

Figure 5.1 from Chapter 5: Improving short read assemblies for comparative genomic insights in *Moorena bouillonii* in The *Moorena bouillonii* and *Alpheus frontalis* Symbiosis: Patterns in Chemical Ecology, Chemogeography, and Genomics; PhD dissertation of C Leber.

3rd party dependencies:
- SPAdes (https://cab.spbu.ru/software/spades/)
- QUAST (http://quast.sourceforge.net/)
- Prokka (https://github.com/tseemann/prokka)
- bbmap (https://jgi.doe.gov/data-and-tools/bbtools/bb-tools-user-guide/bbmap-guide/)

### Module 2 - iterative contig extension & de novo scaffolding, multi-reference scaffolding, gap filling, and gap removal for improving assembly contiguity

![iT m2 diagram](https://github.com/c-leber/iTerator/blob/main/iT_diagram_2.png)

Figure 5.2 from Chapter 5: Improving short read assemblies for comparative genomic insights in *Moorena bouillonii* in The *Moorena bouillonii* and *Alpheus frontalis* Symbiosis: Patterns in Chemical Ecology, Chemogeography, and Genomics; PhD dissertation of C Leber.


3rd party dependencies:
- SSPACE (www.baseclear.com/bioinformatics-tools/)
- Multi-CSAR (https://github.com/ablab-nthu/Multi-CSAR)
- GapFiller (www.baseclear.com/bioinformatics-tools/)

#### Other recommended tools, to be used in association:
- Trimmomatic (http://www.usadellab.org/cms/?page=trimmomatic)
- Celera assembler/WGS (http://wgs-assembler.sourceforge.net/wiki/index.php?title=Main_Page)

Usage instructions and documentation are included in the Jupyter Notebook

***Please report issues if you run into any trouble! -Chris***
