# homebrew-apple
Apple Silicon Homebrew Formulas

`qemu` (git hash: 5b7f5586d182b0cafb1f8d558992a14763e2953e)
* with Apple Silicon patch (https://github.com/stefannilsson/homebrew-apple/blob/0333221a2218abb9dc617406e9bba1561b0255ed/qemu.rb#L108) to work around the error: `qemu_mprotect__osdep: mprotect failed: Permission denied`

# Download a working QEMU for Apple Silicon / M1 (Mac Mini, etc) by simply:
```
brew install stefannilsson/apple/qemu
```
