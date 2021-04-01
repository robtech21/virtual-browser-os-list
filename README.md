# virtual-browser-os-list

This is an exhaustive list of virtual machines/emulators of computers (x86, RISC, etc.) that will run in your browser.

This is still a work in progress.

I will accept pull requests for those who want to add more to this README.

# Contents:

* [Categorization](#categorization)
* [Main Section](#main-section)
  * [v86](#v86)
  * [jslinux list](#jslinux-list)
    * [jslinux](#jslinux)
    * [jslinux-deobfuscated](#jslinux-deobfuscated)
  * [Angel](#angel)
  * [jslm32](#jslm32)
  * [jor1k](#jor1k)
  * [jemul8](#jemul8)

## Categorization

A listing will look something like this:

Name
Author
Link(s)
architectures emulates
What it runs

For the first example I will use Copy's [v86](https://github.com/copy/v86):

Name: v86

Author: Copy

Link(s): [GitHub](https://github.com/copy/v86), [Website](https://copy.sh/v86)

Architecture(s): x86 (Pentium III level)

What it runs: See the [v86 README](https://github.com/copy/v86/blob/master/Readme.md) for OS compatibility or the [website](https://copy.sh/v86) for demos

## Main Section

List of emulators

### v86

Name: v86

Author: Copy

Link(s): [GitHub](https://github.com/copy/v86), [Website](https://copy.sh/v86)

Architecture(s): x86 (Pentium III level)

What it runs: See the [v86 README](https://github.com/copy/v86/blob/master/Readme.md) for OS compatibility or the [website](https://copy.sh/v86) for demos

### jslinux list

This is a list of jslinux (and jslinux-based) emulators.

#### jslinux

Name: jslinux

Author: Fabrice Bellard ([website](https://bellard.org))

Link(s): [Website with Demos](https://bellard.org/jslinux), [Technical Notes](https://bellard.org/jslinux/tech.html)

Architecture(s): x86, riscv64, riscv32

What it runs: 
 * **Alpine Linux 3.12.0**
   * Architecture: x86
   * Networking: yes
   * UI Options:
     * Terminal
     * X Window
 * **Windows 2000**
   * Architecture: x86
   * Networking: yes
    * UI Options:
      * Graphical
 * **FreeDOS**
   * Architecture: x86
   * Networking: undetermined
   * UI Options:
     * VGA Text
 * **Buildroot**
   * Archetecture: riscv64, riscv32 (riscv32 is unmaintained)
   * Networking: yes
   * UI Options:
     * Terminal
     * X Window
 * **Fedora 33**
   * Archetectures: riscv64
   * Networking: yes
   * UI options:
     * Terminal
     * X Window

riscv32 Buildroot links:

 (All riscv32 options are unmaintained according to the [technical notes](https://bellard.org/jslinux/tech.html) page) 
 * [console](https://bellard.org/jslinux/vm.html?cpu=riscv32&url=https://bellard.org/jslinux/buildroot-riscv32.cfg)
 * [x window](https://bellard.org/jslinux/vm.html?cpu=riscv32&url=https://bellard.org/jslinux/buildroot-riscv32-xwin.cfg&graphic=1)

#### jslinux-deobfuscated

Name: jslinux-deobfuscated

Author: levskaya ([GitHub](https://github.com/levskaya))

Link(s): [GitHub](https://github.com/levskaya/jslinux-deobfuscated)

Architecture(s): x86

### Angel

Name: Angel

Author: riscv ([GitHub](github.com/riscv))

Link(s): [GitHub](https://github.com/riscv/riscv-angel), [Demo](https://riscv.org/software-tools/riscv-angel/) (demo link is broken)

Architecture(s): LatticeMico32 (32-bit RISC)

### jslm32

Name: jslm32

Author: ubercomp ([GitHub](https://github.com/ubercomp),[Website](https://www.ubercomp.com))

Link(s): [GitHub](https://github.com/ubercomp/jslm32), [Demo](https://www.ubercomp.com/jslm32/src/)

Architecture(s): LatticeMico32 (32-bit RISC)

### jor1k

Name: jor1k

Author: s-macke ([GitHub](https://github.com/s-macke/))

Link(s): [GitHub](https://github.com/s-macke/jor1k), [Demo](https://s-macke.github.com/jor1k/demos/main.html)

Architecture(s): OpenRISC 1000

### jemul8

Name: jemul8

Author: asmblah ([GitHub](https://github.com/asmblah))

Link(s): [GitHub](https://github.com/asmblah/jemul8), [Demo](http://jemul8.com)

Architecture(s): x86
