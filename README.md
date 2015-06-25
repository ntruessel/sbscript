# sbscript
A little shell script I use to create my secureboot signed efi binaries

## Dependencies
- sbsigntools
- efistub (as included in systemd and gummiboot)
- binutils (objcopy)
- sh
- coreutils (cp, echo ...)
- sudo

## Useful resources
- https://secure.freedesktop.org/~kay/efistub.txt
- https://github.com/systemd/systemd/tree/master/src/boot
- https://github.com/haraldh/mkrescue-uefi
- http://kroah.com/log/blog/2013/09/02/booting-a-self-signed-linux-kernel/

## License
This is free and unencumbered software released into the public domain. See [UNLICENSE](./UNLICENSE) for details.
