<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/130368411-816a637d-8ca6-460c-a21d-13c3fbdadb80.png">
  <br />
 LLVM Guide
</h1>

#### A guide covering LLVM including the applications, libraries and tools that will make you a better and more efficient LLVM development.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/130368415-4f3d02f5-12c7-4bc9-8dc8-dbaa349eb8cc.png">
  <br />
</p>


# Table of Contents

1. [LLVM Learning Resources](https://github.com/mikeroyal/LLVM-Guide#llvm-learning-resources)

2. [LLVM Tools, Libraries and Frameworks](https://github.com/mikeroyal/LLVM-Guide#llvm-tools-libraries-and-frameworks)

3. [C/C++ Development](https://github.com/mikeroyal/LLVM-Guide#cc-development)

4. [Assembly Development](https://github.com/mikeroyal/LLVM-Guide#assembly-development)


# LLVM Learning Resources
[Back to the Top](https://github.com/mikeroyal/LLVM-Guide#table-of-contents)

[LLVM](https://github.com/llvm/) is a library that has collection of modular/reusable compiler and toolchain  components (assemblers, compilers, and debuggers). With these components LLVM can be used as a compiler framework, providing a front-end(parser and lexer) and a back-end (code that converts LLVM's representation to actual machine code).

[Clang](https://clang.llvm.org/) is a language front-end and tooling infrastructure for languages in the C language family (C, C++, Objective C/C++, OpenCL, CUDA, and RenderScript) for the LLVM project.

[LLVM Project GitHub](https://github.com/llvm/llvm-project//)

[LLVM Documentation](https://llvm.org/docs/index.html)

[LLVM Discussion Forum](https://llvm.discourse.group/)

[LLVM | Apple Developer Forums](https://developer.apple.com/forums/tags/llvm/)

[Contributing to LLVM](https://llvm.org/docs/Contributing.html)

[Getting Started with LLVM](https://llvm.org/docs/GettingStartedTutorials.html)

[Getting Started with Clang](https://clang.llvm.org/get_started.html)

[How To Setup Clang Tooling For LLVM](https://clang.llvm.org/docs/HowToSetupToolingForLLVM.html)

[Using Clang-Tidy in Visual Studio](https://docs.microsoft.com/en-us/cpp/code-quality/clang-tidy)

[Configure VS Code for Clang/LLVM on macOS](https://code.visualstudio.com/docs/cpp/config-clang-mac)

# LLVM Tools, Libraries and Frameworks
[Back to the Top](https://github.com/mikeroyal/LLVM-Guide#table-of-contents)

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Code Server](https://coder.com/) is a tool that allows you to run [VS Code](https://code.visualstudio.com/) on any machine anywhere and access it in the browser.

[Clang-Format](https://marketplace.visualstudio.com/items?itemName=xaver.clang-format) is a tool to format C/C++/Java/JavaScript/Objective-C/Objective-C++/Protobuf code.

[Clang-Tidy](https://clang.llvm.org/extra/clang-tidy/) is a clang-based C++ "linter" tool. Its purpose is to provide an extensible framework for diagnosing and fixing typical programming errors, like style violations, interface misuse, or bugs that can be deduced via static analysis. clang-tidy is modular and provides a convenient interface for writing new checks.

[Clangd](https://marketplace.visualstudio.com/items?itemName=llvm-vs-code-extensions.vscode-clangd) is a Visual Studio Code extensio that provides C/C++ language IDE features for VS Code using [clangd](https://clangd.llvm.org/).

[LLD](https://lld.llvm.org/) is a linker from the LLVM project that is a drop-in replacement for system linkers and runs much faster than them. It also provides features that are useful for toolchain developers. The linker supports ELF (Unix), PE/COFF (Windows), Mach-O (macOS) and WebAssembly in descending order.

[TinyGo](https://tinygo.org/) is a Go compiler(based on LLVM) intended for use in small places such as microcontrollers, WebAssembly (Wasm), and command-line tools.

[FileCheck](https://llvm.org/docs/CommandGuide/FileCheck.html) is a flexible pattern matching file verifier.

[tblgen](https://llvm.org/docs/CommandGuide/tblgen.html) is a description to C++ Code.

[clang-tblgen](https://llvm.org/docs/CommandGuide/clang-tblgen.html) is a description to C++ Code for Clang.

[lldb-tblgen](https://llvm.org/docs/CommandGuide/lldb-tblgen.html) is a description to C++ Code for LLDB.

[llvm-tblgen](https://llvm.org/docs/CommandGuide/llvm-tblgen.html) is a target Description to C++ Code for LLVM.

[mlir-tblgen](https://llvm.org/docs/CommandGuide/mlir-tblgen.html) is a description to C++ Code for MLIR.

[lit](https://llvm.org/docs/CommandGuide/lit.html) is a LLVM Integrated Tester.

[llvm-exegesis](https://llvm.org/docs/CommandGuide/llvm-exegesis.html) is a LLVM Machine Instruction Benchmark.

[llvm-locstats](https://llvm.org/docs/CommandGuide/llvm-locstats.html) is a calculate statistics on DWARF debug location.

[llvm-pdbutil](https://llvm.org/docs/CommandGuide/llvm-pdbutil.html) is a PDB File forensics and diagnostics.

[llvm-profgen](https://llvm.org/docs/CommandGuide/llvm-profgen.html) is a LLVM SPGO profile generation tool

[bugpoint](https://llvm.org/docs/CommandGuide/bugpoint.html) is a automatic test case reduction tool.

[llvm-extract](https://llvm.org/docs/CommandGuide/llvm-extract.html) is a extract a function from an LLVM module.

[llvm-bcanalyzer](https://llvm.org/docs/CommandGuide/llvm-bcanalyzer.html) is a LLVM bitcode analyzer.

[llvm-addr2line](https://llvm.org/docs/CommandGuide/llvm-addr2line.html) is a drop-in replacement for addr2line.

[llvm-ar](https://llvm.org/docs/CommandGuide/llvm-ar.html) is a  LLVM archiver.

[llvm-cxxfilt](https://llvm.org/docs/CommandGuide/llvm-cxxfilt.html) is a  LLVM symbol name demangler.

[llvm-install-name-tool](https://llvm.org/docs/CommandGuide/llvm-install-name-tool.html) is a LLVM tool for manipulating install-names and rpaths.

[llvm-nm](https://llvm.org/docs/CommandGuide/llvm-nm.html) is a list LLVM bitcode and object file’s symbol table.

[llvm-objcopy](https://llvm.org/docs/CommandGuide/llvm-objcopy.html) is a  object copying and editing tool.

[llvm-objdump](https://llvm.org/docs/CommandGuide/llvm-objdump.html) is a  LLVM’s object file dumper.

[llvm-ranlib](https://llvm.org/docs/CommandGuide/llvm-ranlib.html) is a  generates an archive index.

[llvm-readelf](https://llvm.org/docs/CommandGuide/llvm-readelf.html) is a  GNU-style LLVM Object Reader.

[llvm-size](https://llvm.org/docs/CommandGuide/llvm-size.html) is a  print size information.

[llvm-strings](https://llvm.org/docs/CommandGuide/llvm-strings.html) is a  print strings.

[llvm-strip](https://llvm.org/docs/CommandGuide/llvm-strip.html) is a  object stripping tool.

# C/C++ Development
[Back to the Top](https://github.com/mikeroyal/LLVM-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115297894-961e0d80-a111-11eb-81c3-e2bd2ac9a7cd.png">
  <br />
</p>

## C/C++ Learning Resources

[C++](https://www.cplusplus.com/doc/tutorial/) is a cross-platform language that can be used to build high-performance applications developed by Bjarne Stroustrup, as an extension to the C language.

[C](https://www.iso.org/standard/74528.html) is a general-purpose, high-level language that was originally developed by Dennis M. Ritchie to develop the UNIX operating system at Bell Labs. It supports structured programming, lexical variable scope, and recursion, with a static type system. C also provides constructs that map efficiently to typical machine instructions, which makes it one was of the most widely used programming languages today.

[Embedded C](https://en.wikipedia.org/wiki/Embedded_C) is a set of language extensions for the C programming language by the [C Standards Committee](https://isocpp.org/std/the-committee) to address issues that exist between C extensions for different [embedded systems](https://en.wikipedia.org/wiki/Embedded_system). The extensions hep enhance microprocessor features such as fixed-point arithmetic, multiple distinct memory banks, and basic I/O operations. This makes Embedded C the most popular embedded software language in the world.

[C & C++ Developer Tools from JetBrains](https://www.jetbrains.com/cpp/)

[Open source C++ libraries on cppreference.com](https://en.cppreference.com/w/cpp/links/libs)

[C++ Graphics libraries](https://cpp.libhunt.com/libs/graphics)

[C++ Libraries in MATLAB](https://www.mathworks.com/help/matlab/call-cpp-library-functions.html)

[C++ Tools and Libraries Articles](https://www.cplusplus.com/articles/tools/)

[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

[Introduction C++ Education course on Google Developers](https://developers.google.com/edu/c++/)

[C++ style guide for Fuchsia](https://fuchsia.dev/fuchsia-src/development/languages/c-cpp/cpp-style)

[C and C++ Coding Style Guide by OpenTitan](https://docs.opentitan.org/doc/rm/c_cpp_coding_style/)

[Chromium C++ Style Guide](https://chromium.googlesource.com/chromium/src/+/master/styleguide/c++/c++.md)

[C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md)

[C++ Style Guide for ROS](http://wiki.ros.org/CppStyleGuide)

[Learn C++](https://www.learncpp.com/)

[Learn C : An Interactive C Tutorial](https://www.learn-c.org/)

[C++ Institute](https://cppinstitute.org/free-c-and-c-courses)

[C++ Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/c-plus-plus)

[C++ Tutorials on W3Schools](https://www.w3schools.com/cpp/default.asp)

[Learn C Programming Online Courses on edX](https://www.edx.org/learn/c-programming)

[Learn C++ with Online Courses on edX](https://www.edx.org/learn/c-plus-plus)

[Learn C++ on Codecademy](https://www.codecademy.com/learn/learn-c-plus-plus)

[Coding for Everyone: C and C++ course on Coursera](https://www.coursera.org/specializations/coding-for-everyone)

[C++ For C Programmers on Coursera](https://www.coursera.org/learn/c-plus-plus-a)

[Top C Courses on Coursera](https://www.coursera.org/courses?query=c%20programming)

[C++ Online Courses on Udemy](https://www.udemy.com/topic/c-plus-plus/)

[Top C Courses on Udemy](https://www.udemy.com/topic/c-programming/)

[Basics of Embedded C Programming for Beginners on Udemy](https://www.udemy.com/course/embedded-c-programming-for-embedded-systems/)

[C++ For Programmers Course on Udacity](https://www.udacity.com/course/c-for-programmers--ud210)

[C++ Fundamentals Course on Pluralsight](https://www.pluralsight.com/courses/learn-program-cplusplus)

[Introduction to C++ on MIT Free Online Course Materials](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-096-introduction-to-c-january-iap-2011/)

[Introduction to C++ for Programmers | Harvard ](https://online-learning.harvard.edu/course/introduction-c-programmers)

[Online C Courses | Harvard University](https://online-learning.harvard.edu/subject/c)


## C/C++ Tools and Frameworks

[AWS SDK for C++](https://aws.amazon.com/sdk-for-cpp/)

[Azure SDK for C++](https://github.com/Azure/azure-sdk-for-cpp)

[Azure SDK for C](https://github.com/Azure/azure-sdk-for-c)

[C++ Client Libraries for Google Cloud Services](https://github.com/googleapis/google-cloud-cpp)

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Vcpkg](https://github.com/microsoft/vcpkg) is a C++ Library Manager for Windows, Linux, and MacOS.

[ReSharper C++](https://www.jetbrains.com/resharper-cpp/features/) is a Visual Studio Extension for C++ developers developed by JetBrains.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages. All code inspections are run on the fly.

[CLion](https://www.jetbrains.com/clion/features/) is a cross-platform IDE for C and C++ developers developed by JetBrains.

[Code::Blocks](https://www.codeblocks.org/) is a free C/C++ and Fortran IDE built to meet the most demanding needs of its users. It is designed to be very extensible and fully configurable. Built around a plugin framework, Code::Blocks can be extended with plugins.

[CppSharp](https://github.com/mono/CppSharp) is a tool and set of libraries which facilitates the usage of native C/C++ code with the .NET ecosystem. It consumes C/C++ header and library files and generates the necessary glue code to surface the native API as a managed API. Such an API can be used to consume an existing native library in your managed code or add managed scripting support to a native codebase.

[Conan](https://conan.io/) is an Open Source Package Manager for C++ development and dependency management into the 21st century and on par with the other development ecosystems.

[High Performance Computing (HPC) SDK](https://developer.nvidia.com/hpc) is a comprehensive toolbox for GPU accelerating HPC modeling and simulation applications. It includes the C, C++, and Fortran compilers, libraries, and analysis tools necessary for developing HPC applications on the NVIDIA platform.

[Thrust](https://github.com/NVIDIA/thrust) is a C++ parallel programming library which resembles the C++ Standard Library. Thrust's high-level interface greatly enhances programmer productivity while enabling performance portability between GPUs and multicore CPUs. Interoperability with established technologies such as CUDA, TBB, and OpenMP integrates with existing software.

[Boost](https://www.boost.org/) is an educational opportunity focused on cutting-edge C++. Boost has been a participant in the annual Google Summer of Code since 2007, in which students develop their skills by working on Boost Library development.

[Automake](https://www.gnu.org/software/automake/) is a tool for automatically generating Makefile.in files compliant with the GNU Coding Standards. Automake requires the use of GNU Autoconf.

[Cmake](https://cmake.org/) is an open-source, cross-platform family of tools designed to build, test and package software. CMake is used to control the software compilation process using simple platform and compiler independent configuration files, and generate native makefiles and workspaces that can be used in the compiler environment of your choice.

[GDB](http://www.gnu.org/software/gdb/) is a debugger, that allows you to see what is going on `inside' another program while it executes or what another program was doing at the moment it crashed.

[GCC](https://gcc.gnu.org/) is a compiler Collection that includes front ends for C, C++, Objective-C, Fortran, Ada, Go, and D, as well as libraries for these languages.

[GSL](https://www.gnu.org/software/gsl/) is a numerical library for C and C++ programmers. It is free software under the GNU General Public License. The library provides a wide range of mathematical routines such as random number generators, special functions and least-squares fitting. There are over 1000 functions in total with an extensive test suite.

[OpenGL Extension Wrangler Library (GLEW)](https://www.opengl.org/sdk/libs/GLEW/) is a cross-platform open-source C/C++ extension loading library. GLEW provides efficient run-time mechanisms for determining which OpenGL extensions are supported on the target platform.

[Libtool](https://www.gnu.org/software/libtool/) is a generic library support script that hides the complexity of using shared libraries behind a consistent, portable interface. To use Libtool, add the new generic library building commands to your Makefile, Makefile.in, or Makefile.am.

[Maven](https://maven.apache.org/) is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

[TAU (Tuning And Analysis Utilities)](http://www.cs.uoregon.edu/research/tau/home.php) is capable of gathering performance information through instrumentation of functions, methods, basic blocks, and statements as well as event-based sampling. All C++ language features are supported including templates and namespaces.

[Clang](https://clang.llvm.org/) is a production quality C, Objective-C, C++ and Objective-C++ compiler when targeting X86-32, X86-64, and ARM (other targets may have caveats, but are usually easy to fix). Clang is used in production to build performance-critical software like Google Chrome or Firefox.

[OpenCV](https://opencv.org/) is a highly optimized library with focus on real-time applications. Cross-Platform C++, Python and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Libcu++](https://nvidia.github.io/libcudacxx) is the NVIDIA C++ Standard Library for your entire system. It provides a heterogeneous implementation of the C++ Standard Library that can be used in and between CPU and GPU code.

[ANTLR (ANother Tool for Language Recognition)](https://www.antlr.org/) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build parse trees and also generates a listener interface that makes it easy to respond to the recognition of phrases of interest.

[Oat++](https://oatpp.io/) is a light and powerful C++ web framework for highly scalable and resource-efficient web application. It's zero-dependency and easy-portable.

[JavaCPP](https://github.com/bytedeco/javacpp) is a program that provides efficient access to native C++ inside Java, not unlike the way some C/C++ compilers interact with assembly language.

[Cython](https://cython.org/) is a language that makes writing C extensions for Python as easy as Python itself. Cython is based on Pyrex, but supports more cutting edge functionality and optimizations such as calling C functions and declaring C types on variables and class attributes.

[Spdlog](https://github.com/gabime/spdlog) is a very fast, header-only/compiled, C++ logging library.

[Infer](https://fbinfer.com/) is a static analysis tool for Java, C++, Objective-C, and C. Infer is written in [OCaml](https://ocaml.org/).

# Assembly Development
[Back to the Top](https://github.com/mikeroyal/LLVM-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/101415607-18154480-389d-11eb-80e8-17a5c57e480f.png">
  <br />
</p>

## Assembly Learning Resources

[Assembly](https://en.wikipedia.org/wiki/Assembly_language) is a low-level programming language. It uses mnemonic codes and labels to represent machine-level code with each instruction corresponding to just one machine operation.

[RISC-V Foundation](https://riscv.org/) is a non-profit corporation controlled by its 500 members(NVIDIA, Google, Samsung, Raspberry Pi, SiFive, Canonical, and Western Digital) to drive forward the adoption and implementation of the free and open RISC-V instruction set architecture (ISA).

[Intel® 64 and IA-32 Architectures Software Developer’s Manual](https://software.intel.com/content/www/us/en/develop/articles/intel-sdm.html)

[Introduction to x64 Assembly from Intel](https://software.intel.com/content/www/us/en/develop/articles/introduction-to-x64-assembly.html)

[x86 Assembly Language Reference Manual for Open Solaris](https://docs.oracle.com/cd/E19120-01/open.solaris/817-5477/index.html)

[AMD64 Architecture Programmer’s Manual Volume 1-5](https://www.amd.com/system/files/TechDocs/40332.pdf)

[AMD GPU ISA documentation](https://gpuopen.com/documentation/amd-isa-documentation/)

[AMD Developer Guides, Manuals, and ISA Documents](https://developer.amd.com/resources/developer-guides-manuals/)

[Assembler language from IBM](https://www.ibm.com/support/knowledgecenter/en/SSLTBW_2.1.0/com.ibm.zos.v2r1.asma400/asmr102112.htm)

[The Assembler language on z/OS from IBM](https://www.ibm.com/support/knowledgecenter/zosbasics/com.ibm.zos.zappldev/zappldev_25.htm)

[MIPS Architecture & Technology from Wave Computing](https://wavecomp.ai/mips-technology/)

[Assemblies in .NET](https://docs.microsoft.com/en-us/dotnet/standard/assembly/)

[Microsoft Macro Assembler reference](https://docs.microsoft.com/en-us/cpp/assembler/masm/microsoft-macro-assembler-reference)

[Compiler Intrinsics and Assembly Language from Microsoft](https://docs.microsoft.com/en-us/cpp/intrinsics/compiler-intrinsics-and-assembly-language)

[x86 and amd64 instruction Reference](https://www.felixcloutier.com/x86/)

[Intro to x86 Assembly Language Programming](https://cs.lmu.edu/~ray/notes/x86assembly/)

[Learn Assembly Programming courses on Udemy](https://www.udemy.com/topic/assembly-language/)

[Assembly Languages and Assemblers courses on Coursera](https://www.coursera.org/lecture/build-a-computer/unit-6-1-assembly-languages-and-assemblers-l4EGm)

[Intro to Assembly Language from MIT](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/index.htm)

## Assembly Tools & Architectures

[Arm Instruction Emulator (ArmIE)](https://developer.arm.com/tools-and-software/server-and-hpc/compile/arm-instruction-emulator/resources/tutorials) is a tool that emulates Scalable Vector Extension (SVE) and SVE2 instructions on AArch64/ARM64 platforms.

[FASM (flat assembler)](https://flatassembler.net/) is an assembler for x86 processors that supports Intel-based assembly language on the IA-32 and x86-64 computer architectures.

[Microsoft Assembler (MASM) for x64](https://docs.microsoft.com/en-us/cpp/assembler/masm/masm-for-x64-ml64-exe) is Microsoft's assembler that accepts x64 assembler language.

[MASM/TASM](https://github.com/xsro/masm-tasm) is a VSCode extension that offers a way to run and debug DOS(80x86) assembly TASM/MASM through DOSBox and msdos-player.

[NASM](https://nasm.us/) is an asssembler/disassembler for the x86 CPU architecture portable to nearly every modern platform, and with code generation for many platforms old and new.

[GAS](https://www.gnu.org/software/binutils/) is the assembler used by the GNU Project for the default back-end of GCC. It is used to assemble the GNU operating system and the Linux kernel.

[MIPS](https://en.wikipedia.org/wiki/MIPS_Technologies) is a reduced instruction set computer (RISC) instruction set architecture (ISA) developed by [MIPS Technologies, Inc.](https://www.mips.com/). In June 2018 [MIPS was Acquired by AI Startup Wave Computing](https://www.top500.org/news/mips-acquired-by-ai-startup-wave-computing/).

[LLVM](https://github.com/llvm/) is a library that has collection of modular/reusable compiler and toolchain  components (assemblers, compilers, debuggers, etc.). With these components LLVM can be used as a compiler framework, providing a front-end(parser and lexer) and a back-end (code that converts LLVM's representation to actual machine code).

[TinyGo](https://tinygo.org/) is a Go compiler(based on LLVM) intended for use in small places such as microcontrollers, WebAssembly (Wasm), and command-line tools.

[Tock](https://www.tockos.org/) is an embedded operating system designed for running multiple concurrent, mutually distrustful applications on Cortex-M and RISC-V based embedded platforms. Tock's design centers around protection, both from potentially malicious applications and from device drivers.

[PlatformIO](https://platformio.org/) is a professional collaborative platform for embedded development with no vendor lock-in. It provides support for multiplatforms and frameworks such as IoT, Arduino, CMSIS, ESP-IDF, FreeRTOS, libOpenCM3, mbed OS, Pulp OS, SPL, STM32Cube, Zephyr RTOS, ARM, AVR, Espressif (ESP8266/ESP32), FPGA, MCS-51 (8051), MSP430, Nordic (nRF51/nRF52), NXP i.MX RT, PIC32, RISC-V.

[PlatformIO for VSCode](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide) is a plugin that provides support for the PlatformIO IDE on VSCode.

[Keystone](https://github.com/keystone-engine/keystone) is a lightweight multi-platform, multi-architecture(Arm, Arm64, Hexagon, Mips, PowerPC, Sparc, SystemZ & X86) assembler framework.

[Unicorn](https://github.com/unicorn-engine/unicorn) is a lightweight, multi-platform, multi-architecture CPU emulator framework(ARM, AArch64, M68K, Mips, Sparc, X86) based on [QEMU](https://www.qemu.org/).


## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/LLVM-Guide/pulls).


## License
[Back to the Top](https://github.com/mikeroyal/LLVM-Guide#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).
