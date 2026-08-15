# CMT-TESTS

Test cases and test results for the [CMT](https://github.com/TeomanDeniz/CMT) project.

## Directory Structure

Test files follow this path structure:

```
Module         CPU       Version               Version               Version
vvvvvv         vvvvv     vvvvvvvvv             vvvvvvvvvvvvvvv       vvvvvvvvvvv
OBJECT / NEW / Intel-x64-i5-13420H / Windows10-HomeSingle_25H2 / GCC-8.1.0_MinGW.md
         ^^^         ^^^             ^^^^^^^^^                   ^^^
         Content     Architecture    Platform                    Compiler
```

Aka: **`<MODULE>/<CONTENT/><CPU>-<ARCH>-<CPU_VER>/<PLATFORM>-<PLATFORM_VER>/<COMPILER>-<COMPILER_VER>.md`**

Where:

* **`<MODULE>`** - The CMT module being tested.
* **`<CONTENT>`** - The module content.
* **`<CPU>`** - CPU vendor or family.
* **`<ARCH>`** - Target architecture, such as `x64`.
* **`<CPU_VER>`** - Specific CPU model/version.
* **`<PLATFORM>`** - Operating system or platform.
* **`<PLATFORM_VER>`** - Platform version.
* **`<COMPILER>`** - Compiler/toolchain used for the test.
* **`<COMPILER_VER>`** - Compiler version.
