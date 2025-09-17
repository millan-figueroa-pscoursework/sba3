# SBA 3: Design and Development

## Reflection

### Challenges you encountered during the project.

One of the first challenges was figuring out how to structure the page correctly for example, I was confused about whether to use a `<header> or a <nav>` element for the navigation bar. I also ran into issues with Tailwind—initially I tried using the CDN but received errors, so I had to install Tailwind locally and realized the duplicate folder structures was causing issues, which meant I had to go back and update many of my file paths.

### Your approach to solving these challenges.

First I marked up the design JPG by drawing boxes around each section and labeling where the divs, text, and images would go. I can then translate this 'diagram' into HTML structure. For the Tailwind setup, I researched and learned the difference between using the CDN and installing it locally, which solved my errors. I also learned that when using a build tool like Vite or Next.js, the @tailwind directives go in a globals.css file. To fix styling issues, I had to swap out headings for `<p> or <span>` elements so the styles would apply properly, but not sure why. For vertical centering, I stopped relying on padding and instead used flexbox, which made it cleaner. It was so much more pleasant to use Tailwind and not having to have extra css files.

### Improvements you would make if given more time.

I chose this challenge because I thought it would be a good project to proggressively add functionality and keep refactoring. With more time, I would add more responsiveness, revisit the navigation bar to make it fully responsive (add dropdowns and hamburger menu for mobile). I would also figure out how to make the thumbnails lighten on hover.
