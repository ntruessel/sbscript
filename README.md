# sbscript
A little shell script I use to create my secureboot signed efi binaries

## Dependencies
- sbsigntools
- efistub (as included in systemd and gummiboot)
- binutils (objcopy)
- sh
- coreutils (cp, echo ...)
- sudo

## Verification failures
Sometimes `sbverify` claims the kernel image is not properly signed (signature
verification fails). Instead of aborting with an error message, the script emits
a warning and continues to do its job, since on all my computers, the generated
images pass the EFI verifiaction step.

## Useful resources
- https://secure.freedesktop.org/~kay/efistub.txt
- https://github.com/systemd/systemd/tree/master/src/boot
- https://github.com/haraldh/mkrescue-uefi
- http://kroah.com/log/blog/2013/09/02/booting-a-self-signed-linux-kernel/

## License
This is free and unencumbered softwarr released into the public domain.
See [UNLICENSE](./UNLICENSE) for details.
