# asm progs

## Compile and run
```sh
nasm -f elf main.asm && ld -m elf_i386 -s -o main main.o && ./main
```