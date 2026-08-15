# CMT-TESTS

Test cases and test results for the [CMT](https://github.com/TeomanDeniz/CMT) project.

## Directory Structure

Test files follow this path structure:

**`<MODULE>/<CPU>-<ARCH>-<CPU_VER>/<PLATFORM>-<PLATFORM_VER>/<COMPILER>-<COMPILER_VER>.md`**

### Example

```
         CPU       Version               Version               Version
         vvvvv     vvvvvvvvv             vvvvvvvvvvvvvvv       vvvvvvvvvvv
OBJECT / Intel-x64-i5-13420H / Windows10-HomeSingle_25H2 / GCC-8.1.0_MinGW.md
^^^^^^         ^^^             ^^^^^^^^^                   ^^^
Module         Architecture    Platform                    Compiler
```

Where:

* **`<MODULE>`** - The CMT module being tested.
* **`<CPU>`** - CPU vendor or family.
* **`<ARCH>`** - Target architecture, such as `x64`.
* **`<CPU_VER>`** - Specific CPU model/version.
* **`<PLATFORM>`** - Operating system or platform.
* **`<PLATFORM_VER>`** - Platform version.
* **`<COMPILER>`** - Compiler/toolchain used for the test.
* **`<COMPILER_VER>`** - Compiler version.
