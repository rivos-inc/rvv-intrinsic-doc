# RISC-V Vector Intrinsic Document

Working draft for the RISC-V vector specification are under [doc/](doc/), intrinsic prototypes under
[auto-generated/](auto-generated/) are generated by scripts under [rvv-intrinsic-generator/](rvv-intrinsic-generator/).

Please check out the latest intrinsics specification under
[Releases](https://github.com/riscv-non-isa/rvv-intrinsic-doc/releases).

[Clang 19](https://github.com/llvm/llvm-project/blob/llvmorg-19.1.0/llvm/docs/RISCV/RISCVVectorExtension.rst) and [GCC 14](https://github.com/gcc-mirror/gcc/tree/releases/gcc-14) supports the [v1.0](https://github.com/riscv-non-isa/rvv-intrinsic-doc/tree/v1.0.x) version.

[Clang 17](https://releases.llvm.org/17.0.1/tools/clang/docs/ReleaseNotes.html) and [GCC trunk](https://github.com/gcc-mirror/gcc/tree/master) supports the [v0.12](https://github.com/riscv-non-isa/rvv-intrinsic-doc/releases/tag/v0.12.0) version, no more incompatibility will be introduced.

[Clang 16](https://releases.llvm.org/16.0.0/tools/clang/docs/ReleaseNotes.html) and
[GCC 13](https://gcc.gnu.org/gcc-13/changes.html) supports the
[v0.11](https://github.com/riscv-non-isa/rvv-intrinsic-doc/releases/tag/v0.11.1) version, which does not have tuple type
segment load/store intrinsics, fixed-point intrinsics with rounding mode parameter, and floating-point intrinsics
with rounding mode parameter.

[The RISC-V Vector C intrinsics TG mailing list](https://lists.riscv.org/g/tech-rvv-intrinsics)

[Monthly meeting Google Doc](https://docs.google.com/document/d/19UucISxO9yuQcQ5S30g7wn2wV5D-1z0fA0GKNVOuktI/edit#)

[Meeting minutes can be found here](https://github.com/riscv-admin/rvv-intrinsics/tree/main)
