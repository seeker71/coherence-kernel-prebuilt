# coherence-kernel-prebuilt

Disposable warm packs for [coherence-kernel](https://github.com/seeker71/coherence-kernel): compiled lowerings and images keyed by the kernel's seed digest and OS-arch, so a fresh clone skips its first build.
Objects are content-addressed and zstd-compressed; `observe/prebuilt-run.bml fetch` verifies every object against a manifest hash pinned in the source repo's `prebuilt/index.txt`. History here may be rewritten at any time; nothing in it is source.
