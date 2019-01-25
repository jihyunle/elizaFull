# Full Eliza Application

You will be creating an interactive chat-bot type program. Eliza is a therapist program that interacts with the user. Your program will need to evaluate what the user asks and turn the user's input into a question that sounds like the therapist really cares.

**Sample hedges:**

  -  Please tell me more
  -  Many of my patients tell me the same thing
  -  It is getting late, maybe we had better quit

**Sample qualifiers:**

  -  Why do you say that
  -  You seem to think that
  -  So, you are concerned that

**Replacements:**

  -  replace *i* with *you*
  -  replace *me* with *you*
  -  replace *my* with *your*
  -  replace *am* with *are*

 

When the user enters a statement the program responds in one of two ways:

1. With a randomly chosen hedge, such as "Please tell me more"

2. By changing some keywords  in the user's input string an appending this string to a randomly chosen qualifier. To get a random item from an array, select a random number for one of the array index values and use the value at that index for your qualifier.

 

**Here's how the replacement works:**

The user enters something at the prompt: "my teacher hates me"

The program will loop through that string and replace "my" with "your" and "me" with "you" and then prepend the qualifier to the replacement string. So, my teacher hates me becomes "Why do you say that your teacher hates you?" The replacement method returns the same words as the user entered only the replacement words have been swapped. Then the qualifier is prepended to the user's words.

Spend some time thinking how you would search through a string and replacing specific words. *Hint*: read about the [split] (https://docs.oracle.com/javase/7/docs/api/java/lang/String.html#split(java.lang.String))Links to an external site.operator.