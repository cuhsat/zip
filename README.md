# Go `archive/zip` with encryption support

[![Go Reference](https://pkg.go.dev/badge/github.com/hiforensics/zip.svg)](https://pkg.go.dev/github.com/hiforensics/zip)
[![Go Report Card](https://goreportcard.com/badge/github.com/hiforensics/zip?style=flat-square)](https://goreportcard.com/report/github.com/hiforensics/zip)
[![Release](https://img.shields.io/github/release/hiforensics/zip.svg?style=flat-square)](https:/

This is a fork of the `archive/zip` package from the Go standard library which adds support for both the legacy (insecure) ZIP encryption scheme and for newer AES-based encryption schemes introduced with *WinZip*.

> This forward-port is based on Go `1.24` and was done to introduce the latest bugfixes and enhancements.

## Schemes
* `zip.StandardEncryption`
* `zip.AES128Encryption`
* `zip.AES192Encryption`
* `zip.AES256Encryption`

## Acknowledgements
* [Alex Mullins](https://github.com/alexmullins/zip)
* [Yakub Kristianto](https://github.com/yeka/zip)
* [Hilko Bengen](https://github.com/hillu/go-archive-zip-crypto)

## License
Released under the [MIT License](LICENSE.md).