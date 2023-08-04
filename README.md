# Visual Studio Code 1.81.0

## Table of Contents
- iPadOS
- `open`
- `export`
- `ignore`
- `private`

```json
{
    /* iPadOS */
        "editor.showFoldingControls": "mouseover",     // should be `"always"`
        "workbench.activityBar.visible": false,        // should be `true`
        "workbench.list.openMode": "doubleClick",      // should be `"singleClick"`
        "workbench.tree.expandMode": "doubleClick",    // should be `"singleClick"`
        "workbench.quickOpen.closeOnFocusLost": false, // should be `true`
    /* open */
        "editor.fontFamily"   : "JetBrains Mono",
        "editor.fontLigatures": false,
        "editor.fontSize"     : 14,
        "editor.fontWeight"   : "normal",
        "editor.tabSize": 4,
        "files.associations": {
            "*.c"    : "c",
            "*.cpp"  : "cpp",
            "*.cs"   : "csharp",
            "*.html" : "html",
            "*.js"   : "javascript",
            "*.jsx"   : "javascriptreact",
            "*.md"   : "markdown",
            "*.sh"   : "shellscript",
            "*.swift": "swift",
            "*.ts"   : "typescript",
            "*.tsx"   : "typescriptreact"
        },
        "workbench.colorTheme"                          : "",
        "workbench.preferredDarkColorTheme"             : "",
        "workbench.preferredHighContrastColorTheme"     : "",
        "workbench.preferredHighContrastLightColorTheme": "",
        "workbench.preferredLightColorTheme"            : "",
        "[html]": {
            "editor.tabSize": 2
        },
    /* export */
        "editor.formatOnPaste": false,
        "editor.formatOnSave" : false,
        "editor.formatOnType" : false,
        "editor.insertSpaces": true,
        "editor.wordSeparators": "`~!@#$%^&*()-=+[{]}\\|;:'\",.<>/?_",
        "extensions.autoCheckUpdates": false,
        "extensions.autoUpdate": false,
        "files.eol"               : "\n",
        "files.insertFinalNewline": true,
        "update.mode": "manual",
        "workbench.list.smoothScrolling": true,
        "workbench.localHistory.maxFileEntries": 4294967295,
        "workbench.localHistory.maxFileSize"   : 1000000,
        "workbench.localHistory.mergeWindow"   : 65535,
    /* ignore */
        "workbench.localHistory.enabled": false,
    /* private */
        "audioCues.lineHasBreakpoint"      : "off",
        "audioCues.lineHasError"           : "off",
        "audioCues.lineHasFoldedArea"      : "off",
        "audioCues.lineHasInlineSuggestion": "off",
        "audioCues.lineHasWarning"         : "off",
        "audioCues.noInlayHints": "off",
        "audioCues.onDebugBreak": "off",
        "audioCues.taskCompleted": "off",
        "audioCues.taskFailed"   : "off",
        "audioCues.terminalQuickFix": "off",
        "audioCues.volume": 100,
        "breadcrumbs.enabled": true,
        "breadcrumbs.filePath": "off",
        "breadcrumbs.icons": false,
        "breadcrumbs.showArrays":        true,
        "breadcrumbs.showBooleans":      true,
        "breadcrumbs.showClasses":       true,
        "breadcrumbs.showConstants":     true,
        "breadcrumbs.showConstructors":  true,
        "breadcrumbs.showEnumMembers":   true,
        "breadcrumbs.showEnums":         true,
        "breadcrumbs.showEvents":        true,
        "breadcrumbs.showFields":        true,
        "breadcrumbs.showFiles":         true,
        "breadcrumbs.showFunctions":     true,
        "breadcrumbs.showInterfaces":    true,
        "breadcrumbs.showKeys":          true,
        "breadcrumbs.showMethods":       true,
        "breadcrumbs.showModules":       true,
        "breadcrumbs.showNamespaces":    true,
        "breadcrumbs.showNull":          true,
        "breadcrumbs.showNumbers":       true,
        "breadcrumbs.showObjects":       true,
        "breadcrumbs.showOperators":     true,
        "breadcrumbs.showPackages":      true,
        "breadcrumbs.showProperties":    true,
        "breadcrumbs.showStrings":       true,
        "breadcrumbs.showStructs":       true,
        "breadcrumbs.showTypeParameters":true,
        "breadcrumbs.showVariables":     true,
        "breadcrumbs.symbolPath": "on",
        "breadcrumbs.symbolSortOrder": "position",
        "css.completion.completePropertyWithSemicolon": true,
        "css.completion.triggerPropertyValueCompletion": true,
        "css.format.braceStyle": "collapse",
        "css.format.enable": true,
        "css.format.maxPreserveNewLines": 2,
        "css.format.newlineBetweenRules": false,
        "css.format.newlineBetweenSelectors": false,
        "css.format.preserveNewLines": true,
        "css.format.spaceAroundSelectorSeparator": true,
        "css.lint.duplicateProperties": "warning",
        "css.lint.emptyRules": "warning",
        "css.lint.float": "warning",
        "css.lint.hexColorLength": "warning",
        "css.lint.idSelector": "ignore",
        "css.lint.important": "ignore",
        "css.lint.propertyIgnoredDueToDisplay": "warning",
        "css.lint.universalSelector": "ignore",
        "css.lint.zeroUnits": "warning",
        "css.validate": true,
        "diffEditor.codeLens": true,
        "diffEditor.ignoreTrimWhitespace": false,
        "diffEditor.maxComputationTime": 0,
        "diffEditor.maxFileSize": 0,
        "diffEditor.renderIndicators": true,
        "diffEditor.renderSideBySide": true,
        "diffEditor.wordWrap": "off",
        "editor.acceptSuggestionOnCommitCharacter": false,
        "editor.acceptSuggestionOnEnter": "off",
        "editor.accessibilityPageSize": 1,
        "editor.accessibilitySupport": "off",
        "editor.autoClosingBrackets": "always",
        "editor.autoClosingDelete": "never",
        "editor.autoClosingOvertype": "auto",
        "editor.autoClosingQuotes": "always",
        "editor.autoIndent": "full",
        "editor.autoSurround": "languageDefined",
        "editor.bracketPairColorization.enabled": true,
        "editor.bracketPairColorization.independentColorPoolPerBracketType": false,
        "editor.codeActionsOnSave": {},
        "editor.codeLens": true,
        "editor.codeLensFontFamily": "",
        "editor.codeLensFontSize": 0,
        "editor.colorDecorators": true,
        "editor.columnSelection": false,
        "editor.comments.ignoreEmptyLines": false,
        "editor.comments.insertSpace": false,
        "editor.copyWithSyntaxHighlighting": false,
        "editor.cursorBlinking": "smooth",
        "editor.cursorSmoothCaretAnimation": "on",
        "editor.cursorStyle": "line",
        "editor.cursorSurroundingLines": 0,
        "editor.cursorSurroundingLinesStyle": "default",
        "editor.defaultFormatter": null,
        "editor.definitionLinkOpensInPeek": true,
        "editor.detectIndentation": false,
        "editor.dragAndDrop": false,
        "editor.emptySelectionClipboard": true,
        "editor.fastScrollSensitivity": 5,
        "editor.find.addExtraSpaceOnTop": false,
        "editor.find.cursorMoveOnType": false,
        "editor.find.loop": false,
        "editor.find.seedSearchStringFromSelection": "selection",
        "editor.folding": true,
        "editor.foldingHighlight": true,
        "editor.foldingImportsByDefault": false,
        "editor.foldingMaximumRegions": 65000,
        "editor.foldingStrategy": "auto",
        "editor.glyphMargin": false,
        "editor.guides.bracketPairs": false,
        "editor.guides.bracketPairsHorizontal": false,
        "editor.guides.highlightActiveBracketPair": true,
        "editor.guides.highlightActiveIndentation": true,
        "editor.guides.indentation": false,
        "editor.hideCursorInOverviewRuler": false,
        "editor.hover.above": true,
        "editor.hover.enabled": true,
        "editor.hover.sticky": true,
        "editor.inlayHints.enabled": "offUnlessPressed",
        "editor.inlayHints.fontFamily": "",
        "editor.inlayHints.fontSize": 0,
        "editor.inlayHints.padding": true,
        "editor.inlineSuggest.enabled": true,
        "editor.largeFileOptimizations": false,
        "editor.letterSpacing": 0,
        "editor.lightbulb.enabled": false,
        "editor.lineHeight": 0,
        "editor.lineNumbers": "on",
        "editor.linkedEditing": true,
        "editor.links": false,
        "editor.matchBrackets": "always",
        "editor.maxTokenizationLineLength": 65535,
        "editor.minimap.autohide": false,
        "editor.minimap.enabled": true,
        "editor.minimap.maxColumn": 110,
        "editor.minimap.renderCharacters": false,
        "editor.minimap.scale": 2,
        "editor.minimap.showSlider": "always",
        "editor.minimap.side": "left",
        "editor.minimap.size": "fit",
        "editor.mouseWheelScrollSensitivity": 1,
        "editor.mouseWheelZoom": false,
        "editor.multiCursorMergeOverlapping": true,
        "editor.multiCursorModifier": "alt",
        "editor.multiCursorLimit": 100000,
        "editor.occurrencesHighlight": true,
        "editor.overviewRulerBorder": false,
        "editor.parameterHints.cycle": true,
        "editor.parameterHints.enabled": true,
        "editor.quickSuggestions": {
            "comments": "on",
            "other": "on",
            "strings": "on"
        },
        "editor.rename.enablePreview": true,
        "editor.renderFinalNewline": "on",
        "editor.renderLineHighlight": "gutter",
        "editor.renderLineHighlightOnlyWhenFocus": false,
        "editor.renderWhitespace": "selection",
        "editor.roundedSelection": true,
        "editor.scrollbar.horizontal": "auto",
        "editor.scrollbar.vertical": "auto",
        "editor.scrollBeyondLastLine": true,
        "editor.scrollPredominantAxis": true,
        "editor.selectionHighlight": true,
        "editor.showDeprecated": true,
        "editor.showUnused": true,
        "editor.smoothScrolling": true,
        "editor.snippetSuggestions": "inline",
        "editor.stickyScroll.enabled": true,
        "editor.stickyTabStops": true,
        "editor.suggest.localityBonus": false,
        "editor.suggest.preview": true,
        "editor.suggest.shareSuggestSelections": true,
        "editor.suggest.showClasses":        true,
        "editor.suggest.showColors":         true,
        "editor.suggest.showConstants":      true,
        "editor.suggest.showConstructors":   true,
        "editor.suggest.showCustomcolors":   true,
        "editor.suggest.showDeprecated":     true,
        "editor.suggest.showEnumMembers":    true,
        "editor.suggest.showEnums":          true,
        "editor.suggest.showEvents":         true,
        "editor.suggest.showFields":         true,
        "editor.suggest.showFiles":          true,
        "editor.suggest.showFolders":        true,
        "editor.suggest.showFunctions":      true,
        "editor.suggest.showIcons":          true,
        "editor.suggest.showInlineDetails":  true,
        "editor.suggest.showInterfaces":     true,
        "editor.suggest.showIssues":         true,
        "editor.suggest.showKeywords":       true,
        "editor.suggest.showMethods":        true,
        "editor.suggest.showModules":        true,
        "editor.suggest.showOperators":      true,
        "editor.suggest.showProperties":     true,
        "editor.suggest.showReferences":     true,
        "editor.suggest.showSnippets":       true,
        "editor.suggest.showStatusBar":      true,
        "editor.suggest.showStructs":        true,
        "editor.suggest.showTypeParameters": true,
        "editor.suggest.showUnits":          true,
        "editor.suggest.showUsers":          true,
        "editor.suggest.showValues":         true,
        "editor.suggest.showVariables":      true,
        "editor.suggest.showWords":          true,
        "editor.suggestFontSize": 0,
        "editor.suggestLineHeight": 0,
        "editor.suggestSelection": "recentlyUsed",
        "editor.tabCompletion": "onlySnippets",
        "editor.trimAutoWhitespace": true,
        "editor.unicodeHighlight.ambiguousCharacters": true,
        "editor.unicodeHighlight.includeComments": false,
        "editor.unicodeHighlight.includeStrings": false,
        "editor.unicodeHighlight.invisibleCharacters": true,
        "editor.unicodeHighlight.nonBasicASCII": false,
        "editor.unusualLineTerminators": "prompt",
        "editor.useTabStops": false,
        "editor.wordBasedSuggestionsMode": "allDocuments",
        "editor.wordWrap": "off",
        "editor.wrappingIndent": "deepIndent",
        "editor.wrappingStrategy": "advanced",
        "emmet.triggerExpansionOnTab": true,
        "explorer.compactFolders": false,
        "explorer.copyRelativePathSeparator": "/",
        "explorer.enableDragAndDrop": false,
        "explorer.fileNesting.enabled": true,
        "explorer.fileNesting.patterns": {
            "*.js" : "${capture}.js.map, ${capture}.min.js, ${capture}.d.ts",
            "*.jsx": "${capture}.js",
            "*.ts" : "${capture}.js",
            "*.tsx": "${capture}.ts",
            "*.h": "${capture}.cpp",
            "package.json": "package-lock.json",
            "tsconfig.json": "tsconfig.*.json"
        },
        "explorer.incrementalNaming": "smart",
        "explorer.openEditors.visible": 0,
        "explorer.sortOrder": "type",
        "extensions.closeExtensionDetailsOnViewChange": true,
        "extensions.ignoreRecommendations": true,
        "files.autoGuessEncoding": false,
        "files.autoSave": "off",
        "files.defaultLanguage": "${activeEditorLanguage}",
        "files.enableTrash": true,
        "files.encoding": "utf8",
        "files.exclude": {
            "*.csproj": true,
            "*.exe": true,
            "*.out": true,
            "**/.DS_Store": false,
            "**/.hg": false,
            "**/.svn": false,
            "**/.vs": true,
            "**/.vscode": true,
            "**/CVS": false,
            "**/Thumbs.db": false
        },
        "files.refactoring.autoSave": false,
        "files.restoreUndoStack": true,
        "files.saveConflictResolution": "askUser",
        "files.simpleDialog.enable": true,
        "files.trimFinalNewlines": false,
        "files.trimTrailingWhitespace": true,
        "git.autoRepositoryDetection": false,
        "git.enabled": true,
        "grunt.autoDetect": "off",
        "gulp.autoDetect": "off",
        "hexeditor.columnWidth": 32,
        "hexeditor.defaultEndianness": "little",
        "hexeditor.inspectorType": "aside",
        "hexeditor.showDecodedText": true,
        "html.autoClosingTags": true,
        "html.autoCreateQuotes": true,
        "html.completion.attributeDefaultValue": "singlequotes",
        "html.format.contentUnformatted": "pre, code",
        "html.format.enable": true,
        "html.format.extraLiners": "html, body",
        "html.format.indentInnerHtml": true,
        "html.format.maxPreserveNewLines": 1,
        "html.format.preserveNewLines": true,
        "html.format.wrapLineLength": 0,
        "http.proxy": "",
        "http.proxyAuthorization": null,
        "http.proxyStrictSSL": true,
        "http.proxySupport": "override",
        "http.systemCertificates": true,
        "jake.autoDetect": "off",
        "javascript.format.enable": true,
        "javascript.format.insertSpaceAfterCommaDelimiter"                         : true,
        "javascript.format.insertSpaceAfterConstructor"                            : false,
        "javascript.format.insertSpaceAfterFunctionKeywordForAnonymousFunctions"   : false,
        "javascript.format.insertSpaceAfterKeywordsInControlFlowStatements"        : true,
        "javascript.format.insertSpaceAfterOpeningAndBeforeClosingEmptyBraces"     : false,
        "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBraces"  : true,
        "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBrackets": false,
        "javascript.format.semicolons": "insert",
        "javascript.inlayHints.functionLikeReturnTypes.enabled": true,
        "javascript.inlayHints.parameterNames.enabled": "all",
        "javascript.inlayHints.parameterNames.suppressWhenArgumentMatchesName": false,
        "javascript.inlayHints.parameterTypes.enabled": true,
        "javascript.inlayHints.propertyDeclarationTypes.enabled": true,
        "javascript.inlayHints.variableTypes.enabled": true,
        "javascript.preferences.quoteStyle": "double",
        "js/ts.implicitProjectConfig.checkJs": false, // use @ts-check
        "js/ts.implicitProjectConfig.experimentalDecorators": true,
        "js/ts.implicitProjectConfig.target": "ESNext",
        "json.maxItemsComputed": 4294967295,
        "markdown.preview.doubleClickToSwitchToEditor": false,
        "markdown.preview.typographer": true,
        "problems.showCurrentInStatus": true,
        "problems.sortOrder": "position",
        "scm.alwaysShowActions": true,
        "scm.alwaysShowRepositories": true,
        "scm.autoReveal": false,
        "scm.repositories.visible": 0,
        "screencastMode.fontSize": 20,
        "screencastMode.keyboardShortcutsFormat": "keys",
        "screencastMode.onlyKeyboardShortcuts": true,
        "scss.completion.completePropertyWithSemicolon": true,
        "scss.format.braceStyle": "collapse",
        "scss.format.spaceAroundSelectorSeparator": true,
        "search.actionsPosition": "auto",
        "search.collapseResults": "alwaysCollapse",
        "search.maxResults": null,
        "search.mode": "reuseEditor",
        "search.showLineNumbers": true,
        "search.sortOrder": "countDescending",
        "security.workspace.trust.banner": "never",
        "security.workspace.trust.emptyWindow": false,
        "security.workspace.trust.enabled": true,
        "security.workspace.trust.startupPrompt": "always",
        "security.workspace.trust.untrustedFiles": "newWindow",
        "settingsSync.ignoredExtensions": [],
        "settingsSync.ignoredSettings": [],
        "settingsSync.keybindingsPerPlatform": false,
        "task.autoDetect": "off",
        "task.saveBeforeRun": "prompt",
        "telemetry.telemetryLevel": "off",
        "terminal.explorerKind": "external",
        "terminal.external.osxExec": "Terminal.app",
        "terminal.external.windowsExec": "wt",
        "terminal.integrated.allowChords": false,
        "terminal.integrated.allowMnemonics": true,
        "terminal.integrated.confirmOnExit": "hasChildProcesses",
        "terminal.integrated.cursorBlinking": true,
        "terminal.integrated.cursorStyle": "line",
        "terminal.integrated.defaultLocation": "editor",
        "terminal.integrated.defaultProfile.linux": "bash",
        "terminal.integrated.defaultProfile.windows": "Command Prompt",
        "terminal.integrated.detectLocale": "on",
        "terminal.integrated.enableBell": true,
        "terminal.integrated.environmentChangesRelaunch": false,
        "terminal.integrated.fontFamily": "",
        "terminal.integrated.fontSize": 14,
        "terminal.integrated.gpuAcceleration": "on",
        //"html.format.wrapAttributes": "force-expand-multiline",
        "terminal.integrated.profiles.windows": {
            "PowerShell": {
                "source": "PowerShell",
                "icon": "terminal-powershell"
            },
            "Command Prompt": {
                "path": [
                    "${env:windir}\\Sysnative\\cmd.exe",
                    "${env:windir}\\System32\\cmd.exe"
                ],
                "args": [],
                "icon": "terminal-cmd"
            },
            "Developer Command Prompt": {
                "path": [
                    "${env:windir}\\System32\\cmd.exe"
                ],
                "args": [
                    "/k",
                    "A:\\Program Files\\Microsoft Visual Studio\\2022\\Community\\Common7\\Tools\\VsDevCmd.bat",
                    "-arch=x64",
                    "-host_arch=x64"
                ],
                "icon": "terminal-cmd"
            }
        },
        "terminal.integrated.rightClickBehavior": "default",
        "terminal.integrated.scrollback": 4294967295,
        "terminal.integrated.shellIntegration.enabled": true,
        "terminal.integrated.shellIntegration.history": 255,
        "terminal.integrated.tabs.enableAnimation": true,
        "terminal.integrated.tabs.location": "left",
        "terminal.integrated.tabs.showActions": "never",
        "terminal.integrated.tabs.showActiveTerminal": "never",
        "terminal.integrated.tabs.title": "${process}",
        "timeline.pageOnScroll": true,
        "timeline.pageSize": null,
        "typescript.inlayHints.enumMemberValues.enabled": true,
        "typescript.inlayHints.functionLikeReturnTypes.enabled": true,
        "typescript.inlayHints.parameterNames.enabled": "all",
        "typescript.inlayHints.parameterNames.suppressWhenArgumentMatchesName": false,
        "typescript.inlayHints.parameterTypes.enabled": true,
        "typescript.inlayHints.propertyDeclarationTypes.enabled": true,
        "typescript.inlayHints.variableTypes.enabled": true,
        "typescript.tsserver.maxTsServerMemory": 2048,
        "update.enableWindowsBackgroundUpdates": false,
        "window.autoDetectColorScheme": true,
        "window.autoDetectHighContrast": false,
        "window.closeWhenEmpty": false,
        "window.commandCenter": true,
        "window.dialogStyle": "native",
        "window.enableMenuBarMnemonics": true,
        "window.experimental.windowControlsOverlay.enabled": true,
        "window.menuBarVisibility": "toggle",
        "window.newWindowDimensions": "default",
        "window.restoreFullscreen": true,
        "window.restoreWindows": "all",
        "window.title": "${rootName}${separator}${activeFolderMedium}${separator}${dirty}${activeEditorShort}",
        "window.titleBarStyle": "custom",
        "window.titleSeparator": " → ",
        "workbench.activityBar.iconClickBehavior": "toggle",
        "workbench.commandPalette.history": 7,
        "workbench.commandPalette.preserveInput": true,
        "workbench.editor.centeredLayoutAutoResize": true,
        "workbench.editor.closeEmptyGroups": true,
        "workbench.editor.closeOnFileDelete": false,
        "workbench.editor.enablePreviewFromQuickOpen": false,
        "workbench.editor.highlightModifiedTabs": true,
        "workbench.editor.languageDetection": false,
        "workbench.editor.mouseBackForwardToNavigate": false,
        "workbench.editor.pinnedTabSizing": "normal",
        "workbench.editor.showIcons": true,
        "workbench.editor.showTabs": true,
        "workbench.editor.splitOnDragAndDrop": false,
        "workbench.editor.untitled.labelFormat": "name",
        "workbench.editor.wrapTabs": true,
        "workbench.enableExperiments": false,
        "workbench.iconTheme": "vs-seti",
        "workbench.layoutControl.enabled": true,
        "workbench.layoutControl.type": "both",
        "workbench.list.defaultFindMode": "filter",
        "workbench.list.horizontalScrolling": false,
        "workbench.list.multiSelectModifier": "alt",
        "workbench.localHistory.exclude": {},
        "workbench.panel.defaultLocation": "right",
        "workbench.panel.opensMaximized": "always",
        "workbench.productIconTheme": "Default",
        "workbench.quickOpen.preserveInput": true,
        "workbench.reduceMotion": "auto",
        "workbench.settings.editor": "ui",
        "workbench.settings.enableNaturalLanguageSearch": false,
        "workbench.settings.settingsSearchTocBehavior": "filter",
        "workbench.settings.useSplitJSON": false,
        "workbench.sideBar.location": "right",
        "workbench.startupEditor": "none",
        "workbench.statusBar.visible": true,
        "workbench.tree.renderIndentGuides": "always",
        "workbench.trustedDomains.promptInTrustedWorkspace": true,
        "workbench.view.alwaysShowHeaderActions": true,
        "zenMode.centerLayout": true,
        "zenMode.fullScreen": true,
        "zenMode.hideActivityBar": false,
        "zenMode.hideLineNumbers": false,
        "zenMode.hideStatusBar"  : false,
        "zenMode.hideTabs"       : true,
        "zenMode.restore": false
}
```
