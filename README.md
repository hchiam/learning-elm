# Learning [Elm](https://elm-lang.org/)

Just one of the things I'm learning. https://github.com/hchiam/learning

Simplicity. Tooling. Compiles to JavaScript.

You can try it out on a small part of an existing project; have it control an HTML node.

It's a [functional programming](https://en.wiktionary.org/wiki/functional_programming) language.

https://guide.elm-lang.org

Install `elm`: https://guide.elm-lang.org/install/elm.html

```sh
elm --help # reminders
elm init # creates elm.json and src folder
elm reactor # runs http://localhost:8000
elm make src/Main.elm # creates HTML file
elm make src/Main.elm --optimize --output=elm.js # creates JS file
elm install elm/http # adds dependency to elm.json
elm repl # to write code within the CLI (leave it with Ctrl+D or :exit)
```
