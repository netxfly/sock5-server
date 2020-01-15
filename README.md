## sock5 server

支持密码认证的sock5 server

### usage

```bash
hartnett at hartnettdeMacBook-Pro in /data/code/golang/src/socks5-server (master)
$ ./main
NAME:
   sock5 server - A sock5 proxy server

USAGE:
   main [global options] command [command options] [arguments...]

VERSION:
   20180226

AUTHOR(S):
   netxfly <x@xsec.io>

COMMANDS:
     proxy    start proxy server
     help, h  Shows a list of commands or help for one command

GLOBAL OPTIONS:
   --port value, -p value  port (default: 8000)
   --help, -h              show help
   --version, -v           print the version


hartnett at hartnettdeMacBook-Pro in /data/code/golang/src/socks5-server (master)
$ ./main proxy -p 8000


```