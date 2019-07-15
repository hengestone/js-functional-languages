# js-functional-languages
Looking for a lightweight functional language to help create a pleasant workflow for creating front-end applications. Extra points if it can easily be used with an Erlang back-end.
 
### Notes
- The Haskell family of languages tend to have good REPL and IDE support, but tend to not emphasize runtime or compile time performance AFAICS.
- WebAssembly output/interop also counts.
 - Does it e.g. make it easy to create apps with S/Surplus? Indented syntax to create HTML elements a al SLIM/HAML/Jade/Pug etc. is nice.
 - Enforcing JSX is a throwback to HTML. Just say no.

## The usual suspects
- ReasonML [https://reasonml.github.io/] Fast compiler, OCaml front-end. Bucklescript back-end.
- PureScript [http://www.purescript.org/] Slow-ish compiler, Haskell-lite, dead-code elimination makes for small output. Boilerplate+. Erlang backend. Active community. Good IDE, REPL support.
- Elm [http://elm-lang.org/] Slow compiler, Haskel-lite--, brings it's own standard library. Boilerplate++

## General purpose
- OCaml [https://ocaml.org/] compiles to js via Bucklescript and js_of_ocaml
- Haskell [https://www.haskell.org/] we will all be smart enough to end up with Haskell eventually :)
- Fay [https://github.com/faylang/fay] Proper Haskell subset, simple js interop.
- Idris [https://www.idris-lang.org/] Haskell family, with explixit support for multiple backends.
- Fable [http://fable.io/] So cool, until the whole Microsoft ecosystem lands on your foot with a reverberating thud...

## Erlang
 - Jarlang [https://github.com/Vereis/jarlang] School project to compile Erlang to js. Don't know if it will continue to be worked on?
 - Shen [https://github.com/synrc/shen] Compiles Erlang to straightforward js. Part of the N2O framework. Code is... not very clean, not touched in 4 years.
 - Luvviescript [https://github.com/hypernumbers/LuvvieScript] Abandoned?
 
## The Zoo
  - Caffeinescript [http://CaffeineScript.com] Looks great, but does it require ArtSuite?
  - Pyret [https://www.pyret.org/] Teaching language - not clear if it can be used outside of that context.
  - Jen [https://github.com/jtorre39/jen] Type-inferred, python-like syntax, Nice.
  - Eff [https://github.com/matijapretnar/eff] OCaml extended for effects
  - Grain [https://grain-lang.org/ OCamlish compiles to WASM. Nice :)
  - GorillaScript [http://ckknight.github.io/gorillascript/] On life support, but nice.
  - Roy [https://github.com/puffnfresh/roy] So cool, but abandoned.
  - Forest [https://github.com/forest-lang/forest-compiler] Compiles to WASM.
  - Kitchen-Ant [https://github.com/GEWalters/Kitchen-Ant] In flux
  - Cream & Sugar [https://github.com/jgnewman/cream-and-sugar] New
  - Smooth [http://bramblex.github.io/Smooth/] In flux, but interesting async contructs.
  - Oxyde [https://github.com/skyne98/oxyde] It has a name ;-)
  - Royalscript [https://github.com/jweinst1/Royalscript] I can haz lisp.
  - JCaml [https://j-woodlee.github.io/JCaml/] Nirvana, with spit?!
  
## Java ecosystem
   - Scala [https://www.scala-js.org/] Thud... foot... Oracle. But nice :)
   - Clojure [https://github.com/clojure/clojurescript] Ditto. Plus Lisp... Erlang back-end though.
   - Kotlin [https://kotlinlang.org/docs/reference/js-interop.html] Hello World takes 2s to compile. Facepalm.
 
   
  
