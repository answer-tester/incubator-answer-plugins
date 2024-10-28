# Translator Plugin for Apache Answer

## Overview
This plugin provides an interface to translate questions into multiple languages using the Azure Text Translation API. Users can select the language from a dropdown injected into the question page. The plugin translates the question content and displays the result.

## Features
- Supports multiple languages (English, Portuguese, Spanish).
- Leverages the Azure Text Translation API.
- Automatically injects UI elements without modifying core Apache Answer code.

## Installation

1. Place this plugin in the `plugins` directory of your Apache Answer instance.
2. Edit `translator.go` to add your Azure API key and region.
3. Build and run your Apache Answer instance with the plugin.

## License

Licensed under the Apache License, Version 2.0.
