# Download Manager

## Why
Because I don't like using a web browser to download files(s)

## Installation

Requirements

- Have rust installed

1. Clone the repo

```bash
$ git clone https://gitea.skynode.me/nerdthatnoonelikes/download-manager.git
```

2. Build it 

```bash
$ cd download-manager
$ cargo build
# You probably have to use sudo
$ cp target/debug/download-manager /usr/bin
```

3. Start downloading files, here is an example of how to do so

```bash
$ cd Downloads/
$ download-manager https://www.rustacean.net/assets/rustacean-flat-happy.png ferris.png
```
