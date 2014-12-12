# Santz Front-end Bolierplate

Santz front-end boilerplate. Responsive, HTML5, retina-ready, IE9+


### Setup folder structure

The bolierplate has 5 main folders:
 * CSS, which contains a SASS folder for development and the main compiled CSS file
 * Fonts
 * Images
 * Includes
 * JavaScript


### Make CSS consistent

Having consistent rules which each developer abodes by means that teams can quickly scale without introducing confusion about how a component works.

##### 1) Class names should contain hyphens

Just convention. Prettier.

##### 2) Use nesting sparingly

If using a pre-processor, don't nest more the 3 times if possible. This simplifies resulting CSS rules and makes specificity easier.

##### 3) Only use IDs when necessary  

IDs are fine in the following contexts.
 * Forms
 * Anchors

IDs should not be used as a styling tool.

##### 4) General style guidelines

CSS should be beautifully designed, just as the site you are coding. Keep these in mind:

 * { on same line as selector
 * Space between rule and brace ( ".asd {" NOT ".asd{" )
 * Properties on new line, unless if it's a single property
 * Properties in somekind of logical order
 * space between property and value colon ( "display: none" NOT "display:none" )
 * 1 line between rules
 * 2 space tabs should be used in files

See example...

    .class {
      property: value;

      @include anymixin(value);

      &.class { property: value; }

      &.class {
        property: value;
        property: value;
      }
    }

ALWAYS keep your CSS modular. Separate assets from page specifics. Do not repeat yourself. Produce clean code, avoid hacks, and since we're already 2014+, try to stop supporting old browsers (being this IE8 for instance...) since by doing that you are just delaying web development future.


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

 - Bootstrap, grid concepts // http://getbootstrap.com
 - Skeleton, grid // http://www.getskeleton.com
 - Normalize.css // http://necolas.github.io/normalize.css
 - Bourbon // http://bourbon.io
