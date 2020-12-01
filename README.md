# Custom SCSS Media Queries

## How it works:

I wrote these mixin media queries to be as SIMPLE and MEMORABLE as possible.

Instead of writing out vague media query names like so:

        @include smallPhone {

        }

Or writing out the full media query line:

        @media screen and (min-width: 400px) {

        }

##### We can use mixins with semantic naming. This one is for a minimum of 400px width:

    @include _400 {

    }

My media queries are based on MIN-WIDTH, meaning these media queries are for the mobile-first approach.

The default size I usually develop for is 320px (iPhone SE)

It is the most popular small phone in the world, hence why I like to target it as my default.

I also highly recommend using an 8-point grid when you design/develop your websites. Why? Because they're common, scalable and easier to design for. If you're a designer, you've probably come across some weird pixel issues in Adobe XD, Figma or Sketch. You can avoid that by using an 8-point grid.

#### All of these media queries are divisible by 8, EXCEPT for Apple's iPhone 11 Pro/12 Pro media queries.

#### List of Media Queries:

1. 320px is default - No mixin for this!
2. 375px (iPhone 11 Pro/12 Pro) - NOT DIVISIBLE BY 8
3. 400px (Most phones)
4. 480px ("Phablets")
5. 640px (Small tablets)
6. 768px (iPad Mini)
7. 1024px
8. 1280px
9. 1360px
10. 1440px
11. 1920px
12. 2560px

##### Obviously, you don't have to use all of them! You should configure these settings to your liking. But again, I highly recommend the 8-point grid.

Here are a few articles on the subject:

1. https://builttoadapt.io/intro-to-the-8-point-grid-system-d2573cde8632

2. https://spec.fm/specifics/8-pt-grid

3. https://medium.com/swlh/the-comprehensive-8pt-grid-guide-aa16ff402179

Happy coding!
