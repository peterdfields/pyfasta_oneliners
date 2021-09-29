# pyfasta_oneliners

##### split larger fasta into smaller (here 100) chunks, different files
`pyfasta split -n 100 original.fasta`

##### split large fasta sequence into smaller pieces (here 60bp; see https://www.biostars.org/p/1852/)
`pyfasta split -n 1 -k 60 chr1.fa`
