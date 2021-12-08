## Question
"They say Flutter is better as it's multi-platform. May I know what's your say on that?"

## Answer
### [<img src="https://ca.slack-edge.com/T01M8HJQ1B4-U01MENEF744-4d4b33f4dc43-48" /> Alex Chiou](https://www.linkedin.com/in/alexander-chiou/)
As my mom would always tell me, "There is no free lunch." In the end, Android and iOS are very different platforms with very specific mechanics. The cross-platform framework has to wrap that in some way; it doesn't magically go away. It can handle basic to medium difficulty use cases just fine, but when you're dealing with deep mobile integrations like frame drops when implementing a native camera capture, they fall behind, either suffering from bad performance or just lack of ability.

This is why frankly most apps I have seen built with cross-platform frameworks like PhoneGap, Flutter, React Native, etc aren't very good. Of course, there's a decent upper bound that you can achieve with them and there's some startups in particular that have done that, but when you get to 10 million+ users, you have to go native as your use-cases become too complex and performance becomes important.

To really illustrate this, Facebook created React Native. For the most part, Facebook as a company is actually moving away from React Native; it will only use it for products it has to ship and iterate on lightning fast. Instagram has actually deprecated React Native; its goal is to delete all instances of it and all new React Native code is banned. When I joined IG, we ripped out several React Native pages and rewrote them in native code to huge performance gains. Moving off of cross-platform made Instagram literally hundreds of millions of dollars.This is why the vast majority of top mobile product companies, at least in Silicon Valley, are native instead of cross-platform.
