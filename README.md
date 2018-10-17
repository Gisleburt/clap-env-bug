Clap Env Bug Demo
=================

Possible bug with detecting environment variables

Usage
-----

```
$ cargo run
not present

$ cargo run -- --test
present

$ TEST=test cargo run
not present

$ TEST=test target/debug/clap-bug
not present
```
