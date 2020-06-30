# e-portfolio-rust

## Requirements
- Visual Studio Code (https://code.visualstudio.com/)
- Rust SDK (https://www.rust-lang.org/)

## Project Setup
Create a new project by invoking the  following command
```
$ cargo new guessing_game
```

A new project should now be created.
Open this folder in command prompt.
```
$ cd guessing_game
```

Now edit `lib/main.rs` and paste in the provided code from `main.rs`

This still isnt able to run, since theres an additional dependency that has to be installed.

Add the following line in `Cargo.toml`
```
[dependencies]
rand = "0.7.3"
```

## Building & Running
To download dependencies and run the project, invoke cargo again.
```
$ cargo run
```

The project is now being compiled and run afterwards
