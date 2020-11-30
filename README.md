# Custom SCSS Media Queries

## How it works:

My media queries are based on MIN-WIDTH, meaning these media queries are based on the mobile-first approach.

The default size I usually design for is 320px (iPhone SE)

It is the most popular small phone in the world, hence why I like to target it as my default.

I highly recommend using an 8-point grid when you design/develop your websites. These are the easiest to design for and should be used at all times and are also the most common.

#### All of these media queries are divisible by 8, EXCEPT for Apple's iPhone 11 Pro/12 Pro media queries.

That being said, I wrote these media queries out to be as SIMPLE and MEMORABLE as possible:

##### This code basically says "Minimum 400px width."

    @include _400 {

    }

###### This code basically says "Minimum 1024px width."

    @include _1024 {

    }

#### List of Media Queries:

1. 320px is default
2. 375px (iPhone 11 Pro/12 Pro) - NOT DIVISIBLE BY 8
3. 400px (Most phones)
4. 480px
5. 640px (Small tablets)
6. 768px (iPad Mini)
7. 1024px
8. 1280px
9. 1360px
10. 1440px
11. 1920px
12. 2560px

##### Obviously, you don't have to use all of them! You should configure these settings to your liking.
