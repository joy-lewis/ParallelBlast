## A GPU-Based Implementation of the BLAST Algorithm

Joy de Carvalho Lucas \
Technical University of Berlin \
Chair of Compilers and Programming Languages \
Course Lecturer: Prof. Dr. Michel Steuwer \

### Execute NCBIs sequential algorithm on CPU:
$ ./blastn -query query.fasta -db db_test -num_threads 8 -outfmt 6 -out results.txt

### Results file description:
1   qseqid    Query sequence ID \
2   sseqid    Subject (database) sequence ID \
3   pident    Percentage of identical matches \
4   length    Alignment length \
5   mismatch  Number of mismatches \
6   gapopen   Number of gap openings \
7   qstart    Start of alignment in query \
8   qend      End of alignment in query \
9   sstart    Start of alignment in subject \
10  send      End of alignment in subject \
11  evalue    Expect value \
12  bitscore  Bit score \

