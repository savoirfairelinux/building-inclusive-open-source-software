# 🍎 Accessible programming for Apple platforms

!!! Info "In this module"
    This module introduces to the practice of programming accessibility for Apple platforms.

**⛳️ Section**: E. Programming inclusive and accessible software

**👥 Audience**: Developers

**⏱️ ️Duration**: 15'

**📚 Prerequisites**: [👩‍💻 Inclusive code 101](D-ICO.md)

---

## When to use

This module should be used with trainees who need to have or want to have a technical understanding how Apple's approach on accessibility. It can be useful for designers who like to understand what's under the hood, particularly the first sections.

## Introduction

For years, Apple has been setting the bar for mobile accessibility. Their design principles, guidelines, as well as the tools and technologies they built are among the best out there. They also provide extensive resources on how to apply and use them. Thanks to these, if you're developing natively for Apple platforms, implementing accessible interfaces will likely be easier than for other OSes.

Consequently, we won't be covering everything you should know about Apple accessibility in this module. Rather, we'll provide a very synthetic overview referencing useful resources, along with some extra tips we wish we had when we started out.

## Apple's accessibility model

## Apple's Assistive Technologies

Having an understanding of the assistive technologies for which you are building your app is necessary to delivering a great experience. Apple has a lot of them, that they list [on this page](https://developer.apple.com/accessibility/). Here our digest of Apple-specific Assistive technologies, along with some additional information and tips. Feel free to follow the links to learn more!

### Major features

- [**VoiceOver**](https://developer.apple.com/documentation/accessibility/voiceover/) is Apple's screen reader. It allows users to access your app without seeing the screen. Like [TalkBack, Android's screen reader](https://www.youtube.com/watch?v=MEp9DtiTw3s), it is gesture based, meaning that users can execute [simple to complex gestures](https://appt.org/en/docs/ios/features/voiceover) in order to control their device. **Learning how to use VoiceOver is probably the best way to understand the levers you can activate to enhance the accessibility of your app**, as it is very intuitive, commonly used, and relies both on labels and group focus.

- [**Voice Control**](https://developer.apple.com/documentation/accessibility/voice-control) is a feature allowing users to interact with their devices using their voice. One takeaway of trying Voice Control is understanding how labels differ from values. In fact, labels are used by Voice Control users to select elements on the screen. We can therefore understand that labels should be short, unique identifiers reflecting what is shown on the screen. Values, on the other side, are only read by screen readers and can (and should) be more extensive.

- [**Switch Control**](https://developer.apple.com/documentation/accessibility/switch-control) lets users navigate your app with the switch devices of their choice, and/or mouth gestures. Having a clear and efficient navigation and elements grouping is crucial to making it accessible to users who rely on switch control. While Switch Control support typically comes for free when VoiceOver is supported, it's great to think about the ways you can enhance its users' experience by [implementing simple custom behaviors allowing for smarter and faster interaction](https://developer.apple.com/videos/play/wwdc2020/10019/).

- [**Assistive access**](https://developer.apple.com/documentation/accessibility/assistive-access)'s goal is to provide a minimal experience for people with cognitive disabilities or who are less familiar with new technologies. With little effort, developers can allow everyone to use the basic features of their app.

### Minor features

- For vision-impaired users:
    - Apple provides a Text to [*Speech*](https://developer.apple.com/documentation/accessibility/speech/) API. While it is not always required for developers to use it as VoiceOver natively does this job, using it allows to programmatically announce visual events, like a new message.
    - [Dynamic Type](https://developer.apple.com/videos/play/wwdc2024/10074/) is Apple's fancy name for their advanced system font settings, which allows developers to adapt their app's layout to any font size.
    - [Display customization settings](https://developer.apple.com/videos/play/wwdc2020/10020/) can be detected to adapt your app's behavior.
    - For apps serving audio and video content, builtin AVFoundation APIs [allow you to add subtitles and alternative audio tracks](https://developer.apple.com/documentation/avfoundation/selecting-subtitles-and-alternative-audio-tracks.)
    - [Magic tap](https://github.com/cvs-health/ios-swiftui-accessibility-techniques/blob/main/iOSswiftUIa11yTechniques/Documentation/MagicTap.md) is a very useful feature that is rarely implemented in third party apps. It allows to perform an arbitrary action upon a "magic tap" - a 2 fingers double tap with VoiceOver activated. If designed and hinted well, it can allow for quicker and easier interactions.
    
- For users with limited physical or motors abilities:
    - [Keyboard support](https://developer.apple.com/videos/play/wwdc2021/10120/) in iOS and iPadOS give developers the opportunity to provide users with shortcuts to navigate their app faster and easier.
    - [Eye Tracking](https://support.apple.com/en-gb/guide/iphone/iph66057d0f6/ios) allows users to control their iPhone through gaze. There is - to our knowledge - typically no additional considerations for this technology.


## Accessibility in SwiftUI

### Understanding it

### Adapting it

## Accessibility in UIKit

## Tools

## Informing users on your app's accessibility