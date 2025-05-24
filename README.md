# miniature-couscous
gba develop with rust

## libraly

* agb https://agbrs.dev/

## how to build template

1. install rust
2. install git
3. install gba-fix
   * `cargo install agb-gbafix`
4. clone template
   * `git clone https://github.com/agbrs/template.git`
5. build
   * `cd template && cargo build --release`
6. convert to gba file
   * `agb-gbafix {{put binary path}} -o agb_template.gba`
7. run game
   * `cargo run --release`
  
WHen you create any game, edit template.
