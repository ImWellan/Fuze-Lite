# Fuze Player V1.0.0

Fuze Player by ImWeLLaN is a self-contained Windows media player built around
libmpv. It is designed first for reliable playback and a configurable Fuze
interface.

Project: https://github.com/ImWellan/Fuze-Player  
Issues and feature requests: https://github.com/ImWellan/Fuze-Player/issues

## Start

Open `Fuze.exe`. The release is self-contained and uses the bundled native
`libmpv-2.dll` for playback and decoding.

## Included playback features

- open files, folders and drives;
- maintain a media queue, playback history and M3U/M3U8 playlists;
- select audio and subtitle tracks and navigate chapters;
- configure the bottom bar, volume display, shortcuts and interface behavior;
- use mouse, wheel and keyboard controls for playback, seeking and speed;
- show media and track information and save screenshots;
- use full-screen playback on the selected display while preserving window state.

Fuze is a playback application first. Future additions such as simple video
trimming, richer playback tracking and other useful player features must not
interfere with playback and are not intended to turn Fuze into a recording or
conversion application.

## Native playback provenance

The bundled DLL was produced by the native Windows build on 2026-08-31:

- mpv/libmpv commit `2ee0b2a04b60d9a76ff2be053ba149f935c57855`;
- FFmpeg commit `818cecc6e1afab932cf4d40ef0d7b8cd40311a17`;
- target `x86_64-w64-mingw32`;
- `libmpv-2.dll` SHA-256:
  `F709C7CA8B183BEC76B8158BF0C45C53018C63366750729352612F228FF7BDEA`.

The matching FFmpeg configure report states `License: GPL version 3 or later`.
The exact source trees, dependency inventory and build records are in the
companion `Fuze Player Code V1.0.0` package.

## Source and notices

Keep this runtime package with the companion Code package, or publish that
package at a stable public URL, whenever distributing `Fuze.exe`. It contains
the corresponding Fuze, mpv, FFmpeg and dependency sources, build patches and
license notices. The complete license texts and third-party notices are
provided in that companion Code package. Download it from:
https://github.com/ImWellan/Fuze-Player/releases/latest

## License and copyright

Fuze Player source code and project documentation are copyright (c) 2026
ImWeLLaN and are released under the GNU General Public License version 2 or
any later version. See `LICENSE.txt` and `COPYING.txt` in the companion Code
package.

The native libmpv DLL and all other third-party components keep their own
copyright and license terms. The effective native FFmpeg build is GPLv3-or-
later. See `THIRD-PARTY-NOTICES.txt` and the `Licences Open` folder in the
companion Code package.
