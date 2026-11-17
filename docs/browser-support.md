# Browser support

| Capability | Requirement | Notes |
|---|---|---|
| Screen capture | getDisplayMedia | Secure context (HTTPS or localhost), explicit user action and browser permission. |
| Recording | MediaRecorder | MIME type is selected from supported WebM variants. |
| System audio | Browser and OS support | Varies by capture source and platform. |
| Microphone | getUserMedia | Requires user permission. |
| Mobile | Browser-dependent | iOS/iPadOS web screen capture is restricted; native screen recording may be required. |

Test the target browser and operating system before relying on a capture workflow.
