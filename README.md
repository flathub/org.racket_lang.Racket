# org.racket_lang.Racket

This is the Racket flatpak. It includes all the executables that a Racket
distribution should have, such as `racket`, `raco` and `drracket`. After
installation, users can open a `DrRracket` instance conveniently through
DE-specific application launchers, e.g. GNOME Activities Overview or
KRunner. 

To run any command at the command line, use
`--command=<the-executable-you-want-to-run>`. For example, you can open a REPL
`flatpak run --command=racket org.racket_lang.Racket`. Or you can use `flatpak
run --command=raco org.racket_lang.Racket` to run `raco`.
