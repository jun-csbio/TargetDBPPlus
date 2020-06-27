# TargetDBP+: 
A DNA-binding protein identification method via using sequence-driven features.

## Pre-requisite:
    - Python, Java, Perl
    - SANN software (https://github.com/newtonjoo/sann)
    - NCBI nr90 database (ftp://ftp.ncbi.nlm.nih.gov/blast/db/FASTA/)
    - Linux system (suggested CentOS 7)

## Installation:

*Download TargetDBP+.jar, xxxx 
~~~
  $ tar xvzf I-LBR.tar.gz
  $ cd I-LBR
  $ java -jar I-LBR.jar "2w1aC" "EIDTLREEIDRLDAEILALVKRRAEVSKAIGKARMASGGTRLVHSREMKVIERYSELGPDGKDLAILLLRLGRGRLGH" null 0.3 ./tempfolder ./savefolder 4
~~~

*Edit the SANN_RUNNER_PATH and BLASTPGP_DB_PATH variable in the file “Config.properties”

## Update History:

- First release 2020-05-23

## References

[1] Jun Hu, Liang Rao, Yi-Heng Zhu, Gui-Jun Zhang, and Dong-Jun Yu. TargetDBP+: Enhancing the Performance of Identifying DNA-Binding Proteins via Weightedly Convolutional Features. Journal of Chemical Information and Modeling. sumitted
