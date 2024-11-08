# How can I help?
The purpose of these public documents is to make a pitch for a software project. Digital signatures already exist, but they are difficult to use. The short version of the pitch is: let's change that.

My first contribution to making digital signatures easier to use to explain what they are, why you might want them, and how to use them.

# Basic assumptions

Even if you are not interested in the software aspect of what I am doing, I hope that the guiding philosophy of the software might be useful in informing how you think about yourself and others.

## Lying is bad

Truth can be complicated, and it only gets more complicated once you start thinking about how easy it is to trick people, especially with modern technology. The purpose of the technology in this Github organization is to make it more difficult to lie.

Promises can be broken, and sometimes there is nothing that you can do about it, but the technology here is trying to make it harder to deny that the promise was ever made.

## Use your best judgement

Nobody is right 100% of the time, but that doesn't mean we shouldn't try. Christians believe that God is merciful. Whether you are worried about God's judgement, or some more earthly power, you have to make your best guess at what you should do at any point in time.

## You're not in this alone

There is a lot of confusing stuff out there. If you need help, find someone to help you. If you can't find anyone to help you, use your best judgement, and hope that others will understand where you're coming from.

## Pick your fights

Understand that even if you conclude that someone is right, it might not be your responsibility to help them. If you need help figuring out what your responsibilities actually are, ask for help.

# What are digital signatures?

Digital cryptographic signatures are the building blocks for establinshing trust on the internet. They are already used in a wide variety of technologies that you might not even be aware of, including SSL, the protocol that internet browsing software uses to decide if a website connection is secure. It works by making and keeping secrets, then computationally combining those secrets with other information without ever revealing the raw secret. It can be used like a written signature because knowing that secret is like having the ability to sign a name. Another computer can read it and verify it, but it can't reproduce it on a different document without violating some very reliable mathematical assumptions. Information is usually very easy to alter and manipulate, so the fact that digital signatures cannot be verified without including a verbatum copy of an original document is a useful property. It means that if the cryptographic portion of a program verifies a signature, it knows with mathematical certainty that the document is a verbatum copy. A key assumption in the math is that the cryptographic key stays secret, and doing that in a way that cannot be hacked is one of the most important objectives in cybersecurity.
