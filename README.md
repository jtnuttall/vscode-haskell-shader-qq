[![GitHub issues](https://img.shields.io/github/issues/jtnuttall/vscode-haskell-shader-qq.svg)](https://github.com/jtnuttall/vscode-haskell-shader-qq/issues)
[![GitHub license button](https://img.shields.io/github/license/jtnuttall/vscode-haskell-shader-qq.svg)](https://github.com/jtnuttall/vscode-haskell-shader-qq/blob/master/LICENSE)

# haskell-shader-qq README

Provides GLSL syntax highlighting for shader QuasiQuotes in Haskell. Intended for use with the [vulkan](https://github.com/expipiplus1/vulkan)
package.

## Features

- Highlights GLSL and HLSL quasiquotes

![Highlighting](images/highlighting.png)

## Requirements

Visual Studio Code v1.17.0

## Known Issues

- Only supports `glsl` and `hlsl` quasiquoters: `frag`, `vert`, etc. are not supported right now.

## Release Notes

### 0.0.1

Initial release
