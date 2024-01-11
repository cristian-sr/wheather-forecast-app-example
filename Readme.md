# Weather Forecast App - Example

We’ve now made it to the final HTML project on our list, which just so happens to be the most challenging project we’ve included so far!

But what are we building, I hear you ask? We’re going to create a weather forecast app! 

This will allow a user to enter a city, which we’ll then use to fetch and display a weather forecast for them.

The final product may look simple, but this is a deceptively challenging project, as we’ll be interacting with an external weather API to fetch and parse the weather data.

As you’ve probably already guessed, this project is going to blend HTML with CSS, JavaScript, and the CSS framework Bootstrap.

I really wanted to tie in everything we’ve done so far for the grand finale, including a brand-new external API provider!

Let’s take a look at the skills we’ll be using to create our HTML weather app: 

- Fetching API Data: Making HTTPS requests to external APIs to fetch weather data.
- Asynchronous JavaScript: Using async and await to handle asynchronous API requests.
- DOM Manipulation: Updating HTML dynamically weather data using JavaScript.
- Bootstrap Grid System: Use Bootstrap's responsive grid system to present forecast data.
- Event Handling: Capture user input and manage click events to trigger data fetching and UI updates.
- Error Handling: Implement error handling for API requests and manage network issues or user errors.

The first thing you should notice is that we’re including error handling to ensure our project is professional. 

This is ideal if you want to add this project to your portfolio, as it shows you know how to think and code like a professional web developer.

When it comes to the standout feature of this project, it has to be the external API integration to fetch weather data. This is super fun and really rewarding. 

Of course, you’ll need to sign up with OpenWeatherMap to get your own API key, but this is really straightforward.

Simply sign up for the free account, verify your email, and you’ll receive your API key to use within a couple of hours. 

Then remember to add this to the JS code instead of the placeholder, and you will be all set.

Let’s now dive into the HTML, CSS, and JavaScript source code for our final HTML project.

You’ll notice that it uses a lot of JavaScript. 

As I mentioned earlier, we cannot avoid it at this point, especially if we want to include dynamic and interactive content.

This is particularly important for the weather data fetching, which is all handled within the JS code.

We simply collect the city and country of interest and send this data in our API request to fetch weather forecast data.

This is a simple RESTful API request to OpenWeatherMap to collect the forecast data.

Depending on how confident you feel, this might all sound very complicated.

But once you’ve looked at the code, you’ll see it’s nothing more than an HTTP request and some string manipulation.

Of course, we also have some asynchronous code processing and error handling, but again, these are fairly standard once you get to grips with JavaScript, so don't be afraid of them!

The final step involves using Bootstrap to neatly package the weather data into a card component, which is dynamically rendered within the HTML.

You’ll see that we’ve barely used any CSS in this example as we’ve chosen to depend on Bootstrap.

That said, I highly recommend and encourage you to make changes to the styling and to experiment with all of the code.

This is especially important if you feel like you’re out of your comfort zone, as it will help you to truly understand what is happening under the hood!

Maybe add some elements we haven’t used yet, like radio buttons or checkboxes? Perhaps you can add a survey form to get user feedback?