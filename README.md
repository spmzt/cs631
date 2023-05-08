# cs631
[CS631 Youtube](https://www.youtube.com/watch?v=QnL4eYpb5Iw&list=PL0qfF8MrJ-jxMfirAdxDs9zIiBg2Wug0z&index=7&pp=iAQB)
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

## Week 2
### Exercise
- What happens if you run `ulimit -n 0` Why?
- If, as a root, you set `ulimit -n unlimited`, what number will be used? why?
- What, If anything, does any of this have to do with `_POSIX_OPEN_MAX`?

### sysconf(3)
check sysconf(3), getdtablesize(2)

### getrlimit(2)
check RLIMIT

### ulimit
Per-Process number of open file limitation:
```sh
ulimit -n
```