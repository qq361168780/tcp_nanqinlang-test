# tcp_nanqinlang

[![build](https://github.com/nanqinlang/SVG/blob/master/build%20passing.svg)](https://github.com/nanqinlang/tcp_nanqinlang-test)
[![language](https://github.com/nanqinlang/SVG/blob/master/language-c-blue.svg)](https://github.com/nanqinlang/tcp_nanqinlang-test)
[![author](https://github.com/nanqinlang/SVG/blob/master/author-nanqinlang-lightgrey.svg)](https://github.com/nanqinlang/tcp_nanqinlang-test)
[![license](https://github.com/nanqinlang/SVG/blob/master/license-GPLv3-orange.svg)](https://github.com/nanqinlang/tcp_nanqinlang-test)

`super-powered-testing branch` !

As this will, `this repo is just for testing`, please do not use it with important environment.

## script
```bash
wget https://raw.githubusercontent.com/nanqinlang/tcp_nanqinlang-test/master/tcp_nanqinlang-test.sh
bash tcp_nanqinlang-test.sh
```
ths usage of script please refer via: https://sometimesnaive.org/article/linux/bash/tcp_nanqinlang

## manual
### requirements
the bbr source file only support for `Ubuntu kernel v4.9.3-v4.12.x`

the Makefile only support for `gcc 6`, you can modify it to (eg.)gcc-4.9

### usage
this repo gives you a source file and Makefile

After you ensure you have a environment with essential requirements, you should run this followings then:
```bash
make
make install
```

If you have no a environment, you should build that.  
via: https://sometimesnaive.org/article/linux/technique/tcp_nanqinlang-manual-debian