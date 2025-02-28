# CoqPlugin-Template

## Introduction

This repository is the template of Coq plugin. The project is inspired by the [Coq plugin tutorial](https://github.com/coq/coq/tree/master/doc/plugin_tutorial).

## Build Requirements

`Ocaml` : `4.14.1`

`Coq` : `8.19.1`


### Build and install procedure

```bash
make
make install
```



### For VSCode OCaml Platform plugin

If you want to see types in `vscode` by [VSCode OCaml Platform](https://marketplace.visualstudio.com/items?itemName=ocamllabs.ocaml-platform) , you can build project by `dune`

```bash
eval $(opam env)
dune build
code .
```

