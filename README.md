# Useful commands

- rustc main.rs

## If using cargo

- cargo new (project_name) [--vcs=git to override the current git folder struct]
- cargo build
- cargo run (development only builds and runs the exe -- faster)
- cargo check (compiles without creating exe -- skips build process)
- cargo build --release

## Notes

- By default, the variables are immutable. If we want the variables to be mutable -- explicitly mention 'mut' (same for references)
