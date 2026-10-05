# Third-Party Notices

This product includes software developed by third parties. The Vazhion
application itself is proprietary (see `EULA.txt`). The components below remain
under their own licenses.

---

## Dear ImGui

- Path: `third_party/imgui`
- License: MIT
- Copyright (c) 2014-2025 Omar Cornut

## ImPlot

- Path: `third_party/implot`
- License: MIT
- Copyright (c) 2020 Evan Pezent

## GLFW

- Path: `third_party/glfw`
- License: zlib/libpng
- Copyright (c) 2002-2006 Marcus Geelnard; (c) 2006-2019 Camilla Löwy

## libssh2

- Path: `third_party/libssh2`
- License: BSD-3-Clause
- See `third_party/libssh2/COPYING`

## SQLite

- Path: `third_party/sqlite3`
- License: Public domain (SQLite blessing)

## libyaml

- Path: `third_party/libyaml`
- License: MIT

## libwebsockets

- Path: `third_party/libwebsockets`
- License: MIT (with some BSD/Apache pieces; see upstream `LICENSE`)

## kubernetes-client/c

- Path: `third_party/kubernetes-client`
- License: Apache License 2.0

## tree-sitter and language grammars

- Path: `third_party/tree-sitter`, `third_party/tree-sitter-*`
- License: MIT (most grammars)
- `tree-sitter-hcl`: Apache License 2.0

## lsp-framework

- Path: `third_party/lsp-framework`
- License: MIT

## utfcpp

- Path: `third_party/utfcpp`
- License: Boost Software License 1.0

## stb (stb_image)

- Path: `third_party/stb`
- License: Public domain / MIT dual

## NanoSVG

- Path: `third_party/nanosvg`
- License: zlib

## md4c

- Path: `third_party/md4c`
- License: MIT
- Copyright © 2016-2026 Martin Mitáš

## OpenSSL 3.x

- Runtime DLLs: `libssl`, `libcrypto`
- License: Apache License 2.0

## curl (libcurl)

- Slim Windows build via `scripts/build_slim_curl_mingw.sh` (no libidn2 / iconv / intl / unistring / brotli / libpsl)
- TLS backend: OpenSSL (required for Kubernetes kubeconfig PEM client certificates on Windows).
  Cluster CA trust typically comes from kubeconfig via CURLOPT_CAINFO; no third-party CA
  bundle is bundled with the application.
- License: curl license (MIT/X-derived)
- See https://curl.se/docs/copyright.html

## zlib

- License: zlib

## nghttp2

- Runtime: `libnghttp2` (when linked)
- License: MIT

## MinGW-w64 / GCC runtime

- Runtime (Windows): `libstdc++-6.dll`, `libgcc_s_seh-1.dll`, `libwinpthread-1.dll`,
  `libgomp-1.dll`, `libquadmath-0.dll`
- License: GPL with GCC Runtime Library Exception (`libwinpthread`: MIT/BSD, mingw-w64 runtime)
- Redistribution with proprietary applications is permitted under the exception

## Fonts

| Font | License |
|------|---------|
| Font Awesome 6 Free Solid (`fa-solid-900.ttf`) | SIL Open Font License 1.1 |
| Noto Sans Mono / Noto Color Emoji | SIL Open Font License 1.1 |
| JetBrains Mono NL | SIL Open Font License 1.1 |
| Source Code Pro | SIL Open Font License 1.1 |
| VT323 | SIL Open Font License 1.1 |
| DejaVu Sans | Bitstream Vera / DejaVu license |

Microsoft Segoe UI Emoji is **not** redistributed. On Windows the application may load the system font from `C:\Windows\Fonts` at runtime if the user selects it.

## IconFontCppHeaders

- Path: `src/icons/IconsFontAwesome6.h` (and related)
- License: MIT (IconFontCppHeaders)

## Ned (AI agent design reference)

- Upstream: https://github.com/nealmick/ned
- License: MIT/X Consortium License
- Used as a design reference for the OpenRouter streaming client shape, chat
  agent tool-calling loop, and ghost-text autocomplete behavior in `src/ai/`.
  Remote SSH/SFTP tool implementations are original to this project.

```
MIT/X Consortium License

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
```

## nlohmann/json

- Path: `src/nlohmann_json.hpp`
- License: MIT
- Version: 3.11.3
- Copyright (c) 2013-2023 Niels Lohmann

## Apache-2.0 components

OpenSSL 3.x and kubernetes-client/c are Apache License 2.0. The license text is in `notices/Apache-2.0.txt` (also installed with the application). Retain any upstream NOTICE files from those projects when redistributing source.

## Google Test (tests only)

- Not shipped with the application
- License: BSD-3-Clause

## imgui-node-editor

- Path: `third_party/imgui-node-editor`
- License: MIT
- Copyright (c) Michał Cichoń / thedmd
- Source: https://github.com/thedmd/imgui-node-editor

## ImGuiColorTextEdit (goossens)

- Path: `third_party/imgui_texteditor` (git submodule)
- License: MIT
- Copyright (c) 2024-2026 Johan A. Goossens
- Source: https://github.com/goossens/ImGuiColorTextEdit
- Bundled Diff Template Library (`dtl.h`): BSD License (Tatsuhiko Kubo / cubicdaiya)
- Optional extras: `extras/TrieAutoComplete.*`, `extras/Notifications.h` (MIT, same project)

---

For full license texts, see the corresponding files under `third_party/` or the upstream project repositories.
