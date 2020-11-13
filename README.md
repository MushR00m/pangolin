# pangolin: linux elf injector
## intro
Based on project [mandibule](https://github.com/ixty/mandibule), separate shellcode from injector.
## installation
```shell
mkdir build
cd build
cmake ..
make
```
## usage
```shell
usage: ./pangolin --file=string [options] ...
options:
  -p, --pid     pid (int [=0])
  -f, --file    file (string)
  -a, --arg     arg (string [=])
  -e, --env     env (string [=])
  -b, --base    base address (string [=])
  -?, --help    print this message
```
