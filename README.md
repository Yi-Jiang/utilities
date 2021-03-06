# Utilities

* `bed2fasta`: Convert bed files or genomic positions to sequences
```
Language: Python3
Usage: python3 bed2fasta -option <argument>
     -i     <STRING>    a string like "chrN:start-end" or a BED file
     -r     <STRING>    can be "hg19", "hg38", or a path to reference genome [hg38]
     --bed              output BED format [FASTA]
     --upper            convert all bases to uppercase
     --mark             mark position at the end of each line
     --reverse          get reverse sequence
     --complement       get complement sequence
     -h/--help
```

---

* `t`: transpose a matrix
```
Language: AWK
```

---

* `dim`: calculate matrix dimension
```
Language: AWK
```

---

* `echohead`: print the header of a table
```
Language: AWK
```

---

* `distribution`: print the counts of data in each equal range
```
Language: AWK
Usage: cat infile | distribution stepLength
```

---

* `tonote`: write commands in history to note
```
Language: shell
Usage: tonote      # write the last command
       tonote -3   # write the 3rd last command
```

---

* `grepcol`: extract columns by header
```
Language: AWK
Usage: cat file |grepcol age,sex  # The first row will be used as header
```

