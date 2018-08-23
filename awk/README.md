# awk
pattern-directed scanning and processing language

```
awk -v a=${user} -v b=${sys} "BEGIN {print a+b}"
```

```
awk -F "|" '/Compression ratio/ {getline;getline;print $9}'
```
