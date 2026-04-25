# Dependencies

To install **Carla** and **Morgana**, you need a working **GNU C++ compiler (G++)** in your system. This compiler is required to build native components and link generated code.

## Installing G++

### Windows

You can install G++ using MinGW-w64:

* Download from SourceForge:
  [https://sourceforge.net/projects/mingw-w64/](https://sourceforge.net/projects/mingw-w64/)

After installing:

* Make sure to add the `bin` directory (e.g. `C:\mingw-w64\bin`) to your **PATH**
* Verify installation:

```sh
g++ --version
```

---

### Linux

#### Arch Linux

```sh
sudo pacman -S gcc
```

#### Ubuntu / Debian

```sh
sudo apt update
sudo apt install g++
```

#### Fedora

```sh
sudo dnf install gcc-c++
```

---

### Verifying Installation

After installation, confirm everything is working:

```sh
g++ --version
```

You should see version information for the GNU compiler.

---

### Notes

* On Linux, installing `gcc` often includes `g++`, but it's safer to explicitly install `g++` where needed.
* Make sure your compiler is accessible globally via PATH.
* Some systems may require additional build tools (like `make` or `binutils`) depending on how Carla/Morgana are used.

---

If you want, I can also add a section for macOS or automate detection inside your installer.
