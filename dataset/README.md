There are seven files in this folder, as follows:

(1) UniSwiss-Tr-posi.fasta  : this contains 6,000 training DNA-binding protein (DBP) sequences extracted from UniProtKB/Swiss-Prot
(2) UniSwiss-Tr-nega.fasta  : this contains 6,000 training non-DNA-binding protein (non-DBP) sequences extracted from UniProtKB/Swiss-Prot
(3) UniSwiss-Tst-posi.fasta : this contains 651 testing DBP sequences extracted from UniProtKB/Swiss-Prot
(4) UniSwiss-Tst-nega.fasta : this contains 651 testing non-DBP sequences extracted from UniProtKB/Swiss-Prot
(5) modified-Stst-posi.fasta: this contains 52 testing DBP sequences extracted from PDB
(6) modified-Stst-nega.fasta: this contains 97 testing non-DBP sequences extracted from PDB
(7) README.md : this is me

In TargetDBP+, the union file of (1) and (2) is employed to tune and train the model of DBP identification, the files of (3), (4), (5), and (6) are used to testing this model.

MORE DETAILS SEE THE CORRESPONDING MANUSCRIPT.
