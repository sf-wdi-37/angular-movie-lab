# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png" height="60"> Angular & Directives Lab

**Objective:** Set up a new Angular app and apply your knowledge of Angular's built-in directives.

## Getting Started

1. Make a new directory called `angular-movie-lab`, change into that directory, and use sample code and/or [these overview of steps](https://github.com/SF-WDI-LABS/intro-angular#setting-up-an-angular-app) to set up a new Angular app. You will need:
	* `index.html` with links to an **Angular 1** CDN and `app.js`.
	* `ng-app` and `ng-controller` directives in the HTML.
	* `app.js` that initializes your Angular app module and adds a controller.
3. Open your index.html file in the browser.
4. Implement solutions to the following challenges. Refer to the [solution branch](https://github.com/SF-WDI-LABS/angular-movie-lab/tree/solution) for guidance.

## Challenges

1. Inside your Angular controller, create an array of objects `vm.moviesToWatch`. Add a few movies -- each movie should be an object with at least a `title` key.

1. Use the `ngRepeat` directive to iterate over your list of movies and display them in the view.

2. Use the `orderBy` filter to sort the list of movies by title in descending order.

3. Include the text "`{{moviesToWatch.length}}` movies to watch", and use the `ngPluralize` directive so that the text displays "movie" when there is one movie and "movies" in all other cases.

4. Create a form on the page for a user to add a new movie to the list. Write a function called `addMovie` and use the `ngSubmit` directive to add the new movie to `vm.moviesToWatch` when the user submits the form.

5. Use the `limitTo` filter to limit the number of movies displayed to five. **Bonus:** Add a link for the user to "View More". Clicking the link should allow the user to view the entire list of movies.

6. Put an icon next to each movie that resembles an "X" or a trash can. When the user clicks the icon, delete the movie from the list. **Hint:** Write a function called `deleteMovie`, and use the use the `ngClick` directive.

## Bonus

1. Implement a way for the user to mark a movie as "watched". Use the `ngStyle` or `ngClass` directive to strikethrough the text of the movie if it's been "watched".

2. Give each movie in `vm.moviesToWatch` an image. Make a button in the view for the user to change the background. When the user clicks the button, set the app's background to a random movie image from `vm.moviesToWatch`. Every time the user clicks the button, they should see a different background image.

<!--
## Submission

* As you make code changes, frequently commit and push to GitHub.
* Once you've finished the assignment and pushed your work to GitHub, make a pull request from your fork to the original repo.
-->

## Optional Practice

* <a href="https://www.codeschool.com/courses/shaping-up-with-angular-js" target="_blank">Shaping up with Angular.js - Code School Tutorial</a>

## Resources

* <a href="https://docs.angularjs.org/guide/directive#what-are-directives-" target="_blank">AngularJS Developer Guide - Directives</a>
* <a href="https://docs.angularjs.org/api/ng/directive" target="_blank">AngularJS API Reference - Directives</a>
* <a href="https://docs.angularjs.org/api/ng/filter" target="_blank">AngularJS API Reference - Filter Components</a>
