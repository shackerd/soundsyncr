# SoundSyncr (WIP)

Yet another volume management tool.

## Dev dependencies

just

``` bash
cargo install just
```

alsa (libasound2-dev)

``` bash
sudo apt install libasound2-dev
```

### Dev documentation

log package : https://docs.rs/log/latest/log/

cpal package : https://docs.rs/cpal/0.15.2/cpal/

clap package : https://docs.rs/clap/4.3.9/clap/

serde package : https://docs.rs/serde/latest/serde/

midir package : https://docs.rs/midir/0.9.1/midir/

## Running project

``` bash
just build
just run
```