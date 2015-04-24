# hello-world-64bit-macosx
Simple hello world using 64 bit assembly to Mac OS X

## How to build
    as hello_asm.s -o hello_asm.o
    ld hello_asm.o -e _main -lc -o hello_asm
    
## About
Based on this blog post <http://www.idryman.org/blog/2014/12/02/writing-64-bit-assembly-on-mac-os-x/>

To create a Linux assembly program you can use <http://www.jyotirmoy.net/posts/2015-04-22-assembly-hello-world.html>