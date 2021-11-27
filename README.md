# Setup rust gtk

1. install rust
2. 
```console
cd C:
mkdir src && cd src

# Download https://sourceforge.net/projects/pkgconfiglite, add `C:\src\pkg-config-lite-0.28-1\bin` to  env `PATH`

git clone https://github.com/microsoft/vcpkg.git

cd vcpkg

.\bootstrap-vcpkg.bat

.\vcpkg.exe install pango:x64-windows
.\vcpkg.exe install cairo:x64-windows
.\vcpkg.exe install gtk:x64-windows
.\vcpkg.exe install gdk-pixbuf:x64-windows
.\vcpkg.exe install graphene:x64-windows
```
