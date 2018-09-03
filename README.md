# testApp

## build instructions

From command line, run:
```bash
yarn
.\node_modules\.bin\electron-builder -w appx
makeappx unpack /p dist\testApp-1.0.0.appx /d dist\unpack
rm dist\unpack\assets\*
cp assets\* dist\unpack\assets\
makeappx pack /p dist\testApp-1.0.0.appx /d dist\unpack
```

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
