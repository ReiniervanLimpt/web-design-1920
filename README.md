# Web Design @cmda-minor-web 1920
//Interactie ontwerpen: Rapid prototypen en testen met echte mensen

## mijn use case

### To improve or present an alternative to Closed Captions / subtitles.

04-08 kickoff! during our online lecture we got seperated into groups to be coupled with someone experiencing difficulties using web applications due to a disability of some sort.

I got coupled with Marie van Driesschen, who works with the VPRO as a UX designer, enjoys watching series such as The Bridge and Friends and enjoys watching kickboxing / cooking videos.

### getting to meet Marie

Marie is Deaf, with a capital D which means she identifies with a smaller culture which acknowledges sign language to be their native language, this does not mean they consider themselves to be handicapped.

I got to ask a couple of questions in an online meeting together with the other students who had been assigned to Marie we spoke using Bongo with the help of her two tolks who translated her gestures to us and our questions to her (it worked surprisingly well!):

1. *What do you imagine when closed captions read [scary music] i imagine not being able to hear anything for the majority of your life means you have no idea what you're ment to expect.

> Coen (one of the other students) also had this question and was able to ask her before me, Marie smiled and explained that while she does understand the concept and can imagine what [birds chirping] would "sound" like that this is indeed one of many things deaf people cant really form a mental model around.

2. *Given that subtitles are usually just plain white lines of text, is it hard for you to distunguish between which character is talking or not?

> Marie nods while i posed the question: It is sometimes very difficult indeed, aspecially when characters are out of focus, she later tells me that she thinks the solution Teletekst used to provide (adding nameplates to the subtitles they belong to) might indeed have been a good solution for platforms like netflix...

3. *Expanding on the previous question i asked Marie if she finds it annoying to be able to read entire sentences beofre the characters have even spoken them in the actual image.

> Marie told us that the most annoying part is when the subtitles are not synched up correctly with the show, while i think this is more of a technical command it does pull into question wether subtitles are better off popping up word by word...

4. *Expanding on Marie telling Gijs (another one of the students) that she does not enjoy scary movies that much i wondered how she is able to enjoy one of her favorite series Friends! considering the amount of sarcasm and timing in punchlines.

> A conversation followed in which we talked about the dutch language is a very "sarcastic" language and i wondered if the reason she preferred english subtitles was because otherwise some context might be lost required to understand the joke. Marie enjoys reading english subtitles because its directly translated from english and not altered in any way which led me to believe there is no correlation between her prefering english subtitles and her hearing disability.

### some other interesting things from the Q&A

- Subitles can be bland, theres no intonation in ityou can only read someones emotion looking at their face or assuming their reactions (this becomes even more difficult if the person speaking is out of focus).

- Marie has seen "New Kids on the Block" recently and really injoyed the captions/subtitles it had, the subtitles read Jonguh instead of jongen so she could imagine how stupid that might have come across.

- The Parasite: A movie awarded for its use of music and sound, Marie gave us this recomendation as a tip to look at.

- Joan asked if there are any specific things she dislikes about the current way media platforms handle CC/subtitles, Marie told us she hates automatically generated captions, they are very inaccurate.

- Mohamad showed Marie a sketch of his idea and what his solution for experiencing podcasts would be, she was worried it might be too much to look at.

- Marie uses an app called Doventolk App on which she can ask someone who understands sign language to serve as a middle man between her and whoever she is calling. In her lecture on the following day after this Q&A she explained that even using this app she encounters difficulties such as having to consent to agreements verbally and not being able to let her tolk give consent for her.

### Maries lecture 04-09

The following day Marie spoke briefly about things she encountered and misconceptions content creators and everyday people have with people who identify as "Deaf".

Sign language is 4 dimensional language, it takes up time and space during movements.

A tolk "lends" their voice to the person who needs them, they dont speak for them.

## What i mean to be focussing on in designing my prototype for the second test round

:star: I showed Marie an example of how i wish to improve on CC for people with a hearing diability, she was happy to see i used a snippet of one of her favorite shows! Marie asked me to replay the example 3 times, she was struggling to understand what some of the animations i used for text were meant to illustrate.

- [x] Emphasizing intonation of characters.
From my conversation with marie i deduced its hard to "see" or read if a character is being sarcastic, annoyed or surprised.

> :exclamation: During the second test round marie said she would like to see some character specific characteristics, i showed her an example where Ross from friends said "carl" in a very monotone annoyed way, i tried to convey this by stretching out the word slowly but Marie could not make out what i was trying to illustrate.

