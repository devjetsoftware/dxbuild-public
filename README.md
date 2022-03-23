# DXBuild

DXBuild is a **free** command line tool. It makes it easier to build multi-version Delphi projects (Delphi 2007 or newer, dproj/groupproj).

## Example

```cmd
dxbuild Spring4D\Packages\DelphiXE2\Spring.Base.dproj -d DelphiXE2 -p Win32 Win64 -c Debug Release
```

## Benefits

- Compile faster with fastdcc (Delphi 2009 - 10.3)

https://www.idefixpack.de/blog/ide-tools/ide-fix-pack/

NOTE: 
- For Delphi XE2 or higher, you just need to download and extract fastdcc*.exe to `$(BDS)\bin`. 
- dxbuild will use fastdcc when possible. Use `--no-fastdcc` to disable it.

## Licensing

Copyright (c) DevJet Software.

SOFTWARE DISTRIBUTED IS DISTRIBUTED ON AN AS IS BASIS WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND EITHER EXPRESS OR IMPLIED.
