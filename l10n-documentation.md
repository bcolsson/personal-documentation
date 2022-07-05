# mozilla l10n documentation

## setting up local environment

1. [Install Rust/cargo](https://www.rust-lang.org/tools/install)
or via [Homebrew](https://formulae.brew.sh/formula/rust)
2. Install mdbook and mdbook-toc
```
$ cargo install mdbook
$ cargo install --vers "^0.3" mdbook-toc
```
3. Install [node/npm](https://formulae.brew.sh/formula/node)
4. Fork [repo](https://github.com/mozilla-l10n/documentation/)
5. Clone fork locally
6. Build preview pages locally
```
$ cargo install --vers "^0.3" mdbook-toc
$ mdbook serve
```
7. Test for formatting
```
$ npm install
$ npm test
```
