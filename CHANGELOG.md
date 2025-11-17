# Changelog

All notable changes to Leaktor will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2025-11-17

### 🎉 Initial Release

First public release of Leaktor - a blazingly fast secrets scanner with validation capabilities!

### Features

- **40+ Secret Patterns** - AWS, GCP, Azure, GitHub, GitLab, Stripe, databases, private keys, and more
- **Git History Scanning** - Scan entire repository history for exposed secrets
- **Live Validation** - Verify if AWS keys and GitHub tokens are active
- **Multiple Output Formats** - Console, JSON, SARIF, HTML
- **Smart Detection** - Entropy analysis, context-aware filtering, confidence scoring
- **CI/CD Ready** - GitHub Actions workflows, SARIF output, fail-on-found option
- **Pre-commit Hooks** - Prevent secrets from being committed
- **Flexible Configuration** - YAML/TOML config, .leaktorignore, inline ignoring
- **Parallel Processing** - Fast multi-threaded scanning
- **Cross-platform** - Linux, macOS, Windows support

### Technical Details

- Built with Rust 2024 Edition
- Async validation with Tokio
- Pattern matching with Regex
- Git integration with git2
- Parallel processing with Rayon

[0.1.0]: https://github.com/reschjonas/leaktor/releases/tag/v0.1.0
