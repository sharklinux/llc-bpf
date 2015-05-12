# llc-bpf

llvm backend with bpf target(compile llvm bitcode to bpf bytecode),
called by shark.

## How to build this binary

The build process is very simple, just follow llvm build instruction.

## Note

Probably we will use a share library or static library linking with shark
binary, instead of separated llc-bpf binary in here.
