
# bios-boot

The Legacy BIOS bootloader from Mac OS X Tiger 10.4.8. Might plan on rewriting it so that it compiles on the latest macOS release.

## Building

The only tested environment was Mac OS X 10.4.11 with the Xcode Tools 2.4.1 running inside a QEMU virtual machine. You need at least 4 GB of RAM. Attempting to build with 2 GB of RAM only results in a Segmentation fault error.

Build bootloader

```bash
  make all
```

## License

[APPLE PUBLIC SOURCE LICENSE][def]

## Acknowledgements

 - [Apple](https://github.com/apple-oss-distributions) for the XNU kernel source code.



[def]: APPLE_LICENSE