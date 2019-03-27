This survey was created to inform the debate over what unit ranges should use in the [Language Server Protocol](https://github.com/Microsoft/language-server-protocol).
The debate is occuring in [issue #376](https://github.com/Microsoft/language-server-protocol/issues/376).
The protocol was updated in version 3.0 to clarify that "character" indexes are in UTF-16, however since UTF-16 is controversial many implementations continue to use other units.

Please send a PR if you know what unit (UTF-8, UTF-16, Codepoints, grapheme clusters) a given implementation uses.

**unkown** should be replaced with `[**unit**](issue/relevant information)` and count should be updated.

## Implementations Count
- UTF-8: 8
- UTF-16: 10
- Codepoints: 3
- grapheme clusters: 1

## Server Count
- UTF-8: 6
- UTF-16: 7
- Codepoints: 3
- grapheme clusters: 0

## Client Count
- UTF-8: 2
- UTF-16: 3
- Codepoints: 0
- grapheme clusters: 1

note: Multiple implementations in the same repo or derived from a shared dependency are counted once.

List Dervied from [langserver.org](https://langserver.org).
If a implementation of the language server protocol is missing from this list please submit a PR here and [github.com/langserver/langserver.github.io](https://github.com/langserver/langserver.github.io).

## Language servers

- **unknown** ActionScript3 Josh Tynjala [BowlerHatLLC/vscode-nextgenas/tree/master/language-server](https://github.com/BowlerHatLLC/vscode-nextgenas/tree/master/language-server)
- **unknown** Apache Camel Camel Tooling [camel-tooling/camel-language-server](https://github.com/camel-tooling/camel-language-server)
- [**UTF-8**](https://github.com/ballerina-platform/ballerina-lang/issues/14722) Ballerina ballerina.io [ballerina-platform/ballerina-lang/tree/master/language-server](https://github.com/ballerina-platform/ballerina-lang/tree/master/language-server)
- **unknown** Bash Mads Hartmann [mads-hartmann/bash-language-server](https://github.com/mads-hartmann/bash-language-server)
- **UTF-16** C# OmniSharp [OmniSharp/omnisharp-node-client/blob/master/languageserver](https://github.com/OmniSharp/omnisharp-node-client/blob/master/languageserver)
- **unknown** C# CXuesong [CXuesong/LanguageServer.NET](https://github.com/CXuesong/LanguageServer.NET)
- [**UTF-16, UTF-8**](https://github.com/clangd/clangd/issues/3) C / C++ LLVM Team [clangd/clangd](https://github.com/clangd/clangd)
- [**UTF-8**] C / C++ Jacob Dufault [cquery-project/cquery](https://github.com/cquery-project/cquery)
- [**UTF-8**](https://github.com/Microsoft/language-server-protocol/issues/376#issuecomment-476923893) C / C++ MaskRay [MaskRay/ccls](https://github.com/MaskRay/ccls)
- **unknown** Clojure snoe [snoe/clojure-lsp](https://github.com/snoe/clojure-lsp)
- **UTF-16** CSS/LESS/SASS Microsoft [Microsoft/vscode/tree/master/extensions/css](https://github.com/Microsoft/vscode/tree/master/extensions/css)
- **unknown** CSS/LESS/SASS DeltaEvo [vscode-langservers/vscode-css-languageserver-bin](https://github.com/vscode-langservers/vscode-css-languageserver-bin)
- [**UTF-16**](https://github.com/Pure-D/serve-d/blob/master/source/served/textdocumentmanager.d) D WebFreak001 [Pure-D/serve-d](https://github.com/Pure-D/serve-d)
- [**UTF-16**](https://github.com/d-language-server/dls/blob/master/util/source/dls/util/document.d) D Laurent Tréguier [d-language-server/dls](https://github.com/d-language-server/dls)
- **unknown** Dart Nate Bosch [natebosch/dart_language_server](https://github.com/natebosch/dart_language_server)
- **unknown** Dockerfile Remy Suen [rcjsuen/dockerfile-language-server-nodejs](https://github.com/rcjsuen/dockerfile-language-server-nodejs)
- **unknown** DreamMaker SpaceManiac [SpaceManiac/SpacemanDMM/tree/master/src/langserver](https://github.com/SpaceManiac/SpacemanDMM/tree/master/src/langserver)
- **unknown** No arbitrary code execution2
- **unknown** Erlang Erlang/OTPand Vlad Dumitrescu [erlang/sourcer](https://github.com/erlang/sourcer)
- **unknown** Elixir Jake Becker [JakeBecker/elixir-ls](https://github.com/JakeBecker/elixir-ls)
- **unknown** Fortran Chris Hansen [hansec/fortran-language-server](https://github.com/hansec/fortran-language-server)
- [**UTF-8**](https://gitter.im/getgauge/chat) Gauge Gauge [getgauge/gauge](https://github.com/getgauge/gauge)
- **unknown** GLSL Sven-Hendrik Haase [svenstaro/glsl-language-server](https://github.com/svenstaro/glsl-language-server)
- [**Codepoints**](http://www.url.com) Go Sourcegraph [sourcegraph/go-langserver](https://github.com/sourcegraph/go-langserver)
- **unknown** No arbitrary code execution2
- **unknown** Files extension3
- **unknown** SymbolDescriptor extension4
- **unknown** GraphQL Facebook GraphQL [graphql/graphql-language-service](https://github.com/graphql/graphql-language-service)
- **unknown** Groovy Palantir [palantir/groovy-language-server](https://github.com/palantir/groovy-language-server)
- [**Codepoints, soon UTF-16**](https://github.com/alanz/haskell-lsp/pull/70) Haskell Alan Zimmerman [haskell/haskell-ide-engine](https://github.com/haskell/haskell-ide-engine)
- **unknown** Haxe Haxe Foundation [vshaxe/haxe-language-server](https://github.com/vshaxe/haxe-language-server)
- **UTF-16** HTML Microsoft [Microsoft/vscode/tree/master/extensions/html](https://github.com/Microsoft/vscode/tree/master/extensions/html)
- **unknown** Imandra Protocol Language Aesthetic Integration https://[AestheticIntegration/ipl-vscode](https://github.com/AestheticIntegration/ipl-vscode)
- **UTF-16** Java Eclipse Foundation, Red Hat, Microsoft [eclipse/eclipse.jdt.ls](https://github.com/eclipse/eclipse.jdt.ls)
- **unknown** Java georgewfraser [georgewfraser/vscode-javac](https://github.com/georgewfraser/vscode-javac)
- **unknown** JavaScript Sourcegraph [sourcegraph/javascript-typescript-langserver](https://github.com/sourcegraph/javascript-typescript-langserver)
- **unknown** No arbitrary code execution2
- **unknown** Files extension3
- **unknown** SymbolDescriptor extension4
- **unknown** JavaScript (Flow) Flowtype [flowtype/flow-for-vscode](https://github.com/flowtype/flow-for-vscode)
- **UTF-16** JSON Microsoft [Microsoft/vscode/tree/master/extensions/json](https://github.com/Microsoft/vscode/tree/master/extensions/json)
- **unknown** JS + PHP + Python SonarSource [SonarSource/sonarlint-core](https://github.com/SonarSource/sonarlint-core)
- **unknown** Julia David Anthoff [JuliaEditorSupport/LanguageServer.jl](https://github.com/JuliaEditorSupport/LanguageServer.jl)
- **unknown** Kotlin fwcd [fwcd/KotlinLanguageServer](https://github.com/fwcd/KotlinLanguageServer)
- **unknown** LaTeX Eric Förster [efoerster/texlab](https://github.com/efoerster/texlab)
- **unknown** Lua Alloyed [Alloyed/lua-lsp](https://github.com/Alloyed/lua-lsp)
- **unknown** Lua tangzx [EmmyLua/EmmyLua-LanguageServer](https://github.com/EmmyLua/EmmyLua-LanguageServer)
- **unknown** OCaml + ReasonML Darin Morrison [freebroccolo/ocaml-language-server](https://github.com/freebroccolo/ocaml-language-server)
- **unknown** PHP Felix Becker [felixfbecker/php-language-server](https://github.com/felixfbecker/php-language-server)
- **unknown** No arbitrary code execution2
- **unknown** Files extension3
- **unknown** SymbolDescriptor extension4
- **unknown** PHP Tom Gerrits gitlab.com/Serenata/Serenata
- **unknown** No arbitrary code execution2
- **unknown** Has custom extensions
- **unknown** PHP Hvy Industries [HvyIndustries/crane/blob/master/server](https://github.com/HvyIndustries/crane/blob/master/server)
- **unknown** PureScript Nicholas Wolverson [nwolverson/purescript-language-server](https://github.com/nwolverson/purescript-language-server)
- **unknown** Python Microsoft [Microsoft/python-language-server](https://github.com/Microsoft/python-language-server)
- **unknown** Python Sourcegraph https://[sourcegraph/python-langserver](https://github.com/sourcegraph/python-langserver)
- **unknown** Automatic dependency management1
- **unknown** No arbitrary code execution2
- **unknown** Files extension3
- **unknown** SymbolDescriptor extension4
- **unknown** Python Palantir [palantir/python-language-server](https://github.com/palantir/python-language-server)
- **unknown** R REditorSupport [REditorSupport/languageserver](https://github.com/REditorSupport/languageserver)
- **unknown** Ruby Fred Snyder [castwide/solargraph](https://github.com/castwide/solargraph)
- [**Codepoints**](https://github.com/rust-lang/rls/issues/1113) Rust Nick Cameron and the Rust community [rust-lang-nursery/rls](https://github.com/rust-lang-nursery/rls)
- [**UTF-16**](https://www.reddit.com/r/programming/comments/b5xoem/lsp_character_index_unit_survey/ejh8e3k) Aleksey Kladov [rust-analyzer](https://github.com/rust-analyzer/rust-analyzer)
- **unknown** Automatic dependency management1
- **unknown** Scala Iulian Dragos [dragos/dragos-vscode-scala](https://github.com/dragos/dragos-vscode-scala)
- **unknown** Scala Scalameta [scalameta/metals](https://github.com/scalameta/metals)
- **unknown** SPARQL Stardog Union [stardog-union/stardog-language-servers/tree/master/packages/sparql-language-server](https://github.com/stardog-union/stardog-language-servers/tree/master/packages/sparql-language-server)
- **unknown** No arbitrary code execution2
- [**UTF-16**](https://bugs.swift.org/browse/SR-9311) Swift & C-family Apple Inc [apple/sourcekit-lsp](https://github.com/apple/sourcekit-lsp)
- **unknown** Turtle Stardog Union [stardog-union/stardog-language-servers/tree/master/packages/turtle-language-server](https://github.com/stardog-union/stardog-language-servers/tree/master/packages/turtle-language-server)
- **unknown** No arbitrary code execution2
- **unknown** TypeScript Sourcegraph [sourcegraph/javascript-typescript-langserver](https://github.com/sourcegraph/javascript-typescript-langserver)
- **unknown** Automatic dependency management1
- **unknown** No arbitrary code execution2
- **unknown** Files extension3
- **unknown** SymbolDescriptor extension4
- **unknown** XML IBM [microclimate-devops/xml-language-server](https://github.com/microclimate-devops/xml-language-server)
- **unknown** XML Red Hat and Angelo ZERR [angelozerr/lsp4xml](https://github.com/angelozerr/lsp4xml) XML Schema validation/completion, Foldings, Rename element, Formatting, Document Link, Extensible to add custom completion, hover, etc
- **unknown** YAML Red Hat [redhat-developer/yaml-language-server](https://github.com/redhat-developer/yaml-language-server)
- **unknown** YANG TypeFox [yang-tools/yang-lsp](https://github.com/yang-tools/yang-lsp)
- **unknown** Xtext (Any Language) TypeFox [eclipse/xtext-core](https://github.com/eclipse/xtext-core)

### Work in Progress

- [**UTF-8**](https://github.com/crystal-lang-tools/scry/issues/154) Crystal Ryan L. Bell and contributors [crystal-lang-tools/scry](https://github.com/crystal-lang-tools/scry)
- **unknown** Elm Elm Tooling [elm-tooling/elm-language-server](https://github.com/elm-tooling/elm-language-server)
- **unknown** reStructuredText Lex Li https://[lextm/restructuredtext-antlr](https://github.com/lextm/restructuredtext-antlr)
- **unknown** Ruby Fumiaki MATSUSHIMA [mtsmfm/language_server-ruby](https://github.com/mtsmfm/language_server-ruby)
- **unknown** TypeCobol TypeCobol Team TypeCobol Language Server

# LSP clients
- **unknown** Eclipse LSP4E Eclipse git.eclipse.org/c/lsp4e/lsp4e.git
- **unknown** Eclipse Che Eclipse, Codenvy [eclipse/che/](https://github.com/eclipse/che/)
- **unknown** IntelliJ / JetBrains IDEs IntelliJ LSP Community [intellij-lsp/intellij-lsp-plugin](https://github.com/intellij-lsp/intellij-lsp-plugin)
- [**grapheme clusters**](http://github.com/ul/kak-lsp/issues/98) Kakoune Ruslan Prokopchuk [ul/kak-lsp](https://github.com/ul/kak-lsp)
- **unknown** Moonshine IDE Prominic [prominic/Moonshine-IDE](https://github.com/prominic/Moonshine-IDE)
- **UTF-16** VSCode Microsoft [Microsoft/VSCode](https://github.com/Microsoft/VSCode)
- **unknown** vim/neovim Nate Bosch [natebosch/vim-lsc](https://github.com/natebosch/vim-lsc)
- [UTF-8; soon maybe UTF-16](https://github.com/prabirshrestha/vim-lsp/pull/284) vim/neovim Prabir Shrestha [prabirshrestha/vim-lsp](https://github.com/prabirshrestha/vim-lsp)
- [UTF-8](https://github.com/autozimu/LanguageClient-neovim/issues/127) vim/neovim Junfeng Li [autozimu/LanguageClient-neovim](https://github.com/autozimu/LanguageClient-neovim)
- **unknown** vim/neovim w0rp [w0rp/ale](https://github.com/w0rp/ale)
- **UTF-16** vim/neovim Qiming zhao [neoclide/coc.nvim](https://github.com/neoclide/coc.nvim)
- **unknown** Sublime Text 3 Tom van Ommeren [tomv564/LSP](https://github.com/tomv564/LSP)
- **UTF-16** MS Monaco Editor TypeFox [TypeFox/monaco-languageclient](https://github.com/TypeFox/monaco-languageclient)
- [**UTF-16**](https://github.com/Valloric/ycmd/pull/857) ycmd ycmd authors [Valloric/ycmd](https://github.com/Valloric/ycmd)

### Work in progress

- **unknown** Acme Fazlul Shahriar https://[fhs/acme-lsp](https://github.com/fhs/acme-lsp)
- **unknown** Atom GitHub [atom/atom-languageclient](https://github.com/atom/atom-languageclient)
- **unknown** CodeMirror Wylie Conlon [wylieconlon/lsp-editor-adapter](https://github.com/wylieconlon/lsp-editor-adapter)
- **unknown** Emacs Corey Richardson [sourcegraph/emacs-lsp](https://github.com/sourcegraph/emacs-lsp)
- **unknown** Emacs Vibhav Pant [emacs-lsp/lsp-mode](https://github.com/emacs-lsp/lsp-mode)
- **unknown** Emacs João Távora [joaotavora/eglot](https://github.com/joaotavora/eglot)
- **unknown** Theia Theia IDE [theia-ide/theia](https://github.com/theia-ide/theia)
- **unknown** neovim TJ DeVries [tjdevries/nvim-langserver-shim](https://github.com/tjdevries/nvim-langserver-shim)
- **unknown** Spyder IDE Spyder IDE Dev Team [spyder-ide/spyder](https://github.com/spyder-ide/spyder)
- **unknown** Oni Oni [onivim/oni](https://github.com/onivim/oni)
- **unknown** Qt Creator Qt Project code.qt.io/cgit/qt-creator