- [x] Show which character is talking with icons or letters??
The usual white lines of text do not show which character is talking, Marie does not have the luxury of hearing the voice of a character so i need to find a way to work around this problem.

> :exclamation: I showed an example in which the character speaking was showed by the letter shown in the bottom left, Ross would be *R* and rachel would be *Ra*, Marie was able to make out who was talking.

> :exclamation: I did not get to show Marie what the CC would look like when a character is out of focus, i need to work on that.

![rachel](https://user-images.githubusercontent.com/36195440/79447189-c81d0100-7fdf-11ea-8338-a7269f720f78.png)

## working on my last prototype

In my previous testing round i did not get to show what would happen if a character was speaking while out of focus, Marie allso said some of the animations i used on text raised some eyebrows.

In my final prototype i worked on trying to create the illusion of space outside of the current viewbox, i did this by:

### adding dots to show where every character is currently located in the room (nonsense)

![dots space](https://user-images.githubusercontent.com/36195440/81168400-37f72980-8f97-11ea-833d-f67c21f78681.png)

> Marie did not seem to think alot of these dots, she was more interested in the colors i used and thought i could make use of them in another way which i did in my final example where i use the color on the characters names as well.

### flashing lights if a character is talking while out of focus

![out of focus 1](https://user-images.githubusercontent.com/36195440/81169183-b1dbe280-8f98-11ea-8fdb-0d916834aaa4.png)

> Marie was confused, she asked me to repeat the section a couple of times because she was unsure what she was looking at.

> :star: Marie commented that she was unsure about the text becoming more visible once the character "spoke" those words, she later commented that she actually DID enjoy the effect (being able to read the sentence and also knowing how and when the character spoke them)

> :exclamation: Marie said she could not make out which character was talking instantly just by the first (or first two) letters of their name, i tried to fix that by adding their full name with their corresponding color

## Polishing up my final prototype

### How i implemented the exclusive desing principles 

1. *Study situation*

Marie is deaf with a capital D, i found it very hard to comprehend what she would think while reading closed captions, sign language is a 4 dimensional language which uses up time and space as wel as gestures, during my tests i asked questions like:

- Do you read space between words as well? as if two words which have a lot of space in between them would be read with a pause or a certain tone of voice

- Do you care about how loud a character in a series is speaking or do you just want to know what they are saying?

- What do you feel if a word is being stretched out or shakes for a brief period of time?

In my example video you can see the result of this, some words said in a happy, warm way are stretched out horizontally while words which are spoken slowly are stretched out vertically and if a person emphasises a certain word this word would shake.

During the design process i kept looking at my video with sound turned off, i felt like i could almost axperience what Marie would experience when looking at my solution whilst understanding i could never fully comprehend her experience. Knowing this i tried not to make any assumptions and ask if she looked at things the same was i did.

2. *Ignore conventions*

When we met Marie we asked which solutions she likes and didnt like, she gave some examples like:

* Youtubes automatically generated closed captions are horrible! the words pop up one by one and are not even accurate

* Marie has seen the movie New Kids on the Block in the subtitles jongen is written as "jonguh" which was nice for Marie because she could now read these characters accents.

Ignoring the common conventions of adding lines completely i faked my prototype in after effects by individually animating each and every word so that i would not be limited by my own ability to create something thats too challenging for me to produce on a technical level.

3. *Prioritise identity*

My prototype shows a short section of one of Maries favorite shows: FRIENDS! i tried to create a believable context in which Marie was just sitting at home watching some comedy show she likes.

I was happy to see Marie smile when she first saw i used FRIENDS as an example, as i indicated in the *ignore conventions* section Marie enjoyed being able to read how a character spoke, i tried to illustrate this with Ross who has a very monotone allmost boring way of saying things, overexagerrating this helped me understand if Marie even knew how slow and sometimes dumb this made him look. 

4. *Add nonsense*

in the final week i overaxagerrated a lot of things, Marie asked me to repeat some sections of my video time and time again which gave me a lot of very usefull feedback.

In my final product i expanded on elements which were unclear to her whilst eliminating things that did not seem to add anything to the experience.

## Final prototype

![out of focus](https://user-images.githubusercontent.com/36195440/81168597-96240c80-8f97-11ea-8434-c20389e65e83.png)

https://vimeo.com/415301047
