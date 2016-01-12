# Objective

You will be building a single page app for listing, editing, and viewing movies. The app should have 2 pages, which are detailed in the project briefing, and the only requirement is that the app is built upon Ember.js. Ember data is optional in this assignment. It's up to you on how detailed you want to be with the page's markup and styles, you'll primarily be judged on how functional your app is, and not how pretty.

# Requirements

The deliverable should be sent via GitHub repository. In addition, the app must be built with the following technologies:

* Ember & Ember CLI
* Use the following API
  * https://www.themoviedb.org/documentation/api
  * http://docs.themoviedb.apiary.io

## Pages

### Movies List

This page will consist of a single list of paginated results from the movie API. You can choose which data points to display or not display.

#### Required

* Single list view of movies with pagination
* Input search box for querying data
* Ability to click an individual result, and have it send you to the movie details page

#### Optional

* Filtering functionality

### Movie Details Page

This page will show the details on a single movie, allow you to edit that movie, and save it back to an API.

#### Required

* Should show basic information about the movie in a form
* Should be able to edit/change the movie's information
* Movie title and year is required
* When saving movie, just create a POST request to [RequestBin](http://requestb.in/), and show success, and a link to the RequestBin's URL

#### Optional

* Pulling in any related data from other API endpoints for display only
