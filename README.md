# TargetDBP+: 
A DNA-binding protein identification method via using sequence-driven features.

## Pre-requisite:
    - Python, Java, Perl
    - SANN software (https://github.com/newtonjoo/sann)
    - NCBI nr90 database (ftp://ftp.ncbi.nlm.nih.gov/blast/db/FASTA/)
    - Linux system (suggested CentOS 7)

## Installation:

*Download this repository at https://github.com/jun-csbio/TargetDBPPlus.git or https://codeload.github.com/jun-csbio/TargetDBPPlus/zip/master first. Then, uncompress it and run the following command lines on Linux System.
~~~
  $ cd ./model/
  $ java -jar xxxx.jar xxx/
  $ java -jar xxxx.jar yyy/
  $ cd ../tools/
  $ tar zxvf blast
  $ java -jar TargetDBP+.jar ./example/
~~~

*The file of “Config.properties” should be set as follows:
~~~
TARGETDBPPLUS_PRED_MODEL=xxxx/model/targetdbpplus.mod
DBS_PRED_MODEL=xxxx/dbs_pred_mod
PSIPRED321_FOLDER_DIR=xxxx/tools/psipred321
BLAST_BIN_DIR=xxxx/tools/blast-2.2.26
BLASTPGP_EXE_PATH=xxxx/tools/blast-2.2.26/blastpgp
BLASTPGP_DB_PATH=xxxx/nr/nr
SANN_RUNNER_PATH=yyyy/SANN/sann/bin/sann.sh
BLASTPGP_SSITE_OUTPUT_PARSER_DIR=xxxx/tools/junh_BlastpgpSSITEOutputPARSER
~~~
Note that, "xxxx" should be the absolute path of this downloaded repository on your system. "yyyy" should be the absolute path of the installed SANN software.

## Update History:

- First release 2020-05-23

## References

[1] Jun Hu, Liang Rao, Yi-Heng Zhu, Gui-Jun Zhang, and Dong-Jun Yu. TargetDBP+: Enhancing the Performance of Identifying DNA-Binding Proteins via Weightedly Convolutional Features. Journal of Chemical Information and Modeling. sumitted
