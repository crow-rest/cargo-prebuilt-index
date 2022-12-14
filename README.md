# cargo-prebuilt-index

Some crate.io binaries built for different platforms.

This is the index, if you are looking for the cli tool it is [here](https://github.com/crow-rest/cargo-prebuilt).

Request a crate to be added [here](https://github.com/crow-rest/cargo-prebuilt-index/issues/new?assignees=&labels=add-crate%2C+under-consideration&template=request-crate.md&title=).

<sub>Only the latest versions of crates are guaranteed to be in the index.</sub>

## Platforms Supported (Targets)

All prebuilt crates are required support these targets:
- x86_64-unknown-linux-gnu
- x86_64-unknown-linux-musl
- x86_64-apple-darwin
- x86_64-pc-windows-msvc
- aarch64-apple-darwin
- aarch64-unknown-linux-gnu
- aarch64-unknown-linux-musl

Prebuilt crates optionally support these targets:

(64-bit)
- x86_64-unknown-freebsd
- x86_64-unknown-netbsd
- x86_64-unknown-illumos
- x86_64-sun-solaris
- riscv64gc-unknown-linux-gnu
- powerpc64-unknown-linux-gnu
- powerpc64le-unknown-linux-gnu
- s390x-unknown-linux-gnu
- mips64-unknown-linux-gnuabi64
- mips64-unknown-linux-muslabi64
- mips64el-unknown-linux-gnuabi64
- mips64el-unknown-linux-muslabi64

(32-bit)
- i686-pc-windows-msvc
- i686-unknown-linux-gnu
- i686-unknown-linux-musl
- i686-unknown-freebsd
- armv7-unknown-linux-gnueabihf
- armv7-unknown-linux-musleabihf
- powerpc-unknown-linux-gnu
- mips-unknown-linux-gnu
- mips-unknown-linux-musl
- mipsel-unknown-linux-gnu
- mipsel-unknown-linux-musl

## Crates

- [bacon](https://github.com/Canop/bacon)
- [cargo-asm](https://github.com/gnzlbg/cargo-asm)
- [cargo-audit](https://github.com/rustsec/rustsec/tree/main/cargo-audit)
- [cargo-auditable](https://github.com/rust-secure-code/cargo-auditable)
- [cargo-benchcmp](https://github.com/BurntSushi/cargo-benchcmp)
- [cargo-bloat](https://github.com/RazrFalcon/cargo-bloat)
- [cargo-build-deps](https://github.com/nacardin/cargo-build-deps)
- [cargo-cache](https://github.com/matthiaskrgr/cargo-cache)
- [cargo-clone](https://github.com/JanLikar/cargo-clone)
- [cargo-deadlinks](https://github.com/deadlinks/cargo-deadlinks)
- [cargo-deb](https://github.com/kornelski/cargo-deb)
- [cargo-deny](https://github.com/EmbarkStudios/cargo-deny)
- [cargo-depgraph](https://git.sr.ht/~jplatte/cargo-depgraph)
- [cargo-diet](https://github.com/the-lean-crate/cargo-diet)
- [cargo-edit](https://github.com/killercup/cargo-edit)
- [cargo-generate](https://github.com/cargo-generate/cargo-generate)
- [cargo-hack](https://github.com/taiki-e/cargo-hack)
- [cargo-make](https://github.com/sagiegurari/cargo-make)
- [cargo-mpirun](https://github.com/AndrewGaspar/cargo-mpirun)
- [cargo-nextest](https://github.com/nextest-rs/nextest)
- [cargo-outdated](https://github.com/kbknapp/cargo-outdated)
- [cargo-prebuilt](https://github.com/crow-rest/cargo-prebuilt)
- [cargo-show-asm](https://github.com/pacak/cargo-show-asm)
- [cargo-update](https://github.com/nabijaczleweli/cargo-update)
- [cargo-watch](https://github.com/watchexec/cargo-watch)
- [cocogitto](https://github.com/cocogitto/cocogitto)
- [grcov](https://github.com/mozilla/grcov)
- [jql](https://github.com/yamafaktory/jql)
- [just](https://github.com/casey/just)
- [sccache](https://github.com/mozilla/sccache)
- [tauri-cli](https://github.com/tauri-apps/tauri)
- [trunk](https://github.com/thedodd/trunk)
- [wasm-pack](https://github.com/rustwasm/wasm-pack)
- [wasmtime-cli](https://github.com/bytecodealliance/wasmtime)

## "API"

- Index holds the latest version built. (https://github.com/crow-rest/cargo-prebuilt-index/releases/download/stable-index/CRATE)
- Builds are put under a prerelease named CRATE-VERSION.
- The binary is in TARGET.tar.gz file and the hash is in TARGET.sha256 file.
