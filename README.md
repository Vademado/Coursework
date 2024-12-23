```bash
$ cd CFGGen/
$ python3 main.py -n=50000 -sv=cfg
$ cd ..

$ cd AFLplusplus/
$ make distrib
$ sudo make install

$ cd utils/afl_proxy/
$ make


$ ../../afl-fuzz -t 100000 -G 8 -i ./In/ -o ./Out/ ./afl-proxy
```
[AFLplusplus](https://github.com/AFLplusplus)

[INSTALL.md](https://github.com/AFLplusplus/AFLplusplus/blob/stable/docs/INSTALL.md)

[afl-proxy.c](https://github.com/AFLplusplus/AFLplusplus/blob/stable/utils/afl_proxy/afl-proxy.c)
