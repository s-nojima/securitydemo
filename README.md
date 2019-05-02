# securitydemo

+ `yum install gcc`

```
./a.out AAA
./a.out $(python -c "print 'A'*200")
sudo sysctl -w kernel.randomize_va_space=0
```

Address space layout randomization (ASLR)

gdb -q a.out 

set disassembly-flavor intel
disas main


