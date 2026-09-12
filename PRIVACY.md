# CodeLingo Privacy Policy

**Effective date:** September 12, 2026  
**Last updated:** September 12, 2026

CodeLingo is a macOS developer tool designed to minimize data collection and keep users in control of their content. This policy explains how the CodeLingo app and its Source Editor Extension handle information.

## Summary

CodeLingo does not contain advertising, analytics, or user tracking. The developer does not operate a translation server and does not create user accounts.

When supported and selected, processing is performed on the user’s Mac with Apple Intelligence. Optional cloud processing is disabled by default and is used only when the user enables it and configures a compatible endpoint and API key.

## Information handled by CodeLingo

CodeLingo may handle the following information only to provide a feature requested by the user:

- Text typed or pasted into the app
- Text or code selected in the source editor
- Compiler and runtime diagnostics copied by the user
- Translation, explanation, and generated-comment results
- Processing mode, output language, endpoint, and model preferences
- An API key supplied for optional cloud processing

The developer does not receive this information unless the user independently includes it in a support request.

## On-device processing

On supported Macs, CodeLingo can process requests on the device using Apple Intelligence and Apple’s Foundation Models framework. Content processed in this mode is not sent to a server operated by the CodeLingo developer.

Apple Intelligence availability and operation are governed by Apple’s applicable terms and privacy policies.

## Optional cloud processing

Cloud processing is disabled by default. It is used only after the user enables **Allow Cloud Processing**, configures a compatible API endpoint and model, and supplies an API key.

When enabled, the input text, task instructions, and configured model name are sent directly from the user’s Mac to the endpoint selected by the user. CodeLingo does not proxy these requests through a developer-operated server.

The selected cloud provider may process or retain information according to its own terms and privacy policy. Users should review those policies and avoid sending passwords, private keys, access tokens, personal data, customer information, or confidential source code. Disabling cloud processing prevents future cloud requests.

## Clipboard and editor access

CodeLingo can read clipboard text when the user chooses a clipboard action. Its Source Editor Extension can access text or code selected by the user in Xcode. Clipboard or selected content is not processed merely because it was loaded; processing starts only after the user initiates a task.

## Local storage and retention

- API keys are stored in macOS Keychain.
- Preferences and recent results are stored locally on the user’s Mac.
- Recent results are limited by the app and can be cleared from the interface.
- CodeLingo does not intentionally synchronize this information to a developer-operated service.

Users can remove locally stored information by deleting the API key in Settings, clearing recent history, or uninstalling the app. macOS may retain Keychain items after an app is removed; these items can be deleted using Keychain Access.

## Data collection, tracking, and advertising

CodeLingo does not collect personal information on behalf of the developer, use advertising or analytics SDKs, track users across apps or websites, sell personal information, share information with data brokers, or create advertising profiles.

Optional direct communication with a user-configured cloud provider is described above.

## Children

CodeLingo is a developer utility and is not directed to children. The developer does not knowingly collect personal information from children.

## Security

CodeLingo uses platform security features including App Sandbox and macOS Keychain. HTTPS is used when supported by the endpoint configured by the user. No method of storage or transmission can guarantee absolute security, particularly when a user selects a third-party service.

## Changes to this policy

This policy may be updated when CodeLingo’s features or legal obligations change. The effective date and last-updated date will be revised when changes are published.

## Contact

For privacy questions or requests, use the [CodeLingo support page](https://github.com/hudongsheng-debug/Code-Lingo/issues/new). Do not include API keys, confidential source code, or sensitive personal information in a public request.

---

# CodeLingo 隐私政策（中文摘要）

**生效日期：**2026 年 9 月 12 日  
**最后更新：**2026 年 9 月 12 日

CodeLingo 不包含广告、分析组件或用户追踪，也不运营开发者自有的翻译服务器。

在受支持的 Mac 上，CodeLingo 可使用 Apple 智能在设备本地处理用户主动提交的内容。云端处理默认关闭，只有在用户主动开启、配置 API 地址并提供 API Key 后才会使用。输入内容将直接发送至用户选择的服务商，并按该服务商的隐私政策处理。

API Key 保存在 macOS 钥匙串中；偏好设置和最近处理记录保存在本机。用户可以清空历史记录、删除 API Key 或关闭云端处理。

CodeLingo 不销售个人信息，不跨应用或网站追踪用户，也不使用用户内容建立广告档案。

如有隐私问题，请通过 [CodeLingo 技术支持页面](https://github.com/hudongsheng-debug/Code-Lingo/issues/new) 联系。请勿在公开请求中提交 API Key、保密代码或敏感个人信息。

CodeLingo 是独立开发者工具，与 Apple Inc. 无隶属或背书关系。Xcode 和 Apple Intelligence 是 Apple Inc. 的商标。
