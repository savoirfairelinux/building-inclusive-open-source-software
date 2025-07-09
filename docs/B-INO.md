# 🔭 Inclusive needs overview

!!! Info "In this module"
    This module aims at giving the trainees an overview of the most common various accessibility needs their users could have.

**⛳️ Section**: B. From accessibility to inclusiveness

**👥 Audience**: Everyone

**⏱️ ️Duration**: 15'

**📚 Prerequisites**: [🫂 We are all disabled and unique : accessibility, plurality and intersectionality](B-WDU.md)

---

## When to use

This module should be used when already having a basis of what accessibility and inclusiveness means as well as how they interact together. It should help trainees have more concrete examples of what working on accessibility will mean technically.

## Main disabilities to account for in softwares

The list of disabilities are the main ones you will need to directly take into account for software development. It is evidently non-exhaustive. Keep in mind that disability is not a binary state but rather represent a wide variety of living experiences and that a lot of users will have multiple disabilities at once.

### Low vision

### Deafness

18% of users are hearing-impaired [according to Microsoft](https://learn.microsoft.com/en-us/windows/win32/uxguide/inter-accessibility). For more specific informations on their needs, you can check the [How to Meet WCAG (Quick Reference)](https://www.w3.org/WAI/WCAG22/quickref/#time-based-media) of the W3C. You will mostly need to provide redundant access to all auditive information. This can be for example a visual notification accompanying all sounds or real-time subtitling like the [Whisper Transcript plugin on Jami](https://jami.net/plugins/).

### Motion sickness

Some users will experience motion sickness when presented with fast moving elements. You should be aware of that, providing them with solutions for a less triggering experience. Known triggers include:

- Zooms
- Flashing or blinking
- Animations playing automatically without user interaction
- Parallax effects

### Color blindness

### Cognitive impairment

### Motor disabilities

### Speech or language

## Intersectional needs

In the [🎨 Inclusive design 101](C-IDE.md) module we will develop further the intersectional needs to take into account. Before that, a *non-exhaustive* list of human characteristics to keep in mind in order to try and include as many user as possible would be:

- Age
- Culture
- Digital literacy
- Education
- Ethnicity
- Gender, gender identity
- Historical context
- Language
- Mental health
- Nationality
- Physical *and* cognitive (dis)abilities
- Sexuality
- Socio-economic context

!!! tip
    **You need to consider the intersections of all of those categories as well as the disabilities listed previously in the first section of this module.**

Realistically, you cannot predict and account perfectly for all of those characteristics, because they are spectrums rather than fixed labels. The best you can do, is actively seek and listen to feedback from diverse user groups and make sure your team is as diverse as possible.

Some of the tools that we will share later in this training should still help you go through the main accessibility and inclusiveness elements when designing and developing.

## Sources

[Microsoft, *Accessibility (Design basics)*](https://learn.microsoft.com/en-us/windows/win32/uxguide/inter-accessibility)

[W3C, *How to Meet WCAG (Quick Reference)*](https://www.w3.org/WAI/WCAG22/quickref/#time-based-media)