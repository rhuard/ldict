# ldict 
 curly-couscous
ldict - less-dict. Was supposed to be dict-less but dictl is already taken

ldict is a simple program to pipe the result from a dict command into less

## dependencies:
* less
* dict (and dictonaries of your choice)
* sudo or root privileges if you wish to run the make install. It will add ldict to your /usr/bin.

I leave the dependency instalation up to you so you can easily choose your dictonaries

## install:
```
git clone https://github.com/rhuard/ldict.git $HOME/Programs/ldict
make -f $HOME/Programs/ldict/Makefile install
```

## uninstall:
```
make -f $HOME/Programs/ldict/Makefile install
```

## manual install:
If you do not have sudo/root privileges or do not want ldict in /usr/bin you can create your own path or symlink to the `/ldict/ldict` executable
