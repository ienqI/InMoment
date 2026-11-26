# Third-party licenses and source downloads

InMoment 1.0.0 includes separately licensed components. This installation keeps the [third-party notices](THIRD_PARTY_NOTICES.md), the [source and replacement notes](THIRD_PARTY_SOURCE_OFFER.md), the Electron and Chromium notices, and the original OCR runtime and model license files. The matching 0.14.31 companion archives retain their filenames because the dependency versions are unchanged.

The [InMoment download page](https://ienqi.github.io/InMoment/#release) lists the installer checksum and these companion files under the version information section.

| Download | Contents |
| --- | --- |
| `InMoment-0.14.31-third-party-notices.zip` | License texts, copyright notices, dependency inventory and source instructions |
| `InMoment-0.14.31-ocr-corresponding-source.zip` | Official OpenCV FFmpeg plug-in source set, complete pinned OpenCV tree, build recipes and the OpenH264 header supplement |
| `InMoment-0.14.31-ocr-geos-source.zip` | GEOS 3.14.1, the Shapely wheel's Windows build recipes and original license notices |
| `InMoment-0.14.31-ocr-openblas-source.zip` | Pinned OpenBLAS source, the Windows build recipe and patches, original notices, and the available toolchain records |
| `InMoment-0.14.31-electron-ffmpeg-source.zip` | Chromium FFmpeg tree, Electron patches and Windows x64 build configuration |
| `InMoment-third-party-sources.zip` | sharp/libvips source collections for the current app and earlier builds |
| `InMoment-0.14.31-canvas-source.zip` | PDF native Canvas component source and license information |
| `InMoment-0.14.31-liberation-font-source.zip` | Liberation Sans 1.07.4 editable sources, build scripts and font license used by PDF.js 6.5.438 |
| `InMoment-Setup-1.0.0-x64.exe.sha256` | SHA-256 checksum of the current installer |

The app ZIP and installer contain the license texts and point to the same companion source files. Retain the corresponding source downloads wherever the matching binaries are offered, including mirrors. The license terms of each third-party component apply; InMoment does not restrict library replacement or reverse engineering for debugging modifications that those licenses allow.

The standalone `ffmpeg.exe` and `ffprobe.exe` tools for GPT/DeepSeek MP4 attachments are supplied separately by the user. They are distinct from the bundled OCR and Chromium FFmpeg libraries.
