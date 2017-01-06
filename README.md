# BNFC-meta-example
A small example use of BNFC-meta

```shell
git clone git@github.com:patrikja/BNFC-meta-example.git
cd BNFC-meta-example/
stack build
stack exec Main
```

Expected output (a small While-language program after variable renaming):
```
f () {
  a = 0 ;
  c := True ;
  b = 0 ;
  while (b < 10){
    b ++ ;
    a = a * a ;
    }
  }
```
