# Apache Commons Lang samples

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) — Normalize a heading and reverse a label with `StringUtils`. This is a standalone consumer with its own `Module module()` dependency.

From the repository root, run:

```sh
norm run samples/hello.norm
```

[module.norm](../commons/lang/module.norm) pins the Java artifact and defines the public API.

Expected output:

```text
Learn norm
mroN
```

API reference: [module.norm](../commons/lang/module.norm) lists the exposed `StringUtils` functions. The module's `Main.norm` remains its own adapter integration entry point.
