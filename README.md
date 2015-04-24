#Trying Haskell
[Book](http://book.realworldhaskell.org/)  

Some things from [haskell in 5 steps](https://wiki.haskell.org/Haskell_in_5_steps)  

`fac.sh`
```
ghci  
:load fac.hs  
fac 0  
fac 1  
fac 99  
fac 1024
```
`parallel.hs`  
```
ghc -02 --make parallel.hs -threaded -rtsopts
time ./A +RTS -N2
```
Couldn't get the parallel.hs example to work as `brew` installed Haskell doesn't seem to have `Control.Parallel`

