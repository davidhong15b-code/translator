Subject to change as i continue this project.

I know there's probably an application that does the exact same thing that i'm trying to create, that also has better implementation and documentation.
But i do not care and this is my project.

I want to make an application where the translator app is actually good.
The issues with regular translator apps can be split into 2 sections: Dictation and translation

Dictation has several different components to consider:

1. Voice to text
Factors such as lack of context, homophones, accents & dialects, puntuation blindspots, overlapping speech, low microphone quality, background noise.

One of the many things that makes humans good at differentiating and understand different noises and words is the ability to understand the context of what the conversation is about.
This allows for the person listening to predict what the other person is saying and has a less rate of error in dictation, even in situations where audio is limited/low quality

Translation


Translators often have a ear-voice span to mentally formulate and correctly sequence the translated language and various for different languages you want to translate from and to.


A solution that can solve this is to run a predictive model on the dialogue that is happening and complete the sentence,
with the translated version already being completed before the sentence is fully said. The ear-voice span allows to give a good baseline on the acceptable lag between said word and translated text, which ranges from 2-5 seconds.

Additionally, future versions of this can implement voice cloning to the translated text for a more personalised feel.

For the first MVP, utilise APIs for structure/foundation for software, then custom if neccessary.
