# Haskell-Experiments
Learning Haskell and trying simple experiments

## Notes

Installed Haskell from [this location.](https://www.haskell.org/platform/)

Ensure your cabal config file contains the following lines:
Make sure that the following lines are added t0 your cabal file

```
extra-prog-path: C:\Program Files\Haskell Platform\8.6.5\msys\usr\bin
extra-lib-dirs: C:\Program Files\Haskell Platform\8.6.5\mingw\lib
extra-include-dirs: C:\Program Files\Haskell Platform\8.6.5\mingw\include
```

You can verify the location by running 

```
cabal user-config init
```

and it is found out to be

```
C:\Users\jacqu_b3u79t4\AppData\Roaming\cabal
```