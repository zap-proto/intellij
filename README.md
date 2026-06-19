# zap-intellij

> **Docs:** [ZAP for IntelliJ](https://zap-proto.dev/docs/sdks) · part of the [ZAP Protocol](https://zap-proto.io)

ZAP schema language support for IntelliJ-based IDEs.

## About

ZAP is a fork of [Cap'n Proto](https://capnproto.org/) and stays wire- and library-compatible with it. This plugin adds editor support for ZAP schema files (`.zap`, and `.capnp` for back-compat).

### What is Cap'n Proto?
Cap’n Proto is an insanely fast data interchange format and capability-based RPC system. Think JSON, except binary. Or think Protocol Buffers, except faster. In fact, in benchmarks, Cap’n Proto is INFINITY TIMES faster than Protocol Buffers.
https://capnproto.org/

### Syntax Highlighting
![alt text](image1.png "Syntax Highlighting")
![alt text](image2.png "ZAP ID Generator")

### Generating IDs
From tools menu -> Generate ZAP ID or Ctrl+Alt+A then G

## Building

The plugin can be built using Gradle.

```
./gradlew buildPlugin
```

The plugin JAR can then be found in `build/libs/zap-intellij-VERSION.jar`.