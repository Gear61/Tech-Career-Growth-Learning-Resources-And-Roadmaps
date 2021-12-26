# <img src="https://avatars.slack-edge.com/2021-06-13/2166832566754_aa3d9874986a999bbff4_102.png" width="48" /> Tech Career Growth: Learning Resources and Roadmaps
## Context

Slack search is bad, and we're also on the free-tier so you can only see the latest 10k messages. No, we're not going to move to Discord as we're in way too deep. The point of this document is to take all the awesome resource recommendations and roadmap posts shared in Slack and eternalize them here.

For public resources from Tech Career Growth specifically (i.e. stuff Alex and Rahul made), you can find them in this [giant Medium post](https://chioualexander.medium.com/the-ultimate-guide-to-advance-your-career-in-tech-regularly-updated-7b2929355f31?sk=bb9fb981ecaee453f31119aac636290b).


## Contents
[🌐 Web](#-web)
- [Resources](#resources)
- [Posts](#posts)

[<img src="https://developer.android.com/images/brand/Android_Robot_100.png" width="16"
/> Android](#-android)
- [Resources](#resources-1)
- [Posts](#posts-1)

[📋 Product Management](#-product-management)
- [Resources](#resources-2)

[📱 iOS](#-ios)
- [Posts](#posts-2)
- [Resources](#resources-3)

[💼 Interviewing](#-interviewing)
- [DSA](#dsa)
  - [Resources](#resources-4)
  - [Posts](#posts-3)
- [System Design](#system-design)
  - [Resources](#resources-5)
  - [Posts](#posts-4)

[📚 Miscellaneous](#-miscellaneous)
- [Resources](#resources-6)
- [Great Threads And Posts](#great-threads-and-posts)
- [Posts](#posts-5)

---

# 🌐 Web

## Resources

CSS:
* [You Probably Need BEM CSS in Your Life (Tutorial)](https://www.youtube.com/watch?v=er1JEDuPbZQ)

JS:
* [W3Schools - JavaScript Tutorial](https://www.w3schools.com/js/)
* [freeCodeCamp - JavaScript Algorithms and Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/)
* [Eloquent JavaScript - A Modern Introduction to Programming](https://eloquentjavascript.net/)
* [You Don't Know JS (book series)](https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/README.md)
* [30 Days of JavaScript, learn JS by building cool stuff](https://www.youtube.com/playlist?list=PLu8EoSxDXHP6CGK4YVJhL_VWetA865GOH)

Everything:
* [Curated collection of web resources at web.dev](https://web.dev/)

## Posts

### [<img src="https://ca.slack-edge.com/T01M8HJQ1B4-U028HLVL613-86f696ffb19d-48" /> Tamal Web](https://www.linkedin.com/in/tamalweb/)

Front End Engineer Roadmap:

HTML:

- Learn semantic layouts header, footer, main, article, divs, classes, id's.
- Know about web accessibility.

CSS:

- Learn the CSS box model.
- Learn flexbox, grid, or both. Make basic layouts.
- Learn css variables. Learn BEM. scss if possible.
- Learn media queries, mobile responsiveness.

JavaScript:

- Learn the core programming concepts, loop, functions, control flow, error handling, classes etc.
- Learn DOM manipulation document.querySelector(), document.appendChild() etc.
- Learn event listeners, addEventListener().
- Learn FORM capturing basics.

Browser APIs:

- fetch (send a GET, POST request)
- localStorage (store and retrieve items)

Frameworks:

Learn one popular framework,

- Vue (easy)
- React (Medium)
- Angular (Hard)

\* Difficulty assessed by FireShip youtube channel.

As you can tell, the frontend web development landscape is huge. I tried to cut down as much as I can and followed the requirements of the Front End Engineer position at Facebook. Learn each topic and try to build some stuff out of it and you will learn them better.

As someone who has spent a lot of years in web dev, even I don't know everything on this list. I still lack web accessibility, flexbox, and know only one framework React. It's only recently I learned BEM and sass styling.

So don't make this list intimidate you.

# <img src="https://developer.android.com/images/brand/Android_Robot_100.png" width=27 /> Android

## Resources
Kotlin:
* [Rahul Pandey's Kotlin Series (Playlist)](https://www.youtube.com/watch?v=iYrgWO2oibY&list=PL7NYbSE8uaBAchSwbJEQTGhWlVM8HYt7T&index=1)
* [Android Basics in Kotlin (Course)](https://developer.android.com/courses/android-basics-kotlin/course)
* [CodePath Android Cliffnotes](https://guides.codepath.com/android)

Videos:
* [Tip Calculator - Build Your First Android App (Playlist)](https://www.youtube.com/watch?v=KLuiX1oHBII&list=PL7NYbSE8uaBCMVBVg6cskGzdYguj3CUP-&index=1)

## Posts

### [<img src="https://ca.slack-edge.com/T01M8HJQ1B4-U01TQ7HGQ30-545d98e94f0b-48" /> Dom Polidoro](https://www.linkedin.com/in/domenic-polidoro-802b72b4/)

Alex and Rahul are big advocates for side projects, and I would +1 that as well. It sounds like you have a solid foundation so far with a bunch of individual pieces, so I would heavily recommend putting them all together to build something. There's actually a lot of stuff you can build with the knowledge you already have - the hard part is realizing what you can build lol

Side projects are great for two major reasons:

- They will help your resume/job search immensely if you really want to become a mobile dev. Relevant domain projects is a quick way to get some attention during the interview process.
- The classic "the whole is greater than the sum of its parts" saying. Take the example of getting a bunch of individual car parts - they are not nearly as useful individually as they are when you combine them to make a physical car. Similar-ish story here - you have a great foundation, but combining all of the skills into a single (or multiple) projects will make all the skills more valuable as a whole. Side projects will give you a clear direction or path to a final product and therefore give you a chance to use, and sharpen, the skills you have, while also gaining new skills you didn't even realize!

Your next hurdle is what to build. Greatest thing you can do is start small and possibly even copy something that exists. You likely aren't going to build the next flappy bird right now, so I'd push you to start on a journey with what you already know and see it all the way through.

I'd first start with something like a cookie clicker, a random-generated guessing game, a calculator, To-Do list or a classic "list -\> detail" app. All of these have a quick and easy approach to them, but can quickly be augmented to make a more interesting app. Then you can move into more advanced topics like networking + asynchronous programming (i.e. Kotlin coroutines), games, connecting to Firebase, authentication, real-time updates, etc. But in all honesty I would start smaller and finish the project before moving on. You'd be surprised how much you can jazz up a simple cookie clicker game or calculator if you get a little creative with it. Animations are always a great way to add more flare!

Last thing I'll mention is that Rahul has a YouTube channel about Android dev and has plenty of resources there to help you, and as of January of this year, I started a channel as well. I think Alex has a channel too? Clearly there is muuucch more content out there than what exists in these channels or Slack community, but there is definitely enough content here for you to get started and make it pretty far! Good luck!

Oh! If you're starving for a project and don't want to copy something out there or build a basic whatever app because everyone does it, ask yourself what daily or weekly problems you ran/run into and make an app to solve for it! This is how I made my first ever application (back in college) that I still use to this day! It has like 3 active users, but I use it at least once a week and it has saved me a major headache at least once a month!

# 📋 Product Management

## Resources

Books:
* [Cracking the PM Interview: How to Land a Product Manager Job in Technology](https://www.crackingthepminterview.com/)
* [Decode and Conquer: Answers to Product Management Interviews](https://www.goodreads.com/book/show/20822143-decode-and-conquer)
* [Swipe to Unlock: A Primer on Technology and Business Strategy](https://swipetounlock.com/index.html)

Courses:
* [How to Prepare for Product Manager (PM) Interviews](https://engineerseekingfire.com/how-to-prepare-for-product-manager-interviews/)

Videos:
* [Making sense of MVP (Minimum Viable Product)](https://www.youtube.com/watch?v=0P7nCmln7PM)
* [Agile Product Ownership in a Nutshell](https://www.youtube.com/watch?v=502ILHjX9EE)

# 📱 iOS

## Posts
None yet

## Resources
* [Apple's SwiftUI Tutorial (Landmarks App)](https://developer.apple.com/tutorials/swiftui)

# 💼 Interviewing

Resume:
* [How To Write An Effective Software Engineering Resume](https://chioualexander.medium.com/how-to-write-an-effective-software-engineering-resume-e42713a7a2ca) - Alex Chiou
* [Resume tips for software developers](https://youtu.be/k22qu08g_40) - Youtube video
* [What's an ATS-Friendly Resume? And How to Write One](https://www.topresume.com/career-advice/what-is-an-ats-resume)

Company:
* [levels.fyi](https://www.levels.fyi/) - Comprehensive data on company workplaces
* [glassdoor](https://www.glassdoor.com/) - Insights about jobs and companies
* [myvisajobs.com](https://www.myvisajobs.com/Reports/2021-H1B-Visa-Sponsor.aspx) - Top 100 H1B visa sponsors

Interview:
* [Preparing for Your Software Engineering Interview](https://www.facebookcareers.com/life/preparing-for-your-software-engineering-interview-at-facebook/) - Facebook
* [interviewing.io](https://interviewing.io/) - Anonymous technical mock interviews
* [prepfully.com](https://prepfully.com/) - Mock interviews, interview questions, guides and recorded interviews
* [pramp.com](https://www.pramp.com/) - Practice mock interviews & coding problems

Negotiation:
* [Employee Stock Purchase Plan (ESPP)](https://www.investopedia.com/terms/e/espp.asp)
* [How Do Employee Stock Options Work?](https://smartasset.com/investing/how-do-stock-options-work)
* [Restricted Stock Units (RSU): Essential Facts](https://www.schwab.com/public/eac/resources/articles/rsu_facts.html)

## DSA

### Resources

* [14 Patterns to Ace Any Coding Interview Question](https://hackernoon.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed)
* [Alex's Medium Articles](https://www.linkedin.com/feed/update/urn:li:activity:6827333391097188352)
* [Algorithms](https://en.wikibooks.org/wiki/Algorithms) - Fundamental techniques (wikibook)
* [Big Tech Interviews](https://www.youtube.com/playlist?list=PL7NYbSE8uaBDEXmgcdfyqY7sJ9wkf4W7q) - Data structures & algorithms (playlist)
* [Data Structures](https://en.wikibooks.org/wiki/Data_Structures) - Fundamental tools (wikibook)
* [Dictionary of Algorithms and Data Structures](https://xlinux.nist.gov/dads/)
* [Must Do Coding Questions](https://www.geeksforgeeks.org/must-do-coding-questions-for-companies-like-amazon-microsoft-adobe/)
* [Tech Interview Handbook](https://techinterviewhandbook.org/) - Curated interview preparation materials

### Posts
None yet

## System Design

### Resources
* [How to master system design interview for FANG in 1 week](https://prachitiwari9.medium.com/master-system-design-interview-in-1-week-c16539370f02)
* [System Design Interesting Reads](https://docs.google.com/document/d/1iKk6vJbWtI02AllnIEZTrKWQb4dT2QthJdRt05vq6Hw/edit)
* [System Design Resources - Nirmal Silwal](https://github.com/NirmalSilwal/system-design-resources)
* [System Design (Playlist) - Gaurav Sen](https://www.youtube.com/watch?v=xpDnVSmNFX0&list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX)
* [System Design (Playlist) - Yogita Sharma (sudoCODE) ](https://www.youtube.com/playlist?list=PLTCrU9sGyburBw9wNOHebv9SjlE4Elv5a)
* [My System Design Template - topcat](https://leetcode.com/discuss/career/229177/My-System-Design-Template)
* [System Design Primer - Donne Martin](https://github.com/donnemartin/system-design-primer)
* [Mobile System Design Article Series](https://proandroiddev.com/a-simple-framework-for-mobile-system-design-interviews-89f6f4134b84)

### Posts
None yet

# 📚 Miscellaneous

## Resources
* [Freely available programming books](https://ebookfoundation.github.io/free-programming-books/)
* [Building an Effective Dev Portfolio](https://storage.googleapis.com/joshwcomeau/building-an-effective-dev-portfolio.pdf)

## Great Threads And Posts
* [How do I choose my path in tech?](./threads/Choosing%20Your%20Path%20In%20Tech.md)
* [Why Your Interviewer Is Not Helping You](./threads/Why%20Your%20Interviewer%20Is%20Not%20Helping%20You.md)
* [Why You're Not Getting Interviews As a Junior Developer With 0 Experience And How To Fix That](./threads/Why%20Junior%20Engineers%20Are%20Not%20Given%20Chances.md)
* [How To Succeed As A Bootcamper And Whether Bootcamp Is Worth It](./threads/Succeeding%20As%20A%20Bootcamper.md)
* [Why Getting An Unexpectedly Hard Question May Be The Interviewer Trying To Help You](./threads/Why%20A%20Harder%20Interview%20Question%20Is%20Good.md)
* [Why Cross Platform Frameworks Struggle](./threads/Why%20Cross%20Platform%20Frameworks%20Struggle.md)
* [Why Imber Failed](./threads/Why%20Imber%20Failed.md)

### Posts
### [<img src="https://ca.slack-edge.com/T01M8HJQ1B4-U01MENEF744-4d4b33f4dc43-48" /> Alex Chiou](https://www.linkedin.com/in/alexander-chiou/)
[...] it seems like you have a decent company you're working for, but you're having trouble growing and also finding an outside place that's clearly better for your growth.

While it's nice when people are proactive, they often times aren't. It is very hard to be a proactive mentor; most of my managers even were very reactive, even at a supposedly top company like Facebook.

I don't think it's reasonable to have a bar set expecting proactive mentorship; you should just flip the script and push your manager and tech lead in particular for growth advice. Ask them what you could be doing better every 3-4 weeks, ask for bigger projects, ask them to make you develop new skills you don't already have. Try to set a goal for the half or year and check-in regularly to meet it. Someone who is very good at being reactive also has a lot of value; you just need to trigger the reactions. You can find our video on how to get feedback flowing here: https://www.youtube.com/watch?v=r6D9dirIqLs

Now let's say you're trying to push all the buttons and you're still not getting real feedback and opportunities to grow every several months - At that point, it's time to find a different team/company.
