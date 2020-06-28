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
BLASXXX=xxx
xxx
xxx
xxx
~~~

## Update History:

- First release 2020-05-23

## References

[1] Jun Hu, Liang Rao, Yi-Heng Zhu, Gui-Jun Zhang, and Dong-Jun Yu. TargetDBP+: Enhancing the Performance of Identifying DNA-Binding Proteins via Weightedly Convolutional Features. Journal of Chemical Information and Modeling. sumitted
