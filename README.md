# fem-space-tourism-site

This is a solution to the [Space tourism website challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/space-tourism-multipage-website-gRWj1URZ3). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Notes

(November 3rd, 2021)

I built this one out with Astro, as has been my inclination lately. The finished project is a data-driven static site populated from an "external" data source (in this case, simply a JSON file), using Astro's dynamic routing feature. This project was somewhat unique, being one of Frontend Mentor's "Free+" challenges, and launching alongside an accompanying [Scrimba Course](https://scrimba.com/learn/spacetravel) taught by Kevin Powell.

I decided to follow along with the course on this occasion, since the opportunity to build something in the style of an expert front-end developer seemed too good to pass up. For the most part, I wasn't disappointed. While I probably could have completed the challenge on my own (and likely faster, with my usual workflow), I took away several useful lessons in planning out CSS styles and layouts, and I'm looking forward to integrating these approaches into my day-to-day workflow.

If I had to identify one downside to the follow-along approach, it's that my code at the end of the process is a little muddled, particularly with respect to the CSS. I didn't want to make use of Astro's scoped components, since I was worried that eventually my solution might diverge too much from the course's and make the later content redundant or unrelatable. At the same time, I wanted a bit more quality-of-life than writing vanilla CSS allowed for, so I settled on global Sass as a reasonable compromise.

Or at least, so I thought - it turns out that blindly translating vanilla CSS into Sass can get confusing in a hurry. If I ever go through a course like this again, I'll try to keep my stack more in line with what's being used.

[The live version of my solution may be found here.](https://aloof-mother.surge.sh/)