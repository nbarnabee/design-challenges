# design-challenges
A repository for holding web pages that I've made in response to various prompts.  I'm not always very good at dreaming up ideas -- I prefer to work to spec -- so when I see a Reddit post or a tweet in which someone talks about a coding challenge they've done, or a take-home test that they've had, I like to make a note of it.  It's good to know what people are being asked to do "in the wild," as it were.

## Prompt #1: Reddit take-home test

This is a two-parter that I found on Reddit, with a [front-end](https://www.reddit.com/r/webdev/comments/11smo3b/im_currently_in_the_interview_process_for_a_jr/) and a [back-end](https://www.reddit.com/r/webdev/comments/128xmp1/i_made_a_post_about_a_frontend_coding_challenge_i/) component

### Front-end Specs ###

**The goal**:  test skills required to maintain an eCommerce site utilizing technology native to the browser.  
**The task**: create a hierarchical menu displaying products by collapsible categories with an "add to favorites" functionality.
1. Create an index.html file.  This file should be semantic, accesssible, responsive, and discoverable.
- The site should pass Lighthouse tests and be keyboard navigable.
- It should display on a mobile device and pass Google mobile tests.
- I should apply SEO fundamentals.
2. Create a script element.  Using no external libraries, do the following:
- Use the Fetch promise API to get a JSON file (I don't have access to this file so will fetch some other data).
- Iterate through the data structure and generate the HTML elements and event listeners.
- Hovering over a product name should reveal some data.
- Clicking/tapping on any of the products should "Add to favorites."  This state will display a heart toggle next to the product.  The list of favorite products will persist in local storage.  Mock a Google Analytics custom event to capture that the product has been favorited.
3. Create a style element for holding all CSS.  Use no external libraries.
- Use BEM naming.
- Use CSS Grid instead of Flexbox
- Try not to use !important
4. Test the work on various modern browsers.

**Thoughts on the front-end challenge:**  
This looks pretty straightforward.  Iterating through data and dynamically generating page elements using vanilla JavaScript is [one of my favorite things](https://nbarnabee.github.io/outreachy/) that I do [literally every chance I get](https://nbarnabee.github.io/club_helpers/recipes/).  I'm not sure whether I will bother to hold myself to the BEM naming convention, but it will be good to get some practice in with CSS Grid, which I hardly ever use.  
I'm less certain about the SEO requirements, but that will give me something to learn.


### Back-end Specs ###

**The task**: create an API that will provide one endpoint that will serve the product data as a json array.  The product data should be imported into a normalized structured database of your design.  (The actual task spec had candidates importing data from a .csv file.)
1. Create a /products endpoint that serves the product data as a json payload.  The endpoint should follow RESTful design practices.
2. Update the frontend to use the endpoint.

**Requirements**:  
1. The application code should be well documented.
2. The code must be developed uying Object-Oriented methodologies.  (The actual task spec required the use of PHP.)
3. All application errors must be handled gracefully and display user-friendly error messages if necessary.

**Bonus**:
Create a second API endpoint that will receive a payload when a user favorites a product, and store that information in a structured database.




