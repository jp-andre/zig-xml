# zig-xml

## This is a fork

This is a quick fork of https://github.com/nektro/zig-xml to fix build for zig 0.15 and remove the tracer.

Cherry-picked changes (with fixups):
- https://github.com/hilariousppp/zig-xml/commit/e03c26f7b2cb73ca6580b5fa61ae7a9dd876705b
- https://github.com/zivoy/zig-xml/commit/7ddae38d72202bd50077243f4b89563566ca7147

Abandoned since it fails on my test file.

## Original README contents

![loc](https://sloc.xyz/github/nektro/zig-xml)
[![license](https://img.shields.io/github/license/nektro/zig-xml.svg)](https://github.com/nektro/zig-xml/blob/master/LICENSE)
[![nektro @ github sponsors](https://img.shields.io/badge/sponsors-nektro-purple?logo=github)](https://github.com/sponsors/nektro)
[![Zig](https://img.shields.io/badge/Zig-0.14-f7a41d)](https://ziglang.org/)
[![Zigmod](https://img.shields.io/badge/Zigmod-latest-f7a41d)](https://github.com/nektro/zigmod)

A pure-zig spec-compliant XML parser.

https://www.w3.org/TR/xml/

Passes all standalone tests from https://www.w3.org/XML/Test/xmlconf-20020606.htm, even more coverage coming soon.

One caveat is that this parser expects UTF-8.

```
Build Summary: 3/3 steps succeeded; 120/120 tests passed
test success
└─ run test 120 passed 5ms MaxRSS:1M
   └─ zig test Debug native success 1s MaxRSS:247M
```
