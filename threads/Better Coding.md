![](https://ca.slack-edge.com/T01M8HJQ1B4-U0364CAGGJU-37d257352271-48)
**NotASyndrome** _Apr 16th 2022_  
Anyone else suffer from feeling like the worst coder that they know? I don't think this is imposter syndrome. I think I just need to improve with code delivery. Would love to discuss with anyone who has overcome this by becoming better. I tend to overthink my code and think my way into over analysis.

![](https://ca.slack-edge.com/T01M8HJQ1B4-U03267VSDGU-8f5e0671baa8-48)
**Alessandra**  
I feel you, what made me feel better was not solving how I feel about my lack of creativity in writing code in a better way, but I finding people more experienced than me that were okay saying "I don't know", "I know that I'll re-write this in a better way", people who does not judge you but mentor you.
Have you tried pair with someone?

![](https://ca.slack-edge.com/T01M8HJQ1B4-U020UEAH0UU-cfd7b797f217-48)
**alexander wang**  
My bootcamp instructor said (And i'll paraphrase) the beautiful code you think you're writing right now will look like absolute garbage to you in a few months.
I love that code writing is an iterative process. It won't be perfect the first time (and probably shouldn't!), but you can continue to refine and adapt it and always return and refactor it.
Some things that helped me write better code:
* read other people's code. google, stack overflow, youtube, endless sources of good (and bad) code. especially if it pertains to my stack/language choice and/or if it's from a leader in the industry.
* write more code
* get feedback from people i trust
* comparing my code for X to other code for X and see where I can improve and where I got things more or less correct
It definitely makes me feel better about my own knowledge gaps when I see how more senior engineers approach problem solving. Learning to be comfortable with uncertainty seems to come with being an engineer, and it's something that I think will take a lot of deliberate practice.

![](https://ca.slack-edge.com/T01M8HJQ1B4-U02EQQAHN6S-32af52857337-48)
**Szymon (he/his):gear:**  
Yeah, I think that analysing code can do much good for us. And I totally agree with @alexander wang about the instructor's quote. However, I personally accept this is totally normal and try to watch other people code. I also watch lots of YouTube videos like "Code this, not that" :computer:  

I can personally recommend Web Dev Simplified and Fireship for these kind of videos related to JavaScript. Don't worry if this isn't your stack. You can surely find lots of similar videos for any technology that you work with :smiley:  

@NotASyndrome, to wrap things up, don't worry, and see how others code. If I were you I would also make some research about accepting the code I write as it is. Hope I helped :blue_heart: :sparkles: (edited) 

![](https://ca.slack-edge.com/T01M8HJQ1B4-U03BLV35F34-g85f62e1fc73-48)
**David Maia**  
Hey,  
I had a feeling of being an actual senior in title in the company I am at now but not really knowing for sure.  
I had thee privilege of being the sole developer on a project where every decision was mine since I had no support.  
I developed a self analysis system with myself while writing the code.  
Every line of code I think about several things such as:  
* What am I trying to say here
* What do I want the other people that reads this to know
*What is the assumption behind my code (for example, you abstract a behavior using some mixin or class. The assumption is that this behavior is shared and used equally everywhere.)
* After you code you think about how you did. What went good and right. Keep in the back of your mind the code decisions you have done
* Revisit that code 1/2/3 months and see if it still holds. How will you know? Your PM wants to give you a new feature. If you go like "omg I need to change everything". Take this opportunity to think about: why do I need it to change? What we was the assumption of that code that changed?
* The objective of this is to make you aware of the decisions you do.
* Don't just follow principles blindly.
* Every abstraction you create to reduce code duplication or something similar always has a trade off. You need to think hard to find it out.
* After a while it gets easier. It's an exercise. Your head will hurt and you will have no idea wtf you should even be thinking.
* Stop following dogmas like DRY, WET, etc.
* You need to develop an intuition on what is GOOD DESIGN in your code. This is the only thing that I cannot explain how I do it. I just feel when something is wrong or sounds awkward in the code. Like a weird code smell (classical example is seeing nestes loops or lots of ifs all over the place for example). This is very language and stack dependent and it also I involved a bit of your personal style of coding...

I also discovered by analyzing the way that I code that in the end of the day, at least this is my experience and I am curious to know if other people feel the same, coding is very emotional oriented.  

The process that I personally experience is the following:  

I might have or not an idea on how to solve the problem
I start coding but I don't start by abstracting anything. It's as "simple" as possible. Code duplication and all.
Every line of code I write i try to be conscious about what I'm doing. Like being actively engaged in my mind with WHY am I writing this code like this.
After the feature is done you take a step back and try to notice and understand what patterns emerge from your code.
Now you refactor the code until the underlying patterns you have found become obvious due to the way that you coded them.  

The emotional parts comes when you start feeling overwhelmed. When you feel this way DONT GIVE UP. Keep pushing and trying, you need to trust that you will get to safe haven.  
As a particular example I spent one week doing a major refactor on the code base that I worked with and there were days I really felt I was not gonna make it. But I just kept pushing (please notice this was a controlled effort. I had time to do it because I knew the amount of work I had to do). I'm not a woman so I can't really know this but to me it feels like giving birth to something. There is this period of pain chaos and uncertainty but you don't give up and then in the end clarity happens and you feel "ok now I understand what my code is doing. Now it makes sense and is clean".  

What I see non senior developers doing is that they stop when the feature is done and don't re write or improve the code you are missing opportunities with this.  

You need to have some skin in the game, imagine If my refactor had failed... The PM would be all over me saying "David you wasted ONE WEEK of work!". Also note this refactor was in the back of my mind for months! I spent months thinking about this code and getting it all in my head to get all the context until I had a general idea of what things i had to change.  
And even now it could still be better.  

Next level of seniority:  
You need to be your own PM of your own code.  
You need to know what you will be working on (ideally anticipate clients needs) and code and prepare your code base so when those needs arrive you dont be surprised).  
Don't ask for permission on refactoring, just make sure what you are refactoring has a benefit in the end. Else you will just get that geek guy that refactors everything for no good reason with very little benefit.
Don't just say the code is trash, try to understand where the other developer comes from. People just do their best with what they have.  

This is very hard to explain ....
I don't even know myself if what I am saying resonates with other devs or not. I don't see anyone talk about these kind of things , specially the emotional part of "giving birth" to something you are coding and being ok with you not knowing what comes next but still push yourself.  

Hopefully this helped. But it's hard to gauge these kind of things.
