All right, guys, before we get into learning till when they see us.

So I just want to briefly talk about what it is and some of its advantages, because in the world of

web development, we're constantly blasted with different frameworks and technologies.

So we should discuss if they're worth using and what they can do for us.

So Tailwind is a CCS framework that uses very low level utility classes to create layouts.

And it's known as what's called a utility first framework.

And in this video, we're going to do quite a bit of comparison with Bootstrap just because it's the

most popular CC framework.

It's been around for a while, and most other frameworks are very similar to bootstrap.

So you can just replace the word bootstrap with foundation or materialize or any other framework.

So frameworks like Bootstrap give you a set of classes where many of them correlate directly to components

like alerts, nav bars, cards, etc. where a tailwind, on the other hand, gives you a huge set of

utilities or utility classes to create your own custom components.

So it's very opinionated.

There is no alert class with a predefined design or anything like that.

You decide what an alert looks like with the utilities that you're given.

So to be more specific, utility classes are simple HTML classes typically scoped to a single and specific

CSS property, whereas with something like bootstrap, you could have a class that represents a dozen

or more different CSS properties.

So let's just take a look at this example here.

So we have a div that has a class of Max W XL.

So this is a class that handles the max with it, doesn't handle anything else, just that.

And the excel is the size which references a certain number of rooms or pixels, and you can actually

customize what that size is from the configuration.

So Max Auto references the margin on the x axis.

So we're saying the right and left margin and we're setting it to auto, which is usually used to center

the element.

And then P2 is a padding class, it means padding all around and that too represents a certain number

of rooms or pixels which again can be changed.

So the H2 has a class of text to excel and that pertains to the font size font bold obviously that that's

the font weight.

And then we have a class of maybe two.

That's margin bottom.

All right.

So in all these classes, they're they're named according to their purpose.

So it's very clear, it's easy to remember, you know, exactly what these classes do.

There's no naming inconsistencies and having these utilities available allows for very fast UI creation.

And if you want to test certain things out and change things around, it's extremely easy to do and

you can do it really quickly.

So in some cases, you know, this gets rid of the need for design software like Figma or, you know,

Adobe XD or something because you can do it so quickly within the within the browser.

And that's really what I love about Tailwind.

Now the downside is that people seem to complain that there's a lot of classes in the HTML and that's

true.

However, you can create custom classes and use certain directives like apply to apply to classes from

within a custom CSV file.

If you really want to clean up the number of classes in your HTML and I'll show you how to do all that

stuff later.

All right.

Now, I don't want to sound like I'm bashing bootstrap.

I really like bootstrap.

I've used it for years.

I have a course on it.

I think having the ability to to quickly create pre-defined components is great for a lot of projects.

And I'm not saying that tailwind is better or worse than bootstrap or any other framework for that matter.

This is a tailwind course.

So I am going to try to outline the advantages, but just know that I'm not saying that anything is

better or worse.

So I just want to look at some some differences here, though.

So Tailwind was released in, I believe it was 2017, and it's a relatively new framework compared to

bootstrap that was released in 2011.

So in the field, you're probably going to run into bootstrap more than tailwind.

However, tailwind is gaining a lot of traction now.

As we talked about, Tailwind uses low level classes or utility classes for fast UI development and

bootstrap uses higher level component based classes, and it does offer some utility classes as well.

So tailwind has more flexibility and uniqueness because it's so opinionated.

In many cases, bootstrap sites can look very similar, especially when the developer doesn't even bother

to configure anything, any colors or anything like that.

So Tailwind is customizable.

You have directives and functions you can use.

There's also a Tailwind C ally to set up.

Your environment.

We're going to get into that in a little bit.

You can also install it as a postseason plug in if you're using something like Webpack and Bootstrap

is also customizable through SAS, so you can change different variables for colors and so on.

Talon is a bit more difficult, I would say.

I feel like to use bootstrap, you don't need to know that much success.

You just need to remember the classes where with Tailwind, the classes essentially are the CSS properties.

So you really have to understand, for instance, Flexbox, in order to use the flex classes more so

than than bootstrap columns or whatever.

And then, of course, we have the fact that many tailwind sites do have a ton of HTML classes.

Bootstrap uses higher level classes, so of course you're going to have less of them.

So another awesome thing about Tailwind is the dynamic or conditional classes for things like responsive

design in different states.

So if we look at this example here, we have a div with the class of flex, which is just Display Flex.

That's all this is doing here.

And then we're setting the flex direction to a column with the class of Flex Call.

But then we're saying on medium screens and up, we actually want it to be a flex row, which is a horizontal

row.

Okay.

So it's rare that we have to write custom media queries because we have these responsive classes for

different widths.

We have small, medium, large, extra large, and you can even create your own.

So we can also add class B classes based on the state of an element.

For instance, here we're saying to make the text color blue if the link is hovered over so that class

won't take effect until it's actually has a hover state.

So this stuff makes Tailwind very powerful and makes it so we we rarely ever have to leave the HTML

for styling.

All right, guys, so enough with the slides.

We're going to get into our environment set up and then we'll start learning more about Tailwind, and

then we'll start to create some cool projects.

