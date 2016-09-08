# React Declarative Programming

## Objectives
1. Explain the difference between declarative and imperative programming
2. Describe the benefits of declarative programming with respect to React
3. Describe some of the trade-offs of declarative programming

## Painting a house
![That's not how you paint a house](https://media.giphy.com/media/Jg6Z88H8Cc9tm/giphy.gif)

There's all this talk about imperative and declarative programming, but what do those scary words actually mean? Turns
out, it's super easy! Let's imagine for a second that we're hiring someone to paint our house.

In an imperative world, we'd tell him to open the can of paint, dip his brush in, and then move the brush in a stroking
fashion along the wall. We'd be telling the painter exactly what to do. In a declarative world, we would tell the
painter _'Paint these walls in this color'_, and he'd get it done. Why? Because the painter knows what to do! We don't
need to tell him how to do his job.

For a more realistic example, let's say we have some kind of search component that allows us to filter a list of
results. When the input updates, we filter the list data and then display the updated results in our component. In
React, we just tell it what we want the component to look like (i.e. display these items that have been filtered),
whereas in a non-declarative application, we'd have to slog through manually updating our DOM — removing the results
that are not relevant anymore, and adding the new ones to the list.

Doesn't a declarative world sound nice? It does to me! No more bossing around and micromanaging everything: everyone
would know what their job is, and do it correctly. Ahh, utopian dreams! While it seems impossible to do this in real
life, at least we can do it in our code!

## The bee's knees
So, why is this so great? Declarative programming allows us to focus on what our application should look like — as
opposed to being concerned with manually updating DOM, adding and removing classes, and so on. That stuff is all done
for us in React: we just tell React what the end result should be. It'll do the heavy lifting for us.

It's not all sunshine and rainbows though — sometimes the underlying mechanism for transforming our declarative code
into actual instructions can suffer from inefficiencies. Fixing this is pretty hard, but luckily, React has done a
tremendous job at ensuring that doing something like this is very rarely (or rather, never) necessary.

## Resources
- [Difference between declarative and imperative in React.js?](http://stackoverflow.com/questions/33655534/difference-between-declarative-and-imperative-in-react-js)
