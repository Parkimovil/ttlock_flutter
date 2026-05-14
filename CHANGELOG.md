##[3.0.2]-[2024-01-16]
*Fix 2 issues

##[3.0.3]-[2024-01-24]
*Fix erro code issues

##[3.0.3]-[2024-01-24]
*Fix android bug

##[0.3.10]-[2026-05-14]
*Android 15+ / 16 KB page-size support
- Pinned `com.ttlock:ttlock:3.5.6` (3.5.5+ ships libLockCore.so with p_align=0x4000 on arm64-v8a and x86_64).
- Bumped plugin `compileSdkVersion` 31 → 35 and `agp_version` 4.1.2 → 7.4.2.
- Added `packagingOptions { jniLibs { useLegacyPackaging = false } }` so consuming apps keep .so files uncompressed and page-aligned.
- Bumped plugin `minSdkVersion` 18 → 21 (AGP 7+ deprecation).
- Removed dead `jcenter()` repository.
- Bumped example `compileSdkVersion`/`targetSdkVersion` to 35.
