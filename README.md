# Herb LSP Intellij Wrapper

![Build](https://github.com/mwnciau/herb-lsp-intellij/workflows/Build/badge.svg)
[![Version](https://img.shields.io/jetbrains/plugin/v/com.herblsp.svg)](https://plugins.jetbrains.com/plugin/com.herblsp)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/com.herblsp.svg)](https://plugins.jetbrains.com/plugin/com.herblsp)

## Template ToDo list
- [x] Create a new [IntelliJ Platform Plugin Template][template] project.
- [x] Get familiar with the [template documentation][template].
- [x] Adjust the [pluginGroup](./gradle.properties), [plugin ID](./src/main/resources/META-INF/plugin.xml) and [sources package](./src/main/kotlin).
- [x] Adjust the plugin description in `README` (see [Tips][docs:plugin-description])
- [x] Review the [Legal Agreements](https://plugins.jetbrains.com/docs/marketplace/legal-agreements.html?from=IJPluginTemplate).
- [x] [Publish a plugin manually](https://plugins.jetbrains.com/docs/intellij/publishing-plugin.html?from=IJPluginTemplate) for the first time.
- [x] Set the `PLUGIN_ID` in the above README badges.
- [ ] Set the [Plugin Signing](https://plugins.jetbrains.com/docs/intellij/plugin-signing.html?from=IJPluginTemplate) related [secrets](https://github.com/JetBrains/intellij-platform-plugin-template#environment-variables).
- [ ] Set the [Deployment Token](https://plugins.jetbrains.com/docs/marketplace/plugin-upload.html?from=IJPluginTemplate).
- [ ] Click the <kbd>Watch</kbd> button on the top of the [IntelliJ Platform Plugin Template][template] to be notified about releases containing new features and fixes.

<!-- Plugin description -->
This plugin is a simple wrapper around [Herb LSP](https://github.com/marcoroth/herb) by [Marco Roth](https://github.com/marcoroth).
<!-- Plugin description end -->

## Installation

- Install the Herb Language Server and ensure that `herb` is on your PATH 
  ```shell
  npm install -g @herb-tools/language-server
  ```
