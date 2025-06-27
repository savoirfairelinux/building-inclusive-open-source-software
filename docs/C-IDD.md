# 🖥️ C-IDD Inclusive design for Desktop

    This module contains the basic of accessible and inclusive design for Desktop.

**⛳️ Section**: C. Designing inclusive and accessible software

**👥 Audience**: Designers

**⏱️ ️Duration**: 15'

**📚 Prerequisites**: [🎨 C-IDE: Inclusive design 101](C-IDE.md)

---

## When to use ?

Use this module right after reading [🎨 C-IDE: Inclusive design 101](C-IDE.md) if you're designing applications for Desktop. It will give you insights on how to adapt those generic principles to your platform.

## What are the resources ?

### ...And why are they so few of them ?

Searching the web for resources on applicative accessibility and inclusiveness guidelines will probably left you unsatisfied and confused as you will liked be overwhelmed by resources and testing tools for web accessibility and none for applications.

<p align="center">
    <img src="../resources/c-designing-inclusive-and-accessible-software/applicativeAccessibilityEvaluationTools.png" alt="A Web search for 'Applicative accessibility evaluation tools' showing only result for web solutions" width="60%">
</p>

This phenomenon is not limited to the first internet search, their is a flagrant lack of accessibility resources for applicative design and development. Indeed, this is one of our motivations for the creation of this training.

This lack of resources while due to multiple factors can largely be attributed to a simple reason: The number of people that need to create and deploy a website is so enormous that it is a completely different scale than the number of persons that need to develop a native desktop application. This has been further accentuated by the rise of webapp frameworks like [Electron](https://www.electronjs.org/) or [Django](https://www.djangoproject.com/).

Therefore, the few resources publicly available on desktop applicative accessibility are often made by the operating system themselves. You can find the [Accessibility overview of Microsoft for Windows](https://learn.microsoft.com/en-us/windows/apps/design/accessibility/accessibility-overview#main), the [one from Apple systems](https://developer.apple.com/accessibility/) or [a list of accessibility tools for Linux](https://web.archive.org/web/20040715033825/http://lars.atrc.utoronto.ca/current.html). Those greatly vary in quality and doesn't provide much insight outside of the classic considerations of "disabled users should be able to use your app".

How to deal with contextual elements, different panes, complex UI elements that you typically don't find on a web page ? Those questions often remain unanswered. We will not have the answer to all of those. Working on applicative accessibility is not memorizing a fix set of rules to apply but rather learning how to find relevant solutions to problems you encounter.


### The WCAG standard

A useful resource to help you design accessibility for your desktop is one that isn't made for applications: [The Web Content Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/) (WCAG). It aims at providing shared worldwide accessibility guidelines for web content. It's therefore really extensive.

While some of it's content doesn't apply directly to native applicative design (for example aria labels are a web only concept), there is still a lot that we can learn from the WCAG. We especially recommend to use the [*How to Meet WCAG (Quick Reference)*](https://www.w3.org/WAI/WCAG22/quickref/) from the Web Accessibility Initiative. It provides you with example of successful and unsuccessful design for every WCAG guideline amd is sorted by topic. Therefore, you can simply navigate to the "1.4.1 Use of color section" and see the list of guidelines related to this point.

![A screenshot of the "How to Meet WCAG (Quick Reference)" guide on the topic of use of color](resources/c-designing-inclusive-and-accessible-software/wcagUseOfColor.png)

You can then check the techniques and failures for this point as well as well documented solutions for each of them. Here is one of the example given for use of color.

![A screenshot of an accessibility failure for use of color stating "A bar chart of sales data is provided as an image. The chart includes yearly sales figures for four employees in the Sales Department. The text alternative for the image says, "The following bar chart displays the yearly sales figures for the Sales Department. Mary sold 3.1 Million; Fred, 2.6 Million; Bob, 2.2 Million; and Andrew, 3.4 Million. The red bars indicate sales that were below the yearly quota". This text alternative fails to provide the information which is conveyed by the color red in the image. The alternative should indicate which people did not meet the sales quota rather than relying on color."](resources/c-designing-inclusive-and-accessible-software/wcagTechnique.png)

## Designing for keyboard usage

### Keyboard navigation

### Shortcuts

## Resources

[Web Accessibility Initiative. *How to Meet WCAG (Quick Reference)*](https://www.w3.org/WAI/WCAG22/quickref/)

## Sources

[Microsoft. *Accessibility overview for Windows*](https://learn.microsoft.com/en-us/windows/apps/design/accessibility/accessibility-overview#main)

[Apple. *Developing accessible apps*](https://developer.apple.com/accessibility/)

[JP Schnapper-Casteras & Janet Hopkins. *Current Work on Linux Accessibility*, 2004](https://web.archive.org/web/20040715033825/http://lars.atrc.utoronto.ca/current.html)