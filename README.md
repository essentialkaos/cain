<p align="center"><a href="#readme"><img src="https://gh.kaos.st/cain.svg"/></a></p>

<p align="center">
  <a href="https://github.com/essentialkaos/cain/actions"><img src="https://github.com/essentialkaos/cain/workflows/CI/badge.svg" alt="GitHub Actions Status" /></a>
  <a href="#license"><img src="https://gh.kaos.st/apache2.svg"></a>
</p>

<p align="center"><a href="#installation">Installation</a> • <a href="#usage">Usage</a> • <a href="#build-status">Build Status</a> • <a href="#license">License</a></p>

<br/>

`cain` is a simple tool for GitHub cache invalidation.

### Installation

#### From GitHub repository

```bash
curl -fL# -o cain https://kaos.sh/cain/cain
chmod +x cain
sudo mv cain /usr/bin/
```

Also, you can use the latest version of utility without installation:

```bash
bash <(curl -fsSL https://kaos.sh/cain/cain) # pass options here
```

### Usage

```
Usage: cain {options} url

Options

  --no-color, -nc    Disable colors in output
  --help, -h         Show this help message
  --version, -v      Show information about version

Examples

  cain https://camo.githubusercontent.com/abcdabcbd1abcd528abcd18acdb1ba31bad
  Invalidate cache for one image

  cain https://github.com/owner/repo/blob/master/README.md
  Invalidate all images on given page

```

### Build Status

| Branch | Status |
|--------|--------|
| `master` | [![CI](https://github.com/essentialkaos/cain/workflows/CI/badge.svg?branch=master)](https://github.com/essentialkaos/cain/actions) |
| `develop` | [![CI](https://github.com/essentialkaos/cain/workflows/CI/badge.svg?branch=develop)](https://github.com/essentialkaos/cain/actions) |

### License

[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)

<p align="center"><a href="https://essentialkaos.com"><img src="https://gh.kaos.st/ekgh.svg"/></a></p>
