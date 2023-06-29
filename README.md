# mkos
A simple OS for fun

## Compile code

```bash
$ nasm -f bin FILE_NAME.asm -o FILE_NAME.bin
```

## Execute with `qemu`

```bash
$ qemu-system-x86_64 --nographic FILE_NAME.bin
```
