# {{project-name}}

A template project for the Raspberry Pi Pico using embassy-rs.

## Configure the computer for building the project
 - `rustup install nightly`
 - `rustup target add thumbv6m-none-eabi`
 - `cargo install probe-rs --features cli`
 - `cargo install elf2uf2-rs`

## Run the application with cargo
 - Connect the application to a debug probe.
 - `cargo run`

## Generate .uf2 file
 - `elf2uf2-rs.exe .\target\thumbv6m-none-eabi\debug\ledmoji-firmware-unicorn ledmoji-firmware-unicorn.uf2`
