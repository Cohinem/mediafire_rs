
<p align="center" >
  <img src="assets/logo.svg" alt="logo">
  <strong>
    Async rust rewrite of
    <a href="https://github.com/nickoehler/mediafire_bulk_downloader">
      mediafire_bulk_downloader
    </a>
  </strong>
</p>

## Preview

<img src="assets/demo.gif" alt="mediafire_rs">


## Installation

```bash
cargo install mediafire_rs
```

## Usage

```bash
Usage: mdrs.exe [OPTIONS] [URL]

Arguments:
  [URL]  Folder or file to download (can be comma-separated)

Options:
  -l, --links <FILE>     Read Mediafire links from a text file (one per line)
  -o, --output <OUTPUT>  Output directory [default: .]
  -m, --max <MAX>        Maximum number of concurrent downloads [default: 10]
  -t, --tries <MAX>      Maximum number of tries to repeat for every download [default: 1]
  -p, --proxy <FILE>     Speficy a file to read proxies from
      --proxy-download   Downloads files through proxies, the default is to use proxies for the API only
  -h, --help             Print help
  -V, --version          Print version
```

For building from source, please refer to the [BUILDING.md](BUILDING.md) file for detailed instructions.
