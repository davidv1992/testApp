# testApp

## build instructions

From command line, run:
```bash
yarn
.\node_modules\.bin\electron-builder -w appx
makeappx unpack /p dist\test*.appx /d dist\unpack
rm dist\unpack\Assets\*
cp assets\* dist\unpack\Assets\*
makeappx pack /p dist\test*.appx /d dist\unpack
```

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
