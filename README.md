# Alpine.js Language Server

> [!WARNING] Please note that this project is a hobby project and still in
> development. It’s currently not functional nor ready for use.

`alpinejs-language-server` is a language server for
[Alpine.js](https://alpinejs.dev) that implements the
[Language Server Protocol (LSP)](https://microsoft.github.io/language-server-protocol/).

> [!NOTE] In addition to hopefully being useful once finished, I want to use
> this project for learning. That’s why I probably won’t accept contributions
> before I have implemented basic language server functionalities.

## Features

As the project is still heavily in development, this is more of a checklist of
different features that a language server can implement. As
[Alpine.js](https://alpinejs.dev) is lightweight, the language server might not
implement all of the features. In addition to that, the first goal of the
language server is to provide support for the Alpine.js attributes, after which
support for the JavaScript in the attribute values will be added.

The
[LSP Specification](https://microsoft.github.io/language-server-protocol/specifications/lsp/3.17/specification/)
contains all of the possible features.

Below is the list of possible language server features and whether they are
implemented. Please note that the list may not be exhaustive.

### Language Features

- [ ] `textDocument/declaration`
- [ ] `textDocument/definition`
- [ ] `textDocument/typeDefinition`
- [ ] `textDocument/implementation`
- [ ] `textDocument/references`
- [ ] `textDocument/prepareCallHierarchy`
- [ ] `callHierarchy/incomingCalls`
- [ ] `callHierarchy/outgoingCalls`
- [ ] `textDocument/prepareTypeHierarchy`
- [ ] `typeHierarchy/supertypes`
- [ ] `typeHierarchy/subtypes`
- [ ] `textDocument/documentHighlight`
- [ ] `textDocument/documentLink`
- [ ] `documentLink/resolve`
- [ ] `textDocument/hover`
- [ ] `textDocument/codeLens`
- [ ] `codeLens/resolve`
- [ ] `workspace/codeLens/refresh`
- [ ] `textDocument/foldingRange`
- [ ] `textDocument/selectionRange`
- [ ] `textDocument/documentSymbol`
- [ ] `textDocument/semanticTokens`
- [ ] `textDocument/inlayHint`
- [ ] `inlayHint/resolve`
- [ ] `workspace/inlayHint/refresh`
- [ ] `textDocument/inlineValue`
- [ ] `workspace/inlineValue/refresh`
- [ ] `textDocument/moniker`
- [ ] `textDocument/completion`
- [ ] `completionItem/resolve`
- [ ] `textDocument/publishDiagnostics`
- [ ] `textDocument/diagnostic`
- [ ] `workspace/diagnostic`
- [ ] `workspace/diagnostic/refresh`
- [ ] `textDocument/signatureHelp`
- [ ] `textDocument/codeAction`
- [ ] `codeAction/resolve`
- [ ] `textDocument/documentColor`
- [ ] `textDocument/colorPresentation`
- [ ] `textDocument/formatting`
- [ ] `textDocument/rangeFormatting`
- [ ] `textDocument/onTypeFormatting`
- [ ] `textDocument/rename`
- [ ] `textDocument/prepareRename`
- [ ] `textDocument/linkedEditingRange`

### Workspace Features

- [ ] `workspace/symbol`
- [ ] `workspaceSymbol/resolve`
- [ ] `workspace/configuration`
- [ ] `workspace/didChangeConfiguration`
- [ ] `workspace/workspaceFolders`
- [ ] `workspace/didChangeWorkspaceFolders`
- [ ] `workspace/willCreateFiles`
- [ ] `workspace/didCreateFiles`
- [ ] `workspace/willRenameFiles`
- [ ] `workspace/didRenameFiles`
- [ ] `workspace/willDeleteFiles`
- [ ] `workspace/didDeleteFiles`
- [ ] `workspace/didChangeWatchedFiles`
- [ ] `workspace/executeCommand`
- [ ] `workspace/applyEdit`

### Window Features

- [ ] `window/showMessage`
- [ ] `window/showMessageRequest`
- [ ] `window/showDocument`
- [ ] `window/logMessage`
- [ ] `window/workDoneProgress/create`
- [ ] `window/workDoneProgress/cancel`
- [ ] `telemetry/event`

## License

Copyright (c) 2024 Antti Kivi

This project is licensed under version 2.0 of the Apache license. See the
[`LICENSE`](LICENSE) for more information.
