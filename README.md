rust-stem
=========

Porter's stemmer for rust.

This is a clone of Do Nhat Minh's project, for use specifically with my [natural language processing library](https://github.com/cjqed/rs-natural).

## How to use ##
1. Clone and compile the code
   ```bash
   git clone https://github.com/mrordinaire/rust-stem.git
   cd rust-stem
   make
   ```

2. Example code
   ```rust
   use stem::*;
   let word = "pencils";
   let s = stem::get(s); // stem == "pencil"
   ```

3. Compile
   ```base
   rustc example.rs -L /path/to/folder/containing/libstem*.so
   ```
