---
title: lldb
platform: android
source: https://lldb.llvm.org/
host: [windows, linux, macOS]
---

## Overview

lldb is the LLVM debugger. On Android, you can use it to debug native code in apps and attach to processes for native-layer analysis.

## Capabilities and Use Cases

- Debug native libraries (JNI) and system calls.
- Attach to running processes to inspect memory and registers.
- Set breakpoints and step through native code paths.

## Installation

Use the lldb version bundled with Android Studio or the Android NDK. Refer to the official Android Studio and NDK debugging documentation for setup and host-specific steps.

## Usage

Use lldb to attach to a running process or launch the app under the debugger. Refer to the official Android debugging guides for the required device-side components and commands.

## Caveats and Limitations

- Requires a device setup that supports native debugging.
- Apps can detect debugging or root and change behavior.

## References

- https://lldb.llvm.org/
- https://developer.android.com/studio/debug
