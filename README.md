# Santz UI Development Boilerplate

Santz's (S)CSS Guidelines

> “Every line of code should appear to be written by a single person, no matter the number of contributors.” —@mdo


### Folder structure

The bolierplate has 5 main folders:
 * /css - which contains a /sass folder for development and the main compiled CSS file
 * /fonts
 * /images
 * /includes
 * /js


### Guidelines

Fortunately, my CSS guidelines were pretty much like Dropbox's brand new ones. I therefore dropped mine. Simply check theirs [here](https://github.com/dropbox/css-style-guide).

There's only this formatting thing I want to keep a standard: 2 **space** tabs should be used in files!

ALWAYS keep your CSS modular. Separate assets from page specifics. Do not repeat yourself. Produce clean code, avoid hacks, and since we're already 2015+, try to stop supporting old browsers (being this IE8 for instance... and even IE9 I dare to say) since by doing that you are just delaying web *development*.


### Workflow

This is particularly important for responsive.

In terms of workflow I consider that working on larger sizes first helps.

 1. Build desktop sizes.
 2. Test.
 3. Start building the responsive adaptations.
 4. Test.
 5. Deploy.


### Responsive development and the mobile first approach

Performance is crucial, and sites we develop must always be 100% performance optimized, disregarding the fact it will never be used on a mobile device whatsoever.

Performance is a non-negotiable factor.

This being said, although mobile first development is usually a personal choice or an enforced request, I'd rather build the desktop site, and then adapt it for smaller screens.

All in all, always produce lean and optimized CSS code, always use hardware accelerated solutions and always prefer clean and modern JavaScript code.


### Credits

 - Bootstrap, grid concepts - http://getbootstrap.com
 - Skeleton, grid - http://www.getskeleton.com
 - Normalize.css - http://necolas.github.io/normalize.css
 - Bourbon - http://bourbon.io
 - Dropbox - https://github.com/dropbox/css-style-guide
