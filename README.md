# Device Spoofer Pro

Advanced iOS device spoofer tweak with per-app settings.

## Features
- Spoof device model (iPhone 7 → iPhone 16 Pro Max)
- Change iOS version
- Per-app configuration
- Bypass jailbreak detection
- Modern preferences UI

## Installation
1. Download latest .deb from [Releases](https://github.com/trungnguyenandy/DeviceSpooferPro/releases)
2. Install via Filza, Sileo, or Cydia
3. Configure in Settings app

## Building
```bash
make package
### 5. Add .gitignore:
```bash
cat > .gitignore << 'EOF'
# Theos
.theos/
packages/
obj/

# macOS
.DS_Store

# Build files
*.deb
*.dylib
*.mm

# IDE
.vscode/
.idea/

# Credentials - NEVER commit these!
*.token
.env

## Build Status
![Build](https://github.com/trungnguyenandy/DeviceSpooferPro/actions/workflows/build.yml/badge.svg)
