# org.racket_lang.Racket

This is the Racket flatpak. It includes all the executables that a Racket
distribution should have, such as `racket`, `raco` and `drracket`. After
installation, users can open a `DrRracket` instance conveniently through
DE-specific application launchers, e.g. GNOME Activities Overview or
KRunner. They can also run the executables at a command line:

1. `flatpak run org.racket_lang.Racket` calls `racket` directly. That is, if no
   extra arguments are provides, a repl gets open.
2. To run other executables, use `flatpak run
   --command=<the-executable-you-want-to-run> org.racket_lang.Racket`
