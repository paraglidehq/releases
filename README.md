# Beyond Releases

Binary releases for Beyond tools.

## CLI

### Quick Install

**macOS / Linux:**

```bash
curl -fsSL https://beyond.dev/install.sh | bash
```

**Windows (PowerShell):**

```powershell
irm beyond.dev/install.ps1 | iex
```

### Homebrew (macOS/Linux)

```bash
brew install beyondoss/tap/beyond
```

### Manual Download

Download the latest release for your platform from the [releases page](https://github.com/beyondoss/releases/releases).

| Platform | Architecture | Download |
|----------|--------------|----------|
| macOS | Apple Silicon | `beyond_darwin_arm64.tar.gz` |
| macOS | Intel | `beyond_darwin_amd64.tar.gz` |
| Linux | x64 | `beyond_linux_amd64.tar.gz` |
| Linux | ARM64 | `beyond_linux_arm64.tar.gz` |
| Windows | x64 | `beyond_windows_amd64.zip` |
| Windows | ARM64 | `beyond_windows_arm64.zip` |

### Verify Checksums

Each release includes a `checksums.txt` file with SHA-256 hashes.
