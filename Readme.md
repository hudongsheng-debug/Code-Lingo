# CodeLingo

Understand developer content. Keep coding.

CodeLingo is a privacy-focused macOS assistant for translating English developer content into Simplified Chinese, Japanese, or Korean. It explains errors, describes code, and generates concise comments while preserving identifiers, API names, and formatting.

CodeLingo can work as a standalone desktop app or through a Source Editor Extension compatible with Xcode.

## Features

- Translate English technical content into Chinese, Japanese, or Korean
- Explain compiler and runtime errors with practical fixes
- Describe the purpose and behavior of selected code
- Generate concise comments without changing code identifiers
- Process copied diagnostics in the desktop workspace
- Search and reuse recent results
- Use Apple Intelligence on device when available
- Optionally connect to a user-configured compatible cloud APICodeLingo


## Privacy

  Cloud processing is disabled by default. On supported Macs, CodeLingo can use Apple Intelligence for on-device processing. Content is sent to a cloud endpoint only when the user explicitly enables cloud processing and configures an API key.

  - No advertising or tracking
  - No developer-operated analytics or translation server
  - API keys are stored in macOS Keychain
  - Settings and recent history are stored locally
  - Clipboard content is not processed until the user starts a task

  Read the complete [Privacy Policy](PRIVACY.md).

## Requirements

  - macOS 14 or later
  - Xcode is required only for Source Editor Extension features
  - Apple Intelligence features require a supported Mac, compatible macOS version, enabled Apple Intelligence, and downloaded on-device models
  - A compatible cloud endpoint and personal API key are optional

## Enable the Source Editor Extension

  1. Install and open CodeLingo once.
  2. Open **System Settings > General > Login Items & Extensions**.
  3. Open **Xcode Source Editor** and enable **CodeLingo Source Editor**.
  4. Restart Xcode.
  5. Select text or code in the source editor.
  6. Choose a CodeLingo command from the **Editor** menu.

  The extension can process the current editor selection. To process an item from the Issue Navigator, copy the diagnostic and paste it into the CodeLingo workspace.

## Processing Modes

  - **Automatic:** uses Apple Intelligence first and uses the cloud only when authorized and configured
  - **Apple Intelligence Only:** keeps processing on the device
  - **Cloud API Only:** uses the endpoint, model, and API key supplied by the user

## Build from Source

  1. Open `XcodeLingo.xcodeproj` in Xcode.
  2. Select the main app scheme.
  3. Choose a development team under **Signing & Capabilities**.
  4. Build and run the macOS app.
  5. Enable the Source Editor Extension using the instructions above.

## Security

  Do not submit passwords, private keys, access tokens, personal information, or confidential source code to a translation service. When cloud processing is enabled, review the privacy and retention policy of the provider you configure.

 ## Support

  - Read the [Support Guide](SUPPORT.md)
  - [Ask a question or report a problem](https://github.com/hudongsheng-debug/Xcode-Lingo/issues/new)
  - [View existing support requests](https://github.com/hudongsheng-debug/Xcode-Lingo/issues)

  Remove API keys, access tokens, confidential code, and personal information before posting logs or screenshots.

## Disclaimer

  CodeLingo is an independent developer tool and is not affiliated with or endorsed by Apple Inc. or OpenAI. Xcode, macOS, and Apple Intelligence are trademarks of Apple Inc.
- Privacy

Cloud processing is disabled by default. On supported Macs, CodeLingo can use Apple Intelligence for on-device processing. Content is sent to a cloud endpoint only when the user explicitly enables cloud processing and configures an API key.

- No advertising or tracking
- No developer-operated analytics or translation server
- API keys are stored in macOS Keychain
- Settings and recent history are stored locally
- Clipboard content is not processed until the user starts a task

Read the complete [Privacy Policy](PRIVACY.md).

## Requirements

- macOS 14 or later
- Xcode is required only for Source Editor Extension features
- Apple Intelligence features require a supported Mac, compatible macOS version, enabled Apple Intelligence, and downloaded on-device models
- A compatible cloud endpoint and personal API key are optional

