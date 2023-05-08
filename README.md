# cs631
[CS631 Youtube](https://www.youtube.com/watch?v=hCqfmuG5Acc&list=PL0qfF8MrJ-jxMfirAdxDs9zIiBg2Wug0z&index=4&pp=iAQB)
[CS631 Resources](https://stevens.netmeister.org/631/)
## Week 1
Read intro(2) and intro(7)

### ctags
ctrl+]
ctrl+t 
```sh
exctags -f ~/.tags -R -I __weak_alias /usr/include/ /usr/src/lib/
echo "set tags=tags\ /home/spmzt/.tags" >> ~/.exrc
echo "set tags+=~/.tags" >> ~/.vimrc
```

### vi
For manual:
shit+k