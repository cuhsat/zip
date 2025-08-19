# Zip with Encryption Support

[![Go Reference](https://pkg.go.dev/badge/github.com/cuhsat/zip.svg)](https://pkg.go.dev/github.com/cuhsat/zip)
[![Go Report Card](https://goreportcard.com/badge/github.com/cuhsat/zip?style=flat-square)](https://goreportcard.com/report/github.com/cuhsat/zip)
[![Release](https://img.shields.io/github/release/cuhsat/zip.svg?style=flat-square)](https://github.com/cuhsat/zip/releases/latest)

This is a fork of the `archive/zip` package from the Go standard library which adds support for both the legacy (insecure) ZIP encryption scheme and for newer AES-based encryption schemes introduced with WinZip.

> This forward-port is based on Go `1.24.6` and was done to introduce the latest bugfixes and enhancements.

## Encryption Schemes
* `Standard`
* `AES128`
* `AES192`
* `AES256`

## Acknowledgements
* [Alex Mullins](https://github.com/alexmullins/zip)
* [Yakub Kristianto](https://github.com/yeka/zip)
* [Hilko Bengen](https://github.com/hillu/go-archive-zip-crypto)

## License
Released under the [BSD License](LICENSE.md).