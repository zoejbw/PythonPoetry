# PythonPoetry
Projects from Reading and Writing Electronic Texts

## Instagram Ad Poetry Generator
For this project I edited the “House of Dust” poetry generator created by Allison Parrish. The text was sourced from transcribing my targeted instagram advertisements.  

## Nested Poetry
Based on Tracery grammar structures, created a poetic form that takes a chunk of text, and ueses the first sentence as a starting point, nesting phrases from the rest of the paragraph inside of it based on where they had matching sets of words. The output has all the words from the original sentence, and starts and ends in the same place, but has sections of the rest of the text nested in places that still have word-to-word coherence.

## Markov Stories
Function that modifies markovify so that it could keep separate parts of a story apart from each other in its averaging. Creates sentences that draw from each part of a story to create an algorithmic summary.

## Cut Ups
This project creats mashups between the texts of original sources and their adaptations, creating a single continous script. Examples are *Emma* and *Clueless*, and *Romeo and Juliet* and *West Side Story*. 

## Final

### Reciting
For this assignment, I was interested in using the phonetic dictionary to create a “translation” of texts that are generally memorized. I was particularly interested in the United States Pledge of Allegiance and prayers, because they are often memorized at a young age before the meaning is understood.

### Speculative Countries

Continued on the idea of the strangeness of the pledge of allegiance from my previous project. When researching it, I found that the original author hoped that the pledge “would be used by citizens in any country", so I decided to make a generator that would create a flag and pledge for a randomly created country. The makeFlag function draws a random sample from a list of colors, then chooses a number for the horizontal stripes, vertical stripes, and stars. The makePledge function uses a tracery grammar to construct a new version of the pledge. The country name is generated from a character-level markov model based on a list of country/state names. The form of government (“to the republic”) and religion (“under God”) is also randomized. To make the country have unique values, it replaces “liberty and justice” with a random noun and a noun with the same vector relationship to it as liberty to justice. It also generates a code of how the pledge should be said, regarding body position.
