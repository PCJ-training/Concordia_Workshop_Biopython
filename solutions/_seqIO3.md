using the `.parse()` approach:

```{.python}
SeqIO.write(SeqIO.parse("data/patato_pep.fasta","fasta"), "testOut.fa",  "fasta")
os.system("grep '>' testOut.fa")
```

> >PGSC0003DMP400067339 PGSC0003DMT400095664 Protein   
> >PGSC0003DMP400027454 PGSC0003DMT400040463 Protein   
> >PGSC0003DMP400020381 PGSC0003DMT400029984 Protein   
> >PGSC0003DMP400022612 PGSC0003DMT400033236 Protein   
> >PGSC0003DMP400040011 PGSC0003DMT400059441 Protein   
> >PGSC0003DMP400032361 PGSC0003DMT400047787 Protein   
> >PGSC0003DMP400030628 PGSC0003DMT400045206 Protein   
> >PGSC0003DMP400028584 PGSC0003DMT400042166 Protein   
> >PGSC0003DMP400060824 PGSC0003DMT400089149 Protein   
> >PGSC0003DMP400037883 PGSC0003DMT400056292 Protein


