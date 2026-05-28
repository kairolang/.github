# Kairo

A statically typed compiled language for systems programming, with native bidirectional C and C++ interoperability.

The Kairo Project is the steward of the Kairo language, its compiler, toolchain, and standard library.

---

## Repositories

**[kairo](https://github.com/kairolang/kairo)**: the compiler. Stage 0 (C++ bootstrap) and Stage 1 (self-hosted, in Kairo). Includes the language server, build tool (kbld), formatter (kfmt), and package manager (kpkg).

**[kairo-web](https://github.com/kairolang/kairo-web)**: source for [kairolang.org](https://www.kairolang.org). Language reference, blog, and project pages.

**[kairo-std](https://github.com/kairolang/kairo-std)**: standard library, written in Kairo. (WIP)

**[lib-helix](https://github.com/kairolang/lib-helix)**: runtime support library (legacy name, in transition).

**[kairo-lsp](https://github.com/kairolang/kairo-lsp)**: lsp server for stage0 and vscode extension

---

## Status

Stage 0 compiles `.k` files to native binaries on macOS, Linux, and Windows. Stage 1 is in active development at ~50k lines, with lexer, preprocessor, parser, AST, diagnostics, and driver working. Sema, codegen, and AMT (ownership model) are next. Working alpha targeted for end of 2026.

## Get involved

- **Documentation:** [kairolang.org/docs](https://www.kairolang.org/docs)
- **Releases:** [Latest builds](https://github.com/kairolang/kairo/releases)
- **Discussion:** [GitHub Discussions](https://github.com/kairolang/kairo/discussions)
- **Issues:** [Bug reports & design](https://github.com/kairolang/kairo/issues)

## License

Kairo is licensed under the Apache License 2.0 with the Kairo Runtime Library Exception. Copyright (C) 2026 Dhruvan Kartik.
