# e24z Homebrew Tap

Homebrew tap for Needle.

Needle is currently published here as a pre-release HEAD formula:

```bash
brew install --HEAD e24z/tap/needle
```

The formula runs `needle setup --from-homebrew` after install. If setup is
deferred because Homebrew is non-interactive, resume with:

```bash
needle setup
```

Stable install without `--HEAD` will be enabled after Needle has a tagged
release tarball and SHA256.
