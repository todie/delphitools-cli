# Changelog

All notable changes to delphitools-cli are documented here. This project follows
[Semantic Versioning](https://semver.org/).

## [0.2.0] - 2026-05-31

### Added
- **Zine imposer — accordion fold.** `delphi zine --fold accordion` lays pages
  out as a single-sheet concertina strip. Choose the panel count with
  `--panels 4|6|8`, print both sides with `--double`, or use `--split` to stack
  two identical copies per sheet (halving panel height) for two-up cutting.
- **Linux packaging templates.** An AUR `PKGBUILD` (`delphitools-cli-bin`) and a
  Fedora/COPR RPM spec for distributing the prebuilt release binaries.

## [0.1.0] - 2026-05-24

### Added
- Initial release: ~40 offline design and publishing tools under the `delphi`
  command (also installed as `delphitools` and `dt`) — colour conversion and
  palettes, image crop/convert/trace/background-removal, PDF imposition and
  preflight, typographic calculators, regex testing, Unicode glyph lookup,
  QR/barcode generation, calculators, Shavian transliteration, and more.
- macOS and Linux binaries published via cargo-dist, with a shell installer and
  a Homebrew formula.

[0.2.0]: https://github.com/1612elphi/delphitools-cli/releases/tag/v0.2.0
[0.1.0]: https://github.com/1612elphi/delphitools-cli/releases/tag/v0.1.0
