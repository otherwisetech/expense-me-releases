# Third-party notices

expense me (© Otherwise Technologies LLC, proprietary) includes the open-source components listed
below. Each one remains under its own licence; nothing here changes those licences or grants
rights to expense me itself (see [LICENSE](LICENSE)). Each component's copyright notice and full
licence text are in its repository, linked in the table. The standard texts of the MIT and
Apache-2.0 licences, which cover most components, are reproduced at the end; the texts of the
other licences are at https://spdx.org/licenses/.

Este archivo lista los componentes de código abierto incluidos en expense me y sus licencias.

List generated from the dependency graph of the expense me 0.3.17 build for macOS (Apple silicon):
libraries compiled into the app only (build-time tools and procedural macros are not distributed).

## Fonts

| Font | Licence | Source |
|---|---|---|
| Inter (Regular, Medium, SemiBold) | OFL-1.1 (SIL Open Font License 1.1) | https://github.com/rsms/inter |

## Note on two Zed crates

`ztracing` and `zlog` (from the Zed editor's repository, a dependency of the GPUI UI framework)
declare GPL-3.0-or-later. In this build `ztracing` is compiled without its tracing feature, so it
contributes only empty no-op stubs, and `zlog` contributes no code to the binary (it is only used
when tracing is enabled). They are listed for completeness.

## Licences used

| Licence (SPDX) | Components |
|---|---|
| MIT OR Apache-2.0 | 268 |
| MIT | 87 |
| Apache-2.0 OR MIT | 75 |
| Apache-2.0 | 22 |
| Unicode-3.0 | 15 |
| Zlib OR Apache-2.0 OR MIT | 14 |
| BSD-3-Clause | 9 |
| Unlicense OR MIT | 8 |
| MIT OR Apache-2.0 OR Zlib | 6 |
| Zlib | 4 |
| BSD-3-Clause OR Apache-2.0 | 3 |
| (MIT OR Apache-2.0) AND Unicode-3.0 | 2 |
| Apache-2.0 WITH LLVM-exception OR Apache-2.0 OR MIT | 2 |
| CC0-1.0 | 2 |
| GPL-3.0-or-later | 2 |
| ISC | 2 |
| (Apache-2.0 OR MIT) AND BSD-3-Clause | 1 |
| 0BSD | 1 |
| 0BSD OR MIT OR Apache-2.0 | 1 |
| Apache-2.0 AND ISC | 1 |
| Apache-2.0 OR BSL-1.0 | 1 |
| Apache-2.0 OR ISC OR MIT | 1 |
| BSD-2-Clause | 1 |
| BSD-2-Clause OR Apache-2.0 OR MIT | 1 |
| BSD-2-Clause OR MIT OR Apache-2.0 | 1 |
| BSD-3-Clause AND MIT | 1 |
| BSD-3-Clause OR MIT | 1 |
| CC0-1.0 OR MIT-0 OR Apache-2.0 | 1 |
| CDLA-Permissive-2.0 | 1 |
| MIT OR BSD-3-Clause | 1 |
| MIT OR Zlib OR Apache-2.0 | 1 |
| MPL-2.0 | 1 |
| bzip2-1.0.6 | 1 |

## Components (538)

| Component | Version | Licence | Repository |
|---|---|---|---|
| ab_glyph_rasterizer | 0.1.10 | Apache-2.0 | https://github.com/alexheretic/ab-glyph |
| accesskit | 0.24.1 | MIT OR Apache-2.0 | https://github.com/AccessKit/accesskit |
| accesskit_consumer | 0.38.0 | MIT OR Apache-2.0 | https://github.com/AccessKit/accesskit |
| accesskit_macos | 0.26.3 | MIT OR Apache-2.0 | https://github.com/AccessKit/accesskit |
| addr2line | 0.25.1 | Apache-2.0 OR MIT | https://github.com/gimli-rs/addr2line |
| adler2 | 2.0.1 | 0BSD OR MIT OR Apache-2.0 | https://github.com/oyvindln/adler2 |
| adobe-cmap-parser | 0.4.1 | MIT | https://github.com/jrmuizel/adobe-cmap-parser |
| aes | 0.8.4 | MIT OR Apache-2.0 | https://github.com/RustCrypto/block-ciphers |
| aes | 0.9.4 | MIT OR Apache-2.0 | https://github.com/RustCrypto/block-ciphers |
| ahash | 0.8.12 | MIT OR Apache-2.0 | https://github.com/tkaitchuck/ahash |
| aho-corasick | 1.1.5 | Unlicense OR MIT | https://github.com/BurntSushi/aho-corasick |
| alacritty_terminal | 0.26.1-dev | Apache-2.0 | https://github.com/alacritty/alacritty |
| alloc-no-stdlib | 2.0.4 | BSD-3-Clause | https://github.com/dropbox/rust-alloc-no-stdlib |
| alloc-stdlib | 0.2.4 | BSD-3-Clause | https://github.com/dropbox/rust-alloc-no-stdlib |
| annotate-snippets | 0.12.16 | MIT OR Apache-2.0 | https://github.com/rust-lang/annotate-snippets-rs |
| anstyle | 1.0.14 | MIT OR Apache-2.0 | https://github.com/rust-cli/anstyle.git |
| anyhow | 1.0.104 | MIT OR Apache-2.0 | https://github.com/dtolnay/anyhow |
| arc-swap | 1.9.2 | MIT OR Apache-2.0 | https://github.com/vorner/arc-swap |
| arraydeque | 0.5.1 | MIT OR Apache-2.0 | https://github.com/andylokandy/arraydeque |
| arrayref | 0.3.9 | BSD-2-Clause | https://github.com/droundy/arrayref |
| arrayvec | 0.7.8 | MIT OR Apache-2.0 | https://github.com/bluss/arrayvec |
| async-channel | 2.5.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-channel |
| async-compression | 0.4.43 | MIT OR Apache-2.0 | https://github.com/Nullus157/async-compression |
| async-executor | 1.14.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-executor |
| async-fs | 2.2.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-fs |
| async-io | 2.6.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-io |
| async-lock | 3.4.2 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-lock |
| async-net | 2.0.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-net |
| async-process | 2.5.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-process |
| async-signal | 0.2.14 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-signal |
| async-task | 4.7.1 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-task |
| atoi_simd | 0.18.1 | MIT OR Apache-2.0 | https://github.com/RoDmitry/atoi_simd |
| atomic | 0.5.3 | Apache-2.0 OR MIT | https://github.com/Amanieu/atomic-rs |
| atomic-waker | 1.1.2 | Apache-2.0 OR MIT | https://github.com/smol-rs/atomic-waker |
| backtrace | 0.3.76 | MIT OR Apache-2.0 | https://github.com/rust-lang/backtrace-rs |
| base62 | 2.2.4 | MIT | https://github.com/fbernier/base62 |
| base64 | 0.22.1 | MIT OR Apache-2.0 | https://github.com/marshallpierce/rust-base64 |
| base64 | 0.23.1 | MIT OR Apache-2.0 | https://github.com/marshallpierce/rust-base64 |
| bincode | 1.3.3 | MIT | https://github.com/servo/bincode |
| bit-set | 0.8.0 | Apache-2.0 OR MIT | https://github.com/contain-rs/bit-set |
| bit-vec | 0.8.0 | Apache-2.0 OR MIT | https://github.com/contain-rs/bit-vec |
| bit_field | 0.10.3 | Apache-2.0 OR MIT | https://github.com/phil-opp/rust-bit-field |
| bitflags | 1.3.2 | MIT OR Apache-2.0 | https://github.com/bitflags/bitflags |
| bitflags | 2.13.1 | MIT OR Apache-2.0 | https://github.com/bitflags/bitflags |
| block | 0.1.6 | MIT |  |
| block-buffer | 0.10.4 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| block-buffer | 0.12.1 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| block-padding | 0.3.3 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| block2 | 0.6.2 | MIT | https://github.com/madsmtm/objc2 |
| blocking | 1.6.2 | Apache-2.0 OR MIT | https://github.com/smol-rs/blocking |
| brotli | 8.0.4 | BSD-3-Clause AND MIT | https://github.com/dropbox/rust-brotli |
| brotli-decompressor | 5.0.3 | BSD-3-Clause OR MIT | https://github.com/dropbox/rust-brotli-decompressor |
| bstr | 1.13.1 | MIT OR Apache-2.0 | https://github.com/BurntSushi/bstr |
| bumpalo | 3.20.3 | MIT OR Apache-2.0 | https://github.com/fitzgen/bumpalo |
| bytemuck | 1.25.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/Lokathor/bytemuck |
| byteorder | 1.5.0 | Unlicense OR MIT | https://github.com/BurntSushi/byteorder |
| byteorder-lite | 0.1.0 | Unlicense OR MIT | https://github.com/image-rs/byteorder-lite |
| bytes | 1.12.1 | MIT | https://github.com/tokio-rs/bytes |
| bzip2 | 0.6.1 | MIT OR Apache-2.0 | https://github.com/trifectatechfoundation/bzip2-rs |
| calamine | 0.38.0 | MIT | https://github.com/tafia/calamine |
| cbc | 0.1.2 | MIT OR Apache-2.0 | https://github.com/RustCrypto/block-modes |
| cff-parser | 0.2.0 | MIT OR Apache-2.0 | https://github.com/jrmuizel/cff-parser |
| cfg-if | 1.0.4 | MIT OR Apache-2.0 | https://github.com/rust-lang/cfg-if |
| cgl | 0.3.2 | MIT OR Apache-2.0 | https://github.com/servo/cgl-rs |
| chacha20 | 0.10.1 | MIT OR Apache-2.0 | https://github.com/RustCrypto/stream-ciphers |
| chrono | 0.4.45 | MIT OR Apache-2.0 | https://github.com/chronotope/chrono |
| cipher | 0.4.4 | MIT OR Apache-2.0 | https://github.com/RustCrypto/traits |
| cipher | 0.5.2 | MIT OR Apache-2.0 | https://github.com/RustCrypto/traits |
| cmov | 0.5.4 | Apache-2.0 OR MIT | https://github.com/RustCrypto/utils |
| cocoa | 0.26.0 | MIT OR Apache-2.0 | https://github.com/servo/core-foundation-rs |
| cocoa-foundation | 0.2.0 | MIT OR Apache-2.0 | https://github.com/servo/core-foundation-rs |
| codepage | 0.1.3 | Apache-2.0 OR MIT | https://github.com/hsivonen/codepage |
| collections | 0.1.0 | Apache-2.0 |  |
| color | 0.3.3 | Apache-2.0 OR MIT | https://github.com/linebender/color |
| color_quant | 1.1.0 | MIT | https://github.com/image-rs/color_quant.git |
| compression-codecs | 0.4.38 | MIT OR Apache-2.0 | https://github.com/Nullus157/async-compression |
| compression-core | 0.4.32 | MIT OR Apache-2.0 | https://github.com/Nullus157/async-compression |
| concurrent-queue | 2.5.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/concurrent-queue |
| const-oid | 0.10.2 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats |
| constant_time_eq | 0.6.1 | CC0-1.0 OR MIT-0 OR Apache-2.0 | https://codeberg.org/cesarb/constant_time_eq |
| convert_case | 0.10.0 | MIT | https://github.com/rutrum/convert-case |
| core-foundation | 0.10.1 | MIT OR Apache-2.0 | https://github.com/servo/core-foundation-rs |
| core-foundation-sys | 0.8.7 | MIT OR Apache-2.0 | https://github.com/servo/core-foundation-rs |
| core-graphics | 0.24.0 | MIT OR Apache-2.0 | https://github.com/servo/core-foundation-rs |
| core-graphics-types | 0.2.0 | MIT OR Apache-2.0 | https://github.com/servo/core-foundation-rs |
| core-graphics2 | 0.5.2 | MIT OR Apache-2.0 | https://github.com/rust-media/apple-media-rs |
| core-text | 21.0.0 | MIT OR Apache-2.0 | https://github.com/servo/core-foundation-rs |
| core-video | 0.5.2 | MIT OR Apache-2.0 | https://github.com/rust-media/apple-media-rs |
| core_maths | 0.1.1 | MIT | https://github.com/robertbastian/core_maths |
| cpubits | 0.1.1 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| cpufeatures | 0.2.17 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| cpufeatures | 0.3.0 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| crc32fast | 1.5.0 | MIT OR Apache-2.0 | https://github.com/srijs/rust-crc32fast |
| crossbeam-channel | 0.5.16 | MIT OR Apache-2.0 | https://github.com/crossbeam-rs/crossbeam |
| crossbeam-deque | 0.8.7 | MIT OR Apache-2.0 | https://github.com/crossbeam-rs/crossbeam |
| crossbeam-epoch | 0.9.20 | MIT OR Apache-2.0 | https://github.com/crossbeam-rs/crossbeam |
| crossbeam-queue | 0.3.13 | MIT OR Apache-2.0 | https://github.com/crossbeam-rs/crossbeam |
| crossbeam-utils | 0.8.22 | MIT OR Apache-2.0 | https://github.com/crossbeam-rs/crossbeam |
| crypto-common | 0.1.7 | MIT OR Apache-2.0 | https://github.com/RustCrypto/traits |
| crypto-common | 0.2.2 | MIT OR Apache-2.0 | https://github.com/RustCrypto/traits |
| ctor | 1.0.13 | Apache-2.0 OR MIT | https://github.com/mmastrac/linktime |
| ctutils | 0.4.8 | Apache-2.0 OR MIT | https://github.com/RustCrypto/utils |
| cursor-icon | 1.2.0 | MIT OR Apache-2.0 OR Zlib | https://github.com/rust-windowing/cursor-icon |
| data-url | 0.3.2 | MIT OR Apache-2.0 | https://github.com/servo/rust-url |
| debug_unsafe | 0.1.4 | MIT OR Apache-2.0 | https://github.com/RoDmitry/debug_unsafe |
| derive_more | 2.1.1 | MIT | https://github.com/JelteF/derive_more |
| digest | 0.10.7 | MIT OR Apache-2.0 | https://github.com/RustCrypto/traits |
| digest | 0.11.3 | MIT OR Apache-2.0 | https://github.com/RustCrypto/traits |
| dirs | 6.0.0 | MIT OR Apache-2.0 | https://github.com/soc/dirs-rs |
| dirs-sys | 0.5.0 | MIT OR Apache-2.0 | https://github.com/dirs-dev/dirs-sys-rs |
| dispatch2 | 0.3.1 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| dyn-clone | 1.0.20 | MIT OR Apache-2.0 | https://github.com/dtolnay/dyn-clone |
| ecb | 0.1.2 | MIT | https://github.com/magic-akari/ecb |
| either | 1.17.0 | MIT OR Apache-2.0 | https://github.com/rayon-rs/either |
| encoding_rs | 0.8.35 | (Apache-2.0 OR MIT) AND BSD-3-Clause | https://github.com/hsivonen/encoding_rs |
| encoding_rs_io | 0.1.8 | MIT OR Apache-2.0 | https://github.com/BurntSushi/encoding_rs_io |
| enum-iterator | 2.3.0 | 0BSD | https://github.com/stephaneyfx/enum-iterator.git |
| equivalent | 1.0.2 | Apache-2.0 OR MIT | https://github.com/indexmap-rs/equivalent |
| erased-serde | 0.4.10 | MIT OR Apache-2.0 | https://github.com/dtolnay/erased-serde |
| errno | 0.3.14 | MIT OR Apache-2.0 | https://github.com/lambda-fairy/rust-errno |
| etagere | 0.2.15 | MIT OR Apache-2.0 | https://github.com/nical/etagere |
| euclid | 0.20.14 | MIT OR Apache-2.0 | https://github.com/servo/euclid |
| euclid | 0.22.14 | MIT OR Apache-2.0 | https://github.com/servo/euclid |
| event-listener | 5.4.2 | Apache-2.0 OR MIT | https://github.com/smol-rs/event-listener |
| event-listener-strategy | 0.5.4 | Apache-2.0 OR MIT | https://github.com/smol-rs/event-listener-strategy |
| exr | 1.74.2 | BSD-3-Clause | https://github.com/johannesvollmer/exrs |
| fallible-iterator | 0.3.0 | MIT OR Apache-2.0 | https://github.com/sfackler/rust-fallible-iterator |
| fallible-streaming-iterator | 0.1.9 | MIT OR Apache-2.0 | https://github.com/sfackler/fallible-streaming-iterator |
| fancy-regex | 0.16.2 | MIT | https://github.com/fancy-regex/fancy-regex |
| fast-float2 | 0.2.4 | MIT OR Apache-2.0 | https://github.com/Alexhuszagh/fast-float-rust |
| fastrand | 2.5.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/fastrand |
| fax | 0.2.7 | MIT | https://github.com/pdf-rs/fax |
| fdeflate | 0.3.7 | MIT OR Apache-2.0 | https://github.com/image-rs/fdeflate |
| fearless_simd | 0.7.0 | Apache-2.0 OR MIT | https://github.com/linebender/fearless_simd |
| fearless_simd | 1.2.0 | Apache-2.0 OR MIT | https://github.com/linebender/fearless_simd |
| filetime | 0.2.29 | MIT OR Apache-2.0 | https://github.com/alexcrichton/filetime |
| fixedbitset | 0.5.7 | MIT OR Apache-2.0 | https://github.com/petgraph/fixedbitset |
| flate2 | 1.1.9 | MIT OR Apache-2.0 | https://github.com/rust-lang/flate2-rs |
| float-cmp | 0.9.0 | MIT | https://github.com/mikedilger/float-cmp |
| float-ord | 0.3.2 | MIT OR Apache-2.0 | https://github.com/notriddle/rust-float-ord |
| float_next_after | 1.0.0 | MIT | https://gitlab.com/bronsonbdevost/next_afterf |
| fluent-uri | 0.1.4 | MIT | https://github.com/yescallop/fluent-uri-rs |
| flume | 0.12.0 | Apache-2.0 OR MIT | https://github.com/zesterer/flume |
| fnv | 1.0.7 | Apache-2.0 OR MIT | https://github.com/servo/rust-fnv |
| foldhash | 0.1.5 | Zlib | https://github.com/orlp/foldhash |
| foldhash | 0.2.0 | Zlib | https://github.com/orlp/foldhash |
| font-types | 0.12.7 | MIT OR Apache-2.0 | https://github.com/googlefonts/fontations |
| fontdb | 0.23.0 | MIT | https://github.com/RazrFalcon/fontdb |
| foreign-types | 0.5.0 | MIT OR Apache-2.0 | https://github.com/sfackler/foreign-types |
| foreign-types-shared | 0.3.1 | MIT OR Apache-2.0 | https://github.com/sfackler/foreign-types |
| form_urlencoded | 1.2.2 | MIT OR Apache-2.0 | https://github.com/servo/rust-url |
| fsevent-sys | 4.1.0 | MIT | https://github.com/octplane/fsevent-rust/tree/master/fsevent-sys |
| futf | 0.1.5 | MIT OR Apache-2.0 | https://github.com/servo/futf |
| futures | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| futures-channel | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| futures-concurrency | 7.7.1 | MIT OR Apache-2.0 | https://github.com/yoshuawuyts/futures-concurrency |
| futures-core | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| futures-executor | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| futures-io | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| futures-lite | 2.6.1 | Apache-2.0 OR MIT | https://github.com/smol-rs/futures-lite |
| futures-sink | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| futures-task | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| futures-util | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| generic-array | 0.14.7 | MIT | https://github.com/fizyk20/generic-array.git |
| gethostname | 1.1.0 | Apache-2.0 | https://codeberg.org/swsnr/gethostname.rs.git |
| getrandom | 0.2.17 | MIT OR Apache-2.0 | https://github.com/rust-random/getrandom |
| getrandom | 0.3.4 | MIT OR Apache-2.0 | https://github.com/rust-random/getrandom |
| getrandom | 0.4.3 | MIT OR Apache-2.0 | https://github.com/rust-random/getrandom |
| gif | 0.14.2 | MIT OR Apache-2.0 | https://github.com/image-rs/image-gif |
| gimli | 0.32.3 | MIT OR Apache-2.0 | https://github.com/gimli-rs/gimli |
| glob | 0.3.4 | MIT OR Apache-2.0 | https://github.com/rust-lang/glob |
| globset | 0.4.20 | Unlicense OR MIT | https://github.com/BurntSushi/ripgrep/tree/master/crates/globset |
| globwalk | 0.8.1 | MIT | https://github.com/gilnaa/globwalk |
| gpui | 0.2.2 | Apache-2.0 | https://github.com/zed-industries/zed |
| gpui-base | 0.5.2 | Apache-2.0 | https://github.com/longbridge/gpui-component |
| gpui-component | 0.5.2 | Apache-2.0 | https://github.com/longbridge/gpui-component |
| gpui-component-assets | 0.5.1 | Apache-2.0 | https://github.com/longbridge/gpui-component |
| gpui_apple | 0.1.0 | Apache-2.0 |  |
| gpui_macos | 0.1.0 | Apache-2.0 |  |
| gpui_platform | 0.1.0 | Apache-2.0 |  |
| gpui_shared_string | 0.1.0 | Apache-2.0 |  |
| gpui_util | 0.1.0 | Apache-2.0 |  |
| granit-parser | 0.0.7 | MIT OR Apache-2.0 | https://github.com/bourumir-wyngs/granit-parser |
| guillotiere | 0.7.0 | MIT OR Apache-2.0 | https://github.com/nical/guillotiere |
| half | 2.7.1 | MIT OR Apache-2.0 | https://github.com/VoidStarKat/half-rs |
| hash32 | 0.3.1 | MIT OR Apache-2.0 | https://github.com/japaric/hash32 |
| hashbrown | 0.15.5 | MIT OR Apache-2.0 | https://github.com/rust-lang/hashbrown |
| hashbrown | 0.16.1 | MIT OR Apache-2.0 | https://github.com/rust-lang/hashbrown |
| hashbrown | 0.17.1 | MIT OR Apache-2.0 | https://github.com/rust-lang/hashbrown |
| hashlink | 0.10.0 | MIT OR Apache-2.0 | https://github.com/kyren/hashlink |
| hayro | 0.9.0 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hayro-ccitt | 0.5.0 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hayro-cmap | 0.1.1 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hayro-font | 0.5.0 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hayro-interpret | 0.9.0 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hayro-jbig2 | 0.4.0 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hayro-jpeg2000 | 0.5.0 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hayro-postscript | 0.2.0 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hayro-syntax | 0.9.0 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hdrhistogram | 7.6.0 | MIT OR Apache-2.0 | https://github.com/HdrHistogram/HdrHistogram_rust.git |
| heapless | 0.9.3 | MIT OR Apache-2.0 | https://github.com/rust-embedded/heapless |
| heck | 0.5.0 | MIT OR Apache-2.0 | https://github.com/withoutboats/heck |
| hmac | 0.13.0 | MIT OR Apache-2.0 | https://github.com/RustCrypto/MACs |
| home | 0.5.12 | MIT OR Apache-2.0 | https://github.com/rust-lang/cargo |
| html5ever | 0.27.0 | MIT OR Apache-2.0 | https://github.com/servo/html5ever |
| http | 1.5.0 | MIT OR Apache-2.0 | https://github.com/hyperium/http |
| http-body | 1.1.0 | MIT | https://github.com/hyperium/http-body |
| http_client | 0.1.0 | Apache-2.0 |  |
| httparse | 1.10.1 | MIT OR Apache-2.0 | https://github.com/seanmonstar/httparse |
| hybrid-array | 0.4.14 | MIT OR Apache-2.0 | https://github.com/RustCrypto/hybrid-array |
| iana-time-zone | 0.1.65 | MIT OR Apache-2.0 | https://github.com/strawlab/iana-time-zone |
| icu_collections | 2.3.0 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| icu_locale_core | 2.3.0 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| icu_normalizer | 2.3.0 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| icu_normalizer_data | 2.3.0 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| icu_properties | 2.3.0 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| icu_properties_data | 2.3.0 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| icu_provider | 2.3.0 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| idna | 1.1.0 | MIT OR Apache-2.0 | https://github.com/servo/rust-url/ |
| idna_adapter | 1.2.2 | Apache-2.0 OR MIT | https://github.com/hsivonen/idna_adapter |
| if-addrs | 0.15.0 | MIT OR BSD-3-Clause | https://github.com/messense/if-addrs |
| ignore | 0.4.33 | Unlicense OR MIT | https://github.com/BurntSushi/ripgrep/tree/master/crates/ignore |
| image | 0.25.10 | MIT OR Apache-2.0 | https://github.com/image-rs/image |
| image-webp | 0.2.4 | MIT OR Apache-2.0 | https://github.com/image-rs/image-webp |
| imagesize | 0.14.0 | MIT | https://github.com/Roughsketch/imagesize |
| indexmap | 2.14.0 | Apache-2.0 OR MIT | https://github.com/indexmap-rs/indexmap |
| inout | 0.1.4 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| inout | 0.2.6 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| instant | 0.1.13 | BSD-3-Clause | https://github.com/sebcrozet/instant |
| inventory | 0.3.24 | MIT OR Apache-2.0 | https://github.com/dtolnay/inventory |
| io-surface | 0.16.1 | MIT OR Apache-2.0 | https://github.com/servo/core-foundation-rs |
| itertools | 0.11.0 | MIT OR Apache-2.0 | https://github.com/rust-itertools/itertools |
| itertools | 0.13.0 | MIT OR Apache-2.0 | https://github.com/rust-itertools/itertools |
| itertools | 0.14.0 | MIT OR Apache-2.0 | https://github.com/rust-itertools/itertools |
| itoa | 1.0.18 | MIT OR Apache-2.0 | https://github.com/dtolnay/itoa |
| keyring | 3.6.3 | MIT OR Apache-2.0 | https://github.com/hwchen/keyring-rs.git |
| kurbo | 0.13.1 | Apache-2.0 OR MIT | https://github.com/linebender/kurbo |
| lazy_static | 1.5.0 | MIT OR Apache-2.0 | https://github.com/rust-lang-nursery/lazy-static.rs |
| leak | 0.1.2 | Apache-2.0 OR MIT | https://github.com/jmesmon/leak.git |
| leaky-cow | 0.1.1 | MIT OR Apache-2.0 | https://github.com/notriddle/rust-leaky-cow |
| lebe | 0.5.3 | BSD-3-Clause | https://github.com/johannesvollmer/lebe |
| libbz2-rs-sys | 0.2.5 | bzip2-1.0.6 | https://github.com/trifectatechfoundation/libbzip2-rs |
| libc | 0.2.189 | MIT OR Apache-2.0 | https://github.com/rust-lang/libc |
| libm | 0.2.16 | MIT | https://github.com/rust-lang/compiler-builtins |
| libsqlite3-sys | 0.35.0 | MIT | https://github.com/rusqlite/rusqlite |
| linebender_resource_handle | 0.1.1 | Apache-2.0 OR MIT | https://github.com/linebender/raw_resource_handle |
| link-section | 0.19.3 | Apache-2.0 OR MIT | https://github.com/mmastrac/linktime |
| litemap | 0.8.3 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| lock_api | 0.4.14 | MIT OR Apache-2.0 | https://github.com/Amanieu/parking_lot |
| log | 0.4.33 | MIT OR Apache-2.0 | https://github.com/rust-lang/log |
| lopdf | 0.42.0 | MIT | https://github.com/J-F-Liu/lopdf.git |
| lsp-types | 0.97.0 | MIT | https://github.com/gluon-lang/lsp-types |
| lyon | 1.0.19 | MIT OR Apache-2.0 | https://github.com/nical/lyon |
| lyon_algorithms | 1.0.20 | MIT OR Apache-2.0 | https://github.com/nical/lyon |
| lyon_geom | 1.0.19 | MIT OR Apache-2.0 | https://github.com/nical/lyon |
| lyon_path | 1.0.19 | MIT OR Apache-2.0 | https://github.com/nical/lyon |
| lyon_tessellation | 1.0.20 | MIT OR Apache-2.0 | https://github.com/nical/lyon |
| mac | 0.1.1 | MIT OR Apache-2.0 | https://github.com/reem/rust-mac.git |
| mach2 | 0.5.0 | BSD-2-Clause OR MIT OR Apache-2.0 | https://github.com/JohnTitor/mach2 |
| mail-parser | 0.11.9 | Apache-2.0 OR MIT | https://github.com/stalwartlabs/mail-parser |
| malloc_buf | 0.0.6 | MIT | https://github.com/SSheldon/malloc_buf |
| markdown | 1.0.0 | MIT | https://github.com/wooorm/markdown-rs |
| markup5ever | 0.12.1 | MIT OR Apache-2.0 | https://github.com/servo/html5ever |
| markup5ever_rcdom | 0.3.0 | MIT OR Apache-2.0 | https://github.com/servo/html5ever |
| md-5 | 0.10.6 | MIT OR Apache-2.0 | https://github.com/RustCrypto/hashes |
| mdns-sd | 0.22.0 | Apache-2.0 OR MIT | https://github.com/keepsimple1/mdns-sd |
| media | 0.1.0 | Apache-2.0 |  |
| memchr | 2.8.3 | Unlicense OR MIT | https://github.com/BurntSushi/memchr |
| memmap2 | 0.9.11 | MIT OR Apache-2.0 | https://github.com/RazrFalcon/memmap2-rs |
| metal | 0.33.0 | MIT OR Apache-2.0 | https://github.com/gfx-rs/metal-rs |
| mime | 0.3.17 | MIT OR Apache-2.0 | https://github.com/hyperium/mime |
| mime_guess | 2.0.5 | MIT | https://github.com/abonander/mime_guess |
| miniz_oxide | 0.8.9 | MIT OR Zlib OR Apache-2.0 | https://github.com/Frommi/miniz_oxide/tree/master/miniz_oxide |
| mio | 1.2.2 | MIT | https://github.com/tokio-rs/mio |
| moxcms | 0.8.1 | BSD-3-Clause OR Apache-2.0 | https://github.com/awxkee/moxcms.git |
| new_debug_unreachable | 1.0.6 | MIT | https://github.com/mbrubeck/rust-debug-unreachable |
| nix | 0.32.0 | MIT | https://github.com/nix-rust/nix |
| nohash-hasher | 0.2.0 | Apache-2.0 OR MIT | https://github.com/paritytech/nohash-hasher |
| nom | 8.0.0 | MIT | https://github.com/rust-bakery/nom |
| normpath | 1.5.1 | MIT OR Apache-2.0 | https://github.com/dylni/normpath |
| notify | 7.0.0 | CC0-1.0 | https://github.com/notify-rs/notify.git |
| notify-types | 1.0.1 | MIT OR Apache-2.0 | https://github.com/notify-rs/notify.git |
| nu-ansi-term | 0.50.3 | MIT | https://github.com/nushell/nu-ansi-term |
| num-complex | 0.4.6 | MIT OR Apache-2.0 | https://github.com/rust-num/num-complex |
| num-traits | 0.2.19 | MIT OR Apache-2.0 | https://github.com/rust-num/num-traits |
| num_cpus | 1.17.0 | MIT OR Apache-2.0 | https://github.com/seanmonstar/num_cpus |
| objc | 0.2.7 | MIT |  |
| objc-sys | 0.3.5 | MIT | https://github.com/madsmtm/objc2 |
| objc2 | 0.5.2 | MIT | https://github.com/madsmtm/objc2 |
| objc2 | 0.6.4 | MIT | https://github.com/madsmtm/objc2 |
| objc2-app-kit | 0.2.2 | MIT | https://github.com/madsmtm/objc2 |
| objc2-app-kit | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-cloud-kit | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-core-data | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-core-foundation | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-core-graphics | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-core-image | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-core-location | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-core-text | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-core-video | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-encode | 4.1.0 | MIT | https://github.com/madsmtm/objc2 |
| objc2-foundation | 0.2.2 | MIT | https://github.com/madsmtm/objc2 |
| objc2-foundation | 0.3.2 | MIT | https://github.com/madsmtm/objc2 |
| objc2-quartz-core | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-user-notifications | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| object | 0.37.3 | Apache-2.0 OR MIT | https://github.com/gimli-rs/object |
| ocrs | 0.14.0 | MIT OR Apache-2.0 | https://github.com/robertknight/ocrs |
| once_cell | 1.21.4 | MIT OR Apache-2.0 | https://github.com/matklad/once_cell |
| option-ext | 0.2.0 | MPL-2.0 | https://github.com/soc/option-ext.git |
| otherwise-agent-panel | 0.2.0 | MIT OR Apache-2.0 | https://github.com/otherwisetech/otherwise-agent-panel |
| otherwise-link | 0.2.0 | MIT OR Apache-2.0 | https://github.com/otherwisetech/otherwise-link |
| otherwise-link | 0.4.0 | MIT OR Apache-2.0 | https://github.com/otherwisetech/otherwise-link |
| otherwise-link | 0.5.2 | MIT OR Apache-2.0 | https://github.com/otherwisetech/otherwise-link |
| otherwise-ui | 0.1.3 | MIT OR Apache-2.0 | https://github.com/otherwisetech/otherwise-ui |
| parking | 2.2.1 | Apache-2.0 OR MIT | https://github.com/smol-rs/parking |
| parking_lot | 0.12.5 | MIT OR Apache-2.0 | https://github.com/Amanieu/parking_lot |
| parking_lot_core | 0.9.12 | MIT OR Apache-2.0 | https://github.com/Amanieu/parking_lot |
| pathfinder_geometry | 0.5.1 | MIT OR Apache-2.0 | https://github.com/servo/pathfinder |
| pathfinder_simd | 0.5.6 | MIT OR Apache-2.0 | https://github.com/servo/pathfinder |
| pbkdf2 | 0.13.0 | MIT OR Apache-2.0 | https://github.com/RustCrypto/password-hashes |
| pdf-extract | 0.12.1 | MIT | https://github.com/jrmuizel/pdf-extract |
| pdf-writer | 0.14.0 | MIT OR Apache-2.0 | https://github.com/typst/pdf-writer |
| peniko | 0.6.1 | Apache-2.0 OR MIT | https://github.com/linebender/peniko |
| percent-encoding | 2.3.2 | MIT OR Apache-2.0 | https://github.com/servo/rust-url/ |
| perf | 0.1.0 | Apache-2.0 |  |
| phf | 0.11.3 | MIT | https://github.com/rust-phf/rust-phf |
| phf | 0.13.1 | MIT | https://github.com/rust-phf/rust-phf |
| phf_generator | 0.13.1 | MIT | https://github.com/rust-phf/rust-phf |
| phf_shared | 0.11.3 | MIT | https://github.com/rust-phf/rust-phf |
| phf_shared | 0.13.1 | MIT | https://github.com/rust-phf/rust-phf |
| pic-scale | 0.7.14 | BSD-3-Clause OR Apache-2.0 | https://github.com/awxkee/pic-scale |
| pico-args | 0.5.0 | MIT | https://github.com/RazrFalcon/pico-args |
| pin-project | 1.1.13 | Apache-2.0 OR MIT | https://github.com/taiki-e/pin-project |
| pin-project-lite | 0.2.17 | Apache-2.0 OR MIT | https://github.com/taiki-e/pin-project-lite |
| piper | 0.2.5 | MIT OR Apache-2.0 | https://github.com/smol-rs/piper |
| png | 0.17.16 | MIT OR Apache-2.0 | https://github.com/image-rs/image-png |
| png | 0.18.1 | MIT OR Apache-2.0 | https://github.com/image-rs/image-png |
| polling | 3.11.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/polling |
| pollster | 0.2.5 | Apache-2.0 OR MIT | https://github.com/zesterer/pollster |
| pollster | 0.4.0 | Apache-2.0 OR MIT | https://github.com/zesterer/pollster |
| polycool | 0.4.0 | MIT OR Apache-2.0 | https://github.com/linebender/kurbo |
| pom | 1.1.0 | MIT | https://github.com/J-F-Liu/pom.git |
| postage | 0.5.0 | MIT | https://github.com/austinjones/postage-rs |
| postscript | 0.14.1 | Apache-2.0 OR MIT | https://github.com/bodoni/postscript |
| potential_utf | 0.1.6 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| ppv-lite86 | 0.2.21 | MIT OR Apache-2.0 | https://github.com/cryptocorrosion/cryptocorrosion |
| precomputed-hash | 0.1.1 | MIT | https://github.com/emilio/precomputed-hash |
| proc-macro2 | 1.0.107 | MIT OR Apache-2.0 | https://github.com/dtolnay/proc-macro2 |
| profiling | 1.0.18 | MIT OR Apache-2.0 | https://github.com/aclysma/profiling |
| psm | 0.1.32 | MIT OR Apache-2.0 | https://github.com/rust-lang/stacker/ |
| pulp | 0.22.3 | MIT | https://github.com/sarah-quinones/pulp/ |
| pulp-wasm-simd-flag | 0.1.1 | MIT | https://github.com/sarah-quinones/pulp/ |
| pxfm | 0.1.30 | BSD-3-Clause OR Apache-2.0 | https://github.com/awxkee/pxfm |
| qoi | 0.4.1 | MIT OR Apache-2.0 | https://github.com/aldanor/qoi-rust |
| qrcode | 0.15.0 | MIT OR Apache-2.0 | https://github.com/kennytm/qrcode-rust |
| quick-error | 2.0.1 | MIT OR Apache-2.0 |  |
| quick-xml | 0.42.0 | MIT | https://github.com/tafia/quick-xml |
| quote | 1.0.47 | MIT OR Apache-2.0 | https://github.com/dtolnay/quote |
| rand | 0.10.2 | MIT OR Apache-2.0 | https://github.com/rust-random/rand |
| rand | 0.9.5 | MIT OR Apache-2.0 | https://github.com/rust-random/rand |
| rand_chacha | 0.9.0 | MIT OR Apache-2.0 | https://github.com/rust-random/rand |
| rand_core | 0.10.1 | MIT OR Apache-2.0 | https://github.com/rust-random/rand_core |
| rand_core | 0.9.5 | MIT OR Apache-2.0 | https://github.com/rust-random/rand |
| rangemap | 1.8.0 | MIT OR Apache-2.0 | https://github.com/jeffparsons/rangemap |
| raw-window-handle | 0.6.2 | MIT OR Apache-2.0 OR Zlib | https://github.com/rust-windowing/raw-window-handle |
| rayon | 1.12.0 | MIT OR Apache-2.0 | https://github.com/rayon-rs/rayon |
| rayon-core | 1.13.0 | MIT OR Apache-2.0 | https://github.com/rayon-rs/rayon |
| read-fonts | 0.46.0 | MIT OR Apache-2.0 | https://github.com/googlefonts/fontations |
| reborrow | 0.5.5 | MIT | https://github.com/sarah-ek/reborrow/ |
| ref-cast | 1.0.26 | MIT OR Apache-2.0 | https://github.com/dtolnay/ref-cast |
| refineable | 0.1.0 | Apache-2.0 |  |
| regex | 1.13.1 | MIT OR Apache-2.0 | https://github.com/rust-lang/regex |
| regex-automata | 0.4.18 | MIT OR Apache-2.0 | https://github.com/rust-lang/regex |
| regex-syntax | 0.8.11 | MIT OR Apache-2.0 | https://github.com/rust-lang/regex |
| resvg | 0.46.0 | Apache-2.0 OR MIT | https://github.com/linebender/resvg |
| rgb | 0.8.53 | MIT | https://github.com/kornelski/rust-rgb |
| ring | 0.17.14 | Apache-2.0 AND ISC | https://github.com/briansmith/ring |
| ropey | 2.0.0-beta.1 | MIT OR Apache-2.0 | https://github.com/cessen/ropey |
| roxmltree | 0.21.1 | MIT OR Apache-2.0 | https://github.com/RazrFalcon/roxmltree |
| rten | 0.28.0 | MIT OR Apache-2.0 | https://github.com/robertknight/rten |
| rten-base | 0.28.0 | MIT OR Apache-2.0 | https://github.com/robertknight/rten |
| rten-gemm | 0.28.0 | MIT OR Apache-2.0 | https://github.com/robertknight/rten |
| rten-imageproc | 0.28.0 | MIT OR Apache-2.0 | https://github.com/robertknight/rten |
| rten-onnx | 0.28.0 | MIT OR Apache-2.0 | https://github.com/robertknight/rten |
| rten-parallel | 0.28.0 | MIT OR Apache-2.0 | https://github.com/robertknight/rten |
| rten-sequence | 0.28.0 | MIT OR Apache-2.0 | https://github.com/robertknight/rten |
| rten-shape-inference | 0.28.0 | MIT OR Apache-2.0 | https://github.com/robertknight/rten |
| rten-simd | 0.28.0 | MIT OR Apache-2.0 | https://github.com/robertknight/rten |
| rten-tensor | 0.28.0 | MIT OR Apache-2.0 | https://github.com/robertknight/rten |
| rten-vecmath | 0.28.0 | MIT OR Apache-2.0 | https://github.com/robertknight/rten |
| rusqlite | 0.37.0 | MIT | https://github.com/rusqlite/rusqlite |
| rust-embed | 8.12.0 | MIT | https://pyrossh.dev/repos/rust-embed |
| rust-embed-utils | 8.12.0 | MIT | https://pyrossh.dev/repos/rust-embed |
| rust-i18n | 4.2.1 | MIT | https://github.com/longbridge/rust-i18n |
| rust-i18n-support | 4.2.1 | MIT | https://github.com/longbridge/rust-i18n |
| rust_xlsxwriter | 0.103.0 | MIT OR Apache-2.0 | https://github.com/jmcnamara/rust_xlsxwriter |
| rustc-demangle | 0.1.28 | MIT OR Apache-2.0 | https://github.com/rust-lang/rustc-demangle |
| rustc-hash | 2.1.3 | Apache-2.0 OR MIT | https://github.com/rust-lang/rustc-hash |
| rustix | 1.1.4 | Apache-2.0 WITH LLVM-exception OR Apache-2.0 OR MIT | https://github.com/bytecodealliance/rustix |
| rustix-openpty | 0.2.0 | Apache-2.0 WITH LLVM-exception OR Apache-2.0 OR MIT | https://github.com/sunfishcode/rustix-openpty |
| rustls | 0.23.46 | Apache-2.0 OR ISC OR MIT | https://github.com/rustls/rustls |
| rustls-pki-types | 1.15.1 | MIT OR Apache-2.0 | https://github.com/rustls/pki-types |
| rustls-webpki | 0.103.14 | ISC | https://github.com/rustls/webpki |
| rustybuzz | 0.20.1 | MIT | https://github.com/harfbuzz/rustybuzz |
| ryu | 1.0.23 | Apache-2.0 OR BSL-1.0 | https://github.com/dtolnay/ryu |
| same-file | 1.0.6 | Unlicense OR MIT | https://github.com/BurntSushi/same-file |
| scheduler | 0.1.0 | Apache-2.0 |  |
| schemars | 1.2.2 | MIT | https://github.com/GREsau/schemars |
| scopeguard | 1.2.0 | MIT OR Apache-2.0 | https://github.com/bluss/scopeguard |
| seahash | 4.1.0 | MIT | https://gitlab.redox-os.org/redox-os/seahash |
| security-framework | 3.7.0 | MIT OR Apache-2.0 | https://github.com/kornelski/rust-security-framework |
| security-framework-sys | 2.17.0 | MIT OR Apache-2.0 | https://github.com/kornelski/rust-security-framework |
| semver | 1.0.28 | MIT OR Apache-2.0 | https://github.com/dtolnay/semver |
| serde | 1.0.229 | MIT OR Apache-2.0 | https://github.com/serde-rs/serde |
| serde-saphyr | 0.0.29 | MIT OR Apache-2.0 | https://github.com/bourumir-wyngs/serde-saphyr |
| serde_core | 1.0.229 | MIT OR Apache-2.0 | https://github.com/serde-rs/serde |
| serde_derive_internals | 0.30.0 | MIT OR Apache-2.0 | https://github.com/serde-rs/serde |
| serde_fmt | 1.1.0 | Apache-2.0 OR MIT | https://github.com/KodrAus/serde_fmt.git |
| serde_json | 1.0.151 | MIT OR Apache-2.0 | https://github.com/serde-rs/json |
| serde_spanned | 0.6.9 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| serde_urlencoded | 0.7.1 | MIT OR Apache-2.0 | https://github.com/nox/serde_urlencoded |
| sha1 | 0.11.0 | MIT OR Apache-2.0 | https://github.com/RustCrypto/hashes |
| sha1_smol | 1.0.1 | BSD-3-Clause | https://github.com/mitsuhiko/sha1-smol |
| sha2 | 0.10.9 | MIT OR Apache-2.0 | https://github.com/RustCrypto/hashes |
| sha2 | 0.11.0 | MIT OR Apache-2.0 | https://github.com/RustCrypto/hashes |
| sharded-slab | 0.1.7 | MIT | https://github.com/hawkw/sharded-slab |
| shellexpand | 3.1.2 | MIT OR Apache-2.0 | https://gitlab.com/ijackson/rust-shellexpand |
| signal-hook | 0.4.6 | MIT OR Apache-2.0 | https://github.com/vorner/signal-hook |
| signal-hook-registry | 1.4.8 | MIT OR Apache-2.0 | https://github.com/vorner/signal-hook |
| simd-adler32 | 0.3.10 | MIT | https://github.com/mcountryman/simd-adler32 |
| simplecss | 0.2.2 | Apache-2.0 OR MIT | https://github.com/linebender/simplecss |
| siphasher | 1.0.3 | MIT OR Apache-2.0 | https://github.com/jedisct1/rust-siphash |
| skrifa | 0.49.0 | MIT OR Apache-2.0 | https://github.com/googlefonts/fontations |
| slab | 0.4.12 | MIT | https://github.com/tokio-rs/slab |
| slotmap | 1.1.1 | Zlib | https://github.com/orlp/slotmap |
| smallvec | 1.15.2 | MIT OR Apache-2.0 | https://github.com/servo/rust-smallvec |
| smol | 2.0.2 | Apache-2.0 OR MIT | https://github.com/smol-rs/smol |
| smol_str | 0.3.6 | MIT OR Apache-2.0 | https://github.com/rust-lang/rust-analyzer/tree/master/lib/smol_str |
| socket-pktinfo | 0.4.2 | MIT | https://github.com/pixsper/socket-pktinfo |
| socket2 | 0.6.5 | MIT OR Apache-2.0 | https://github.com/rust-lang/socket2 |
| spin | 0.10.1 | MIT | https://github.com/mvdnes/spin-rs.git |
| spin | 0.9.9 | MIT | https://github.com/mvdnes/spin-rs.git |
| stable_deref_trait | 1.2.1 | MIT OR Apache-2.0 | https://github.com/storyyeller/stable_deref_trait |
| stacker | 0.1.25 | MIT OR Apache-2.0 | https://github.com/rust-lang/stacker |
| stacksafe | 1.0.3 | Apache-2.0 | https://github.com/fast/stacksafe |
| static_assertions | 1.1.0 | MIT OR Apache-2.0 | https://github.com/nvzqz/static-assertions-rs |
| str_indices | 0.4.4 | MIT OR Apache-2.0 | https://github.com/cessen/str_indices |
| strict-num | 0.1.1 | MIT | https://github.com/RazrFalcon/strict-num |
| string_cache | 0.8.9 | MIT OR Apache-2.0 | https://github.com/servo/string-cache |
| stringprep | 0.1.5 | MIT OR Apache-2.0 | https://github.com/sfackler/rust-stringprep |
| strum | 0.27.2 | MIT | https://github.com/Peternator7/strum |
| subtle | 2.6.1 | BSD-3-Clause | https://github.com/dalek-cryptography/subtle |
| sum_tree | 0.1.0 | Apache-2.0 |  |
| svg_fmt | 0.4.5 | MIT OR Apache-2.0 | https://github.com/nical/rust_debug |
| svgtypes | 0.16.1 | Apache-2.0 OR MIT | https://github.com/linebender/svgtypes |
| syn | 2.0.119 | MIT OR Apache-2.0 | https://github.com/dtolnay/syn |
| syn | 3.0.3 | MIT OR Apache-2.0 | https://github.com/dtolnay/syn |
| synstructure | 0.13.2 | MIT | https://github.com/mystor/synstructure |
| syntect | 5.3.0 | MIT | https://github.com/trishume/syntect |
| taffy | 0.13.0 | MIT | https://github.com/DioxusLabs/taffy |
| tendril | 0.4.3 | MIT OR Apache-2.0 | https://github.com/servo/tendril |
| thiserror | 1.0.69 | MIT OR Apache-2.0 | https://github.com/dtolnay/thiserror |
| thiserror | 2.0.20 | MIT OR Apache-2.0 | https://github.com/dtolnay/thiserror |
| thread_local | 1.1.10 | MIT OR Apache-2.0 | https://github.com/Amanieu/thread_local-rs |
| tiff | 0.11.3 | MIT | https://github.com/image-rs/image-tiff |
| tiny-skia | 0.11.4 | BSD-3-Clause | https://github.com/RazrFalcon/tiny-skia |
| tiny-skia-path | 0.11.4 | BSD-3-Clause | https://github.com/RazrFalcon/tiny-skia/tree/master/path |
| tinystr | 0.8.4 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| tinyvec | 1.12.0 | Zlib OR Apache-2.0 OR MIT | https://github.com/Lokathor/tinyvec |
| tinyvec_macros | 0.1.1 | MIT OR Apache-2.0 OR Zlib | https://github.com/Soveu/tinyvec_macros |
| toml | 0.8.23 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| toml_datetime | 0.6.11 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| toml_edit | 0.22.27 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| toml_write | 0.1.2 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| tracing | 0.1.44 | MIT | https://github.com/tokio-rs/tracing |
| tracing-core | 0.1.36 | MIT | https://github.com/tokio-rs/tracing |
| tracing-log | 0.2.0 | MIT | https://github.com/tokio-rs/tracing |
| tracing-subscriber | 0.3.23 | MIT | https://github.com/tokio-rs/tracing |
| triomphe | 0.1.16 | MIT OR Apache-2.0 | https://github.com/Manishearth/triomphe |
| ttf-parser | 0.25.1 | MIT OR Apache-2.0 | https://github.com/harfbuzz/ttf-parser |
| type1-encoding-parser | 0.1.1 | MIT | https://github.com/jrmuizel/type1-encoding-parser |
| typed-path | 0.13.0 | MIT OR Apache-2.0 | https://github.com/chipsenkbeil/typed-path |
| typeid | 1.0.3 | MIT OR Apache-2.0 | https://github.com/dtolnay/typeid |
| typenum | 1.20.1 | MIT OR Apache-2.0 | https://github.com/paholg/typenum |
| unicase | 2.9.0 | MIT OR Apache-2.0 | https://github.com/seanmonstar/unicase |
| unicode-bidi | 0.3.18 | MIT OR Apache-2.0 | https://github.com/servo/unicode-bidi |
| unicode-bidi-mirroring | 0.4.0 | MIT OR Apache-2.0 | https://github.com/RazrFalcon/unicode-bidi-mirroring |
| unicode-ccc | 0.4.0 | MIT OR Apache-2.0 | https://github.com/RazrFalcon/unicode-ccc |
| unicode-id | 0.3.6 | MIT OR Apache-2.0 | https://github.com/Boshen/unicode-id |
| unicode-ident | 1.0.24 | (MIT OR Apache-2.0) AND Unicode-3.0 | https://github.com/dtolnay/unicode-ident |
| unicode-normalization | 0.1.26 | (MIT OR Apache-2.0) AND Unicode-3.0 | https://github.com/unicode-rs/unicode-normalization |
| unicode-properties | 0.1.4 | MIT OR Apache-2.0 | https://github.com/unicode-rs/unicode-properties |
| unicode-script | 0.5.8 | MIT OR Apache-2.0 | https://github.com/unicode-rs/unicode-script |
| unicode-segmentation | 1.13.3 | MIT OR Apache-2.0 | https://github.com/unicode-rs/unicode-segmentation |
| unicode-vo | 0.1.0 | MIT OR Apache-2.0 | https://github.com/RazrFalcon/unicode-vo |
| unicode-width | 0.2.2 | MIT OR Apache-2.0 | https://github.com/unicode-rs/unicode-width |
| unicode-xid | 0.2.6 | MIT OR Apache-2.0 | https://github.com/unicode-rs/unicode-xid |
| untrusted | 0.9.0 | ISC | https://github.com/briansmith/untrusted |
| ureq | 3.4.2 | MIT OR Apache-2.0 | https://github.com/algesten/ureq |
| ureq-proto | 0.6.5 | MIT OR Apache-2.0 | https://github.com/algesten/ureq-proto |
| url | 2.5.8 | MIT OR Apache-2.0 | https://github.com/servo/rust-url |
| usvg | 0.46.0 | Apache-2.0 OR MIT | https://github.com/linebender/resvg |
| utf-8 | 0.7.6 | MIT OR Apache-2.0 | https://github.com/SimonSapin/rust-utf8 |
| utf8-zero | 0.8.1 | MIT OR Apache-2.0 | https://github.com/algesten/utf8-zero |
| utf8_iter | 1.0.4 | Apache-2.0 OR MIT | https://github.com/hsivonen/utf8_iter |
| uuid | 1.24.1 | Apache-2.0 OR MIT | https://github.com/uuid-rs/uuid |
| value-bag | 1.13.2 | Apache-2.0 OR MIT | https://github.com/sval-rs/value-bag |
| value-bag-serde1 | 1.13.2 | Apache-2.0 OR MIT |  |
| vello_common | 0.3.0 | Apache-2.0 OR MIT | https://github.com/linebender/vello |
| vello_cpu | 0.3.0 | Apache-2.0 OR MIT | https://github.com/linebender/vello |
| vte | 0.15.0 | Apache-2.0 OR MIT | https://github.com/alacritty/vte |
| waker-fn | 1.2.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/waker-fn |
| walkdir | 2.5.0 | Unlicense OR MIT | https://github.com/BurntSushi/walkdir |
| web-time | 1.1.0 | MIT OR Apache-2.0 | https://github.com/daxpedda/web-time |
| webpki-roots | 1.0.12 | CDLA-Permissive-2.0 | https://github.com/rustls/webpki-roots |
| weezl | 0.1.12 | MIT OR Apache-2.0 | https://github.com/image-rs/weezl |
| winnow | 0.7.15 | MIT | https://github.com/winnow-rs/winnow |
| workspace-hack | 0.1.0 | CC0-1.0 | https://github.com/facebookincubator/cargo-guppy |
| writeable | 0.6.4 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| xml5ever | 0.18.1 | MIT OR Apache-2.0 | https://github.com/servo/html5ever |
| xmlwriter | 0.1.0 | MIT | https://github.com/RazrFalcon/xmlwriter |
| yoke | 0.8.3 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| zed-font-kit | 0.14.1-zed | MIT OR Apache-2.0 | https://github.com/servo/font-kit |
| zed-sum-tree | 0.2.0 | Apache-2.0 |  |
| zerocopy | 0.8.56 | BSD-2-Clause OR Apache-2.0 OR MIT | https://github.com/google/zerocopy |
| zerofrom | 0.1.8 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| zeroize | 1.9.0 | Apache-2.0 OR MIT | https://github.com/RustCrypto/utils |
| zerotrie | 0.2.5 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| zerovec | 0.11.7 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| zip | 9.8.0 | MIT | https://github.com/zip-rs/zip2 |
| zlib-rs | 0.6.8 | Zlib | https://github.com/trifectatechfoundation/zlib-rs |
| zlog | 0.1.0 | GPL-3.0-or-later |  |
| zmij | 1.0.23 | MIT | https://github.com/dtolnay/zmij |
| zopfli | 0.8.3 | Apache-2.0 | https://github.com/zopfli-rs/zopfli |
| ztracing | 0.1.0 | GPL-3.0-or-later |  |
| zune-core | 0.5.3 | MIT OR Apache-2.0 OR Zlib | https://github.com/etemesi254/zune-image |
| zune-inflate | 0.2.54 | MIT OR Apache-2.0 OR Zlib |  |
| zune-jpeg | 0.5.15 | MIT OR Apache-2.0 OR Zlib | https://github.com/etemesi254/zune-image/tree/dev/crates/zune-jpeg |

## MIT License (standard text)

```
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and
associated documentation files (the "Software"), to deal in the Software without restriction,
including without limitation the rights to use, copy, modify, merge, publish, distribute,
sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or
substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT
NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT
OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

## Apache License 2.0 (standard text)

```
                              Apache License
                        Version 2.0, January 2004
                     http://www.apache.org/licenses/

TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

1. Definitions.

   "License" shall mean the terms and conditions for use, reproduction,
   and distribution as defined by Sections 1 through 9 of this document.

   "Licensor" shall mean the copyright owner or entity authorized by
   the copyright owner that is granting the License.

   "Legal Entity" shall mean the union of the acting entity and all
   other entities that control, are controlled by, or are under common
   control with that entity. For the purposes of this definition,
   "control" means (i) the power, direct or indirect, to cause the
   direction or management of such entity, whether by contract or
   otherwise, or (ii) ownership of fifty percent (50%) or more of the
   outstanding shares, or (iii) beneficial ownership of such entity.

   "You" (or "Your") shall mean an individual or Legal Entity
   exercising permissions granted by this License.

   "Source" form shall mean the preferred form for making modifications,
   including but not limited to software source code, documentation
   source, and configuration files.

   "Object" form shall mean any form resulting from mechanical
   transformation or translation of a Source form, including but
   not limited to compiled object code, generated documentation,
   and conversions to other media types.

   "Work" shall mean the work of authorship, whether in Source or
   Object form, made available under the License, as indicated by a
   copyright notice that is included in or attached to the work
   (an example is provided in the Appendix below).

   "Derivative Works" shall mean any work, whether in Source or Object
   form, that is based on (or derived from) the Work and for which the
   editorial revisions, annotations, elaborations, or other modifications
   represent, as a whole, an original work of authorship. For the purposes
   of this License, Derivative Works shall not include works that remain
   separable from, or merely link (or bind by name) to the interfaces of,
   the Work and Derivative Works thereof.

   "Contribution" shall mean any work of authorship, including
   the original version of the Work and any modifications or additions
   to that Work or Derivative Works thereof, that is intentionally
   submitted to Licensor for inclusion in the Work by the copyright owner
   or by an individual or Legal Entity authorized to submit on behalf of
   the copyright owner. For the purposes of this definition, "submitted"
   means any form of electronic, verbal, or written communication sent
   to the Licensor or its representatives, including but not limited to
   communication on electronic mailing lists, source code control systems,
   and issue tracking systems that are managed by, or on behalf of, the
   Licensor for the purpose of discussing and improving the Work, but
   excluding communication that is conspicuously marked or otherwise
   designated in writing by the copyright owner as "Not a Contribution."

   "Contributor" shall mean Licensor and any individual or Legal Entity
   on behalf of whom a Contribution has been received by Licensor and
   subsequently incorporated within the Work.

2. Grant of Copyright License. Subject to the terms and conditions of
   this License, each Contributor hereby grants to You a perpetual,
   worldwide, non-exclusive, no-charge, royalty-free, irrevocable
   copyright license to reproduce, prepare Derivative Works of,
   publicly display, publicly perform, sublicense, and distribute the
   Work and such Derivative Works in Source or Object form.

3. Grant of Patent License. Subject to the terms and conditions of
   this License, each Contributor hereby grants to You a perpetual,
   worldwide, non-exclusive, no-charge, royalty-free, irrevocable
   (except as stated in this section) patent license to make, have made,
   use, offer to sell, sell, import, and otherwise transfer the Work,
   where such license applies only to those patent claims licensable
   by such Contributor that are necessarily infringed by their
   Contribution(s) alone or by combination of their Contribution(s)
   with the Work to which such Contribution(s) was submitted. If You
   institute patent litigation against any entity (including a
   cross-claim or counterclaim in a lawsuit) alleging that the Work
   or a Contribution incorporated within the Work constitutes direct
   or contributory patent infringement, then any patent licenses
   granted to You under this License for that Work shall terminate
   as of the date such litigation is filed.

4. Redistribution. You may reproduce and distribute copies of the
   Work or Derivative Works thereof in any medium, with or without
   modifications, and in Source or Object form, provided that You
   meet the following conditions:

   (a) You must give any other recipients of the Work or
       Derivative Works a copy of this License; and

   (b) You must cause any modified files to carry prominent notices
       stating that You changed the files; and

   (c) You must retain, in the Source form of any Derivative Works
       that You distribute, all copyright, patent, trademark, and
       attribution notices from the Source form of the Work,
       excluding those notices that do not pertain to any part of
       the Derivative Works; and

   (d) If the Work includes a "NOTICE" text file as part of its
       distribution, then any Derivative Works that You distribute must
       include a readable copy of the attribution notices contained
       within such NOTICE file, excluding those notices that do not
       pertain to any part of the Derivative Works, in at least one
       of the following places: within a NOTICE text file distributed
       as part of the Derivative Works; within the Source form or
       documentation, if provided along with the Derivative Works; or,
       within a display generated by the Derivative Works, if and
       wherever such third-party notices normally appear. The contents
       of the NOTICE file are for informational purposes only and
       do not modify the License. You may add Your own attribution
       notices within Derivative Works that You distribute, alongside
       or as an addendum to the NOTICE text from the Work, provided
       that such additional attribution notices cannot be construed
       as modifying the License.

   You may add Your own copyright statement to Your modifications and
   may provide additional or different license terms and conditions
   for use, reproduction, or distribution of Your modifications, or
   for any such Derivative Works as a whole, provided Your use,
   reproduction, and distribution of the Work otherwise complies with
   the conditions stated in this License.

5. Submission of Contributions. Unless You explicitly state otherwise,
   any Contribution intentionally submitted for inclusion in the Work
   by You to the Licensor shall be under the terms and conditions of
   this License, without any additional terms or conditions.
   Notwithstanding the above, nothing herein shall supersede or modify
   the terms of any separate license agreement you may have executed
   with Licensor regarding such Contributions.

6. Trademarks. This License does not grant permission to use the trade
   names, trademarks, service marks, or product names of the Licensor,
   except as required for reasonable and customary use in describing the
   origin of the Work and reproducing the content of the NOTICE file.

7. Disclaimer of Warranty. Unless required by applicable law or
   agreed to in writing, Licensor provides the Work (and each
   Contributor provides its Contributions) on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
   implied, including, without limitation, any warranties or conditions
   of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
   PARTICULAR PURPOSE. You are solely responsible for determining the
   appropriateness of using or redistributing the Work and assume any
   risks associated with Your exercise of permissions under this License.

8. Limitation of Liability. In no event and under no legal theory,
   whether in tort (including negligence), contract, or otherwise,
   unless required by applicable law (such as deliberate and grossly
   negligent acts) or agreed to in writing, shall any Contributor be
   liable to You for damages, including any direct, indirect, special,
   incidental, or consequential damages of any character arising as a
   result of this License or out of the use or inability to use the
   Work (including but not limited to damages for loss of goodwill,
   work stoppage, computer failure or malfunction, or any and all
   other commercial damages or losses), even if such Contributor
   has been advised of the possibility of such damages.

9. Accepting Warranty or Additional Liability. While redistributing
   the Work or Derivative Works thereof, You may choose to offer,
   and charge a fee for, acceptance of support, warranty, indemnity,
   or other liability obligations and/or rights consistent with this
   License. However, in accepting such obligations, You may act only
   on Your own behalf and on Your sole responsibility, not on behalf
   of any other Contributor, and only if You agree to indemnify,
   defend, and hold each Contributor harmless for any liability
   incurred by, or claims asserted against, such Contributor by reason
   of your accepting any such warranty or additional liability.

END OF TERMS AND CONDITIONS
```
