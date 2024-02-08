GeminiX is a cross-platform, cross-framework abstraction providing a single unified API for using Google's [Gemini AI SDKs](https://ai.google.dev/docs) in cross-platform mobile apps on iOS, Android and Web platforms.

It enables the use of cutting-edge generative AI directly in cross-platform mobile apps with no server-side code required.

Gemini AI models are designed to understand and generate natural language and multi-modal (text and vision) content, and are available in a variety of languages and regions.

Features include:
- Unified cross-platform abstraction for the Gemini AI SDKs.
- Text-only and multi-modal (text and vision) models.
- Streaming and non-streaming interactions.
- Chat history for multi-turn conversations.
- Counting tokens for input text and images.
- Safety settings for filtering unsafe content.
- Model configuration parameters such as temperature, topP, topK, maxOutputTokens, and stopSequences.

# Framework implementations
There implementations are for the following cross-platform frameworks:

| Framework | Implementation | Status | Android | iOS | Web |
| --- | --- | --- |---------|-----|--|
| Apache Cordova | [Cordova GeminiX plugin](https://github.com/dpa99c/cordova-plugin-gemini-x) | available on npm | X | X  |  |
| Capacitor | [Capacitor GeminiX plugin](https://github.com/dpa99c/capacitor-plugin-gemini-x)  | coming soon | X | X  | X | 
| React Native | [React Native GeminiX module](https://github.com/dpa99c/react-native-gemini-x) | coming soon | X | X  |  |
| Flutter | [Flutter GeminiX module](https://github.com/dpa99c/flutter-gemini-x) | coming soon | X | X  | X |

# Platform implementations
Each framework implementation uses the following platform-specific submodules:

- Web: [gemini-x-web](https://github.com/dpa99c/gemini-x-web)
- Android: [gemini-x-android](https://github.com/dpa99c/gemini-x-android)
- iOS: [gemini-x-ios](https://github.com/dpa99c/gemini-x-ios)
