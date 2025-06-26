<<<<<<< B-DSU-new-module
# 🤺 B-DSU: Developer stance & user collaboration

    When creating, finding the right stance can be perilous;
        - how to help without infantilizing ?
        - How to care without assuming one's needs ?
        - How to design for something we don't experience ?

    This module aims at finding answers to those questions from a software
    perspective.

**⛳️ Section**: B. From accessibility to inclusiveness

**👥 Audience**: Everyone

**⏱️ ️Duration**: 10'

**📚 Prerequisites**:

---

# When to use ?

This module try and provide you with a reflection on what your perspective on the world is and how to attempt to account for other's ones.

# Description

## Who are you

Who are we as people ? We all have an incomplete perspective of the world. These comes with biases but also insights and experiences. Opening up to different views is always a tough process. In [Developing Inclusive Mobile Apps](https://link.springer.com/book/10.1007/978-1-4842-5814-9), Rob Whitetaker propose an exercise to identify our biases. The following workshop is a variation adapted from their's.

Provide a piece of paper to all of the trainees attempting the training. Ask them to make a list of five person the 5 peoples they trust the must, people they would go to for advices (no matter whether they are colleagues, family or friends). Once that's done, ask them to count a point each time the answer is yes to the following questions.

1. Are all of them of the same ethnicity as you ?
2. Do all of them have the same sexual orientation ?
3. Do all of them have the same nationality as you ?
4. Are all of them considered valid ?
5. Did all of them have or are pursuing a diploma ?
6. Are all of them cisgender ?
7. Are all of them working/studying or being retired ?
8. Are all of them from the same or higher economic background as you ?
9. Are most of them mens ?
10. Do they all speak the language of the country they live in ?

---

Once that's done, count from 1 up to 10 and ask the trainees to raise their hand on the number corresponding with their score. T ease of trainees you can also raise your hand on the number corresponding to your own results. This should help the group to start reflecting on their own biases. Note that you can adapt those questions to fit the cultural environment in which you give this formation.

## Who is disabled

Who exactly is disabled is a question with no evident answer. According to the [2024 study](https://appt.org/en/stats) of the [APPT foundation](https://appt.org/en/about), a non profit based in the Netherlands; 61% of Dutch Android users and 45% of Dutch iOS users have one or more accessibility settings activated on their phone. A quarter of the Android user they surveyed used two or more accessibility features.

![Stats about accessibility usage showing that 22% of iOS users and 24% of Android users have a bigger font size activated.](ressources/C-FromAccessibilityToInclusivity/accessibilitystatsbiggertext.png)

<sub>Source: [APPT Foundation, Accessibility Statistics 2024](https://appt.org/en/stats)</sub>

Disability is not something easy to categorize. A lot of disabilities are not visible, some develops over time, other have varying effects that make them hard to apprehend. A lot of people, thinking of themselves as valid will use a bigger font on their phone. The frontiers between someone valid sho has glasses and someone with low vision is hard to establish. As stated in the book [Developing Inclusive Mobile Apps](https://link.springer.com/book/10.1007/978-1-4842-5814-9), by Rob Whitetaker:

>Disability is not a binary state. We all have abilities and limits to those abilities. Disability happens when we have built something that doesn’t work for someone with particular skills.


**In fact it could even not be desirable to draw this line.** Ashley Shew in In [Against Technoableism: rethinking who needs improvement](https://wwnorton.com/books/9781324036661) states:

>Today, many of our ideas about able-bodiedness and disability come from classifications based on who is suitable for plantation or factory work: we call
people “disabled” when they can’t perform “normal” amounts of physical labor. [...] Disability has not always been as deeply tied to the ability to do labor as it is now. As Kim Nielsen’s A Disability History of the United States shows, many Native American cultures had more room for variation and a different sense of health and wellness; **disability was (and is) not stigmatized in the same ways among some Native American groups **(and, incidentally, many Native languages have no word for “disability” as a category). Nielsen explains how Plains Indian Sign Language (the most well documented of Native sign languages), for instance, was used by various Plains tribes as a common language of trade—so signed language was a natural part of culture and language such that communication norms allowed more easily and naturally for deaf inclusion.

Depending of the circumstances, we are all disabled and we will all be. As stated previously, disability is plural, a shallow category that shouldn't negate intersectional thinking.

## Who do you want to be ?

### Disability experts and disabled experts
In [Against Technoableism: rethinking who needs improvement](https://wwnorton.com/books/9781324036661), Ashley Shew also talks largely about expertise on accessibility. While disabled experts are often not taken seriously, some of their valid peers consider themselves experts at understanding one's needs. She states:

>Throughout, I consider disabled people the experts about disability. I’m no longer interested in what so-called experts (nondisabled scientists, physicians, therapists, and so on) have to say. These narratives are already overrepresented, and in some cases, they have done damage to disabled people as a community, disabled people as knowers, and the experience of disability as valid and valuable. When we don’t listen to those with actual experience, we often get accounts of disability and technology completely wrong. Disabled people are “the real experts” (the title of Michelle Sutton’s 2015 edited volume about and authored by autistic people) when it comes to technology and disability. We use technologies. We also reject them, grapple with them, or repurpose them. The views on technology we get from listening to disabled people often look very different from those of people educated in the medical and “helping” professions.

We cannot replace the perspectives of people with disabilities simply by reading about them or running a series of automated tests. We highly encourage recruiting people from diverse backgrounds in your team. The whole project will benefit from varying perspectives and it could help to leverage against systemic exclusion and hiring discriminations which affect minorities. In fact, [a study from the Chartered Institute for IT](https://www.bcs.org/articles-opinion-and-research/nearly-90-000-disabled-people-are-missing-from-tech-industry-says-professional-body/) state that "Nearly 90,000 disabled people are 'missing' from tech industry" in the UK alone.

**But your working environment will never be representative of the whole world and every user.** As quoted from [Developing Inclusive Mobile Apps](https://link.springer.com/book/10.1007/978-1-4842-5814-9) in [🔭 B-INO Inclusive needs overview](B-INO.md) :

>“Employing the word “users” can result in falling into the trap of thinking of users as one group – an amalgamation of people who are out there somewhere in the world using your app, a group of people that you’ll never meet and never know. This form of “group think” leads to creating a “one-size-fits-all” solution that, like everything claiming to be “one size fits all,” in reality fits no one.”

### Embracing diversity

**As we need to embrace diversity, we believe it's crucial to fight a natural urge of all software creators; the will to find, implement and design the solution to a problem. There is no one solution, and assuming that you can find it is cutting off and unempowering the real accessibility experts : disabled peoples. Therefore, rather than trying to produce a perfectly (by your perspective) accessible and inclusive code, we would rather suggest to try and make the main features as inclusive as possible and then get feedback from diverse users on what are their main issues with your software are.**

It's probable that your anticipation of their needs will not match their experience. Maybe you've spent hours making a video calling feature accessible for low vision users while they mostly struggled with the main button for sending messages not being labeled as such, a fix that would have taken you a few minutes. Let them, the real experts dictate your priorities.

You must still be careful about getting feedback. For example, low vision users cannot know aht they ignore. For example, that means that if a button to send an image is not reachable, they will not be able to tell you that it's not accessible as they have no way of knowing its existence.

Furthermore, getting remote feedback from disabled users can be challenging. For example, how can you identify the issue of someone telling you "Sometimes when creating an account, my screen reader stops working"? The best way of tackling those issues is by directly looking at them using the application. It's only at the intersection of your two expertise that an understanding of what goes wrong can emerge.

# Sources

[Whitaker Rob. *Developing Inclusive Mobile Apps, Building Accessible Apps for iOS and Android*, 2020.](https://link.springer.com/book/10.1007/978-1-4842-5814-9)

[Shew Ashley, *Against Technoableism: rethinking who needs improvement*. 2023](https://wwnorton.com/books/9781324036661)

[The Chartered Institute for IT, *Nearly 90,000 disabled people are 'missing' from tech industry, says professional body*. 2024](https://www.bcs.org/articles-opinion-and-research/nearly-90-000-disabled-people-are-missing-from-tech-industry-says-professional-body/)
=======
[todo]
>>>>>>> main
