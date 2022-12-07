## Project Redesign - Campus Dive Navigation

After having issues with a bootstrap and bootstrap library nav bar, I decided to do a redesign across our site. I didn't want to oversimplify or change too much of the user experience, but I wanted to add a cleaner and more readable interface, hover actions, active tab styling, and a hamburger menu for mobile. (As you can see in the original video, the mobile menu was completely broken making the site impossible to use on phones.)

I stripped the entire navbar of bootstrap and library classes, and wrote the new library entirely with vanilla CSS and a small amount of JS to detect the active tab.

There are also quite a few things happening behind the scenes that you can't see, but that will have a big impact on this project, like a new `constants.css` file where I refactored a substantial amount of CSS and set custom CSS variables for our platform so that we can easily update colors, fonts, and more across the site in the future. After cleaning up some of the more functional components, I'd like to add a light mode and dark mode and so custom css variables will be critical.

[link to updated nav bar] (https://www.loom.com/share/d0c6c8d4d57841139ee12340325fb379)
